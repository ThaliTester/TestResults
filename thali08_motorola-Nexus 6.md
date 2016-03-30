#### Test 646862831c69957_thali08_motorola-Nexus 6 Logs


```
--------- beginning of system
03-30 22:19:30.946   823   861 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,--------- beginning of main
03-30 22:19:30.968   823   861 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
03-30 22:19:31.013   279  1003 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (322 us)
03-30 22:19:31.230  3251  3251 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-30 22:19:31.233  3251  3251 D AndroidRuntime: CheckJNI is OFF
03-30 22:19:31.360  3251  3251 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-30 22:19:31.370   823  2549 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-30 22:19:31.384   823  2549 V WindowManager: addAppToken: AppWindowToken{2dffe4ba token=Token{3fcda1e5 ActivityRecord{10b2bcdc u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-30 22:19:31.388  3251  3251 D AndroidRuntime: Shutting down VM
03-30 22:19:31.390   823   859 V WindowManager: Adding window Window{1457289d u0 Starting com.test.thalitest} at 2 of 7 (after Window{1c652414 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-30 22:19:31.401  1526  1795 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@27b340e2
03-30 22:19:31.402  1526  1526 I HotwordDetector: Closing mic
03-30 22:19:31.459   357  1802 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-30 22:19:31.459   357  1802 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-30 22:19:31.464   357  1031 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-30 22:19:31.466   823  1433 I ActivityManager: Start proc 3267:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-30 22:19:31.466  1526  1799 I HotwordRecognitionRnr: Hotword detection finished
03-30 22:19:31.466  1526  1797 I HotwordRecognitionRnr: Stopping hotword detection.
03-30 22:19:31.518   823   838 I ActivityManager: Killing 2910:com.android.settings/1000 (adj 15): empty #17
03-30 22:19:31.566   823   859 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-30 22:19:31.567   823   823 V ActivityManager: Display changed displayId=0
03-30 22:19:31.568   823   859 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
03-30 22:19:31.569   823   859 W DisplayManagerService: Failed to notify process 2910 that displays changed, assuming it died.
03-30 22:19:31.569   823   859 W DisplayManagerService: android.os.TransactionTooLargeException
03-30 22:19:31.569   823   859 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 22:19:31.569   823   859 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
03-30 22:19:31.569   823   859 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
03-30 22:19:31.569   823   859 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1094)
03-30 22:19:31.569   823   859 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:932)
03-30 22:19:31.569   823   859 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:112)
03-30 22:19:31.569   823   859 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1027)
03-30 22:19:31.569   823   859 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 22:19:31.569   823   859 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:135)
03-30 22:19:31.569   823   859 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-30 22:19:31.569   823   859 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
03-30 22:19:31.571   279   279 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-30 22:19:31.571   279   279 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-30 22:19:31.726   823   838 I ActivityManager: Killing 2875:com.google.android.apps.messaging/u0a75 (adj 15): empty #18
,03-30 22:19:31.738   870   870 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-30 22:19:31.738   870   870 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-30 22:19:31.778   870   870 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,03-30 22:19:31.778   870   870 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-30 22:19:31.840   279   319 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-30 22:19:31.843   279   279 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-30 22:19:31.843   823  1047 D SurfaceControl: Excessive delay in setPowerMode(): 277ms
,03-30 22:19:31.943   823   861 I DreamManagerService: Entering dreamland.
,03-30 22:19:31.945   823   861 I PowerManagerService: Dozing...
,03-30 22:19:31.962   823   856 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-30 22:19:31.971   357  1033 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-30 22:19:31.971   357  1033 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-30 22:19:31.977   823  1011 E WifiStateMachine: cancelDelayedScan -> 16
,03-30 22:19:31.982   823  1011 E native  : do suspend false
,03-30 22:19:32.011   823  1278 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658545427
03-30 22:19:32.011   823  1278 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-30 22:19:32.025  3267  3267 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-30 22:19:32.038  3267  3267 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5629-5631)
,03-30 22:19:32.038  3267  3267 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-30 22:19:32.052  3267  3267 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f80295a}
,03-30 22:19:32.053  3267  3267 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-30 22:19:32.053  3267  3267 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-30 22:19:32.067  3267  3267 I BrowserStartupController: Initializing chromium process, singleProcess=true,
03-30 22:19:32.067  3267  3267 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-30 22:19:32.069  3267  3267 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-30 22:19:32.079  3267  3293 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.,
,03-30 22:19:32.088  3267  3267 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-30 22:19:32.093  3267  3267 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-30 22:19:32.093  3267  3267 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-30 22:19:32.093  3267  3267 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-30 22:19:32.098   823  1011 E WifiStateMachine: cancelDelayedScan -> 18,
,03-30 22:19:32.143   357   357 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-30 22:19:32.143   357   357 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-30 22:19:32.150   823  1011 E native  : do suspend true
,03-30 22:19:32.180   823  1011 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-30 22:19:32.183   823   858 D BluetoothManagerService: Message: 20
03-30 22:19:32.183   823   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2768481a:true
,03-30 22:19:32.202  3267  3267 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-30 22:19:32.209  3267  3267 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-30 22:19:32.220  3267  3267 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-30 22:19:32.224  3267  3267 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-30 22:19:32.224  3267  3267 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-30 22:19:32.271  3267  3316 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-30 22:19:32.274  3267  3267 D Atlas   : Validating map...
,03-30 22:19:32.288   823  1260 V WindowManager: Adding window Window{2cf2ebca u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1457289d u0 Starting com.test.thalitest})
,03-30 22:19:32.291  3267  3302 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-30 22:19:32.324  3267  3316 I OpenGLRenderer: Initialized EGL, version 1.4
,03-30 22:19:32.330  3267  3316 D OpenGLRenderer: Enabling debug mode 0
,03-30 22:19:32.377   823   859 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +983ms
,03-30 22:19:32.383  1258  1258 I Keyboard.Facilitator: onFinishInput()
,03-30 22:19:32.397   823  1011 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-30 22:19:32.400  3267  3267 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-30 22:19:32.428  3267  3267 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3267
,03-30 22:19:32.539  3267  3267 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-30 22:19:32.660  3267  3318 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576331776
,03-30 22:19:32.666  3267  3318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-30 22:19:32.666  3267  3318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-30 22:19:32.666  3267  3318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-30 22:19:32.666  3267  3318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-30 22:19:32.666  3267  3318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-30 22:19:32.666  3267  3318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f19ff47 added. We now have 1 listener(s)
,03-30 22:19:32.667   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:19:32.676  3267  3318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-30 22:19:32.681  3267  3318 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-30 22:19:32.683  3267  3318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-30 22:19:32.684  3267  3318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-30 22:19:32.694  3267  3318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
03-30 22:19:32.694  3267  3318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-30 22:19:32.694  3267  3318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-30 22:19:32.694  3267  3318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-30 22:19:32.694  3267  3318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-30 22:19:32.694  3267  3318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-30 22:19:32.694  3267  3318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-30 22:19:32.694  3267  3318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-30 22:19:32.694  3267  3318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-30 22:19:32.694  3267  3318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-30 22:19:32.694  3267  3318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-30 22:19:32.695  3267  3318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2188c912 added. We now have 1 listener(s)
,03-30 22:19:32.695  3267  3318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-30 22:19:32.701   823  1013 D WifiService: New client listening to asynchronous messages
,03-30 22:19:32.704  3267  3318 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-30 22:19:32.708  3267  3318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-30 22:19:32.709  3267  3318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-30 22:19:32.709  3267  3318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-30 22:19:32.709  3267  3318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-30 22:19:32.714  3267  3318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 22:19:32.715   823  1230 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:19:32.717  3267  3318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-30 22:19:32.723  3267  3318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 22:19:32.723  3267  3318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:19:32.723  3267  3318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:19:32.723  3267  3318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:19:32.723  3267  3318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:19:32.723  3267  3318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-30 22:19:32.723  3267  3318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,03-30 22:19:32.723  3267  3318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-30 22:19:32.723  3267  3318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-30 22:19:32.723  3267  3318 D io.jxcore.node.ConnectivityMonitor: start: OK
03-30 22:19:32.725  3267  3267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-30 22:19:32.725  3267  3318 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-30 22:19:32.760  3267  3267 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-30 22:19:32.763   870   870 I kickstart: STATUS: Received file 'm9kefs1'
03-30 22:19:32.764   870   870 I kickstart: STATUS: 950272 bytes transferred in 0.984806 seconds
03-30 22:19:32.764   870   870 I kickstart: STATUS: Successfully downloaded files from target 
03-30 22:19:32.764   870   870 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-30 22:19:32.767   870   870 I kickstart: STATUS: Sahara protocol completed
,03-30 22:19:33.020   823   999 I art     : Explicit concurrent mark sweep GC freed 44326(2MB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.292ms total 55.114ms
,03-30 22:19:33.164  1239  1239 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:33.186  1239  1754 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-30 22:19:33.187  1239  1754 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:33.187  1239  1754 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:33.187  1239  1754 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:33.190  1239  1754 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-30 22:19:33.203  2749  2749 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-30 22:19:33.203  2749  2749 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-30 22:19:33.203  2749  2749 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-30 22:19:33.419  3267  3325 W jxcore-log: Initializing JXcore engine
03-30 22:19:33.419  3267  3325 W jxcore-log: JXcore engine is ready
,03-30 22:19:33.446  3325  3325 W Thread-344: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12957]" dev="sockfs" ino=12957 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-30 22:19:33.446  3325  3325 W Thread-344: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-30 22:19:33.446  3325  3325 W Thread-344: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9687]" dev="sockfs" ino=9687 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-30 22:19:33.456  3325  3325 W Thread-344: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19162]" dev="sockfs" ino=19162 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-30 22:19:33.468  3267  3325 W jxcore-log: Starting JXcore engine
,03-30 22:19:33.547  3267  3325 W jxcore-log: Platform android
03-30 22:19:33.547  3267  3325 W jxcore-log: 
03-30 22:19:33.547  3267  3325 W jxcore-log: Process ARCH arm
03-30 22:19:33.547  3267  3325 W jxcore-log: 
,03-30 22:19:33.737  3267  3325 I jxcore-log: JXcore Cordova bridge is ready!
03-30 22:19:33.737  3267  3325 I jxcore-log: 
03-30 22:19:33.737  3267  3325 W jxcore-log: JXcore engine is started
,03-30 22:19:33.749  3267  3318 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-30 22:19:33.754  3267  3267 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-30 22:19:34.533  1145  1145 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-30 22:19:34.947  1145  1145 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-30 22:19:34.983  1145  1145 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,03-30 22:19:34.984  1145  1145 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-30 22:19:34.998   823  1011 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,03-30 22:19:34.998   823  1011 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
03-30 22:19:34.998   823  1014 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-30 22:19:35.001   823  1011 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-30 22:19:35.006   353   799 D CommandListener: Setting iface cfg
,03-30 22:19:35.013   823  1011 E WifiStateMachine: Start Dhcp Watchdog 1
,03-30 22:19:35.018   823  1011 E WifiStateMachine:  WifiLinkLayerStats: 
03-30 22:19:35.018   823  1011 E WifiStateMachine:  my bss beacon rx: 1
03-30 22:19:35.018   823  1011 E WifiStateMachine:  RSSI mgmt: -38
03-30 22:19:35.018   823  1011 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=0
03-30 22:19:35.018   823  1011 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-30 22:19:35.018   823  1011 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-30 22:19:35.018   823  1011 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-30 22:19:35.018   823  1011 E WifiStateMachine:  on_time : 464 tx_time=62 rx_time=79 scan_time=0
,03-30 22:19:35.123   823  1011 E native  : do suspend false,
,03-30 22:19:35.135   823  1011 E WifiStateMachine: scanCount==0 - aborting
,03-30 22:19:35.381  3328  3328 I dhcpcd  : version 5.5.6 starting
,03-30 22:19:35.466  3328  3328 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-30 22:19:35.609  3328  3328 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1,
,03-30 22:19:35.648  3328  3328 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-30 22:19:35.952   823  1011 E native  : do suspend true
,03-30 22:19:35.979   823  1014 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
03-30 22:19:35.980   823  1014 D ConnectivityService: Adding iface wlan0 to network 100
,03-30 22:19:35.984   823  1011 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-30 22:19:36.009   823  1014 E ConnectivityService: Unexpected mtu value: 0, wlan0
,03-30 22:19:36.009   823  1014 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-30 22:19:36.013   823  1014 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-30 22:19:36.015   823  1014 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-30 22:19:36.018   823  1014 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-30 22:19:36.025   823  1014 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-30 22:19:36.028   823  1014 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
03-30 22:19:36.029   823  3326 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-30 22:19:36.029   823  3326 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-30 22:19:36.029   823  1014 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-30 22:19:36.029   823  1014 D ConnectivityService:    accepting network in place of null
,03-30 22:19:36.030   823  3326 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-30 22:19:36.030   823  1014 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,03-30 22:19:36.031   823  3326 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
03-30 22:19:36.031   823  1014 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-30 22:19:36.035   823  1014 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-30 22:19:36.036   823  1014 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-30 22:19:36.036   823  1014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-30 22:19:36.036   823  1014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
03-30 22:19:36.036  1069  1535 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-30 22:19:36.039   823   858 D Tethering: MasterInitialState.processMessage what=3
,03-30 22:19:36.051  2933  2933 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-30 22:19:36.052   823  1433 V BackupManagerService: Scheduling immediate backup pass,
03-30 22:19:36.055   823   823 V BackupManagerService: Running a backup pass
03-30 22:19:36.055   823  1046 V BackupManagerService: clearing pending backups
,03-30 22:19:36.059  3267  3267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-30 22:19:36.059  3267  3267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:19:36.059  3267  3267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:19:36.059  3267  3267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:19:36.059  3267  3267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:19:36.059  3267  3267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:19:36.059  3267  3267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:19:36.059  3267  3267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-30 22:19:36.059  3267  3267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-30 22:19:36.061  1526  1526 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,03-30 22:19:36.063   823  1046 V PerformBackupTask: Beginning backup of 14 targets
03-30 22:19:36.063  1327  1352 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-30 22:19:36.064  1327  1352 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
03-30 22:19:36.064   823   853 D TelephonyManager: getDataEnabled: retVal=false
03-30 22:19:36.064  2933  2933 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-30 22:19:36.072   823   853 E GpsLocationProvider: No APN found to select.
,03-30 22:19:36.074   823  1046 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-30 22:19:36.080   823  1046 V BackupServiceBinder: doBackup() invoked
,03-30 22:19:36.082   823  1046 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-30 22:19:36.104   823  1433 I ActivityManager: Start proc 3368:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-30 22:19:36.105   823  1046 I BackupRestoreController: Getting widget state for user: 0
,03-30 22:19:36.158  1842  1897 W GmsBackupTransport: Unknown package in backup request: @pm@
,03-30 22:19:36.166  1842  1897 V GmsBackupTransport: starting performBackup for @pm@
,03-30 22:19:36.171  1842  1897 V GmsBackupTransport: performBackup done for @pm@
,03-30 22:19:36.177  1239  1239 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:36.195  1239  1730 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-30 22:19:36.195  1239  1730 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:36.195  1239  1730 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:36.195  1239  1730 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:36.200  1239  1730 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:36.240   823  3388 D GpsLocationProvider: NTP server returned: 1459369176336 (Wed Mar 30 22:19:36 GMT+02:00 2016) reference: 169833 certainty: 35 system time offset: 96
03-30 22:19:36.242   823  1284 D AlarmManagerService: Setting time of day to sec=1459369176
03-30 22:19:36.338   823  1284 W AlarmManagerService: Unable to set rtc to 1459369176: Invalid argument
03-30 22:19:36.341   823  1102 I ActivityManager: Start proc 3401:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-30 22:19:36.353   369   369 I art     : Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 189us total 12.924ms
,03-30 22:19:36.359  1239  1730 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-30 22:19:36.359  1239  1730 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-30 22:19:36.359  1239  1730 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-30 22:19:36.359  1239  1730 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-30 22:19:36.359  1239  1730 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-30 22:19:36.359  1239  1730 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-30 22:19:36.359  1239  1730 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-30 22:19:36.366  1842  1858 W GmsBackupTransport: Error sending final backup to server: 
03-30 22:19:36.366  1842  1858 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-30 22:19:36.366  1842  1858 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-30 22:19:36.366  1842  1858 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-30 22:19:36.366  1842  1858 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-30 22:19:36.366  1842  1858 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-30 22:19:36.366  1842  1858 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-30 22:19:36.366  1842  1858 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-30 22:19:36.366  1842  1858 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-30 22:19:36.366  1842  1858 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-30 22:19:36.366  1842  1858 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-30 22:19:36.366  1842  1858 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-30 22:19:36.366  1842  1858 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-30 22:19:36.366  1842  1858 W GmsBackupTransport: 	... 1 more
03-30 22:19:36.366   823  1046 D BackupManagerService: Now staging backup of com.google.android.talk
,03-30 22:19:36.375   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 207us total 14.412ms
03-30 22:19:36.388   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 211us total 10.614ms
03-30 22:19:36.395   823  1046 D BackupManagerService: Now staging backup of com.google.android.dialer
03-30 22:19:36.403   823  1046 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-30 22:19:36.409   823  1046 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-30 22:19:36.413   823  1046 D BackupManagerService: Now staging backup of com.google.android.gm
,03-30 22:19:36.419  3401  3401 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-30 22:19:36.421   823  1046 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-30 22:19:36.424   823  1046 D BackupManagerService: Now staging backup of com.android.nfc
,03-30 22:19:36.429   823  1046 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-30 22:19:36.433   823  1046 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-30 22:19:36.437  3401  3401 D SprintDMHelper: simOperator:  IMSI: null
03-30 22:19:36.437  3401  3401 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-30 22:19:36.446   823  1046 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-30 22:19:36.448   823  1046 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-30 22:19:36.453   823  1046 D BackupManagerService: Now staging backup of com.android.vending
,03-30 22:19:36.454   823  3326 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 30 Mar 2016 20:19:36 GMT], X-Android-Received-Millis=[1459369176454], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1459369176366]}
,03-30 22:19:36.455   823  3326 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-30 22:19:36.455   823  1014 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-30 22:19:36.455   823  1014 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
,03-30 22:19:36.456   823  1014 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-30 22:19:36.456   823  1014 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-30 22:19:36.456   823  1014 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-30 22:19:36.456   823  1014 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-30 22:19:36.458  1069  1535 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-30 22:19:36.461  1804  1804 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-30 22:19:36.464  1804  1804 D SystemUpdateService: onCreate
,03-30 22:19:36.466  1804  1804 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-30 22:19:36.467   823  1046 D BackupManagerService: Now staging backup of android
,03-30 22:19:36.469  1804  3422 W DriveInitializer: Background init thread started
03-30 22:19:36.470  1804  3424 I SystemUpdateService: active receiver: enabled
,03-30 22:19:36.472  1804  3424 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-30 22:19:36.474  1804  3424 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-30 22:19:36.474  1804  3424 I SystemUpdateService: now status is 0 (complete)
03-30 22:19:36.474  1804  3424 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-30 22:19:36.474  1804  3424 I SystemUpdateService: file has been verified
03-30 22:19:36.474  1804  3424 I SystemUpdateService: OTA package size = 25802302
,03-30 22:19:36.478  1804  3423 W DriveInitializer: Awaiting to be initialized
,03-30 22:19:36.481   823  1046 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-30 22:19:36.504  1842  1897 I GmsBackupTransport: Next backup will happen in 43199857 millis.
,03-30 22:19:36.512  1804  3430 I iu.SyncManager: SYNC; picasa accounts
,03-30 22:19:36.515  1804  3424 I SystemUpdateService: showing system update notification
,03-30 22:19:36.516   823  1046 I BackupManagerService: Backup pass finished.
,03-30 22:19:36.522  1804  1804 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-30 22:19:36.525  1804  1804 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-30 22:19:36.535  1804  3430 I iu.UploadsManager: num queued entries: 0
03-30 22:19:36.536  1804  3430 I iu.UploadsManager: num updated entries: 0
03-30 22:19:36.536  1804  3430 I iu.SyncManager: NEXT; no task
,03-30 22:19:36.541   823   823 I ValidateNoPeople: skipping global notification
,03-30 22:19:36.543  1804  1804 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-30 22:19:36.547  1804  1804 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-30 22:19:36.554  1804  1804 D SystemUpdateService: onDestroy
,03-30 22:19:36.569   823   838 I ActivityManager: Start proc 3436:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-30 22:19:36.606  1239  1257 I art     : Explicit concurrent mark sweep GC freed 20506(1042KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 836us total 22.150ms
,03-30 22:19:36.621   823   853 I ActivityManager: Start proc 3459:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-30 22:19:36.644  1239  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-30 22:19:36.645  1239  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:36.645  1239  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:36.645  1239  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:36.648  1239  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:36.666  3089  3419 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-30 22:19:36.666  3089  3419 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at jdm.a(PG:82)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at jcs.o(PG:406)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at jcn.a(PG:1379)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at jcs.i(PG:143)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at blb.a(PG:3937)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at czp.a(PG:18188)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at czp.a(PG:9081)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at czq.run(PG:1686)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:19:36.666  3089  3419 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at jdj.a(PG:4091)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at jdj.a(PG:1125)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at jdm.a(PG:77)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	... 12 more
03-30 22:19:36.666  3089  3419 E HttpOperation: Caused by: faj: BadAuthentication
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at fal.a(PG:38)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	at jdj.a(PG:4089)
03-30 22:19:36.666  3089  3419 E HttpOperation: 	... 14 more
,03-30 22:19:36.703  1239  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-30 22:19:36.703  1239  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:36.703  1239  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:36.703  1239  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:36.706  1239  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:36.715  3089  3419 E HttpOperation: [getmobileexperiments] Unexpected exception
03-30 22:19:36.715  3089  3419 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at jdm.a(PG:82)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at jcs.o(PG:406)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at jcn.a(PG:1379)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at jcs.i(PG:143)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at hec.a(PG:42)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at hee.a(PG:102)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at czr.a(PG:65)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at kka.a(PG:108)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at czp.a(PG:19176)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at czp.a(PG:9081)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at czq.run(PG:1686)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:19:36.715  3089  3419 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at jdj.a(PG:4091)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at jdj.a(PG:1125)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at jdm.a(PG:77)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	... 15 more
03-30 22:19:36.715  3089  3419 E HttpOperation: Caused by: faj: BadAuthentication
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at fal.a(PG:38)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	at jdj.a(PG:4089)
03-30 22:19:36.715  3089  3419 E HttpOperation: 	... 17 more
,03-30 22:19:36.716  3089  3419 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-30 22:19:36.716  3089  3419 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at jdm.a(PG:82)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at jcs.o(PG:406)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at jcn.a(PG:1379)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at jcs.i(PG:143)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at hec.a(PG:42)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at hee.a(PG:102)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at czr.a(PG:65)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at kka.a(PG:108)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at czp.a(PG:19176)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at czp.a(PG:9081)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at czq.run(PG:1686)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at jdj.a(PG:4091)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at jdj.a(PG:1125)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at jdm.a(PG:77)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	... 15 more
03-30 22:19:36.716  3089  3419 E ExperimentLoader: Caused by: faj: BadAuthentication
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at fal.a(PG:38)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	at jdj.a(PG:4089)
03-30 22:19:36.716  3089  3419 E ExperimentLoader: 	... 17 more
,03-30 22:19:36.810   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 39922, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-30 22:19:36.857   823   853 I ActivityManager: Start proc 3488:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-30 22:19:36.865  1804  3422 W DriveInitializer: Background init thread ended
,03-30 22:19:36.882  3436  3436 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-30 22:19:36.882  3436  3436 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-30 22:19:36.882  3436  3436 I GAv4    :   adb logcat -s GAv4
03-30 22:19:36.882  3459  3484 V KeepSync: Connecting to GoogleApiClient
,03-30 22:19:36.903  3151  3435 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-30 22:19:36.905   823   839 I ActivityManager: Killing 2442:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-30 22:19:36.961  3436  3436 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-30 22:19:36.978  3436  3436 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-30 22:19:37.006  3436  3513 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-30 22:19:37.032  1804  3514 W BaseAppContext: Using Auth Proxy for data requests.
,03-30 22:19:37.038  1804  3514 W BaseAppContext: Using Auth Proxy for data requests.
,03-30 22:19:37.063  1239  1257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-30 22:19:37.063  1239  1257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:37.063  1239  1257 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:37.063  1239  1257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:37.066  1239  1257 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: Handling authorization failure
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-30 22:19:37.078  1804  3514 E ClientConnectionOperation: 	... 7 more
,03-30 22:19:37.080  3459  3484 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-30 22:19:37.082  3459  3484 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-30 22:19:37.088  3459  3484 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-30 22:19:37.088  3459  3484 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-30 22:19:37.166  3436  3436 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-30 22:19:37.177  3436  3436 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 671-673)
,03-30 22:19:37.177  3436  3436 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-30 22:19:37.181  3436  3436 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ed70b09}
03-30 22:19:37.181  3436  3436 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-30 22:19:37.181  3436  3436 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-30 22:19:37.186  1239  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-30 22:19:37.186  1239  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:37.186  1239  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:37.186  1239  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:37.189  1239  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-30 22:19:37.192  3436  3436 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-30 22:19:37.194  3436  3436 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-30 22:19:37.195  3436  3436 E SysUtils: ApplicationContext is null in ApplicationStatus
03-30 22:19:37.213  3436  3436 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-30 22:19:37.218  3436  3436 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-30 22:19:37.218  3436  3436 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-30 22:19:37.218  3436  3436 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-30 22:19:37.265   823  1433 I art     : Explicit concurrent mark sweep GC freed 49543(2MB) AllocSpace objects, 6(137KB) LOS objects, 32% free, 33MB/49MB, paused 1.335ms total 70.739ms
,03-30 22:19:37.294  3436  3548 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-30 22:19:37.304  3488  3488 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-30 22:19:37.308  3459  3484 E KeepSync: IOException
03-30 22:19:37.308  3459  3484 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-30 22:19:37.308  3459  3484 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-30 22:19:37.308  3459  3484 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-30 22:19:37.308  3459  3484 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-30 22:19:37.308  3459  3484 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-30 22:19:37.308  3459  3484 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-30 22:19:37.308  3459  3484 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-30 22:19:37.308  3459  3484 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-30 22:19:37.308  3459  3484 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-30 22:19:37.308  3459  3484 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-30 22:19:37.308  3459  3484 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-30 22:19:37.308  3459  3484 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-30 22:19:37.308  3459  3484 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-30 22:19:37.308  3459  3484 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-30 22:19:37.308  3459  3484 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-30 22:19:37.308  3459  3484 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-30 22:19:37.308  3459  3484 E KeepSync: 	... 10 more
,03-30 22:19:37.309  3459  3484 W KeepSync: Sync result 2
03-30 22:19:37.311  3436  3436 I NSApplication: Starting up...
03-30 22:19:37.311  3488  3488 I BooksApp: Created application version: 3.6.8 (30608)
,03-30 22:19:37.319   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 39928, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-30 22:19:37.340  1239  1256 I art     : Explicit concurrent mark sweep GC freed 13051(780KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 26MB/42MB, paused 574us total 20.283ms
,03-30 22:19:37.350   823  1242 I ActivityManager: Start proc 3556:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-30 22:19:37.351   823  1242 I ActivityManager: Killing 2997:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-30 22:19:37.581   823  1242 I ActivityManager: Killing 3017:com.android.musicfx/u0a18 (adj 15): empty #17
,03-30 22:19:37.734  3488  3575 I BooksSync: Starting books sync for 61035162, extras: ade
,03-30 22:19:37.871  3488  3581 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-30 22:19:37.941  1239  3574 D GCM     : Connected
,03-30 22:19:37.948  1239  1257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-30 22:19:37.948  1239  1257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:37.948  1239  1257 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:37.948  1239  1257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:37.951  1239  1257 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:37.954  1239  3574 D GCM     : Message class com.google.f.a.a.p
,03-30 22:19:37.996  1239  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-30 22:19:37.996  1239  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:37.996  1239  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:37.996  1239  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:37.999  1239  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:38.009  3488  3581 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-30 22:19:38.010  3488  3575 E BooksSync: Soft error
03-30 22:19:38.010  3488  3575 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-30 22:19:38.010  3488  3575 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-30 22:19:38.010  3488  3575 E BooksSync: Sync error
03-30 22:19:38.010  3488  3575 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-30 22:19:38.010  3488  3575 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-30 22:19:38.010  3488  3575 I BooksSync: Finished books sync
,03-30 22:19:38.017   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 39928, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-30 22:19:38.017   823  1230 I ActivityManager: Killing 2790:com.google.android.gms:car/u0a11 (adj 15): empty #17
,03-30 22:19:38.123   823  1230 I ActivityManager: Killing 3048:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,03-30 22:19:38.235   823  2549 I ActivityManager: Killing 1437:android.process.acore/u0a5 (adj 15): empty #17
,03-30 22:19:38.402   823  1230 I ActivityManager: Start proc 3586:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-30 22:19:39.278   823  1102 I ActivityManager: Killing 2810:com.google.android.gm/u0a78 (adj 15): empty #17
,03-30 22:19:39.433   823   839 I ActivityManager: Start proc 3604:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-30 22:19:39.500  3604  3604 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459369179500
03-30 22:19:39.500  3604  3604 D         : TimeServiceNative: User Time to be set is 1459369179500
03-30 22:19:39.500  3604  3604 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-30 22:19:39.500  3604  3604 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-30 22:19:39.500  3604  3604 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459369179500
03-30 22:19:39.501   372   873 D QC-time-services: Daemon: Connection accepted:time_genoff
03-30 22:19:39.501  3604  3604 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-30 22:19:39.501   372  3621 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459369179500
03-30 22:19:39.501   372  3621 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459369179500, operation = 0
03-30 22:19:39.501   372  3621 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/16/70 16:31:18
03-30 22:19:39.501   372  3621 D QC-time-services: Daemon:Value read from RTC seconds = 19672278000
03-30 22:19:39.501   372  3621 D QC-time-services: Daemon:new time 1459369179500 
03-30 22:19:39.501   372  3621 D QC-time-services: Daemon: delta 1439696901500 genoff 1439696901500 
03-30 22:19:39.501   372  3621 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696901500 to memory
,03-30 22:19:39.501   372  3621 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-30 22:19:39.501   372  3621 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-30 22:19:39.504   372  3621 D QC-time-services: Updating the TOD offset
,03-30 22:19:39.504   372  3621 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696901500 to memory
03-30 22:19:39.504   372  3621 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-30 22:19:39.504   372  3621 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-30 22:19:39.507   372  3621 E QC-time-services: Daemon:Update to modem bit set
03-30 22:19:39.507   372  3621 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !,
03-30 22:19:39.507   372  3621 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143404379500
03-30 22:19:39.507  3604  3604 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-30 22:19:39.576   372   873 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-30 22:19:39.581   372   871 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-30 22:19:39.615   823  1260 I ActivityManager: Start proc 3623:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-30 22:19:39.621   823  1102 I ActivityManager: Killing 1879:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-30 22:19:39.764  3623  3623 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-30 22:19:39.764  3623  3623 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-30 22:19:39.764  3623  3623 I GAv4    :   adb logcat -s GAv4
,03-30 22:19:39.797  3623  3623 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-30 22:19:39.809  3623  3623 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-30 22:19:39.822  3623  3642 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-30 22:19:39.937   823  1102 I ActivityManager: Killing 3124:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-30 22:19:40.096  1804  1804 V Herrevad: NQAS connected
,03-30 22:19:40.100   823  1013 D WifiService: New client listening to asynchronous messages
,03-30 22:19:40.107  3151  3151 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-30 22:19:40.107  3151  3151 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-30 22:19:40.145   823  1433 I ActivityManager: Start proc 3650:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,03-30 22:19:40.168  3650  3650 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-30 22:19:40.210  3650  3650 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@3e079505(com.android.providers.calendar.CalendarProvider2@3f80295a)
,03-30 22:19:40.278  1239  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-30 22:19:40.279  1239  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:40.279  1239  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:40.279  1239  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:40.282  1239  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:40.343   823  1242 I art     : Explicit concurrent mark sweep GC freed 18127(839KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 1.850ms total 56.049ms
,03-30 22:19:40.377  3151  3667 E Babel   : UserRecoverableAuthException.
,03-30 22:19:40.377  3151  3667 E Babel   : eei: BadAuthentication
03-30 22:19:40.377  3151  3667 E Babel   : 	at eeg.a(Unknown Source)
03-30 22:19:40.377  3151  3667 E Babel   : 	at eeg.a(Unknown Source)
03-30 22:19:40.377  3151  3667 E Babel   : 	at eeg.a(Unknown Source)
03-30 22:19:40.377  3151  3667 E Babel   : 	at g.a(Unknown Source)
03-30 22:19:40.377  3151  3667 E Babel   : 	at cae.a(SourceFile:3089)
03-30 22:19:40.377  3151  3667 E Babel   : 	at cae.a(SourceFile:1131)
03-30 22:19:40.377  3151  3667 E Babel   : 	at cws.a(SourceFile:4333)
03-30 22:19:40.377  3151  3667 E Babel   : 	at cws.a(SourceFile:1419)
03-30 22:19:40.377  3151  3667 E Babel   : 	at crl.a(SourceFile:492)
03-30 22:19:40.377  3151  3667 E Babel   : 	at crl.a(SourceFile:1468)
03-30 22:19:40.377  3151  3667 E Babel   : 	at cqu.a(SourceFile:4416)
03-30 22:19:40.377  3151  3667 E Babel   : 	at cas.b(SourceFile:106)
03-30 22:19:40.377  3151  3667 E Babel   : 	at cap.d(SourceFile:335)
03-30 22:19:40.377  3151  3667 E Babel   : 	at caq.run(SourceFile:81)
03-30 22:19:40.377  3151  3667 E Babel   : Error getting auth token
03-30 22:19:40.378  3151  3667 E Babel   : dvm
03-30 22:19:40.378  3151  3667 E Babel   : 	at g.a(Unknown Source)
03-30 22:19:40.378  3151  3667 E Babel   : 	at cae.a(SourceFile:3089)
03-30 22:19:40.378  3151  3667 E Babel   : 	at cae.a(SourceFile:1131)
03-30 22:19:40.378  3151  3667 E Babel   : 	at cws.a(SourceFile:4333)
03-30 22:19:40.378  3151  3667 E Babel   : 	at cws.a(SourceFile:1419)
03-30 22:19:40.378  3151  3667 E Babel   : 	at crl.a(SourceFile:492)
03-30 22:19:40.378  3151  3667 E Babel   : 	at crl.a(SourceFile:1468)
03-30 22:19:40.378  3151  3667 E Babel   : 	at cqu.a(SourceFile:4416)
03-30 22:19:40.378  3151  3667 E Babel   : 	at cas.b(SourceFile:106)
03-30 22:19:40.378  3151  3667 E Babel   : 	at cap.d(SourceFile:335)
03-30 22:19:40.378  3151  3667 E Babel   : 	at caq.run(SourceFile:81)
,03-30 22:19:40.380  3151  3667 E Babel   : Account registration failed 1-Redacted-21
,03-30 22:19:40.380  3151  3667 E Babel   : cyp: null -- null
03-30 22:19:40.380  3151  3667 E Babel   : 	at cae.a(SourceFile:3121)
03-30 22:19:40.380  3151  3667 E Babel   : 	at cae.a(SourceFile:1131)
03-30 22:19:40.380  3151  3667 E Babel   : 	at cws.a(SourceFile:4333)
03-30 22:19:40.380  3151  3667 E Babel   : 	at cws.a(SourceFile:1419)
03-30 22:19:40.380  3151  3667 E Babel   : 	at crl.a(SourceFile:492)
03-30 22:19:40.380  3151  3667 E Babel   : 	at crl.a(SourceFile:1468)
03-30 22:19:40.380  3151  3667 E Babel   : 	at cqu.a(SourceFile:4416)
03-30 22:19:40.380  3151  3667 E Babel   : 	at cas.b(SourceFile:106)
03-30 22:19:40.380  3151  3667 E Babel   : 	at cap.d(SourceFile:335)
03-30 22:19:40.380  3151  3667 E Babel   : 	at caq.run(SourceFile:81)
,03-30 22:19:40.389  3151  3667 I art     : Note: end time exceeds epoch: 
,03-30 22:19:40.401  1239  2547 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-30 22:19:40.401  1239  2547 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-30 22:19:40.401  1239  2547 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:40.402  1239  2547 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:40.404  1239  2547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:40.415  1239  2547 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-30 22:19:40.429  3151  3678 E Babel   : Unexpected exception while authenticating.
,03-30 22:19:40.430  3151  3678 E Babel   : eej: User intervention required. Notification has been pushed.
03-30 22:19:40.430  3151  3678 E Babel   : 	at eeg.b(Unknown Source)
03-30 22:19:40.430  3151  3678 E Babel   : 	at eeg.b(Unknown Source)
03-30 22:19:40.430  3151  3678 E Babel   : 	at g.a(Unknown Source)
03-30 22:19:40.430  3151  3678 E Babel   : 	at cae.b(SourceFile:1146)
03-30 22:19:40.430  3151  3678 E Babel   : 	at dcg.run(SourceFile:5617)
03-30 22:19:40.430  3151  3678 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:19:40.430  3151  3678 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:19:40.430  3151  3678 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-30 22:19:41.257  3650  3650 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-30 22:19:41.257  3650  3650 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-30 22:19:41.371  3650  3681 E SQLiteLog: (284) automatic index on view_events(_id)
,03-30 22:19:42.315  3488  3549 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-30 22:19:43.765  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 22:19:43.765  3267  3325 I jxcore-log: 
,03-30 22:19:43.768  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-30 22:19:43.768  3267  3325 I jxcore-log: 
,03-30 22:19:43.785  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 22:19:43.785  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:19:43.785  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:19:43.785  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:19:43.785  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:19:43.785  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
03-30 22:19:43.785  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:19:43.785  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:19:43.823  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 22:19:43.826  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 22:19:43.826  3267  3325 I jxcore-log: 
,03-30 22:19:43.829  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 22:19:43.829  3267  3325 I jxcore-log: 
,03-30 22:19:43.882  1239  1239 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:43.969  1239  3689 I VacuumService: Vacuum at: now=1459369183969 tag=VacuumService
,03-30 22:19:44.036  3368  3688 V GoogleAuthProtoRequest: [335] a.<init>: mAccountName set to: thalitester@gmail.com
,03-30 22:19:44.066  1239  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-30 22:19:44.066  1239  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:44.066  1239  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:44.066  1239  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:44.072  1239  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:44.085  3368  3688 W ExperimentUpdateService: [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-30 22:19:44.087  3368  3688 W ExperimentUpdateService: [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-30 22:19:44.087  3368  3688 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-30 22:19:44.087  3368  3688 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-30 22:19:44.087  3368  3688 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-30 22:19:44.087  3368  3688 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-30 22:19:44.087  3368  3688 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-30 22:19:44.087  3368  3688 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-30 22:19:44.087  3368  3688 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-30 22:19:44.087  3368  3688 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-30 22:19:44.087  3368  3688 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-30 22:19:44.087  3368  3688 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-30 22:19:44.161  1239  3690 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-30 22:19:44.175  1239  3690 W Uploader: No account for auth token provided
,03-30 22:19:44.365  3267  3325 I jxcore-log: Unit Test app is loaded
03-30 22:19:44.365  3267  3325 I jxcore-log: 
,03-30 22:19:44.371  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:19:44.371  3267  3325 I jxcore-log: 
,03-30 22:19:44.384  3267  3325 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-30 22:19:44.388  3267  3267 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-30 22:19:44.390  3267  3325 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-30 22:19:44.390  3267  3325 I jxcore-log: 
,03-30 22:19:44.395  3267  3325 I jxcore-log: My device name is: motorola-Nexus 6
03-30 22:19:44.395  3267  3325 I jxcore-log: 
,03-30 22:19:44.745  1239  3690 W Uploader: No account for auth token provided
,03-30 22:19:44.942  1239  3690 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-30 22:19:44.943  1239  3690 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:44.943  1239  3690 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-30 22:19:44.943  1239  3690 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:44.953  1239  3690 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:45.014  1239  3690 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-30 22:19:45.014  1239  3690 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-30 22:19:45.014  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-30 22:19:45.014  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-30 22:19:45.014  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-30 22:19:45.014  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-30 22:19:45.014  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-30 22:19:45.014  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-30 22:19:45.014  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-30 22:19:45.014  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-30 22:19:45.014  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-30 22:19:45.014  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-30 22:19:45.014  1239  3690 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-30 22:19:45.135  1239  3690 W Uploader: No account for auth token provided
,03-30 22:19:45.327  1239  3690 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-30 22:19:45.327  1239  3690 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-30 22:19:45.327  1239  3690 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-30 22:19:45.327  1239  3690 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:45.344  1239  3690 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:45.404  1239  3690 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-30 22:19:45.404  1239  3690 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-30 22:19:45.404  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-30 22:19:45.404  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-30 22:19:45.404  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-30 22:19:45.404  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-30 22:19:45.404  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-30 22:19:45.404  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-30 22:19:45.404  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-30 22:19:45.404  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-30 22:19:45.404  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-30 22:19:45.404  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-30 22:19:45.404  1239  3690 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-30 22:19:45.747  1239  3690 W Uploader: No account for auth token provided
,03-30 22:19:45.850  1239  3690 W Uploader: No account for auth token provided
,03-30 22:19:45.980  1239  3690 W Uploader: No account for auth token provided
,03-30 22:19:46.120  1239  3690 W Uploader: No account for auth token provided
,03-30 22:19:46.289  1239  3690 W Uploader: No account for auth token provided
,03-30 22:19:46.424  1239  3690 W Uploader:  no longer exists, so no auth token.
,03-30 22:19:46.444   823   838 I ActivityManager: Killing 2749:com.android.vending/u0a19 (adj 15): empty #17
,03-30 22:19:46.722  1239  1239 I art     : Explicit concurrent mark sweep GC freed 52623(3MB) AllocSpace objects, 6(401KB) LOS objects, 36% free, 27MB/43MB, paused 1.581ms total 40.553ms
,03-30 22:19:46.775  1239  3690 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-30 22:19:46.775  1239  3690 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:46.776  1239  3690 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:46.776  1239  3690 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:46.779  1239  3690 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:46.806  1239  3690 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-30 22:19:46.806  1239  3690 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-30 22:19:46.806  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-30 22:19:46.806  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-30 22:19:46.806  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-30 22:19:46.806  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-30 22:19:46.806  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-30 22:19:46.806  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-30 22:19:46.806  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-30 22:19:46.806  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-30 22:19:46.806  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-30 22:19:46.806  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-30 22:19:46.806  1239  3690 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-30 22:19:46.943  1239  3690 W Uploader: No account for auth token provided
,03-30 22:19:47.200  1239  3690 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-30 22:19:47.201  1239  3690 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:47.201  1239  3690 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:47.201  1239  3690 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:47.213  1239  3690 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:47.294  1239  3690 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-30 22:19:47.294  1239  3690 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-30 22:19:47.294  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-30 22:19:47.294  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-30 22:19:47.294  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-30 22:19:47.294  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-30 22:19:47.294  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-30 22:19:47.294  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-30 22:19:47.294  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-30 22:19:47.294  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-30 22:19:47.294  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-30 22:19:47.294  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-30 22:19:47.294  1239  3690 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-30 22:19:47.413  1239  3690 W Uploader: No account for auth token provided
,03-30 22:19:47.576  1239  3690 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-30 22:19:47.576  1239  3690 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:47.576  1239  3690 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:47.576  1239  3690 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:47.581  1239  3690 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:47.625  1239  3690 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-30 22:19:47.625  1239  3690 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-30 22:19:47.625  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-30 22:19:47.625  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-30 22:19:47.625  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-30 22:19:47.625  1239  3690 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-30 22:19:47.625  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-30 22:19:47.625  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-30 22:19:47.625  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-30 22:19:47.625  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-30 22:19:47.625  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-30 22:19:47.625  1239  3690 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-30 22:19:47.625  1239  3690 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-30 22:19:47.752   823  1260 I ActivityManager: Start proc 3693:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,03-30 22:19:47.919  3693  3693 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-30 22:19:48.020  3693  3693 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-30 22:19:48.124   823  1230 I ActivityManager: Start proc 3729:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-30 22:19:48.162  3693  3693 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-30 22:19:48.165  3693  3693 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-30 22:19:48.184  3729  3729 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-30 22:19:48.184  3729  3729 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-30 22:19:48.203   823  1433 I ActivityManager: Killing 2933:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-30 22:19:48.218  3693  3708 D Finsky  : [374] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-30 22:19:48.227  3729  3729 I MultiDex: VM with version 2.1.0 has multidex support
,03-30 22:19:48.227  3729  3729 I MultiDex: install
03-30 22:19:48.227  3729  3729 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-30 22:19:48.343  1239  1239 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:48.346  3693  3693 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-30 22:19:48.346  3693  3693 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-30 22:19:48.353  3693  3693 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-30 22:19:48.364  3729  3729 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-30 22:19:48.380  1239  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-30 22:19:48.381  1239  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:48.381  1239  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:48.381  1239  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:48.384  1239  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-30 22:19:48.384  3693  3693 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-30 22:19:48.398  3693  3708 D Finsky  : [374] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-30 22:19:48.421  3729  3729 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-30 22:19:48.428  1239  2105 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-30 22:19:48.431  1239  1239 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-30 22:19:48.438  1804  1804 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-30 22:19:48.454  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-30 22:19:48.454  3267  3325 I jxcore-log: 
,03-30 22:19:48.485   823  1242 I ActivityManager: Start proc 3757:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-30 22:19:48.498   369   369 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 313us total 14.045ms
,03-30 22:19:48.512   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 308us total 12.803ms
,03-30 22:19:48.524   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 248us total 10.887ms
,03-30 22:19:48.530  1804  3772 D LocationInitializer: Restart initialization of location
,03-30 22:19:48.534  3757  3757 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-30 22:19:48.535  3757  3757 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-30 22:19:48.559  3757  3757 I MultiDex: VM with version 2.1.0 has multidex support
03-30 22:19:48.559  3757  3757 I MultiDex: install
03-30 22:19:48.559  3757  3757 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-30 22:19:48.584  3757  3757 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-30 22:19:48.616  3757  3757 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-30 22:19:48.623  1239  2109 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-30 22:19:48.627  1239  1239 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-30 22:19:48.631  1804  1804 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-30 22:19:48.634  3757  3780 W NativeLibraryUtils: Install did not work
03-30 22:19:48.634  3757  3780 W NativeLibraryUtils: java.io.IOException: fcntl failed: EAGAIN (Try again)
03-30 22:19:48.634  3757  3780 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
03-30 22:19:48.634  3757  3780 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
03-30 22:19:48.634  3757  3780 W NativeLibraryUtils: 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
03-30 22:19:48.634  3757  3780 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
03-30 22:19:48.634  3757  3780 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:136)
03-30 22:19:48.634  3757  3780 W NativeLibraryUtils: Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
03-30 22:19:48.634  3757  3780 W NativeLibraryUtils: 	at libcore.io.Posix.fcntlFlock(Native Method)
03-30 22:19:48.634  3757  3780 W NativeLibraryUtils: 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
03-30 22:19:48.634  3757  3780 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
03-30 22:19:48.634  3757  3780 W NativeLibraryUtils: 	... 4 more
,03-30 22:19:48.634  3757  3757 D WearableService: callingUid 10011, callindPid: 3757
,03-30 22:19:48.647  1804  3781 D LocationInitializer: Restart initialization of location
,03-30 22:19:48.657  1842  2067 E MDM     : [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-30 22:19:48.660  1842  2067 E MDM     : [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-30 22:19:48.795  3693  3693 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-30 22:19:48.860  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-30 22:19:48.860  3267  3325 I jxcore-log: 
,03-30 22:19:48.870  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-30 22:19:48.870  3267  3325 I jxcore-log: 
,03-30 22:19:48.874  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-30 22:19:48.874  3267  3325 I jxcore-log: 
,03-30 22:19:48.909  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-30 22:19:48.909  3267  3325 I jxcore-log: 
,03-30 22:19:48.924  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-30 22:19:48.924  3267  3325 I jxcore-log: 
,03-30 22:19:48.927  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-30 22:19:48.927  3267  3325 I jxcore-log: 
,03-30 22:19:49.116   823   999 I art     : Explicit concurrent mark sweep GC freed 24186(1144KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 2.380ms total 86.588ms
,03-30 22:19:49.153  3693  3693 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-30 22:19:49.182  1239  1239 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:49.200  1239  1257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-30 22:19:49.200  1239  1257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:49.200  1239  1257 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:49.200  1239  1257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:49.203  1239  1257 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:49.213  3693  3693 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-30 22:19:49.218  1239  1239 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:49.237  1239  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-30 22:19:49.238  1239  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-30 22:19:49.238  1239  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:49.238  1239  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:49.242  1239  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:49.266  1239  1239 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:49.292  1239  1730 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-30 22:19:49.292  1239  1730 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:19:49.292  1239  1730 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:49.292  1239  1730 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:19:49.298  1239  1730 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:49.315  3693  3693 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-30 22:19:49.662  1239  1239 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:49.726  1239  1754 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-30 22:19:49.727  1239  1754 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,03-30 22:19:49.727  1239  1754 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:19:49.727  1239  1754 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,03-30 22:19:49.738  1239  1754 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:19:49.776  3693  3693 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-30 22:19:49.783  3693  3693 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-30 22:19:49.801  3693  3693 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-30 22:19:49.809  3693  3693 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,03-30 22:19:49.837  1842  1858 D DeviceConnectionService: client connected with version: 7571000
,03-30 22:19:50.955  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-30 22:19:50.955  3267  3325 I jxcore-log: 
,03-30 22:19:50.972  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
03-30 22:19:50.972  3267  3325 I jxcore-log: 
,03-30 22:19:50.981  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-30 22:19:50.981  3267  3325 I jxcore-log: 
,03-30 22:19:51.227  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-30 22:19:51.227  3267  3325 I jxcore-log: 
,03-30 22:19:51.297  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-30 22:19:51.297  3267  3325 I jxcore-log: 
,03-30 22:19:51.352  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-30 22:19:51.352  3267  3325 I jxcore-log: 
,03-30 22:19:51.359  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-30 22:19:51.359  3267  3325 I jxcore-log: 
,03-30 22:19:51.370  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-30 22:19:51.370  3267  3325 I jxcore-log: 
,03-30 22:19:51.374  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-30 22:19:51.374  3267  3325 I jxcore-log: 
,03-30 22:19:51.380  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-30 22:19:51.380  3267  3325 I jxcore-log: 
,03-30 22:19:51.395  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-30 22:19:51.395  3267  3325 I jxcore-log: 
,03-30 22:19:51.413  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-30 22:19:51.413  3267  3325 I jxcore-log: 
,03-30 22:19:51.495  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-30 22:19:51.495  3267  3325 I jxcore-log: 
,03-30 22:19:51.501  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-30 22:19:51.501  3267  3325 I jxcore-log: 
,03-30 22:19:51.527  3267  3325 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-30 22:19:51.527  3267  3325 I jxcore-log: 
,03-30 22:19:52.791  3267  3325 I jxcore-log: TAP version 13
03-30 22:19:52.791  3267  3325 I jxcore-log: 
,03-30 22:19:52.794  3267  3325 I jxcore-log: # setup
03-30 22:19:52.794  3267  3325 I jxcore-log: 
,03-30 22:19:53.336  3267  3325 I jxcore-log: # 1. calling createNativeListener directly rejects
03-30 22:19:53.336  3267  3325 I jxcore-log: 
,03-30 22:19:53.479  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server,
03-30 22:19:53.479  3267  3325 I jxcore-log: 
,03-30 22:19:53.484  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 51960
03-30 22:19:53.484  3267  3325 I jxcore-log: 
,03-30 22:19:53.490  3267  3325 I jxcore-log: ok 1 Should throw
03-30 22:19:53.490  3267  3325 I jxcore-log: 
,03-30 22:19:53.492  3267  3325 I jxcore-log: # teardown
03-30 22:19:53.492  3267  3325 I jxcore-log: 
,03-30 22:19:53.678   823   839 I ActivityManager: Killing 3401:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-30 22:19:53.702  3267  3325 I jxcore-log: # setup
03-30 22:19:53.702  3267  3325 I jxcore-log: 
,03-30 22:19:53.889  3267  3325 I jxcore-log: # 2. emits incomingConnectionState
03-30 22:19:53.889  3267  3325 I jxcore-log: 
,03-30 22:19:53.908   823  1102 I ActivityManager: Killing 3436:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-30 22:19:54.078  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:19:54.078  3267  3325 I jxcore-log: 
,03-30 22:19:54.082  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 42541,
03-30 22:19:54.082  3267  3325 I jxcore-log: ,
,03-30 22:19:54.092  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:19:54.092  3267  3325 I jxcore-log: 
,03-30 22:19:54.096  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:19:54.096  3267  3325 I jxcore-log: 
,03-30 22:19:54.106  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:19:54.106  3267  3325 I jxcore-log: 
,03-30 22:19:54.112  3267  3325 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-30 22:19:54.112  3267  3325 I jxcore-log: 
,03-30 22:19:54.129  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:19:54.129  3267  3325 I jxcore-log: 
,03-30 22:19:54.130  3267  3325 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-30 22:19:54.130  3267  3325 I jxcore-log: 
,03-30 22:19:54.138  3267  3325 I jxcore-log: # teardown,
03-30 22:19:54.138  3267  3325 I jxcore-log: 
,03-30 22:19:54.158  2148  2213 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,03-30 22:19:55.647  3267  3325 I jxcore-log: # setup
03-30 22:19:55.647  3267  3325 I jxcore-log: 
,03-30 22:19:55.867  3267  3325 I jxcore-log: # 3. emits routerPortConnectionFailed
03-30 22:19:55.867  3267  3325 I jxcore-log: 
,03-30 22:19:56.234  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:19:56.234  3267  3325 I jxcore-log: 
,03-30 22:19:56.236  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 38421
03-30 22:19:56.236  3267  3325 I jxcore-log: 
,03-30 22:19:56.246  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:19:56.246  3267  3325 I jxcore-log: 
,03-30 22:19:56.249  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:19:56.249  3267  3325 I jxcore-log: 
,03-30 22:19:56.253  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:19:56.253  3267  3325 I jxcore-log: 
,03-30 22:19:56.287  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:19:56.287  3267  3325 I jxcore-log: 
,03-30 22:19:56.290  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:19:56.290  3267  3325 I jxcore-log: 
,03-30 22:19:56.295  3267  3325 I jxcore-log: DEBUG createNativeListener: 
03-30 22:19:56.295  3267  3325 I jxcore-log: 
,03-30 22:19:56.297  3267  3325 I jxcore-log: ok 4 tried to connect to right port
03-30 22:19:56.297  3267  3325 I jxcore-log: 
03-30 22:19:56.297  3267  3325 I jxcore-log: ok 5 failed due to refused connection
03-30 22:19:56.297  3267  3325 I jxcore-log: 
,03-30 22:19:56.298  3267  3325 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-30 22:19:56.298  3267  3325 I jxcore-log: 
,03-30 22:19:56.303  3267  3325 I jxcore-log: # teardown
03-30 22:19:56.303  3267  3325 I jxcore-log: 
,03-30 22:19:56.305  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:19:56.305  3267  3325 I jxcore-log: 
,03-30 22:19:56.647  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:19:56.647  3267  3325 I jxcore-log: 
,03-30 22:19:56.652  3267  3325 I jxcore-log: # setup
03-30 22:19:56.652  3267  3325 I jxcore-log: 
03-30 22:19:56.653  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:19:56.653  3267  3325 I jxcore-log: 
,03-30 22:19:57.026  3267  3325 I jxcore-log: # 4. native server connections all up
03-30 22:19:57.026  3267  3325 I jxcore-log: 
,03-30 22:19:57.151  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:19:57.151  3267  3325 I jxcore-log: 
,03-30 22:19:57.161  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 55032
03-30 22:19:57.161  3267  3325 I jxcore-log: 
,03-30 22:19:57.170  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:19:57.170  3267  3325 I jxcore-log: 
,03-30 22:19:57.171  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:19:57.171  3267  3325 I jxcore-log: 
,03-30 22:19:57.173  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:19:57.173  3267  3325 I jxcore-log: 
,03-30 22:19:57.199  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:19:57.199  3267  3325 I jxcore-log: 
,03-30 22:19:57.203  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:19:57.203  3267  3325 I jxcore-log: 
,03-30 22:19:57.206  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:19:57.206  3267  3325 I jxcore-log: 
,03-30 22:19:57.208  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:19:57.208  3267  3325 I jxcore-log: 
,03-30 22:19:57.237  3267  3325 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-30 22:19:57.237  3267  3325 I jxcore-log: 
,03-30 22:19:57.237  3267  3325 I jxcore-log: ok 8 Send/recvd #1 should be same
03-30 22:19:57.237  3267  3325 I jxcore-log: 
,03-30 22:19:57.240  3267  3325 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-30 22:19:57.240  3267  3325 I jxcore-log: 
03-30 22:19:57.240  3267  3325 I jxcore-log: ok 10 Send/recvd #2 should be same
03-30 22:19:57.240  3267  3325 I jxcore-log: 
,03-30 22:19:57.243  3267  3325 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-30 22:19:57.243  3267  3325 I jxcore-log: 
,03-30 22:19:57.250  3267  3325 I jxcore-log: # teardown
03-30 22:19:57.250  3267  3325 I jxcore-log: 
,03-30 22:19:57.429  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:19:57.429  3267  3325 I jxcore-log: 
,03-30 22:19:57.432  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:19:57.432  3267  3325 I jxcore-log: 
,03-30 22:19:57.435  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:19:57.435  3267  3325 I jxcore-log: 
,03-30 22:19:57.439  3267  3325 I jxcore-log: # setup
03-30 22:19:57.439  3267  3325 I jxcore-log: 
,03-30 22:19:57.440  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:19:57.440  3267  3325 I jxcore-log: 
,03-30 22:19:57.626  3267  3325 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-30 22:19:57.626  3267  3325 I jxcore-log: 
,03-30 22:19:57.784  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:19:57.784  3267  3325 I jxcore-log: 
,03-30 22:19:57.787  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 51232
,03-30 22:19:57.787  3267  3325 I jxcore-log: 
,03-30 22:19:57.793  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:19:57.793  3267  3325 I jxcore-log: 
,03-30 22:19:57.794  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:19:57.794  3267  3325 I jxcore-log: 
,03-30 22:19:57.796  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:19:57.796  3267  3325 I jxcore-log: 
,03-30 22:19:57.808  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:19:57.808  3267  3325 I jxcore-log: 
,03-30 22:19:57.810  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:19:57.810  3267  3325 I jxcore-log: 
,03-30 22:19:57.823  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:19:57.823  3267  3325 I jxcore-log: 
,03-30 22:19:57.836  3267  3325 I jxcore-log: ok 12 socket shouldn't close until after stream
03-30 22:19:57.836  3267  3325 I jxcore-log: 
,03-30 22:19:57.836  3267  3325 I jxcore-log: ok 13 incoming remains open
03-30 22:19:57.836  3267  3325 I jxcore-log: 
,03-30 22:19:57.842  3267  3325 I jxcore-log: # teardown
03-30 22:19:57.842  3267  3325 I jxcore-log: 
,03-30 22:19:57.987  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:19:57.987  3267  3325 I jxcore-log: 
,03-30 22:19:57.992  3267  3325 I jxcore-log: # setup
03-30 22:19:57.992  3267  3325 I jxcore-log: 
,03-30 22:19:57.993  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:19:57.993  3267  3325 I jxcore-log: 
,03-30 22:19:58.886  3267  3325 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-30 22:19:58.886  3267  3325 I jxcore-log: 
,03-30 22:19:59.025  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:19:59.025  3267  3325 I jxcore-log: 
,03-30 22:19:59.028  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 51110
03-30 22:19:59.028  3267  3325 I jxcore-log: 
,03-30 22:19:59.034  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:19:59.034  3267  3325 I jxcore-log: 
,03-30 22:19:59.035  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:19:59.035  3267  3325 I jxcore-log: 
03-30 22:19:59.036  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:19:59.036  3267  3325 I jxcore-log: 
,03-30 22:19:59.047  3267  3325 I jxcore-log: ok 14 we should not have gotten an error
03-30 22:19:59.047  3267  3325 I jxcore-log: 
,03-30 22:19:59.052  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:19:59.052  3267  3325 I jxcore-log: 
,03-30 22:19:59.057  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:19:59.057  3267  3325 I jxcore-log: 
,03-30 22:19:59.067  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:19:59.067  3267  3325 I jxcore-log: 
,03-30 22:19:59.070  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:19:59.070  3267  3325 I jxcore-log: 
,03-30 22:19:59.077  3267  3325 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-30 22:19:59.077  3267  3325 I jxcore-log: ,
03-30 22:19:59.078  3267  3325 I jxcore-log: ok 16 incoming is cleaned up
03-30 22:19:59.078  3267  3325 I jxcore-log: 
,03-30 22:19:59.084  3267  3325 I jxcore-log: # teardown
03-30 22:19:59.084  3267  3325 I jxcore-log: 
,03-30 22:19:59.351  3267  3325 I jxcore-log: # setup
03-30 22:19:59.351  3267  3325 I jxcore-log: 
,03-30 22:19:59.648  3267  3325 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-30 22:19:59.648  3267  3325 I jxcore-log: 
,03-30 22:19:59.999  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:19:59.999  3267  3325 I jxcore-log: 
,03-30 22:20:00.007  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 35856
03-30 22:20:00.007  3267  3325 I jxcore-log: 
,03-30 22:20:00.012  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:00.012  3267  3325 I jxcore-log: 
,03-30 22:20:00.014  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:20:00.014  3267  3325 I jxcore-log: 
,03-30 22:20:00.017  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:00.017  3267  3325 I jxcore-log: 
,03-30 22:20:00.029  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:00.029  3267  3325 I jxcore-log: 
,03-30 22:20:00.032  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:00.032  3267  3325 I jxcore-log: 
,03-30 22:20:00.046  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:00.046  3267  3325 I jxcore-log: 
,03-30 22:20:00.056  3267  3325 I jxcore-log: ok 17 stream was closed
03-30 22:20:00.056  3267  3325 I jxcore-log: 
,03-30 22:20:00.057  3267  3325 I jxcore-log: ok 18 incoming should survive
03-30 22:20:00.057  3267  3325 I jxcore-log: 
,03-30 22:20:00.057  3267  3325 I jxcore-log: ok 19 mux should have no streams
03-30 22:20:00.057  3267  3325 I jxcore-log: 
,03-30 22:20:00.065  3267  3325 I jxcore-log: # teardown
03-30 22:20:00.065  3267  3325 I jxcore-log: 
,03-30 22:20:00.818  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:20:00.818  3267  3325 I jxcore-log: 
,03-30 22:20:00.824  3267  3325 I jxcore-log: # setup
03-30 22:20:00.824  3267  3325 I jxcore-log: 
,03-30 22:20:00.825  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:00.825  3267  3325 I jxcore-log: 
,03-30 22:20:01.378  3267  3325 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-30 22:20:01.378  3267  3325 I jxcore-log: 
,03-30 22:20:01.598  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:20:01.598  3267  3325 I jxcore-log: 
,03-30 22:20:01.608  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 59389
03-30 22:20:01.608  3267  3325 I jxcore-log: 
,03-30 22:20:01.622  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:01.622  3267  3325 I jxcore-log: 
,03-30 22:20:01.626  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:20:01.626  3267  3325 I jxcore-log: 
,03-30 22:20:01.630  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:01.630  3267  3325 I jxcore-log: 
,03-30 22:20:01.642  3267  3325 I jxcore-log: ok 20 we should not have gotten an error
03-30 22:20:01.642  3267  3325 I jxcore-log: 
,03-30 22:20:01.658  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:01.658  3267  3325 I jxcore-log: 
,03-30 22:20:01.664  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 22:20:01.664  3267  3325 I jxcore-log: 
,03-30 22:20:01.679  3267  3325 I jxcore-log: ok 21 Buffers are identical
03-30 22:20:01.679  3267  3325 I jxcore-log: ,
,03-30 22:20:01.682  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
,03-30 22:20:01.682  3267  3325 I jxcore-log: 
,03-30 22:20:01.686  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
,03-30 22:20:01.686  3267  3325 I jxcore-log: 
,03-30 22:20:01.690  3267  3325 I jxcore-log: ok 22 native server is nulled out
,03-30 22:20:01.690  3267  3325 I jxcore-log: 
,03-30 22:20:01.690  3267  3325 I jxcore-log: ok 23 native server should be closed
03-30 22:20:01.690  3267  3325 I jxcore-log: 
,03-30 22:20:01.691  3267  3325 I jxcore-log: ok 24 incoming has been removed
03-30 22:20:01.691  3267  3325 I jxcore-log: 
03-30 22:20:01.691  3267  3325 I jxcore-log: ok 25 Incoming should be done
03-30 22:20:01.691  3267  3325 I jxcore-log: 
03-30 22:20:01.691  3267  3325 I jxcore-log: ok 26 The mux object should be closed
03-30 22:20:01.691  3267  3325 I jxcore-log: 
03-30 22:20:01.692  3267  3325 I jxcore-log: ok 27 The mux stream should be closed
03-30 22:20:01.692  3267  3325 I jxcore-log: 
03-30 22:20:01.692  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:01.692  3267  3325 I jxcore-log: 
,03-30 22:20:01.710  3267  3325 I jxcore-log: # teardown
03-30 22:20:01.710  3267  3325 I jxcore-log: 
,03-30 22:20:02.070  3267  3325 I jxcore-log: # setup
03-30 22:20:02.070  3267  3325 I jxcore-log: 
,03-30 22:20:02.238  3267  3325 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-30 22:20:02.238  3267  3325 I jxcore-log: 
,03-30 22:20:02.441  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:20:02.441  3267  3325 I jxcore-log: 
,03-30 22:20:02.445  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 42498
03-30 22:20:02.445  3267  3325 I jxcore-log: 
,03-30 22:20:02.466  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:02.466  3267  3325 I jxcore-log: 
,03-30 22:20:02.467  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:20:02.467  3267  3325 I jxcore-log: 
,03-30 22:20:02.468  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:02.468  3267  3325 I jxcore-log: 
,03-30 22:20:02.472  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:02.472  3267  3325 I jxcore-log: 
,03-30 22:20:02.473  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:20:02.473  3267  3325 I jxcore-log: 
,03-30 22:20:02.475  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:02.475  3267  3325 I jxcore-log: 
,03-30 22:20:02.477  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:02.477  3267  3325 I jxcore-log: 
03-30 22:20:02.478  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:20:02.478  3267  3325 I jxcore-log: 
,03-30 22:20:02.479  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:02.479  3267  3325 I jxcore-log: 
03-30 22:20:02.481  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:02.481  3267  3325 I jxcore-log: 
,03-30 22:20:02.482  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:20:02.482  3267  3325 I jxcore-log: 
,03-30 22:20:02.483  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:02.483  3267  3325 I jxcore-log: 
03-30 22:20:02.486  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:02.486  3267  3325 I jxcore-log: 
,03-30 22:20:02.491  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:20:02.491  3267  3325 I jxcore-log: 
,03-30 22:20:02.492  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:02.492  3267  3325 I jxcore-log: 
03-30 22:20:02.495  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:02.495  3267  3325 I jxcore-log: 
03-30 22:20:02.496  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-30 22:20:02.496  3267  3325 I jxcore-log: 
03-30 22:20:02.497  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:02.497  3267  3325 I jxcore-log: 
,03-30 22:20:02.500  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:02.500  3267  3325 I jxcore-log: 
,03-30 22:20:02.500  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:20:02.500  3267  3325 I jxcore-log: 
03-30 22:20:02.501  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:02.501  3267  3325 I jxcore-log: 
,03-30 22:20:02.504  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:02.504  3267  3325 I jxcore-log: 
,03-30 22:20:02.505  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:20:02.505  3267  3325 I jxcore-log: 
,03-30 22:20:02.506  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:02.506  3267  3325 I jxcore-log: 
03-30 22:20:02.509  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:02.509  3267  3325 I jxcore-log: 
,03-30 22:20:02.509  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:20:02.509  3267  3325 I jxcore-log: 
03-30 22:20:02.510  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:02.510  3267  3325 I jxcore-log: 
,03-30 22:20:02.512  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:02.512  3267  3325 I jxcore-log: 
03-30 22:20:02.513  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:20:02.513  3267  3325 I jxcore-log: 
,03-30 22:20:02.514  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:02.514  3267  3325 I jxcore-log: 
,03-30 22:20:02.602  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.602  3267  3325 I jxcore-log: 
,03-30 22:20:02.605  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.605  3267  3325 I jxcore-log: 
,03-30 22:20:02.608  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.608  3267  3325 I jxcore-log: 
,03-30 22:20:02.609  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.609  3267  3325 I jxcore-log: 
,03-30 22:20:02.611  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.611  3267  3325 I jxcore-log: 
,03-30 22:20:02.613  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.613  3267  3325 I jxcore-log: 
,03-30 22:20:02.615  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.615  3267  3325 I jxcore-log: 
,03-30 22:20:02.617  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.617  3267  3325 I jxcore-log: 
,03-30 22:20:02.620  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.620  3267  3325 I jxcore-log: 
,03-30 22:20:02.622  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.622  3267  3325 I jxcore-log: 
,03-30 22:20:02.623  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.623  3267  3325 I jxcore-log: 
,03-30 22:20:02.625  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.625  3267  3325 I jxcore-log: 
,03-30 22:20:02.626  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.626  3267  3325 I jxcore-log: 
,03-30 22:20:02.628  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.628  3267  3325 I jxcore-log: 
,03-30 22:20:02.629  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.629  3267  3325 I jxcore-log: 
,03-30 22:20:02.631  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.631  3267  3325 I jxcore-log: 
,03-30 22:20:02.633  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.633  3267  3325 I jxcore-log: 
,03-30 22:20:02.635  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.635  3267  3325 I jxcore-log: 
,03-30 22:20:02.637  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.637  3267  3325 I jxcore-log: 
,03-30 22:20:02.638  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.638  3267  3325 I jxcore-log: 
,03-30 22:20:02.643  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.643  3267  3325 I jxcore-log: 
,03-30 22:20:02.645  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.645  3267  3325 I jxcore-log: 
,03-30 22:20:02.646  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.646  3267  3325 I jxcore-log: 
,03-30 22:20:02.648  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.648  3267  3325 I jxcore-log: 
,03-30 22:20:02.651  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.651  3267  3325 I jxcore-log: 
,03-30 22:20:02.653  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.653  3267  3325 I jxcore-log: 
,03-30 22:20:02.654  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.654  3267  3325 I jxcore-log: 
,03-30 22:20:02.656  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.656  3267  3325 I jxcore-log: 
,03-30 22:20:02.657  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.657  3267  3325 I jxcore-log: 
,03-30 22:20:02.659  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.659  3267  3325 I jxcore-log: 
,03-30 22:20:02.660  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.660  3267  3325 I jxcore-log: 
,03-30 22:20:02.661  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 22:20:02.661  3267  3325 I jxcore-log: 
03-30 22:20:02.664  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.664  3267  3325 I jxcore-log: ,
03-30 22:20:02.665  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.665  3267  3325 I jxcore-log: 
,03-30 22:20:02.666  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.666  3267  3325 I jxcore-log: 
,03-30 22:20:02.668  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.668  3267  3325 I jxcore-log: 
,03-30 22:20:02.669  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.669  3267  3325 I jxcore-log: 
,03-30 22:20:02.671  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.671  3267  3325 I jxcore-log: 
,03-30 22:20:02.672  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.672  3267  3325 I jxcore-log: 
,03-30 22:20:02.674  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.674  3267  3325 I jxcore-log: 
,03-30 22:20:02.676  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.676  3267  3325 I jxcore-log: 
,03-30 22:20:02.677  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.677  3267  3325 I jxcore-log: 
,03-30 22:20:02.678  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.678  3267  3325 I jxcore-log: 
,03-30 22:20:02.680  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.680  3267  3325 I jxcore-log: 
,03-30 22:20:02.681  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.681  3267  3325 I jxcore-log: 
,03-30 22:20:02.683  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-30 22:20:02.683  3267  3325 I jxcore-log: 
,03-30 22:20:02.684  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.684  3267  3325 I jxcore-log: 
,03-30 22:20:02.686  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 22:20:02.686  3267  3325 I jxcore-log: 
,03-30 22:20:02.695  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-30 22:20:02.695  3267  3325 I jxcore-log: 
,03-30 22:20:02.697  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-30 22:20:02.697  3267  3325 I jxcore-log: 
,03-30 22:20:02.699  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-30 22:20:02.699  3267  3325 I jxcore-log: 
,03-30 22:20:02.701  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 22:20:02.701  3267  3325 I jxcore-log: 
,03-30 22:20:02.702  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-30 22:20:02.702  3267  3325 I jxcore-log: 
,03-30 22:20:02.704  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-30 22:20:02.704  3267  3325 I jxcore-log: 
,03-30 22:20:02.706  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-30 22:20:02.706  3267  3325 I jxcore-log: 
,03-30 22:20:02.708  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 22:20:02.708  3267  3325 I jxcore-log: 
,03-30 22:20:02.710  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-30 22:20:02.710  3267  3325 I jxcore-log: 
,03-30 22:20:02.713  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 22:20:02.713  3267  3325 I jxcore-log: 
03-30 22:20:02.715  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-30 22:20:02.715  3267  3325 I jxcore-log: 
,03-30 22:20:02.717  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 22:20:02.717  3267  3325 I jxcore-log: 
,03-30 22:20:02.718  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.718  3267  3325 I jxcore-log: 
,03-30 22:20:02.720  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 22:20:02.720  3267  3325 I jxcore-log: 
,03-30 22:20:02.721  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.721  3267  3325 I jxcore-log: 
,03-30 22:20:02.723  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 22:20:02.723  3267  3325 I jxcore-log: 
,03-30 22:20:02.726  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-30 22:20:02.726  3267  3325 I jxcore-log: 
,03-30 22:20:02.728  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.728  3267  3325 I jxcore-log: 
,03-30 22:20:02.729  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-30 22:20:02.729  3267  3325 I jxcore-log: 
,03-30 22:20:02.732  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 22:20:02.732  3267  3325 I jxcore-log: 
,03-30 22:20:02.733  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.733  3267  3325 I jxcore-log: 
,03-30 22:20:02.735  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-30 22:20:02.735  3267  3325 I jxcore-log: 
,03-30 22:20:02.737  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.737  3267  3325 I jxcore-log: 
,03-30 22:20:02.739  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 22:20:02.739  3267  3325 I jxcore-log: 
,03-30 22:20:02.741  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-30 22:20:02.741  3267  3325 I jxcore-log: 
,03-30 22:20:02.743  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 22:20:02.743  3267  3325 I jxcore-log: 
03-30 22:20:02.745  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.745  3267  3325 I jxcore-log: 
,03-30 22:20:02.746  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 22:20:02.746  3267  3325 I jxcore-log: 
03-30 22:20:02.747  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.747  3267  3325 I jxcore-log: 
03-30 22:20:02.749  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 22:20:02.749  3267  3325 I jxcore-log: 
03-30 22:20:02.750  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:02.750  3267  3325 I jxcore-log: 
,03-30 22:20:02.752  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:02.752  3267  3325 I jxcore-log: 
,03-30 22:20:02.828  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.828  3267  3325 I jxcore-log: 
,03-30 22:20:02.829  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.829  3267  3325 I jxcore-log: 
03-30 22:20:02.830  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.830  3267  3325 I jxcore-log: 
03-30 22:20:02.831  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.831  3267  3325 I jxcore-log: 
,03-30 22:20:02.832  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:20:02.832  3267  3325 I jxcore-log: 
03-30 22:20:02.834  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.834  3267  3325 I jxcore-log: 
03-30 22:20:02.836  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.836  3267  3325 I jxcore-log: 
,03-30 22:20:02.837  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.837  3267  3325 I jxcore-log: 
03-30 22:20:02.838  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.838  3267  3325 I jxcore-log: 
,03-30 22:20:02.839  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:20:02.839  3267  3325 I jxcore-log: 
,03-30 22:20:02.843  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.843  3267  3325 I jxcore-log: 
,03-30 22:20:02.844  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.844  3267  3325 I jxcore-log: 
,03-30 22:20:02.845  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.845  3267  3325 I jxcore-log: 
03-30 22:20:02.846  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.846  3267  3325 I jxcore-log: 
,03-30 22:20:02.848  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:20:02.848  3267  3325 I jxcore-log: 
,03-30 22:20:02.849  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.849  3267  3325 I jxcore-log: 
,03-30 22:20:02.850  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.850  3267  3325 I jxcore-log: 
,03-30 22:20:02.852  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.852  3267  3325 I jxcore-log: 
,03-30 22:20:02.853  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.853  3267  3325 I jxcore-log: 
,03-30 22:20:02.854  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:20:02.854  3267  3325 I jxcore-log: 
,03-30 22:20:02.855  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.855  3267  3325 I jxcore-log: 
,03-30 22:20:02.856  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.856  3267  3325 I jxcore-log: 
,03-30 22:20:02.858  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.858  3267  3325 I jxcore-log: 
,03-30 22:20:02.859  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.859  3267  3325 I jxcore-log: 
,03-30 22:20:02.860  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:20:02.860  3267  3325 I jxcore-log: 
,03-30 22:20:02.862  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.862  3267  3325 I jxcore-log: 
,03-30 22:20:02.863  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.863  3267  3325 I jxcore-log: 
,03-30 22:20:02.864  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.864  3267  3325 I jxcore-log: 
,03-30 22:20:02.865  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.865  3267  3325 I jxcore-log: 
,03-30 22:20:02.866  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:20:02.866  3267  3325 I jxcore-log: 
03-30 22:20:02.867  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.867  3267  3325 I jxcore-log: 
,03-30 22:20:02.868  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.868  3267  3325 I jxcore-log: 
,03-30 22:20:02.869  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.869  3267  3325 I jxcore-log: 
,03-30 22:20:02.869  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.869  3267  3325 I jxcore-log: 
03-30 22:20:02.870  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:20:02.870  3267  3325 I jxcore-log: 
,03-30 22:20:02.871  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.871  3267  3325 I jxcore-log: 
03-30 22:20:02.872  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.872  3267  3325 I jxcore-log: 
,03-30 22:20:02.872  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.872  3267  3325 I jxcore-log: 
03-30 22:20:02.873  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.873  3267  3325 I jxcore-log: 
,03-30 22:20:02.874  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:20:02.874  3267  3325 I jxcore-log: 
03-30 22:20:02.875  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.875  3267  3325 I jxcore-log: 
03-30 22:20:02.876  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.876  3267  3325 I jxcore-log: 
,03-30 22:20:02.877  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.877  3267  3325 I jxcore-log: 
03-30 22:20:02.877  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.877  3267  3325 I jxcore-log: 
03-30 22:20:02.878  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:20:02.878  3267  3325 I jxcore-log: 
,03-30 22:20:02.879  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.879  3267  3325 I jxcore-log: 
03-30 22:20:02.880  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.880  3267  3325 I jxcore-log: 
03-30 22:20:02.881  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.881  3267  3325 I jxcore-log: 
,03-30 22:20:02.881  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:02.881  3267  3325 I jxcore-log: 
03-30 22:20:02.882  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:20:02.882  3267  3325 I jxcore-log: 
03-30 22:20:02.885  3267  3325 I jxcore-log: ok 28 native server is nulled out
03-30 22:20:02.885  3267  3325 I jxcore-log: 
,03-30 22:20:02.886  3267  3325 I jxcore-log: ok 29 native server should be closed
03-30 22:20:02.886  3267  3325 I jxcore-log: 
03-30 22:20:02.886  3267  3325 I jxcore-log: ok 30 incoming has been removed
03-30 22:20:02.886  3267  3325 I jxcore-log: 
03-30 22:20:02.887  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:02.887  3267  3325 I jxcore-log: 
,03-30 22:20:02.888  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:02.888  3267  3325 I jxcore-log: 
03-30 22:20:02.888  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:02.888  3267  3325 I jxcore-log: 
03-30 22:20:02.888  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:02.888  3267  3325 I jxcore-log: 
,03-30 22:20:02.889  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:02.889  3267  3325 I jxcore-log: 
03-30 22:20:02.889  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:02.889  3267  3325 I jxcore-log: 
03-30 22:20:02.889  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:02.889  3267  3325 I jxcore-log: 
,03-30 22:20:02.890  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:02.890  3267  3325 I jxcore-log: 
03-30 22:20:02.890  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:02.890  3267  3325 I jxcore-log: 
03-30 22:20:02.890  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:02.890  3267  3325 I jxcore-log: 
,03-30 22:20:02.992  3267  3325 I jxcore-log: # teardown
03-30 22:20:02.992  3267  3325 I jxcore-log: 
,03-30 22:20:03.279  3267  3325 I jxcore-log: # setup
03-30 22:20:03.279  3267  3325 I jxcore-log: 
,03-30 22:20:03.473  3267  3325 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-30 22:20:03.473  3267  3325 I jxcore-log: 
,03-30 22:20:03.644  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:20:03.644  3267  3325 I jxcore-log: 
,03-30 22:20:03.655  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 40500
03-30 22:20:03.655  3267  3325 I jxcore-log: 
,03-30 22:20:03.661  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:03.661  3267  3325 I jxcore-log: 
,03-30 22:20:03.662  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:20:03.662  3267  3325 I jxcore-log: 
,03-30 22:20:03.664  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:03.664  3267  3325 I jxcore-log: 
,03-30 22:20:03.672  3267  3325 I jxcore-log: ok 31 we should not have gotten an error
03-30 22:20:03.672  3267  3325 I jxcore-log: 
,03-30 22:20:03.676  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:03.676  3267  3325 I jxcore-log: 
,03-30 22:20:03.679  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:03.679  3267  3325 I jxcore-log: 
,03-30 22:20:03.686  3267  3325 I jxcore-log: ok 32 Buffers are identical
03-30 22:20:03.686  3267  3325 I jxcore-log: 
,03-30 22:20:03.687  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:03.687  3267  3325 I jxcore-log: 
,03-30 22:20:03.689  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:20:03.689  3267  3325 I jxcore-log: 
,03-30 22:20:03.701  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:03.701  3267  3325 I jxcore-log: 
,03-30 22:20:03.702  3267  3325 I jxcore-log: ok 33 server should be fine
03-30 22:20:03.702  3267  3325 I jxcore-log: 
03-30 22:20:03.702  3267  3325 I jxcore-log: ok 34 server should be open
03-30 22:20:03.702  3267  3325 I jxcore-log: 
,03-30 22:20:03.703  3267  3325 I jxcore-log: ok 35 incoming has been removed
03-30 22:20:03.703  3267  3325 I jxcore-log: 
,03-30 22:20:03.703  3267  3325 I jxcore-log: ok 36 The mux object should be closed
03-30 22:20:03.703  3267  3325 I jxcore-log: 
03-30 22:20:03.704  3267  3325 I jxcore-log: ok 37 The mux stream should be closed
03-30 22:20:03.704  3267  3325 I jxcore-log: 
,03-30 22:20:03.711  3267  3325 I jxcore-log: # teardown
03-30 22:20:03.711  3267  3325 I jxcore-log: 
,03-30 22:20:03.892  3267  3325 I jxcore-log: # setup
03-30 22:20:03.892  3267  3325 I jxcore-log: 
,03-30 22:20:04.147  3267  3325 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-30 22:20:04.147  3267  3325 I jxcore-log: 
,03-30 22:20:04.254  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:20:04.254  3267  3325 I jxcore-log: 
,03-30 22:20:04.258  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 47287
03-30 22:20:04.258  3267  3325 I jxcore-log: 
,03-30 22:20:04.264  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:04.264  3267  3325 I jxcore-log: 
,03-30 22:20:04.265  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:20:04.265  3267  3325 I jxcore-log: 
03-30 22:20:04.266  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:04.266  3267  3325 I jxcore-log: 
03-30 22:20:04.272  3267  3325 I jxcore-log: ok 38 we should not have gotten an error
03-30 22:20:04.272  3267  3325 I jxcore-log: 
,03-30 22:20:04.281  3267  3325 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 22:20:04.281  3267  3325 I jxcore-log: 
,03-30 22:20:04.287  3267  3325 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 22:20:04.287  3267  3325 I jxcore-log: 
,03-30 22:20:04.297  3267  3325 I jxcore-log: ok 39 Buffers are identical
03-30 22:20:04.297  3267  3325 I jxcore-log: 
,03-30 22:20:04.302  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-30 22:20:04.302  3267  3325 I jxcore-log: 
,03-30 22:20:04.303  3267  3325 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 22:20:04.303  3267  3325 I jxcore-log: 
,03-30 22:20:04.306  3267  3325 I jxcore-log: DEBUG createNativeListener: mux close
03-30 22:20:04.306  3267  3325 I jxcore-log: 
,03-30 22:20:04.311  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:04.311  3267  3325 I jxcore-log: 
,03-30 22:20:04.312  3267  3325 I jxcore-log: ok 40 server should be fine
03-30 22:20:04.312  3267  3325 I jxcore-log: 
03-30 22:20:04.312  3267  3325 I jxcore-log: ok 41 server should be open
03-30 22:20:04.312  3267  3325 I jxcore-log: 
03-30 22:20:04.313  3267  3325 I jxcore-log: ok 42 incoming has been removed
03-30 22:20:04.313  3267  3325 I jxcore-log: 
,03-30 22:20:04.313  3267  3325 I jxcore-log: ok 43 The mux object should be closed
03-30 22:20:04.313  3267  3325 I jxcore-log: 
03-30 22:20:04.314  3267  3325 I jxcore-log: ok 44 The mux stream should be closed
03-30 22:20:04.314  3267  3325 I jxcore-log: 
,03-30 22:20:04.323  3267  3325 I jxcore-log: # teardown
03-30 22:20:04.323  3267  3325 I jxcore-log: 
,03-30 22:20:04.456  3267  3325 I jxcore-log: # setup
,03-30 22:20:04.456  3267  3325 I jxcore-log: 
,03-30 22:20:04.634  3267  3325 I jxcore-log: # 12. closeAll can close even when connections open
,03-30 22:20:04.634  3267  3325 I jxcore-log: 
,03-30 22:20:04.828  3267  3325 I jxcore-log: ok 45 not possible to connect to the server anymore
03-30 22:20:04.828  3267  3325 I jxcore-log: 
,03-30 22:20:04.833  3267  3325 I jxcore-log: # teardown
03-30 22:20:04.833  3267  3325 I jxcore-log: 
,03-30 22:20:04.983  3267  3325 I jxcore-log: # setup
03-30 22:20:04.983  3267  3325 I jxcore-log: 
,03-30 22:20:05.174  3267  3325 I jxcore-log: # 13. closeAll with promise
03-30 22:20:05.174  3267  3325 I jxcore-log: 
,03-30 22:20:05.328  3267  3325 I jxcore-log: ok 46 not possible to connect to the server anymore
03-30 22:20:05.328  3267  3325 I jxcore-log: 
,03-30 22:20:05.333  3267  3325 I jxcore-log: # teardown
03-30 22:20:05.333  3267  3325 I jxcore-log: 
,03-30 22:20:06.225  3267  3325 I jxcore-log: # setup
03-30 22:20:06.225  3267  3325 I jxcore-log: 
,03-30 22:20:06.428  3267  3325 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-30 22:20:06.428  3267  3325 I jxcore-log: 
,03-30 22:20:06.661  3267  3325 I jxcore-log: ok 47 Got the right error
03-30 22:20:06.661  3267  3325 I jxcore-log: 
,03-30 22:20:06.666  3267  3325 I jxcore-log: # teardown
03-30 22:20:06.666  3267  3325 I jxcore-log: 
,03-30 22:20:06.787  3267  3325 I jxcore-log: # setup
03-30 22:20:06.787  3267  3325 I jxcore-log: 
,03-30 22:20:06.994  3267  3325 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-30 22:20:06.994  3267  3325 I jxcore-log: 
,03-30 22:20:07.198  3267  3325 I jxcore-log: # teardown
03-30 22:20:07.198  3267  3325 I jxcore-log: 
,03-30 22:20:07.352  3267  3325 I jxcore-log: # setup
03-30 22:20:07.352  3267  3325 I jxcore-log: 
,03-30 22:20:07.465  3267  3325 I jxcore-log: # 16. multiplex can send data
03-30 22:20:07.465  3267  3325 I jxcore-log: 
,03-30 22:20:07.691  3267  3325 I jxcore-log: ok 48 String should be length:200
03-30 22:20:07.691  3267  3325 I jxcore-log: 
,03-30 22:20:07.699  3267  3325 I jxcore-log: # teardown
03-30 22:20:07.699  3267  3325 I jxcore-log: 
,03-30 22:20:07.790  1239  1729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-30 22:20:07.791  1239  1729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-30 22:20:07.792  1239  1729 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:20:07.792  1239  1729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:20:07.799  1239  1729 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:20:07.825  3089  3802 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-30 22:20:07.825  3089  3802 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at jdm.a(PG:82)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at jcs.o(PG:406)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at jcn.a(PG:1379)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at jcs.i(PG:143)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at blb.a(PG:3937)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at czp.a(PG:18188)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at czp.a(PG:9081)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at czq.run(PG:1686)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:20:07.825  3089  3802 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at jdj.a(PG:4091)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at jdj.a(PG:1125)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at jdm.a(PG:77)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	... 12 more
03-30 22:20:07.825  3089  3802 E HttpOperation: Caused by: faj: BadAuthentication
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at fal.a(PG:38)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	at jdj.a(PG:4089)
03-30 22:20:07.825  3089  3802 E HttpOperation: 	... 14 more
,03-30 22:20:07.870  3267  3325 I jxcore-log: # setup
03-30 22:20:07.870  3267  3325 I jxcore-log: 
,03-30 22:20:07.899  1239  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-30 22:20:07.899  1239  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-30 22:20:07.900  1239  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:20:07.900  1239  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:20:07.910  1239  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:20:07.931  3089  3802 E HttpOperation: [getmobileexperiments] Unexpected exception,
03-30 22:20:07.931  3089  3802 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at jdm.a(PG:82)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at jcs.o(PG:406)
03-30 22:20:07.931  3089  3802 E HttpOperation: ,	at jcn.a(PG:1379)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at jcs.i(PG:143)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at hec.a(PG:42)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at hee.a(PG:102)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at czr.a(PG:65)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	,at kka.a(PG:108)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at czp.a(PG:19176)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at czp.a(PG:9081)
03-30 22:20:07.931  3089  3802 E HttpOperation: ,	at czq.run(PG:1686),
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:20:07.931  3089  3802 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at jdj.a(PG:4091)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at jdj.a(PG:1125)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at jdm.a(PG:77)
03-30 22:20:07.931  3089  3802 E HttpOperation: ,	... 15 more
03-30 22:20:07.931  3089  3802 E HttpOperation: Caused by: faj: BadAuthentication
03-30 22:20:07.931  3089  3802 E HttpOperation: 	at fal.a(PG:38)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	,at jdj.a(PG:4089)
03-30 22:20:07.931  3089  3802 E HttpOperation: 	... 17 more
03-30 22:20:07.932  3089  3802 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-30 22:20:07.932  3089  3802 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token,
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at jdm.a(PG:82)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at jcs.o(PG:406)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at jcn.a(PG:1379)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at jcs.i(PG:143)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	,at hec.a(PG:42)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at hee.a(PG:102)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at czr.a(PG:65)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at kka.a(PG:108)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at czp.a(PG:19176),
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at czp.a(PG:9081)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at czq.run(PG:1686)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at jdj.a(PG:4091),
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at jdj.a(PG:1125)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at jdm.a(PG:77)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	... 15 more
03-30 22:20:07.932  3089  3802 E ExperimentLoader: Caused by: faj: BadAuthentication
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at fal.a(PG:38)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	at jdj.a(PG:4089)
03-30 22:20:07.932  3089  3802 E ExperimentLoader: 	... 17 more
,03-30 22:20:08.031  3267  3325 I jxcore-log: # 17. enqueue and run in order
03-30 22:20:08.031  3267  3325 I jxcore-log: 
,03-30 22:20:08.072   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 201014, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-30 22:20:08.129  3459  3804 V KeepSync: Connecting to GoogleApiClient
,03-30 22:20:08.206  1239  1256 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-30 22:20:08.206  1239  1256 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-30 22:20:08.206  1239  1256 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-30 22:20:08.206  1239  1256 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:20:08.212  1239  1256 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: Handling authorization failure
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-30 22:20:08.236  1804  3805 E ClientConnectionOperation: 	... 7 more
,03-30 22:20:08.239  3459  3804 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-30 22:20:08.241  3459  3804 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-30 22:20:08.255  3459  3804 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-30 22:20:08.256  3459  3804 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-30 22:20:08.357  1239  1730 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-30 22:20:08.358  1239  1730 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:20:08.358  1239  1730 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:20:08.358  1239  1730 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:20:08.374  1239  1730 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:20:08.405  3267  3325 I jxcore-log: ok 49 firstPromise setTimeout
03-30 22:20:08.405  3267  3325 I jxcore-log: 
,03-30 22:20:08.409  3267  3325 I jxcore-log: ok 50 firstPromise result
03-30 22:20:08.409  3267  3325 I jxcore-log: 
,03-30 22:20:08.412  3267  3325 I jxcore-log: ok 51 firstPromise testValue
03-30 22:20:08.412  3267  3325 I jxcore-log: 
,03-30 22:20:08.442  1239  1239 I art     : Explicit concurrent mark sweep GC freed 41703(2MB) AllocSpace objects, 12(1254KB) LOS objects, 37% free, 26MB/42MB, paused 1.179ms total 54.166ms
,03-30 22:20:08.484  3459  3804 E KeepSync: IOException
03-30 22:20:08.484  3459  3804 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-30 22:20:08.484  3459  3804 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-30 22:20:08.484  3459  3804 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-30 22:20:08.484  3459  3804 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-30 22:20:08.484  3459  3804 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-30 22:20:08.484  3459  3804 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-30 22:20:08.484  3459  3804 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-30 22:20:08.484  3459  3804 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-30 22:20:08.484  3459  3804 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-30 22:20:08.484  3459  3804 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-30 22:20:08.484  3459  3804 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-30 22:20:08.484  3459  3804 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-30 22:20:08.484  3459  3804 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-30 22:20:08.484  3459  3804 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-30 22:20:08.484  3459  3804 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-30 22:20:08.484  3459  3804 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-30 22:20:08.484  3459  3804 E KeepSync: 	... 10 more
,03-30 22:20:08.485  3459  3804 W KeepSync: Sync result 2
,03-30 22:20:08.490   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 201430, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-30 22:20:08.517  3267  3325 I jxcore-log: ok 52 secondPromise setTimeout
03-30 22:20:08.517  3267  3325 I jxcore-log: 
,03-30 22:20:08.521  3267  3325 I jxcore-log: ok 53 secondPromise result
03-30 22:20:08.521  3267  3325 I jxcore-log: 
,03-30 22:20:08.523  3267  3325 I jxcore-log: ok 54 secondPromise testValue,
03-30 22:20:08.523  3267  3325 I jxcore-log: 
,03-30 22:20:08.526  3267  3325 I jxcore-log: ok 55 thirdPromise in promise
03-30 22:20:08.526  3267  3325 I jxcore-log: 
,03-30 22:20:08.529  3267  3325 I jxcore-log: ok 56 thirdPromise result
03-30 22:20:08.529  3267  3325 I jxcore-log: 
,03-30 22:20:08.531  3267  3325 I jxcore-log: ok 57 thirdPromise testValue
03-30 22:20:08.531  3267  3325 I jxcore-log: 
,03-30 22:20:08.540  3267  3325 I jxcore-log: # teardown
03-30 22:20:08.540  3267  3325 I jxcore-log: 
,03-30 22:20:08.935  2148  2213 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-30 22:20:09.046  3267  3325 I jxcore-log: # setup
03-30 22:20:09.046  3267  3325 I jxcore-log: 
,03-30 22:20:09.176  3267  3325 I jxcore-log: # 18. enqueueAtTop and run backwards
03-30 22:20:09.176  3267  3325 I jxcore-log: 
,03-30 22:20:09.435  3267  3325 I jxcore-log: ok 58 thirdPromise - first to run
03-30 22:20:09.435  3267  3325 I jxcore-log: 
,03-30 22:20:09.437  3267  3325 I jxcore-log: ok 59 thirdPromise - in resolve
03-30 22:20:09.437  3267  3325 I jxcore-log: 
,03-30 22:20:09.438  3267  3325 I jxcore-log: ok 60 secondPromise - second to run
03-30 22:20:09.438  3267  3325 I jxcore-log: 
,03-30 22:20:09.440  3267  3325 I jxcore-log: ok 61 secondPromise - in catch
03-30 22:20:09.440  3267  3325 I jxcore-log: 
,03-30 22:20:09.441  3267  3325 I jxcore-log: ok 62 firstPromise - third to run
03-30 22:20:09.441  3267  3325 I jxcore-log: 
,03-30 22:20:09.442  3267  3325 I jxcore-log: ok 63 firstPromise - in then
03-30 22:20:09.442  3267  3325 I jxcore-log: 
,03-30 22:20:09.443  3267  3325 I jxcore-log: ok 64 testing promises
03-30 22:20:09.443  3267  3325 I jxcore-log: 
,03-30 22:20:09.446  3267  3325 I jxcore-log: # teardown
03-30 22:20:09.446  3267  3325 I jxcore-log: 
,03-30 22:20:09.592  3267  3325 I jxcore-log: # setup
03-30 22:20:09.592  3267  3325 I jxcore-log: 
,03-30 22:20:09.691  3267  3325 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-30 22:20:09.691  3267  3325 I jxcore-log: 
,03-30 22:20:09.716  1239  1239 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:20:09.759  1239  2547 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-30 22:20:09.760  1239  2547 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-30 22:20:09.760  1239  2547 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:20:09.760  1239  2547 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:20:09.767  1239  2547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:20:09.795  3693  3693 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-30 22:20:09.795  3693  3693 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-30 22:20:09.796  3693  3693 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-30 22:20:09.814  3267  3325 I jxcore-log: ok 65 fourth
03-30 22:20:09.814  3267  3325 I jxcore-log: 
,03-30 22:20:09.816  3267  3325 I jxcore-log: ok 66 fourth
03-30 22:20:09.816  3267  3325 I jxcore-log: 
,03-30 22:20:09.819  3267  3325 I jxcore-log: ok 67 second
03-30 22:20:09.819  3267  3325 I jxcore-log: 
,03-30 22:20:09.822  3267  3325 I jxcore-log: ok 68 secondPromise - in then
03-30 22:20:09.822  3267  3325 I jxcore-log: 
,03-30 22:20:09.925  3267  3325 I jxcore-log: ok 69 first
03-30 22:20:09.925  3267  3325 I jxcore-log: 
,03-30 22:20:09.928  3267  3325 I jxcore-log: ok 70 firstPromise - in catch
03-30 22:20:09.928  3267  3325 I jxcore-log: 
,03-30 22:20:09.931  3267  3325 I jxcore-log: ok 71 third
03-30 22:20:09.931  3267  3325 I jxcore-log: 
,03-30 22:20:09.935  3267  3325 I jxcore-log: ok 72 thirdPromise - in then
03-30 22:20:09.935  3267  3325 I jxcore-log: 
,03-30 22:20:09.937  3267  3325 I jxcore-log: ok 73 testingPromises
03-30 22:20:09.937  3267  3325 I jxcore-log: 
,03-30 22:20:09.947  3267  3325 I jxcore-log: # teardown
03-30 22:20:09.947  3267  3325 I jxcore-log: 
,03-30 22:20:10.105  3267  3325 I jxcore-log: # setup
03-30 22:20:10.105  3267  3325 I jxcore-log: 
,03-30 22:20:10.237  3267  3325 I jxcore-log: # 20. queues handled independently
03-30 22:20:10.237  3267  3325 I jxcore-log: 
,03-30 22:20:10.410  3267  3325 I jxcore-log: ok 74 all short operations completed before the long resolves
03-30 22:20:10.410  3267  3325 I jxcore-log: 
,03-30 22:20:10.421  3267  3325 I jxcore-log: # teardown
03-30 22:20:10.421  3267  3325 I jxcore-log: ,
,03-30 22:20:10.509  3267  3325 I jxcore-log: # setup
03-30 22:20:10.509  3267  3325 I jxcore-log: 
,03-30 22:20:10.655  3267  3325 I jxcore-log: # 21. basic
03-30 22:20:10.655  3267  3325 I jxcore-log: 
,03-30 22:20:10.776  3267  3325 I jxcore-log: ok 75 sane,
03-30 22:20:10.776  3267  3325 I jxcore-log: 
,03-30 22:20:10.785  3267  3325 I jxcore-log: # teardown,
03-30 22:20:10.785  3267  3325 I jxcore-log: 
,03-30 22:20:10.936  3267  3325 I jxcore-log: # setup,
03-30 22:20:10.936  3267  3325 I jxcore-log: 
,03-30 22:20:11.092  3267  3325 I jxcore-log: # 22. another,
03-30 22:20:11.092  3267  3325 I jxcore-log: 
,03-30 22:20:11.266  3267  3325 I jxcore-log: ok 76 sane,
03-30 22:20:11.266  3267  3325 I jxcore-log: 
,03-30 22:20:11.274  3267  3325 I jxcore-log: # teardown,
03-30 22:20:11.274  3267  3325 I jxcore-log: 
,03-30 22:20:11.447  3267  3325 I jxcore-log: # setup,
03-30 22:20:11.447  3267  3325 I jxcore-log: 
,03-30 22:20:11.575  3267  3325 I jxcore-log: # 23. can pass data in setup,
03-30 22:20:11.575  3267  3325 I jxcore-log: 
,03-30 22:20:11.660  3267  3325 I jxcore-log: ok 77 test participant has uuid,
03-30 22:20:11.660  3267  3325 I jxcore-log: 
03-30 22:20:11.662  3267  3325 I jxcore-log: ok 78 participant data matches
03-30 22:20:11.662  3267  3325 I jxcore-log: 
,03-30 22:20:11.665  3267  3325 I jxcore-log: ok 79 test participant has uuid
03-30 22:20:11.665  3267  3325 I jxcore-log: 
,03-30 22:20:11.666  3267  3325 I jxcore-log: ok 80 participant data matches
03-30 22:20:11.666  3267  3325 I jxcore-log: 
,03-30 22:20:11.666  3267  3325 I jxcore-log: ok 81 test participant has uuid
03-30 22:20:11.666  3267  3325 I jxcore-log: 
03-30 22:20:11.666  3267  3325 I jxcore-log: ok 82 participant data matches
03-30 22:20:11.666  3267  3325 I jxcore-log: 
,03-30 22:20:11.667  3267  3325 I jxcore-log: ok 83 own UUID is found from the participants list
03-30 22:20:11.667  3267  3325 I jxcore-log: 
,03-30 22:20:11.671  3267  3325 I jxcore-log: # teardown
03-30 22:20:11.671  3267  3325 I jxcore-log: 
,03-30 22:20:11.776  3267  3325 I jxcore-log: # setup
03-30 22:20:11.776  3267  3325 I jxcore-log: 
,03-30 22:20:11.941  3267  3325 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-30 22:20:11.941  3267  3325 I jxcore-log: 
,03-30 22:20:12.096  3267  3325 I jxcore-log: ok 84 specific error should be returned
,03-30 22:20:12.096  3267  3325 I jxcore-log: 
,03-30 22:20:12.099  3267  3325 I jxcore-log: # teardown
03-30 22:20:12.099  3267  3325 I jxcore-log: ,
,03-30 22:20:12.245  3267  3325 I jxcore-log: ok 85 error should be null
03-30 22:20:12.245  3267  3325 I jxcore-log: 
,03-30 22:20:12.245  3267  3325 I jxcore-log: ok 86 error should be null
03-30 22:20:12.245  3267  3325 I jxcore-log: 
03-30 22:20:12.247  3267  3325 I jxcore-log: # setup
03-30 22:20:12.247  3267  3325 I jxcore-log: 
,03-30 22:20:12.439  3267  3325 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-30 22:20:12.439  3267  3325 I jxcore-log: 
,03-30 22:20:12.586  3267  3325 I jxcore-log: ok 87 specific error should be returned,
03-30 22:20:12.586  3267  3325 I jxcore-log: 
,03-30 22:20:12.593  3267  3325 I jxcore-log: # teardown,
03-30 22:20:12.593  3267  3325 I jxcore-log: 
,03-30 22:20:12.755  3267  3325 I jxcore-log: ok 88 error should be null,
03-30 22:20:12.755  3267  3325 I jxcore-log: 
03-30 22:20:12.757  3267  3325 I jxcore-log: ok 89 error should be null
03-30 22:20:12.757  3267  3325 I jxcore-log: 
,03-30 22:20:12.762  3267  3325 I jxcore-log: # setup,
03-30 22:20:12.762  3267  3325 I jxcore-log: 
,03-30 22:20:12.940  3267  3325 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times
03-30 22:20:12.940  3267  3325 I jxcore-log: 
,03-30 22:20:13.212  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server,
03-30 22:20:13.212  3267  3325 I jxcore-log: 
03-30 22:20:13.213  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 35066
03-30 22:20:13.213  3267  3325 I jxcore-log: 
,03-30 22:20:13.216  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:20:13.216  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:13.216  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:13.222  3267  3325 I jxcore-log: ok 90 error should be null
03-30 22:20:13.222  3267  3325 I jxcore-log: 
,03-30 22:20:13.222  3267  3325 I jxcore-log: ok 91 error should be null
03-30 22:20:13.222  3267  3325 I jxcore-log: 
03-30 22:20:13.223  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 22:20:13.223  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:13.223  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:13.226  3267  3325 I jxcore-log: ok 92 error should be null
03-30 22:20:13.226  3267  3325 I jxcore-log: 
03-30 22:20:13.226  3267  3325 I jxcore-log: ok 93 error should be null
03-30 22:20:13.226  3267  3325 I jxcore-log: 
,03-30 22:20:13.230  3267  3325 I jxcore-log: # teardown
03-30 22:20:13.230  3267  3325 I jxcore-log: 
,03-30 22:20:13.412  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-30 22:20:13.412  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:13.412  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:13.417  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-30 22:20:13.418  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 22:20:13.418  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:13.422  3267  3325 I jxcore-log: ok 94 error should be null
03-30 22:20:13.422  3267  3325 I jxcore-log: 
,03-30 22:20:13.423  3267  3325 I jxcore-log: ok 95 error should be null
03-30 22:20:13.423  3267  3325 I jxcore-log: 
,03-30 22:20:13.429  3267  3325 I jxcore-log: # setup
03-30 22:20:13.429  3267  3325 I jxcore-log: 
,03-30 22:20:13.577  3267  3325 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-30 22:20:13.577  3267  3325 I jxcore-log: 
,03-30 22:20:13.738  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:20:13.738  3267  3325 I jxcore-log: 
,03-30 22:20:13.740  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 48273
03-30 22:20:13.740  3267  3325 I jxcore-log: 
,03-30 22:20:13.752  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-30 22:20:13.752  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:13.752  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 22:20:13.752  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-30 22:20:13.752  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:13.752  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 22:20:13.763  3267  3325 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 22:20:13.763   823  1242 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:13.774  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 22:20:13.783  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 22:20:13.783  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 22:20:13.783  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-30 22:20:13.784  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 22:20:13.793  2148  2164 D BtGatt.GattService: registerClient() - UUID=8948e0d9-f61f-4bf8-a6de-2579513d372f
,03-30 22:20:13.795  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=8948e0d9-f61f-4bf8-a6de-2579513d372f, clientIf=5
,03-30 22:20:13.797  3267  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 22:20:13.800  2148  2163 D BtGatt.GattService: start scan with filters
,03-30 22:20:13.804  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 22:20:13.804  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 22:20:13.804  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 22:20:13.804  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 22:20:13.805  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:13.805  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:20:13.805  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 22:20:13.805  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:13.806   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 22:20:13.808  2148  2221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bc7378b
,03-30 22:20:13.816  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-30 22:20:13.816  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-30 22:20:13.819  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-30 22:20:13.819  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 22:20:13.820  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 22:20:13.821  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 22:20:13.824  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-30 22:20:13.824  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-30 22:20:13.827  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:13.827  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:13.827  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:13.827  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-30 22:20:13.831  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 22:20:13.831  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:13.831  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:13.831  3267  3325 I jxcore-log: 
03-30 22:20:13.833  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:13.833  3267  3325 I jxcore-log: 
03-30 22:20:13.833  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 22:20:13.833  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:13.836  3267  3325 I jxcore-log: ok 96 error should be null
03-30 22:20:13.836  3267  3325 I jxcore-log: 
,03-30 22:20:13.836  3267  3325 I jxcore-log: ok 97 error should be null
03-30 22:20:13.836  3267  3325 I jxcore-log: 
,03-30 22:20:13.842  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-30 22:20:13.842  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 22:20:13.842  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 22:20:13.842  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:20:13.842  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 22:20:13.845  3267  3325 I jxcore-log: ok 98 error should be null
,03-30 22:20:13.845  3267  3325 I jxcore-log: 
03-30 22:20:13.846  3267  3325 I jxcore-log: ok 99 error should be null
03-30 22:20:13.846  3267  3325 I jxcore-log: 
,03-30 22:20:13.853  3267  3325 I jxcore-log: # teardown
03-30 22:20:13.853  3267  3325 I jxcore-log: ,
,03-30 22:20:14.122  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
,03-30 22:20:14.124  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:14.124  3267  3325 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-30 22:20:14.127  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-30 22:20:14.127  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 22:20:14.127  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 22:20:14.127  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 22:20:14.128  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-30 22:20:14.128  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 22:20:14.131  2148  2163 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:20:14.144  2148  2994 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 22:20:14.145  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-30 22:20:14.145  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-30 22:20:14.145  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 22:20:14.145  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-30 22:20:14.145  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:20:14.145  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-30 22:20:14.145  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-30 22:20:14.145  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:20:14.145  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:14.148  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:14.148  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:14.148  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:20:14.149  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:14.149  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 22:20:14.149  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 22:20:14.150  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 22:20:14.150  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:14.150  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-30 22:20:14.150  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:14.150  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 22:20:14.150  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 22:20:14.151  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 22:20:14.155  3267  3325 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,03-30 22:20:14.155  3267  3325 I jxcore-log: 
,03-30 22:20:14.160  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 22:20:14.160   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:14.166  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 22:20:14.167  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:14.167  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:14.170  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 22:20:14.171  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:14.171  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:14.171  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 22:20:14.172  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:20:14.172  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:14.172  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:20:14.174  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:14.174  3267  3325 I jxcore-log: 
,03-30 22:20:14.174  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:14.174  3267  3325 I jxcore-log: 
,03-30 22:20:14.178  3267  3325 I jxcore-log: ok 100 error should be null
,03-30 22:20:14.178  3267  3325 I jxcore-log: 
,03-30 22:20:14.179  3267  3325 I jxcore-log: ok 101 error should be null
03-30 22:20:14.179  3267  3325 I jxcore-log: 
,03-30 22:20:14.185  3267  3325 I jxcore-log: # setup
,03-30 22:20:14.185  3267  3325 I jxcore-log: 
,03-30 22:20:14.383  3267  3325 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
03-30 22:20:14.383  3267  3325 I jxcore-log: 
,03-30 22:20:14.565  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:20:14.565  3267  3325 I jxcore-log: 
,03-30 22:20:14.567  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 39628
03-30 22:20:14.567  3267  3325 I jxcore-log: 
,03-30 22:20:14.585  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 39628, start advertisements: true
,03-30 22:20:14.585  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 22:20:14.585  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 22:20:14.585  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 22:20:14.589  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 22:20:14.589  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 22:20:14.589  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-30 22:20:14.589  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-30 22:20:14.593  2148  2163 D BtGatt.GattService: registerClient() - UUID=4d34a053-1574-4c08-9fb9-1a230365c3bf,
03-30 22:20:14.594  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=4d34a053-1574-4c08-9fb9-1a230365c3bf, clientIf=5
03-30 22:20:14.595  3267  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 22:20:14.595  2148  2994 D BtGatt.GattService: start scan with filters
03-30 22:20:14.597  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:20:14.598  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 22:20:14.598  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 22:20:14.598  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 22:20:14.598  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 22:20:14.598  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-30 22:20:14.598  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:14.598  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 22:20:14.598  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-30 22:20:14.600  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-30 22:20:14.601  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:14.602  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 22:20:14.602  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 22:20:14.602  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 22:20:14.602  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:14.605  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:14.606  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:14.606  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
,03-30 22:20:14.606  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 22:20:14.608  2148  2164 D BtGatt.GattService: registerClient() - UUID=b1b27f91-5a11-4f8b-9703-3c78d0a376e0
03-30 22:20:14.608  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=b1b27f91-5a11-4f8b-9703-3c78d0a376e0, clientIf=6
03-30 22:20:14.609  3267  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 22:20:14.610  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-30 22:20:14.610  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:14.612  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 22:20:14.612  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:14.612  2148  2220 D BtGatt.AdvertiseManager: message : 0
,03-30 22:20:14.616  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 22:20:14.619  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-30 22:20:14.621  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 22:20:14.622  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 22:20:14.622  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 22:20:14.623   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:14.626  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 22:20:14.626  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 22:20:14.626  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 22:20:14.627  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 22:20:14.628  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-30 22:20:14.629  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-30 22:20:14.629  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 22:20:14.629  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-30 22:20:14.629  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 22:20:14.629  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 22:20:14.629  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 22:20:14.629  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-30 22:20:14.629  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 22:20:14.630  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 22:20:14.630  3267  3267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 22:20:14.630  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:20:14.630  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-30 22:20:14.630  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 22:20:14.630  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 22:20:14.630  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-30 22:20:14.630  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:14.634   823  1236 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:14.636  3267  3810 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 22:20:14.640  3267  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 22:20:14.642  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-30 22:20:14.642  3267  3325 I jxcore-log: 
,03-30 22:20:14.653  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:14.653  3267  3325 I jxcore-log: 
,03-30 22:20:14.654  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 22:20:14.654  3267  3325 I jxcore-log: 
,03-30 22:20:14.656  3267  3325 I jxcore-log: ok 102 error should be null
03-30 22:20:14.656  3267  3325 I jxcore-log: 
03-30 22:20:14.656  3267  3325 I jxcore-log: ok 103 error should be null
03-30 22:20:14.656  3267  3325 I jxcore-log: 
,03-30 22:20:14.664  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 39628, start advertisements: true
,03-30 22:20:14.664  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:14.664  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-30 22:20:14.664  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:20:14.664  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 22:20:14.673  3267  3325 I jxcore-log: ok 104 error should be null
03-30 22:20:14.673  3267  3325 I jxcore-log: 
,03-30 22:20:14.673  3267  3325 I jxcore-log: ok 105 error should be null
03-30 22:20:14.673  3267  3325 I jxcore-log: 
,03-30 22:20:14.679  3267  3325 I jxcore-log: # teardown
03-30 22:20:14.679  3267  3325 I jxcore-log: 
,03-30 22:20:15.116  2148  2148 D BtGatt.ScanManager: awakened up at time 208613
,03-30 22:20:15.119  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 22:20:15.129  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
03-30 22:20:15.129  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:15.129  2148  2211 D BtGatt.GattService: current time is 208626535230
,03-30 22:20:15.130  2148  2211 D BtGatt.GattService: Batch record : [-8, 125, -27, -34, 44, 97, 1, -128, -80, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -68, 7, 0, 0, 0, -127, -59, 40, 32, -73, -32, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-30 22:20:15.132  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-30 22:20:15.135  2148  2211 D BtGatt.GattService: ScanRecord : []
03-30 22:20:15.135  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-30 22:20:15.143  3267  3267 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-30 22:20:15.145  3267  3267 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
,03-30 22:20:15.145  3267  3267 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-30 22:20:15.146  3267  3267 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-30 22:20:15.150  3267  3325 I jxcore-log: DEBUG createPeerListener: createPeerListener
,03-30 22:20:15.150  3267  3325 I jxcore-log: 
,03-30 22:20:15.154  3267  3325 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
,03-30 22:20:15.154  3267  3325 I jxcore-log: 
,03-30 22:20:15.157  3267  3325 I jxcore-log: DEBUG createPeerListener: createPeerListener
,03-30 22:20:15.157  3267  3325 I jxcore-log: 
,03-30 22:20:15.160  3267  3325 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
,03-30 22:20:15.160  3267  3325 I jxcore-log: 
,03-30 22:20:15.172  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:20:15.173  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-30 22:20:15.173  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-30 22:20:15.173  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-30 22:20:15.173  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
03-30 22:20:15.174  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-30 22:20:15.175  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 22:20:15.175  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 22:20:15.175  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-30 22:20:15.175  3267  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 22:20:15.175  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-30 22:20:15.175  3267  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-30 22:20:15.175  3267  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 22:20:15.176  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-30 22:20:15.176  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 22:20:15.178  2148  2994 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:20:15.180  2148  2163 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 22:20:15.180  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:15.180  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:15.180  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 22:20:15.180  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 22:20:15.181  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 22:20:15.181  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 22:20:15.181  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:15.181  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:20:15.182  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 22:20:15.182  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 22:20:15.183  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:15.183  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:15.183  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:20:15.185  2148  2220 D BtGatt.AdvertiseManager: message : 1
03-30 22:20:15.185  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 22:20:15.186  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-30 22:20:15.186  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:15.186  2148  2211 D BtGatt.GattService: current time is 208683188563
03-30 22:20:15.186  2148  2211 D BtGatt.GattService: Batch record : [-8, 125, -27, -34, 44, 97, 1, -128, -80, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-30 22:20:15.186  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 22:20:15.188  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 22:20:15.188  2148  2211 D BtGatt.GattService: Client app is not null!
03-30 22:20:15.188  2148  2163 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 22:20:15.189  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:15.189  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:15.189  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 22:20:15.189  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 22:20:15.189  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-30 22:20:15.189  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:15.189  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 22:20:15.189  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 22:20:15.190  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 22:20:15.190  3267  3325 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-30 22:20:15.190  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:15.190  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 22:20:15.190  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:15.190  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 22:20:15.198  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 22:20:15.203   823  1236 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:15.204  3267  3325 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-30 22:20:15.204  3267  3325 I jxcore-log: 
,03-30 22:20:15.211  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 22:20:15.214  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 22:20:15.214  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:15.217  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
,03-30 22:20:15.217  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
03-30 22:20:15.217  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 22:20:15.217  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:15.217  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 22:20:15.218  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:15.218  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 22:20:15.218  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 22:20:15.218  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:15.218  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:20:15.219  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-30 22:20:15.219  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 22:20:15.219  3267  3325 I jxcore-log: 
,03-30 22:20:15.219  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:15.219  3267  3325 I jxcore-log: 
03-30 22:20:15.220  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:15.220  3267  3325 I jxcore-log: 
,03-30 22:20:15.224  3267  3325 I jxcore-log: ok 106 error should be null,
03-30 22:20:15.224  3267  3325 I jxcore-log: 
03-30 22:20:15.224  3267  3325 I jxcore-log: ok 107 error should be null
03-30 22:20:15.224  3267  3325 I jxcore-log: 
,03-30 22:20:15.228  3267  3325 I jxcore-log: # setup,
03-30 22:20:15.228  3267  3325 I jxcore-log: 
,03-30 22:20:15.358  3267  3325 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times,
03-30 22:20:15.358  3267  3325 I jxcore-log: 
,03-30 22:20:15.562  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server,
03-30 22:20:15.562  3267  3325 I jxcore-log: 
,03-30 22:20:15.565  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 42782,
03-30 22:20:15.565  3267  3325 I jxcore-log: 
,03-30 22:20:15.569  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:20:15.570  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:15.570  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:20:15.573  3267  3325 I jxcore-log: ok 108 error should be null
03-30 22:20:15.573  3267  3325 I jxcore-log: 
,03-30 22:20:15.573  3267  3325 I jxcore-log: ok 109 error should be null
03-30 22:20:15.573  3267  3325 I jxcore-log: 
,03-30 22:20:15.576  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 22:20:15.576  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:15.576  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:15.579  3267  3325 I jxcore-log: ok 110 error should be null
03-30 22:20:15.579  3267  3325 I jxcore-log: 
,03-30 22:20:15.580  3267  3325 I jxcore-log: ok 111 error should be null
03-30 22:20:15.580  3267  3325 I jxcore-log: 
,03-30 22:20:15.586  3267  3325 I jxcore-log: # teardown
03-30 22:20:15.586  3267  3325 I jxcore-log: 
,03-30 22:20:15.730  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:20:15.730  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:15.730  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:15.735  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:20:15.735  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:15.735  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-30 22:20:15.741  3267  3325 I jxcore-log: ok 112 error should be null
03-30 22:20:15.741  3267  3325 I jxcore-log: 
,03-30 22:20:15.741  3267  3325 I jxcore-log: ok 113 error should be null
03-30 22:20:15.741  3267  3325 I jxcore-log: 
,03-30 22:20:15.747  3267  3325 I jxcore-log: # setup
03-30 22:20:15.747  3267  3325 I jxcore-log: 
,03-30 22:20:15.901  3267  3325 I jxcore-log: # 30. #start should fail if called twice in a row
03-30 22:20:15.901  3267  3325 I jxcore-log: 
,03-30 22:20:16.087  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:20:16.087  3267  3325 I jxcore-log: 
,03-30 22:20:16.089  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 40177
03-30 22:20:16.089  3267  3325 I jxcore-log: 
,03-30 22:20:16.091  3267  3325 I jxcore-log: ok 114 first call should succeed
03-30 22:20:16.091  3267  3325 I jxcore-log: 
,03-30 22:20:16.092  3267  3325 I jxcore-log: ok 115 first call should succeed
03-30 22:20:16.092  3267  3325 I jxcore-log: 
,03-30 22:20:16.095  3267  3325 I jxcore-log: ok 116 specific error should be returned
03-30 22:20:16.095  3267  3325 I jxcore-log: 
,03-30 22:20:16.097  3267  3325 I jxcore-log: # teardown
03-30 22:20:16.097  3267  3325 I jxcore-log: 
,03-30 22:20:16.262  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:20:16.262  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 22:20:16.262  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:16.267  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 22:20:16.267  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 22:20:16.267  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:16.277  3267  3325 I jxcore-log: ok 117 error should be null
03-30 22:20:16.277  3267  3325 I jxcore-log: 
,03-30 22:20:16.277  3267  3325 I jxcore-log: ok 118 error should be null
03-30 22:20:16.277  3267  3325 I jxcore-log: 
,03-30 22:20:16.282  3267  3325 I jxcore-log: # setup
03-30 22:20:16.282  3267  3325 I jxcore-log: 
,03-30 22:20:16.429  3267  3325 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-30 22:20:16.429  3267  3325 I jxcore-log: 
,03-30 22:20:16.645  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:20:16.645  3267  3325 I jxcore-log: 
,03-30 22:20:16.648  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 53151
03-30 22:20:16.648  3267  3325 I jxcore-log: 
,03-30 22:20:16.657  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 39628, start advertisements: false
03-30 22:20:16.657  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:16.657  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 22:20:16.657  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 22:20:16.664  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 22:20:16.664  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 22:20:16.664  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 22:20:16.670  2148  2163 D BtGatt.GattService: registerClient() - UUID=ba30ecb9-4f7a-40d0-97d4-f08d2a1186de
,03-30 22:20:16.671  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=ba30ecb9-4f7a-40d0-97d4-f08d2a1186de, clientIf=5
03-30 22:20:16.671  3267  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 22:20:16.672  2148  2164 D BtGatt.GattService: start scan with filters
,03-30 22:20:16.674  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 22:20:16.674  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 22:20:16.675  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 22:20:16.675  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:20:16.675  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 22:20:16.675  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:16.676  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:16.676  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 22:20:16.677   823  3512 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:16.684  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:20:16.684  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-30 22:20:16.684  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-30 22:20:16.684  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:16.684  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:20:16.685  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:16.685  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 22:20:16.686  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:16.689  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:16.689  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:16.689  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:16.690  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 22:20:16.691  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:16.691  3267  3325 I jxcore-log: 
03-30 22:20:16.693  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:16.693  3267  3325 I jxcore-log: 
,03-30 22:20:16.694  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 22:20:16.694  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:16.696  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-30 22:20:16.697  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:16.708  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 53151, start advertisements: true
03-30 22:20:16.708  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 22:20:16.708  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 22:20:16.709  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 22:20:16.713  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-30 22:20:16.713  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-30 22:20:16.713  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 22:20:16.713  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-30 22:20:16.714  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-30 22:20:16.714  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:16.714  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:16.714  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 22:20:16.719  2148  2994 D BtGatt.GattService: registerClient() - UUID=7792cd0b-d0f7-4ccc-ab7e-80b1865a3ad4
03-30 22:20:16.719  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=7792cd0b-d0f7-4ccc-ab7e-80b1865a3ad4, clientIf=6
03-30 22:20:16.720  3267  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 22:20:16.722  2148  2220 D BtGatt.AdvertiseManager: message : 0
,03-30 22:20:16.728  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising,
,03-30 22:20:16.732  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-30 22:20:16.736  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-30 22:20:16.736  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 22:20:16.736  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 22:20:16.736  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 22:20:16.736  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 22:20:16.737  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 22:20:16.737  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 22:20:16.737  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 22:20:16.737   823  1102 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:16.740  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 22:20:16.740  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-30 22:20:16.740  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 22:20:16.740  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:16.740  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 22:20:16.741  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 22:20:16.742  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 22:20:16.742  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 22:20:16.742  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 22:20:16.742  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 22:20:16.742  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 22:20:16.742  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:16.742  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 22:20:16.744   823  1260 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 22:20:16.745  3267  3811 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 22:20:16.750  3267  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 22:20:16.751  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 22:20:16.751  3267  3325 I jxcore-log: 
,03-30 22:20:16.756  3267  3325 I jxcore-log: ok 119 called only once
03-30 22:20:16.756  3267  3325 I jxcore-log: 
,03-30 22:20:16.757  3267  3325 I jxcore-log: ok 120 discovery state matches
03-30 22:20:16.757  3267  3325 I jxcore-log: 
,03-30 22:20:16.757  3267  3325 I jxcore-log: ok 121 advertising state matches
03-30 22:20:16.757  3267  3325 I jxcore-log: 
,03-30 22:20:16.766  3267  3325 I jxcore-log: # teardown
03-30 22:20:16.766  3267  3325 I jxcore-log: 
,03-30 22:20:17.325  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:20:17.326  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-30 22:20:17.326  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 22:20:17.326  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 22:20:17.326  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 22:20:17.326  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 22:20:17.326  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 22:20:17.326  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 22:20:17.326  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-30 22:20:17.326  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 22:20:17.326  3267  3811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 22:20:17.326  3267  3811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 22:20:17.326  3267  3811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 22:20:17.327  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 22:20:17.327  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 22:20:17.330  2148  2163 D BtGatt.GattService: stopScan() - queue size =1
03-30 22:20:17.331  2148  2164 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 22:20:17.332  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:17.332  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:17.332  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 22:20:17.332  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 22:20:17.332  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 22:20:17.333  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 22:20:17.333  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 22:20:17.335  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:20:17.335  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:17.335  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:20:17.338  2148  2220 D BtGatt.AdvertiseManager: message : 1
03-30 22:20:17.338  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:17.338  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:17.339  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
03-30 22:20:17.339  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 22:20:17.342  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
,03-30 22:20:17.342  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:17.342  2148  2211 D BtGatt.GattService: current time is 210839519500
03-30 22:20:17.343  2148  2211 D BtGatt.GattService: Batch record : [33, -9, -75, -66, -94, 122, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0],
03-30 22:20:17.343  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 22:20:17.344  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 22:20:17.344  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-30 22:20:17.344  2148  2211 D BtGatt.GattService: Client app is not null!
03-30 22:20:17.346  2148  2164 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 22:20:17.346  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-30 22:20:17.347  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:17.347  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 22:20:17.347  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-30 22:20:17.347  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 22:20:17.347  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:17.347  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-30 22:20:17.347  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 22:20:17.348  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 22:20:17.348  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-30 22:20:17.348  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:17.348  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:17.348  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 22:20:17.356  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-30 22:20:17.356   823  3512 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 22:20:17.358  3267  3325 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-30 22:20:17.358  3267  3325 I jxcore-log: 
,03-30 22:20:17.358  3267  3325 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-30 22:20:17.358  3267  3325 I jxcore-log: 
03-30 22:20:17.360  3267  3325 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-30 22:20:17.360  3267  3325 I jxcore-log: 
,03-30 22:20:17.366  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 22:20:17.368  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 22:20:17.368  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 22:20:17.368  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 22:20:17.368  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:17.374  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-30 22:20:17.375  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:17.375  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:17.375  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:17.376  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:17.377  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 22:20:17.377  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-30 22:20:17.377  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:17.377  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:20:17.378  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 22:20:17.378  3267  3325 I jxcore-log: 
03-30 22:20:17.379  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:17.379  3267  3325 I jxcore-log: 
03-30 22:20:17.380  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:17.380  3267  3325 I jxcore-log: 
03-30 22:20:17.384  3267  3325 I jxcore-log: ok 122 error should be null
03-30 22:20:17.384  3267  3325 I jxcore-log: 
,03-30 22:20:17.385  3267  3325 I jxcore-log: ok 123 error should be null
03-30 22:20:17.385  3267  3325 I jxcore-log: 
,03-30 22:20:17.398  3267  3325 I jxcore-log: # setup
03-30 22:20:17.398  3267  3325 I jxcore-log: 
,03-30 22:20:17.656  3267  3325 I jxcore-log: # 32. does not send duplicate availability changes
03-30 22:20:17.656  3267  3325 I jxcore-log: 
,03-30 22:20:18.038  3368  3812 V GoogleAuthProtoRequest: [336] a.<init>: mAccountName set to: thalitester@gmail.com
,03-30 22:20:18.118  1239  2547 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-30 22:20:18.119  1239  2547 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:20:18.119  1239  2547 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-30 22:20:18.119  1239  2547 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:20:18.129  1239  2547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:20:18.148  3368  3812 W ExperimentUpdateService: [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-30 22:20:18.150  3368  3812 W ExperimentUpdateService: [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-30 22:20:18.150  3368  3812 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-30 22:20:18.150  3368  3812 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-30 22:20:18.150  3368  3812 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-30 22:20:18.150  3368  3812 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-30 22:20:18.150  3368  3812 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-30 22:20:18.150  3368  3812 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-30 22:20:18.150  3368  3812 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-30 22:20:18.150  3368  3812 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-30 22:20:18.150  3368  3812 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-30 22:20:18.150  3368  3812 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-30 22:20:18.821  3267  3325 I jxcore-log: ok 124 should be called once
03-30 22:20:18.821  3267  3325 I jxcore-log: 
,03-30 22:20:18.824  3267  3325 I jxcore-log: ok 125 should not have been called more than once,
03-30 22:20:18.824  3267  3325 I jxcore-log: 
,03-30 22:20:18.828  3267  3325 I jxcore-log: # teardown
,03-30 22:20:18.828  3267  3325 I jxcore-log: 
,03-30 22:20:18.969  3267  3325 I jxcore-log: ok 126 error should be null
03-30 22:20:18.969  3267  3325 I jxcore-log: 
,03-30 22:20:18.971  3267  3325 I jxcore-log: ok 127 error should be null
03-30 22:20:18.971  3267  3325 I jxcore-log: 
,03-30 22:20:18.975  3267  3325 I jxcore-log: # setup
03-30 22:20:18.975  3267  3325 I jxcore-log: 
,03-30 22:20:19.270  3267  3325 I jxcore-log: # 33. can get the network status
03-30 22:20:19.270  3267  3325 I jxcore-log: 
,03-30 22:20:19.433  3267  3325 I jxcore-log: ok 128 network status should have certain non-empty properties
03-30 22:20:19.433  3267  3325 I jxcore-log: 
,03-30 22:20:19.436  3267  3325 I jxcore-log: # teardown
,03-30 22:20:19.436  3267  3325 I jxcore-log: 
,03-30 22:20:19.615  3267  3325 I jxcore-log: ok 129 error should be null
03-30 22:20:19.615  3267  3325 I jxcore-log: 
,03-30 22:20:19.615  3267  3325 I jxcore-log: ok 130 error should be null
03-30 22:20:19.615  3267  3325 I jxcore-log: 
,03-30 22:20:19.623  3267  3325 I jxcore-log: # setup
03-30 22:20:19.623  3267  3325 I jxcore-log: 
,03-30 22:20:19.795  3267  3325 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-30 22:20:19.795  3267  3325 I jxcore-log: 
,03-30 22:20:19.967  3267  3325 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-30 22:20:19.967  3267  3325 I jxcore-log: 
,03-30 22:20:19.992  3267  3325 I jxcore-log: ok 131 host address should match
03-30 22:20:19.992  3267  3325 I jxcore-log: 
,03-30 22:20:19.992  3267  3325 I jxcore-log: ok 132 port should match
03-30 22:20:19.992  3267  3325 I jxcore-log: 
,03-30 22:20:21.973  3267  3325 I jxcore-log: ok 133 host address should be null
03-30 22:20:21.973  3267  3325 I jxcore-log: 
,03-30 22:20:21.974  3267  3325 I jxcore-log: ok 134 port should should be null
03-30 22:20:21.974  3267  3325 I jxcore-log: 
,03-30 22:20:21.996  3267  3325 I jxcore-log: # teardown
03-30 22:20:21.996  3267  3325 I jxcore-log: 
,03-30 22:20:22.215  3267  3325 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,03-30 22:20:22.215  3267  3325 I jxcore-log: 
03-30 22:20:22.217  3267  3325 I jxcore-log: ok 135 error should be null
03-30 22:20:22.217  3267  3325 I jxcore-log: 
03-30 22:20:22.218  3267  3325 I jxcore-log: ok 136 error should be null
03-30 22:20:22.218  3267  3325 I jxcore-log: 
,03-30 22:20:22.220  3267  3325 I jxcore-log: # setup
03-30 22:20:22.220  3267  3325 I jxcore-log: 
,03-30 22:20:22.445  3267  3325 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
03-30 22:20:22.445  3267  3325 I jxcore-log: 
,03-30 22:20:22.617  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 53151, start advertisements: false
03-30 22:20:22.617  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:22.617  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-30 22:20:22.617  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 22:20:22.623  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 22:20:22.623  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 22:20:22.623  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 22:20:22.629  2148  2994 D BtGatt.GattService: registerClient() - UUID=d84dd44d-d517-42ce-bca3-fc12897a91a6
,03-30 22:20:22.630  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=d84dd44d-d517-42ce-bca3-fc12897a91a6, clientIf=5,
03-30 22:20:22.630  3267  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 22:20:22.631  2148  2164 D BtGatt.GattService: start scan with filters
03-30 22:20:22.632  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 22:20:22.632  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 22:20:22.632  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 22:20:22.632  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 22:20:22.632  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:22.632  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 22:20:22.632  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 22:20:22.633  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:20:22.633   823  1433 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:22.646  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-30 22:20:22.646  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 22:20:22.646  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 22:20:22.646  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 22:20:22.646  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 22:20:22.647  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:20:22.647  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 22:20:22.647  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:22.649  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-30 22:20:22.650  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:22.651  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:22.651  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 22:20:22.652  3267  3325 I jxcore-log: ok 137 Can call startListeningForAdvertisements without error
03-30 22:20:22.652  3267  3325 I jxcore-log: 
,03-30 22:20:22.654  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-30 22:20:22.654  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 22:20:22.654  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:22.654  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:22.654  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-30 22:20:22.654  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 22:20:22.656  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-30 22:20:22.656  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:22.657  2148  2163 D BtGatt.GattService: stopScan() - queue size =1
03-30 22:20:22.659  2148  2994 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 22:20:22.660  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:20:22.660  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:22.660  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
,03-30 22:20:22.661  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:22.661  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-30 22:20:22.661  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 22:20:22.662  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-30 22:20:22.662  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
03-30 22:20:22.662  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:22.662  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 22:20:22.663  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:22.663  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:22.663  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:22.663  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:22.664  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:20:22.665  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 22:20:22.665  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:22.669  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-30 22:20:22.669  3267  3325 I jxcore-log: 
03-30 22:20:22.670  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:22.670  3267  3325 I jxcore-log: 
03-30 22:20:22.671  3267  3325 I jxcore-log: ok 138 Can call stopListeningForAdvertisements without error
03-30 22:20:22.671  3267  3325 I jxcore-log: 
,03-30 22:20:22.679  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-30 22:20:22.679  3267  3325 I jxcore-log: 
03-30 22:20:22.680  3267  3325 I jxcore-log: # teardown
03-30 22:20:22.680  3267  3325 I jxcore-log: 
,03-30 22:20:23.326  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:20:23.326  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:23.326  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:23.331  3267  3325 I jxcore-log: ok 139 Should be able to call stopListeningForAdvertisments in teardown
03-30 22:20:23.331  3267  3325 I jxcore-log: 
,03-30 22:20:23.333  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:20:23.333  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:23.334  3267  3325 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
03-30 22:20:23.334  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 22:20:23.334  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-30 22:20:23.334  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 22:20:23.334  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 22:20:23.334  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 22:20:23.337  3267  3325 D BluetoothLeScanner: could not find callback wrapper
,03-30 22:20:23.337  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:23.340  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:23.340  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 22:20:23.340  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 22:20:23.344  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 22:20:23.345  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:23.345  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 22:20:23.345  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 22:20:23.345  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 22:20:23.355  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 22:20:23.356   823  1260 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:23.368  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 22:20:23.369  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:23.369  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:23.375  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
,03-30 22:20:23.376  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-30 22:20:23.376  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 22:20:23.379  3267  3325 I jxcore-log: ok 140 Should be able to call stopAdvertisingAndListening in teardown,
03-30 22:20:23.379  3267  3325 I jxcore-log: 
03-30 22:20:23.394  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:23.394  3267  3325 I jxcore-log: 
,03-30 22:20:23.395  3267  3325 I jxcore-log: # setup,
03-30 22:20:23.395  3267  3325 I jxcore-log: 
,03-30 22:20:23.522  3267  3325 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error,
03-30 22:20:23.522  3267  3325 I jxcore-log: 
,03-30 22:20:23.692  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 53151, start advertisements: false
03-30 22:20:23.693  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:23.693  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 22:20:23.693  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 22:20:23.702  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-30 22:20:23.702  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 22:20:23.702  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 22:20:23.712  2148  2163 D BtGatt.GattService: registerClient() - UUID=59337ce1-7d61-44e6-96e6-c2fe218cbac1
,03-30 22:20:23.713  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=59337ce1-7d61-44e6-96e6-c2fe218cbac1, clientIf=5
03-30 22:20:23.714  3267  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 22:20:23.715  2148  2994 D BtGatt.GattService: start scan with filters
,03-30 22:20:23.717  2148  2221 D BtGatt.ScanManager: handling starting scan
,03-30 22:20:23.718  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 22:20:23.718  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 22:20:23.718  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-30 22:20:23.718  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 22:20:23.718  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:23.719  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 22:20:23.719  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 22:20:23.720   823  1242 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:23.730  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-30 22:20:23.730  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:23.731  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:20:23.731  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-30 22:20:23.732  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:23.732  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 22:20:23.732  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:23.732  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-30 22:20:23.732  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:23.733  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:20:23.733  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:23.733  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-30 22:20:23.736  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 22:20:23.736  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:23.738  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-30 22:20:23.738  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:23.742  3267  3325 I jxcore-log: ok 141 Can call startListeningForAdvertisements without error
,03-30 22:20:23.742  3267  3325 I jxcore-log: 
,03-30 22:20:23.747  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 53151, start advertisements: false
,03-30 22:20:23.747  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:23.748  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-30 22:20:23.748  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:23.748  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 22:20:23.749  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:23.749  3267  3325 I jxcore-log: 
03-30 22:20:23.750  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:23.750  3267  3325 I jxcore-log: ,
03-30 22:20:23.751  3267  3325 I jxcore-log: ok 142 Can call startListeningForAdvertisements twice without error
03-30 22:20:23.751  3267  3325 I jxcore-log: 
,03-30 22:20:23.757  3267  3325 I jxcore-log: # teardown
,03-30 22:20:23.757  3267  3325 I jxcore-log: 
,03-30 22:20:23.993  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:20:23.994  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:23.994  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 22:20:23.994  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 22:20:23.998  2148  2163 D BtGatt.GattService: stopScan() - queue size =1
03-30 22:20:24.002  2148  2994 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 22:20:24.002  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:20:24.002  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:24.003  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:20:24.004  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:24.004  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:24.004  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 22:20:24.005  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-30 22:20:24.005  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-30 22:20:24.005  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:24.006  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 22:20:24.007  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:24.007  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:24.008  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:24.008  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:24.008  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:20:24.010  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 22:20:24.010  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:24.013  3267  3325 I jxcore-log: ok 143 Should be able to call stopListeningForAdvertisments in teardown,
03-30 22:20:24.013  3267  3325 I jxcore-log: 
03-30 22:20:24.015  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:20:24.015  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:24.015  3267  3325 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-30 22:20:24.015  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-30 22:20:24.016  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-30 22:20:24.016  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 22:20:24.016  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-30 22:20:24.017  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 22:20:24.018  3267  3325 D BluetoothLeScanner: could not find callback wrapper
,03-30 22:20:24.018  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:24.019  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-30 22:20:24.019  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 22:20:24.019  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 22:20:24.021  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 22:20:24.021  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 22:20:24.022  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-30 22:20:24.022  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:24.022  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,03-30 22:20:24.026  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:24.026  3267  3325 I jxcore-log: ,
,03-30 22:20:24.030  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 22:20:24.031   823  3512 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:24.039  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 22:20:24.041  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 22:20:24.041  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:24.046  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-30 22:20:24.046  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:24.046  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:24.047  3267  3325 I jxcore-log: ok 144 Should be able to call stopAdvertisingAndListening in teardown
03-30 22:20:24.047  3267  3325 I jxcore-log: 
,03-30 22:20:24.054  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:24.054  3267  3325 I jxcore-log: 
,03-30 22:20:24.055  3267  3325 I jxcore-log: # setup
03-30 22:20:24.055  3267  3325 I jxcore-log: 
,03-30 22:20:24.196  3267  3325 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening
03-30 22:20:24.196  3267  3325 I jxcore-log: 
,03-30 22:20:24.361  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-30 22:20:24.361  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:24.361  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 22:20:24.361  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 22:20:24.369  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-30 22:20:24.369  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 22:20:24.369  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 22:20:24.369  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 22:20:24.377  2148  2163 D BtGatt.GattService: registerClient() - UUID=42693189-f2b0-4105-a76f-6d65aa0ca693
,03-30 22:20:24.378  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=42693189-f2b0-4105-a76f-6d65aa0ca693, clientIf=5
,03-30 22:20:24.378  3267  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 22:20:24.380  2148  2994 D BtGatt.GattService: start scan with filters
,03-30 22:20:24.382  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:20:24.383  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 22:20:24.383  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 22:20:24.383  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
,03-30 22:20:24.383  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 22:20:24.383  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 22:20:24.384  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 22:20:24.384  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:24.384  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 22:20:24.384  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-30 22:20:24.385  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:24.385  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:24.385  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 22:20:24.387  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 22:20:24.387  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:24.389  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:24.389  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:24.390  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:24.390  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 22:20:24.394  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-30 22:20:24.394  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:24.397  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 22:20:24.397  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:24.399  2148  2164 D BtGatt.GattService: registerClient() - UUID=6951cbef-4154-4837-b57a-424d48dfa20f
03-30 22:20:24.400  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=6951cbef-4154-4837-b57a-424d48dfa20f, clientIf=6
,03-30 22:20:24.401  3267  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 22:20:24.404  2148  2220 D BtGatt.AdvertiseManager: message : 0
,03-30 22:20:24.411  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 22:20:24.416  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-30 22:20:24.421  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 22:20:24.422  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 22:20:24.422  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 22:20:24.423   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:24.432  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-30 22:20:24.432  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 22:20:24.432  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-30 22:20:24.432  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 22:20:24.434  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-30 22:20:24.434  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 22:20:24.435  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 22:20:24.435  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 22:20:24.435  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:24.435  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-30 22:20:24.436  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 22:20:24.436  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 22:20:24.436  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 22:20:24.436  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-30 22:20:24.436  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 22:20:24.436  3267  3267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 22:20:24.437  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:20:24.437  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-30 22:20:24.437  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:24.438  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 22:20:24.438  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 22:20:24.439   823  1260 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-30 22:20:24.440  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:24.440  3267  3325 I jxcore-log: 
03-30 22:20:24.443  3267  3814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-30 22:20:24.444  3267  3325 I jxcore-log: ok 145 Can call startUpdateAdvertisingAndListening without error
03-30 22:20:24.444  3267  3325 I jxcore-log: 
,03-30 22:20:24.445  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 22:20:24.446  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-30 22:20:24.446  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-30 22:20:24.446  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 22:20:24.446  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 22:20:24.446  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 22:20:24.446  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 22:20:24.446  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 22:20:24.446  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 22:20:24.446  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-30 22:20:24.447  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 22:20:24.447  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 22:20:24.450  2148  2994 D BtGatt.GattService: stopScan() - queue size =1
03-30 22:20:24.453  2148  2164 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 22:20:24.454  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:20:24.454  3267  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-30 22:20:24.454  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:24.454  3267  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 22:20:24.454  3267  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 22:20:24.455  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
,03-30 22:20:24.455  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:24.455  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:24.455  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 22:20:24.455  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-30 22:20:24.455  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-30 22:20:24.455  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 22:20:24.455  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 22:20:24.457  2148  2220 D BtGatt.AdvertiseManager: message : 1
03-30 22:20:24.457  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:24.457  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:24.457  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 22:20:24.457  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:20:24.459  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-30 22:20:24.459  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:24.459  2148  2211 D BtGatt.GattService: current time is 217956595435
03-30 22:20:24.459  2148  2211 D BtGatt.GattService: Batch record : [104, 117, -120, 94, 63, 117, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-30 22:20:24.460  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-30 22:20:24.461  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 22:20:24.461  2148  2211 D BtGatt.GattService: Client app is not null!
03-30 22:20:24.462  2148  2163 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 22:20:24.462  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:24.462  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:24.462  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 22:20:24.462  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 22:20:24.462  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 22:20:24.462  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:24.462  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 22:20:24.463  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 22:20:24.464  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 22:20:24.464  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:24.464  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 22:20:24.464  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:24.464  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 22:20:24.467  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:24.467  3267  3325 I jxcore-log: 
,03-30 22:20:24.468  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 22:20:24.469   823  3512 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 22:20:24.471  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 22:20:24.471  3267  3325 I jxcore-log: 
,03-30 22:20:24.473  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-30 22:20:24.474  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 22:20:24.474  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:24.477  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-30 22:20:24.477  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 22:20:24.477  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 22:20:24.477  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:24.477  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:24.477  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 22:20:24.477  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:24.477  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-30 22:20:24.479  3267  3325 I jxcore-log: ok 146 Can call stopAdvertisingAndListening without error
03-30 22:20:24.479  3267  3325 I jxcore-log: 
,03-30 22:20:24.484  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 22:20:24.484  3267  3325 I jxcore-log: 
,03-30 22:20:24.485  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:24.485  3267  3325 I jxcore-log: 
,03-30 22:20:24.486  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:24.486  3267  3325 I jxcore-log: 
,03-30 22:20:24.487  3267  3325 I jxcore-log: # teardown
03-30 22:20:24.487  3267  3325 I jxcore-log: 
,03-30 22:20:24.957  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:20:24.957  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:24.957  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:24.967  3267  3325 I jxcore-log: ok 147 Should be able to call stopListeningForAdvertisments in teardown
03-30 22:20:24.967  3267  3325 I jxcore-log: 
,03-30 22:20:24.969  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 22:20:24.969  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 22:20:24.969  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:24.974  3267  3325 I jxcore-log: ok 148 Should be able to call stopAdvertisingAndListening in teardown
03-30 22:20:24.974  3267  3325 I jxcore-log: 
,03-30 22:20:24.980  3267  3325 I jxcore-log: # setup
03-30 22:20:24.980  3267  3325 I jxcore-log: 
,03-30 22:20:25.126  3267  3325 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-30 22:20:25.126  3267  3325 I jxcore-log: 
,03-30 22:20:25.488  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-30 22:20:25.489  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 22:20:25.489  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 22:20:25.489  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 22:20:25.498  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 22:20:25.498  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 22:20:25.498  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 22:20:25.498  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 22:20:25.507  2148  2163 D BtGatt.GattService: registerClient() - UUID=0b116a56-da3f-4380-9df4-2478d88eb22b
,03-30 22:20:25.508  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=0b116a56-da3f-4380-9df4-2478d88eb22b, clientIf=5
,03-30 22:20:25.509  3267  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 22:20:25.510  2148  2994 D BtGatt.GattService: start scan with filters
,03-30 22:20:25.513  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:20:25.513  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 22:20:25.513  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 22:20:25.514  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 22:20:25.514  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 22:20:25.514  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:25.515  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 22:20:25.515  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:25.515  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 22:20:25.515  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-30 22:20:25.518  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:25.518  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:25.518  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 22:20:25.524  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 22:20:25.524  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:25.526  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:25.526  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:25.527  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:25.527  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 22:20:25.530  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 22:20:25.530  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:25.534  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-30 22:20:25.534  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:25.540  2148  2164 D BtGatt.GattService: registerClient() - UUID=c41ea4f3-5548-454f-af47-35dc22e77ad8,
03-30 22:20:25.541  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=c41ea4f3-5548-454f-af47-35dc22e77ad8, clientIf=6
03-30 22:20:25.541  3267  3283 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 22:20:25.544  2148  2220 D BtGatt.AdvertiseManager: message : 0,
,03-30 22:20:25.549  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising,
03-30 22:20:25.553  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 22:20:25.556  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-30 22:20:25.557  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 22:20:25.557  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 22:20:25.558   823  2549 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:25.566  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:20:25.566  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 22:20:25.566  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 22:20:25.566  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 22:20:25.567  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 22:20:25.567  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 22:20:25.567  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 22:20:25.567  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 22:20:25.568  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 22:20:25.568  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 22:20:25.568  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 22:20:25.568  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-30 22:20:25.568  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 22:20:25.568  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 22:20:25.568  3267  3267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 22:20:25.568  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:20:25.568  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 22:20:25.568  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:25.568  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 22:20:25.568  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 22:20:25.569  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:25.573   823  1230 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:25.575  3267  3817 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 22:20:25.578  3267  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 22:20:25.578  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:25.578  3267  3325 I jxcore-log: 
,03-30 22:20:25.582  3267  3325 I jxcore-log: ok 149 Can call startUpdateAdvertisingAndListening without error
03-30 22:20:25.582  3267  3325 I jxcore-log: 
,03-30 22:20:25.587  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,03-30 22:20:25.587  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 22:20:25.588  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-30 22:20:25.588  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:20:25.588  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:25.590  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:25.590  3267  3325 I jxcore-log: 
,03-30 22:20:25.593  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 22:20:25.593  3267  3325 I jxcore-log: 
,03-30 22:20:25.596  3267  3325 I jxcore-log: ok 150 Can call startUpdateAdvertisingAndListening twice without error
03-30 22:20:25.596  3267  3325 I jxcore-log: 
,03-30 22:20:25.606  3267  3325 I jxcore-log: # teardown,
03-30 22:20:25.606  3267  3325 I jxcore-log: 
,03-30 22:20:26.417  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-30 22:20:26.418  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 22:20:26.418  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 22:20:26.418  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 22:20:26.423  2148  2163 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:20:26.425  2148  2994 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 22:20:26.427  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:26.427  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:20:26.427  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:26.427  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-30 22:20:26.427  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-30 22:20:26.428  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 22:20:26.428  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:20:26.428  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 22:20:26.428  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 22:20:26.429  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-30 22:20:26.429  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-30 22:20:26.429  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 22:20:26.432  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:26.432  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:26.432  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:20:26.436  3267  3325 I jxcore-log: ok 151 Should be able to call stopListeningForAdvertisments in teardown
03-30 22:20:26.436  3267  3325 I jxcore-log: 
03-30 22:20:26.436  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-30 22:20:26.436  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:26.437  2148  2211 D BtGatt.GattService: current time is 219933776372
,03-30 22:20:26.437  2148  2211 D BtGatt.GattService: Batch record : [-98, 33, -26, 101, -55, 126, 1, -128, -76, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -70, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-30 22:20:26.437  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 22:20:26.437  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything,
,03-30 22:20:26.437  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 22:20:26.437  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 22:20:26.437  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-30 22:20:26.437  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 22:20:26.437  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-30 22:20:26.437  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-30 22:20:26.438  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 22:20:26.438  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 22:20:26.438  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 22:20:26.438  3267  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 22:20:26.438  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 22:20:26.438  3267  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 22:20:26.438  3267  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 22:20:26.438  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 22:20:26.438  3267  3325 D BluetoothLeScanner: could not find callback wrapper
,03-30 22:20:26.438  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:26.438  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 22:20:26.440  2148  2220 D BtGatt.AdvertiseManager: message : 1
03-30 22:20:26.441  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 22:20:26.443  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 22:20:26.444  2148  2211 D BtGatt.GattService: Client app is not null!
03-30 22:20:26.446  2148  2994 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 22:20:26.448  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:26.448  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:26.448  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-30 22:20:26.448  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 22:20:26.448  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 22:20:26.449  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:26.449  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 22:20:26.450  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 22:20:26.452  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 22:20:26.452  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:26.452  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 22:20:26.452  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:26.452  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 22:20:26.464  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 22:20:26.464  3267  3325 I jxcore-log: 
,03-30 22:20:26.475  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 22:20:26.475   823  1102 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-30 22:20:26.483  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-30 22:20:26.484  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:26.484  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:26.488  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
,03-30 22:20:26.488  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 22:20:26.488  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 22:20:26.488  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:26.488  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:26.489  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:26.489  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-30 22:20:26.491  3267  3325 I jxcore-log: ok 152 Should be able to call stopAdvertisingAndListening in teardown,
03-30 22:20:26.491  3267  3325 I jxcore-log: 
,03-30 22:20:26.499  3267  3325 I jxcore-log: # setup,
03-30 22:20:26.499  3267  3325 I jxcore-log: 
,03-30 22:20:26.501  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:26.501  3267  3325 I jxcore-log: 
,03-30 22:20:26.503  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:26.503  3267  3325 I jxcore-log: 
,03-30 22:20:26.653  3267  3325 I jxcore-log: # 39. peerAvailabilityChange is called
03-30 22:20:26.653  3267  3325 I jxcore-log: 
,03-30 22:20:27.241  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true,
03-30 22:20:27.242  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 22:20:27.242  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 22:20:27.242  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 22:20:27.248  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-30 22:20:27.248  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 22:20:27.248  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-30 22:20:27.248  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 22:20:27.252  2148  2994 D BtGatt.GattService: registerClient() - UUID=8fd749bc-b281-4cd6-9f63-acfbad01d0d4
,03-30 22:20:27.253  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=8fd749bc-b281-4cd6-9f63-acfbad01d0d4, clientIf=5
,03-30 22:20:27.254  3267  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 22:20:27.254  2148  2164 D BtGatt.GattService: start scan with filters
,03-30 22:20:27.256  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-30 22:20:27.256  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 22:20:27.256  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:20:27.256  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 22:20:27.256  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-30 22:20:27.256  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:27.257  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 22:20:27.257  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:27.257  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 22:20:27.257  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 22:20:27.258  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 22:20:27.258  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:27.258  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 22:20:27.264  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 22:20:27.264  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-30 22:20:27.266  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:27.266  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:27.266  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:27.266  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-30 22:20:27.268  2148  3816 D BtGatt.GattService: registerClient() - UUID=90304fc0-1f6a-4bb0-8b89-37fd336500da
,03-30 22:20:27.269  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-30 22:20:27.269  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:27.269  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=90304fc0-1f6a-4bb0-8b89-37fd336500da, clientIf=6
03-30 22:20:27.270  3267  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 22:20:27.271  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-30 22:20:27.271  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:27.273  2148  2220 D BtGatt.AdvertiseManager: message : 0
,03-30 22:20:27.277  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 22:20:27.281  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 22:20:27.283  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 22:20:27.284  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 22:20:27.284  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 22:20:27.285   823  1230 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:27.291  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 22:20:27.291  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 22:20:27.291  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-30 22:20:27.291  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:27.293  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 22:20:27.294  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-30 22:20:27.294  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 22:20:27.294  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-30 22:20:27.294  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-30 22:20:27.295  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 22:20:27.295  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-30 22:20:27.295  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 22:20:27.295  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-30 22:20:27.295  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-30 22:20:27.295  3267  3267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 22:20:27.295   823   838 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 22:20:27.296  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 22:20:27.296  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 22:20:27.296  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:27.296  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-30 22:20:27.296  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 22:20:27.297  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:27.298  3267  3818 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 22:20:27.303  3267  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 22:20:27.304  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-30 22:20:27.304  3267  3325 I jxcore-log: 
,03-30 22:20:27.307  3267  3325 I jxcore-log: ok 153 Can call startUpdateAdvertisingAndListeningwithout error
,03-30 22:20:27.307  3267  3325 I jxcore-log: 
,03-30 22:20:27.313  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
,03-30 22:20:27.313  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 22:20:27.314  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only,
03-30 22:20:27.314  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:20:27.314  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 22:20:27.316  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:27.316  3267  3325 I jxcore-log: 
,03-30 22:20:27.318  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
,03-30 22:20:27.318  3267  3325 I jxcore-log: 
,03-30 22:20:27.320  3267  3325 I jxcore-log: ok 154 Can call startListeningForAdvertisements without error
,03-30 22:20:27.320  3267  3325 I jxcore-log: 
,03-30 22:20:28.279  2148  2148 D BtGatt.ScanManager: awakened up at time 221776
,03-30 22:20:28.284  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-30 22:20:28.292  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-30 22:20:28.292  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:28.292  2148  2211 D BtGatt.GattService: current time is 221789360746
03-30 22:20:28.292  2148  2211 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -58, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -100, 85, 45, 1, -114, 90, 1, -128, -82, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-30 22:20:28.293  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-30 22:20:28.294  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 22:20:28.296  3267  3267 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
,03-30 22:20:28.297  3267  3267 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
,03-30 22:20:28.297  3267  3267 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-30 22:20:28.298  3267  3267 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-30 22:20:28.300  3267  3325 I jxcore-log: ok 155 peers must be an array
03-30 22:20:28.300  3267  3325 I jxcore-log: 
,03-30 22:20:28.302  3267  3325 I jxcore-log: ok 156 peers must not be zero-length
03-30 22:20:28.302  3267  3325 I jxcore-log: 
,03-30 22:20:28.303  3267  3325 I jxcore-log: ok 157 peer must have peerIdentifier
03-30 22:20:28.303  3267  3325 I jxcore-log: 
,03-30 22:20:28.320  3267  3325 I jxcore-log: ok 158 peerIdentifier must be a string
,03-30 22:20:28.320  3267  3325 I jxcore-log: 
03-30 22:20:28.321  3267  3325 I jxcore-log: ok 159 peer must have peerAvailable
03-30 22:20:28.321  3267  3325 I jxcore-log: 
,03-30 22:20:28.322  3267  3325 I jxcore-log: ok 160 peer must have pleaseConnect
03-30 22:20:28.322  3267  3325 I jxcore-log: 
,03-30 22:20:28.328  3267  3325 I jxcore-log: # teardown
,03-30 22:20:28.328  3267  3325 I jxcore-log: 
,03-30 22:20:28.921  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:20:28.922  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 22:20:28.922  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 22:20:28.922  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 22:20:28.927  2148  2164 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:20:28.931  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 22:20:28.931  2148  3816 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 22:20:28.931  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:28.932  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:20:28.932  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 22:20:28.933  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:28.933  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-30 22:20:28.933  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 22:20:28.934  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-30 22:20:28.934  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-30 22:20:28.935  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
,03-30 22:20:28.935  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:28.936  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:28.936  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 22:20:28.936  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:20:28.936  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:28.940  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-30 22:20:28.940  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:28.940  2148  2211 D BtGatt.GattService: current time is 222437591371
03-30 22:20:28.941  2148  2211 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -63, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -100, 85, 45, 1, -114, 90, 1, -128, -80, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-30 22:20:28.941  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 22:20:28.942  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 22:20:28.943  3267  3325 I jxcore-log: ok 161 Should be able to call stopListeningForAdvertisments in teardown
03-30 22:20:28.943  3267  3325 I jxcore-log: 
03-30 22:20:28.945  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:20:28.945  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-30 22:20:28.945  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 22:20:28.946  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-30 22:20:28.946  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 22:20:28.946  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 22:20:28.946  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-30 22:20:28.947  3267  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 22:20:28.947  3267  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-30 22:20:28.947  3267  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 22:20:28.947  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 22:20:28.947  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-30 22:20:28.948  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-30 22:20:28.949  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 22:20:28.949  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-30 22:20:28.949  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 22:20:28.949  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-30 22:20:28.953  3267  3325 D BluetoothLeScanner: could not find callback wrapper
03-30 22:20:28.953  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:28.953  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-30 22:20:28.955  2148  2220 D BtGatt.AdvertiseManager: message : 1
03-30 22:20:28.956  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-30 22:20:28.958  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 22:20:28.958  2148  2211 D BtGatt.GattService: Client app is not null!
03-30 22:20:28.959  2148  3816 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 22:20:28.959  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:28.960  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:28.960  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
03-30 22:20:28.961  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 22:20:28.961  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-30 22:20:28.961  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-30 22:20:28.962  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-30 22:20:28.962  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 22:20:28.963  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 22:20:28.963  3267  3325 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-30 22:20:28.964  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 22:20:28.964  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:28.964  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:28.964  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:28.964  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:28.964  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 22:20:28.969  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-30 22:20:28.969  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 22:20:28.969  3267  3325 I jxcore-log: 
,03-30 22:20:28.969   823  1230 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:28.974  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 22:20:28.975  3267  3325 I jxcore-log: ok 162 Should be able to call stopAdvertisingAndListening in teardown
03-30 22:20:28.975  3267  3325 I jxcore-log: 
03-30 22:20:28.975  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:28.975  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-30 22:20:28.978  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 22:20:28.978  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 22:20:28.983  3267  3325 I jxcore-log: # setup
,03-30 22:20:28.983  3267  3325 I jxcore-log: 
03-30 22:20:28.990  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:28.990  3267  3325 I jxcore-log: 
03-30 22:20:28.993  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:28.993  3267  3325 I jxcore-log: 
,03-30 22:20:29.145  3267  3325 I jxcore-log: # 40. Can connect to a remote peer
03-30 22:20:29.145  3267  3325 I jxcore-log: 
,03-30 22:20:29.321  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 47509, start advertisements: true
,03-30 22:20:29.321  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:29.321  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 22:20:29.321  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true,
,03-30 22:20:29.327  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 22:20:29.327  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 22:20:29.328  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-30 22:20:29.328  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 22:20:29.334  2148  2163 D BtGatt.GattService: registerClient() - UUID=338f7ebd-4b21-467c-afe2-5fbad3712ecc,
,03-30 22:20:29.334  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=338f7ebd-4b21-467c-afe2-5fbad3712ecc, clientIf=5
,03-30 22:20:29.335  3267  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 22:20:29.335  2148  2994 D BtGatt.GattService: start scan with filters
,03-30 22:20:29.337  2148  2221 D BtGatt.ScanManager: handling starting scan
,03-30 22:20:29.338  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 22:20:29.338  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 22:20:29.338  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 22:20:29.338  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-30 22:20:29.338  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 22:20:29.340  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:29.341  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-30 22:20:29.341  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 22:20:29.341  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-30 22:20:29.341  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 22:20:29.342  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 22:20:29.342  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 22:20:29.345  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-30 22:20:29.345  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:29.347  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:29.347  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:29.347  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:29.347  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 22:20:29.350  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 22:20:29.350  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:29.352  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 22:20:29.352  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:29.353  2148  2994 D BtGatt.GattService: registerClient() - UUID=b286fed3-2ecc-455f-a5c0-eda826b969d8
,03-30 22:20:29.354  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=b286fed3-2ecc-455f-a5c0-eda826b969d8, clientIf=6
03-30 22:20:29.355  3267  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 22:20:29.358  2148  2220 D BtGatt.AdvertiseManager: message : 0
,03-30 22:20:29.363  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising,
,03-30 22:20:29.366  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-30 22:20:29.370  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-30 22:20:29.370  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 22:20:29.371  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 22:20:29.371   823  3512 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:29.378  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 22:20:29.378  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 22:20:29.378  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 22:20:29.378  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 22:20:29.380  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 22:20:29.381  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-30 22:20:29.381  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 22:20:29.381  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-30 22:20:29.381  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:29.381  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-30 22:20:29.382  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-30 22:20:29.382  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-30 22:20:29.382  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 22:20:29.382  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-30 22:20:29.382  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 22:20:29.382  3267  3267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 22:20:29.382  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:20:29.382  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 22:20:29.382  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:29.383  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 22:20:29.383  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 22:20:29.385  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:29.385  3267  3325 I jxcore-log: 
03-30 22:20:29.387   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 22:20:29.389  3267  3819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 22:20:29.393  3267  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
,03-30 22:20:29.394  3267  3325 I jxcore-log: ok 163 Can call startUpdateAdvertisingAndListening without error,
03-30 22:20:29.394  3267  3325 I jxcore-log: 
,03-30 22:20:29.399  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 47509, start advertisements: false,
03-30 22:20:29.399  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 22:20:29.399  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-30 22:20:29.399  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:29.399  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:29.400  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:29.400  3267  3325 I jxcore-log: 
03-30 22:20:29.401  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 22:20:29.401  3267  3325 I jxcore-log: 
,03-30 22:20:29.402  3267  3325 I jxcore-log: ok 164 Can call startListeningForAdvertisements without error
03-30 22:20:29.402  3267  3325 I jxcore-log: 
,03-30 22:20:30.361  2148  2148 D BtGatt.ScanManager: awakened up at time 223858
,03-30 22:20:30.363  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 22:20:30.374  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
03-30 22:20:30.374  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:30.374  2148  2211 D BtGatt.GattService: current time is 223871663141
03-30 22:20:30.375  2148  2211 D BtGatt.GattService: Batch record : [-37, 23, -118, -27, -102, 121, 1, -128, -81, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -58, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-30 22:20:30.376  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 22:20:30.376  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-30 22:20:30.380  3267  3267 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-30 22:20:30.381  3267  3267 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-30 22:20:30.381  3267  3267 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-30 22:20:30.382  3267  3267 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-30 22:20:30.388  3267  3325 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}],
03-30 22:20:30.388  3267  3325 I jxcore-log: 
,03-30 22:20:30.401  3267  3325 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
03-30 22:20:30.402  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-30 22:20:30.407  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,03-30 22:20:30.409  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-30 22:20:30.409  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-30 22:20:30.410  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
03-30 22:20:30.410  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
03-30 22:20:30.410  3267  3325 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-30 22:20:30.413  3267  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 351)
03-30 22:20:30.413  3267  3821 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 22:20:30.414  3267  3325 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-30 22:20:30.414  3267  3325 I jxcore-log: 
03-30 22:20:30.418  2148  2163 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-30 22:20:31.724  2148  2224 W bt-btif : No ag scb for peer addr
,03-30 22:20:31.750  2148  2224 W bt-btif : info:x10
,03-30 22:20:31.750  2148  2211 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-30 22:20:31.751  2148  2211 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-30 22:20:31.793  2148  2224 W bt-sdp  : process_service_search_attr_rsp
,03-30 22:20:31.948  2148  2211 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-30 22:20:31.957  2148  2211 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1,
,03-30 22:20:31.958  2148  2211 E bt-btif : check_cod: remote_cod = 0x5a020c,
,03-30 22:20:31.967  2148  2212 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-30 22:20:31.967  2148  2212 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-30 22:20:32.029   823   854 I ActivityManager: Start proc 3822:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-30 22:20:32.164   823  1236 I art     : Explicit concurrent mark sweep GC freed 27817(1320KB) AllocSpace objects, 8(693KB) LOS objects, 32% free, 33MB/49MB, paused 1.579ms total 68.816ms
,03-30 22:20:32.211   823   858 D BluetoothManagerService: Message: 20
,03-30 22:20:32.212   823   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20885e79:true
,03-30 22:20:32.213   823  1236 I ActivityManager: Killing 3556:com.android.chrome/u0a40 (adj 15): empty #17
,03-30 22:20:32.255  2148  2211 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-30 22:20:32.256  2148  2212 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-30 22:20:32.327  2148  2212 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-30 22:20:32.435  2148  2212 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-30 22:20:32.504  1258  1501 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-30 22:20:32.505  1258  1501 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-30 22:20:32.534  1239  1239 I ConfigService: onCreate
,03-30 22:20:33.802  2148  2224 W bt-btif : new conn_srvc id:26, app_id:255
03-30 22:20:33.802  2148  2224 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-30 22:20:33.802  2148  2224 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-30 22:20:33.804  3267  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-30 22:20:33.806  3267  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 352)
03-30 22:20:33.807  3267  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 22:20:33.808   823  2549 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:33.811  3267  3819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 22:20:33.812  3267  3843 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 352)
,03-30 22:20:33.817  3267  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 22:20:33.867  2148  2224 W bt-btif : new conn_srvc id:26, app_id:1
,03-30 22:20:33.868  2148  2224 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-30 22:20:33.868  2148  2224 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-30 22:20:33.868  2148  2224 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-30 22:20:33.868  3267  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 351)
,03-30 22:20:33.868  3267  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 351)
03-30 22:20:33.870  3267  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 353)
03-30 22:20:33.870  3267  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 353)
03-30 22:20:33.870  3267  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 351)
,03-30 22:20:33.877  3267  3844 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 353)
,03-30 22:20:34.107  3267  3843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 352)
,03-30 22:20:34.111  3267  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-30 22:20:34.113  3267  3843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 352)
03-30 22:20:34.113  3267  3843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 352
,03-30 22:20:34.113  3267  3843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 352)
,03-30 22:20:34.113  3267  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-30 22:20:34.115  3267  3843 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 352)
,03-30 22:20:34.115  3267  3267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51],
03-30 22:20:34.116  3267  3267 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-30 22:20:34.116  3267  3267 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-30 22:20:34.119  3267  3267 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-30 22:20:34.120  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-30 22:20:34.120  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 22:20:34.120  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE,
03-30 22:20:34.120  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 22:20:34.120  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 22:20:34.120  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 22:20:34.120  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-30 22:20:34.125  3267  3844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 353)
,03-30 22:20:34.127  2148  2220 D BtGatt.AdvertiseManager: message : 1,
03-30 22:20:34.128  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 22:20:34.130  3267  3844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-30 22:20:34.130  3267  3844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 351)
03-30 22:20:34.130  3267  3844 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 351)
03-30 22:20:34.131  3267  3844 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 353)
03-30 22:20:34.136  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-30 22:20:34.136  2148  2211 D BtGatt.GattService: Client app is not null!
03-30 22:20:34.139  2148  3816 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 22:20:34.140  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:34.140  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:34.141  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-30 22:20:34.141  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 22:20:34.141  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 22:20:34.142  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 22:20:34.142  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:34.142  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:34.143  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 22:20:34.147  2148  3816 D BtGatt.GattService: registerClient() - UUID=9ea33ed8-f16b-4d72-8554-0caa372ec5e2
03-30 22:20:34.148  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=9ea33ed8-f16b-4d72-8554-0caa372ec5e2, clientIf=6
03-30 22:20:34.148  3267  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 22:20:34.150  2148  2220 D BtGatt.AdvertiseManager: message : 0
,03-30 22:20:34.152  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 22:20:34.154  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 22:20:34.156  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 22:20:34.156  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 22:20:34.157  2148  2994 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:20:34.158  2148  2163 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 22:20:34.159  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-30 22:20:34.159  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:34.159  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:20:34.159  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:34.159  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.159  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 22:20:34.159  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 22:20:34.159  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-30 22:20:34.159  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:20:34.161  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:34.161  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:34.161  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:20:34.162  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-30 22:20:34.163  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.163  2148  2211 D BtGatt.GattService: current time is 227659906317
03-30 22:20:34.163  2148  2163 D BtGatt.GattService: registerClient() - UUID=a4285ee7-ffdf-41bc-a46a-97d722f39217
03-30 22:20:34.163  2148  2211 D BtGatt.GattService: Batch record : [-37, 23, -118, -27, -102, 121, 1, -128, -77, 52, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -56, 52, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-30 22:20:34.163  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 22:20:34.163  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-30 22:20:34.163  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=a4285ee7-ffdf-41bc-a46a-97d722f39217, clientIf=5
03-30 22:20:34.164  3267  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 22:20:34.164  2148  2164 D BtGatt.GattService: start scan with filters
03-30 22:20:34.164  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 22:20:34.164  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 22:20:34.165  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-30 22:20:34.165  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 22:20:34.165  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 22:20:34.165  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 22:20:34.165  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
,03-30 22:20:34.165  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 22:20:34.165  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 22:20:34.166  2148  2220 D BtGatt.AdvertiseManager: message : 1
03-30 22:20:34.167  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 22:20:34.169  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 22:20:34.169  2148  2211 D BtGatt.GattService: Client app is not null!
,03-30 22:20:34.169  2148  2163 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 22:20:34.170  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:34.170  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:20:34.170  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-30 22:20:34.170  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-30 22:20:34.170  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 22:20:34.170  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 22:20:34.170  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-30 22:20:34.171  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:34.171  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:34.171  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 22:20:34.171  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 22:20:34.171  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.173  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:34.173  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.173  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:34.173  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 22:20:34.175  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-30 22:20:34.175  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.176  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 22:20:34.176  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.180  2148  2994 D BtGatt.GattService: registerClient() - UUID=305b7ace-acb7-456e-a5fc-4f0785324fbc
03-30 22:20:34.180  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=305b7ace-acb7-456e-a5fc-4f0785324fbc, clientIf=6
03-30 22:20:34.181  3267  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 22:20:34.181  2148  2220 D BtGatt.AdvertiseManager: message : 0
,03-30 22:20:34.185  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 22:20:34.187  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 22:20:34.189  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 22:20:34.190  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 22:20:34.191  2148  2164 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:20:34.192  2148  2994 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 22:20:34.193  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:20:34.193  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 22:20:34.193  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.193  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:34.193  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:34.193  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:20:34.193  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 22:20:34.193  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 22:20:34.193  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-30 22:20:34.195  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-30 22:20:34.195  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.195  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:20:34.196  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 22:20:34.196  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:34.199  2148  2994 D BtGatt.GattService: registerClient() - UUID=39ea903d-d3b4-4ecf-9541-c2df9a388453
03-30 22:20:34.199  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=39ea903d-d3b4-4ecf-9541-c2df9a388453, clientIf=5
03-30 22:20:34.199  3267  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 22:20:34.200  2148  3816 D BtGatt.GattService: start scan with filters
,03-30 22:20:34.200  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 22:20:34.200  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 22:20:34.200  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-30 22:20:34.200  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:20:34.200  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 22:20:34.200  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 22:20:34.200  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0,
03-30 22:20:34.200  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 22:20:34.200  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 22:20:34.200  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 22:20:34.203  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-30 22:20:34.203  2148  2220 D BtGatt.AdvertiseManager: message : 1
03-30 22:20:34.203  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.204  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:34.205  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.205  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:34.205  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 22:20:34.205  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 22:20:34.207  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 22:20:34.207  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:34.208  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-30 22:20:34.208  2148  2211 D BtGatt.GattService: Client app is not null!
03-30 22:20:34.209  2148  3816 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 22:20:34.210  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:34.210  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-30 22:20:34.210  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 22:20:34.210  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-30 22:20:34.210  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-30 22:20:34.210  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 22:20:34.210  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 22:20:34.211  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 22:20:34.211  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:34.211  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:34.211  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 22:20:34.217  2148  3816 D BtGatt.GattService: registerClient() - UUID=17955914-1442-45ef-99d0-2c31d9e64c72
,03-30 22:20:34.217  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=17955914-1442-45ef-99d0-2c31d9e64c72, clientIf=6
03-30 22:20:34.218  3267  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 22:20:34.218  2148  2220 D BtGatt.AdvertiseManager: message : 0
,03-30 22:20:34.221  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising,
,03-30 22:20:34.224  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-30 22:20:34.226  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 22:20:34.227  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 22:20:34.229  2148  2164 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:20:34.230  2148  3816 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-30 22:20:34.230  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:34.230  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:34.230  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:34.230  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 22:20:34.231  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
03-30 22:20:34.231  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-30 22:20:34.231  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:20:34.231  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.231  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:20:34.234  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-30 22:20:34.234  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.234  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 22:20:34.235  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-30 22:20:34.235  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.236  2148  3816 D BtGatt.GattService: registerClient() - UUID=51ccee36-49a9-4f9c-8fc0-7afe2905e0ed
,03-30 22:20:34.236  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=51ccee36-49a9-4f9c-8fc0-7afe2905e0ed, clientIf=5
03-30 22:20:34.237  3267  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 22:20:34.237  2148  2163 D BtGatt.GattService: start scan with filters
,03-30 22:20:34.239  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 22:20:34.239  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 22:20:34.239  3267  3267 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
,03-30 22:20:34.239  3267  3267 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
,03-30 22:20:34.239  3267  3267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-30 22:20:34.240  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-30 22:20:34.240  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 22:20:34.240  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 22:20:34.240  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:20:34.240  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 22:20:34.240  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 22:20:34.240  3267  3267 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-30 22:20:34.240  3267  3267 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-30 22:20:34.241  3267  3845 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 354)
03-30 22:20:34.242  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 22:20:34.242  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.242  3267  3267 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-30 22:20:34.242  3267  3267 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-30 22:20:34.243  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-30 22:20:34.243  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.243  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:34.243  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 22:20:34.243  3267  3846 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 355)
03-30 22:20:34.245  3267  3846 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57420
03-30 22:20:34.245  3267  3846 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-30 22:20:34.245  3267  3846 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 57420 (peer ID: F8:95:C7:87:3C:51)
,03-30 22:20:34.245  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 22:20:34.245  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.245  3267  3846 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-30 22:20:34.247  3267  3845 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47509
03-30 22:20:34.247  3267  3845 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-30 22:20:34.248  3267  3845 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-30 22:20:34.248  3267  3325 I jxcore-log: INFO testThaliMobileNative: 
03-30 22:20:34.248  3267  3325 I jxcore-log: 
03-30 22:20:34.248  3267  3845 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-30 22:20:34.248  3267  3325 I jxcore-log: ok 165 Must have listeningPort
03-30 22:20:34.248  3267  3325 I jxcore-log: 
03-30 22:20:34.249  3267  3848 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 356, name: Sender)
03-30 22:20:34.249  3267  3325 I jxcore-log: ok 166 listeningPort must be a number
03-30 22:20:34.249  3267  3325 I jxcore-log: 
,03-30 22:20:34.249  3267  3845 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 354)
03-30 22:20:34.249  3267  3845 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 354)
03-30 22:20:34.249  3267  3325 I jxcore-log: ok 167 Connection must have clientPort
03-30 22:20:34.249  3267  3325 I jxcore-log: 
03-30 22:20:34.250  3267  3325 I jxcore-log: ok 168 clientPort must be a number
03-30 22:20:34.250  3267  3325 I jxcore-log: 
03-30 22:20:34.250  3267  3325 I jxcore-log: ok 169 Connection must have serverPort
03-30 22:20:34.250  3267  3325 I jxcore-log: 
03-30 22:20:34.250  3267  3849 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 357, name: Receiver)
03-30 22:20:34.251  3267  3325 I jxcore-log: ok 170 serverPort must be a number
03-30 22:20:34.251  3267  3325 I jxcore-log: 
03-30 22:20:34.251  3267  3325 I jxcore-log: ok 171 forward connection must have clientPort == 0
03-30 22:20:34.251  3267  3325 I jxcore-log: 
,03-30 22:20:34.252  3267  3325 I jxcore-log: ok 172 forward connection must have serverPort == 0
03-30 22:20:34.252  3267  3325 I jxcore-log: 
03-30 22:20:34.253  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 22:20:34.253  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:34.262  3267  3325 I jxcore-log: # teardown
03-30 22:20:34.262  3267  3325 I jxcore-log: 
,03-30 22:20:37.586  1239  1239 I ConfigService: onDestroy,
,03-30 22:20:37.680  3488  3850 I BooksSync: Starting books sync for 61035162, extras: ade
,03-30 22:20:37.719  3488  3851 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-30 22:20:37.752  2148  2209 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-30 22:20:37.819  1239  2547 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-30 22:20:37.820  1239  2547 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:20:37.820  1239  2547 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:20:37.820  1239  2547 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:20:37.833  1239  2547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-30 22:20:37.970  1239  1257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-30 22:20:37.971  1239  1257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-30 22:20:37.971  1239  1257 I GLSUser : [GLSUser] Extracting token using key: Auth
03-30 22:20:37.971  1239  1257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-30 22:20:37.980  1239  1257 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-30 22:20:38.011  3488  3851 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-30 22:20:38.014  3488  3850 E BooksSync: Soft error
,03-30 22:20:38.014  3488  3850 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-30 22:20:38.014  3488  3850 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-30 22:20:38.015  3488  3850 E BooksSync: Sync error
03-30 22:20:38.015  3488  3850 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-30 22:20:38.015  3488  3850 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-30 22:20:38.015  3488  3850 I BooksSync: Finished books sync
,03-30 22:20:38.031   823   853 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 203102, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,03-30 22:20:38.370  3267  3848 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 356, thread name: Sender),
03-30 22:20:38.371  3267  3848 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-30 22:20:38.371  3267  3848 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-30 22:20:38.371  3267  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 354
03-30 22:20:38.371  3267  3848 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 354)
03-30 22:20:38.372  3267  3848 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-30 22:20:38.372  3267  3848 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-30 22:20:38.372  3267  3848 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 357
03-30 22:20:38.372  3267  3849 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 357, thread name: Receiver): bt socket closed, read return: -1
03-30 22:20:38.372  3267  3848 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,03-30 22:20:38.372  3267  3848 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 356
03-30 22:20:38.372  3267  3849 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 357, name: Receiver)
03-30 22:20:38.375  3267  3848 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 354)
,03-30 22:20:38.376  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 22:20:38.376  3267  3848 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 354)
03-30 22:20:38.376  3267  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-30 22:20:38.376  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-30 22:20:38.376  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 22:20:38.376  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 22:20:38.377  3267  3848 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 356, name: Sender)
,03-30 22:20:38.379  2148  2164 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:20:38.381  2148  3816 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 22:20:38.381  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:20:38.381  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:38.381  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:20:38.382  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:38.382  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:38.382  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 22:20:38.382  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 22:20:38.382  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 22:20:38.382  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-30 22:20:38.383  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 22:20:38.384  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 22:20:38.384  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:38.385  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:38.385  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:38.385  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 22:20:38.387  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-30 22:20:38.387  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:38.388  2148  2211 D BtGatt.GattService: current time is 231885052513
03-30 22:20:38.388  2148  2211 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -57, 47, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-30 22:20:38.389  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 22:20:38.393  3267  3325 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-30 22:20:38.393  3267  3325 I jxcore-log: 
,03-30 22:20:38.394  3267  3325 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-30 22:20:38.394  3267  3325 I jxcore-log: 
03-30 22:20:38.395  3267  3325 I jxcore-log: ok 173 Should be able to call stopListeningForAdvertisments in teardown
03-30 22:20:38.395  3267  3325 I jxcore-log: 
03-30 22:20:38.395  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 22:20:38.395  3267  3325 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-30 22:20:38.396  3267  3325 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 355)
,03-30 22:20:38.396  3267  3325 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 355)
03-30 22:20:38.396  3267  3325 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-30 22:20:38.396  3267  3325 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 355)
03-30 22:20:38.396  3267  3325 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 355)
,03-30 22:20:38.397  3267  3846 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 355)
03-30 22:20:38.398  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-30 22:20:38.398  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 22:20:38.398  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 22:20:38.398  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-30 22:20:38.398  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 22:20:38.398  3267  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 22:20:38.398  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 22:20:38.398  3267  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 22:20:38.398  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 22:20:38.398  3267  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-30 22:20:38.398  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 22:20:38.398  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 22:20:38.399  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-30 22:20:38.399  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-30 22:20:38.400  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-30 22:20:38.400  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 22:20:38.401  3267  3325 D BluetoothLeScanner: could not find callback wrapper
03-30 22:20:38.401  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:38.401  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-30 22:20:38.403  2148  2220 D BtGatt.AdvertiseManager: message : 1
03-30 22:20:38.404  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 22:20:38.407  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 22:20:38.407  2148  2211 D BtGatt.GattService: Client app is not null!
03-30 22:20:38.407  2148  3816 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 22:20:38.408  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:38.408  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-30 22:20:38.408  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 22:20:38.408  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 22:20:38.408  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 22:20:38.408  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:38.408  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 22:20:38.408  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 22:20:38.409  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 22:20:38.409  3267  3325 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-30 22:20:38.409  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:38.409  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:38.409  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:38.409  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 22:20:38.409  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:38.409  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 22:20:38.413  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 22:20:38.413  3267  3325 I jxcore-log: 
03-30 22:20:38.415  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-30 22:20:38.415   823  1433 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:38.417  2148  2224 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
03-30 22:20:38.417  2148  2224 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-30 22:20:38.419  3267  3325 I jxcore-log: ok 174 Should be able to call stopAdvertisingAndListening in teardown
03-30 22:20:38.419  3267  3325 I jxcore-log: 
,03-30 22:20:38.420  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-30 22:20:38.421  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:38.421  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:38.425  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:38.425  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 22:20:38.426  3267  3325 I jxcore-log: # setup
03-30 22:20:38.426  3267  3325 I jxcore-log: 
,03-30 22:20:38.428  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:38.428  3267  3325 I jxcore-log: 
03-30 22:20:38.428  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:38.428  3267  3325 I jxcore-log: 
,03-30 22:20:38.620  3267  3325 I jxcore-log: # 41. Can shift large amounts of data
03-30 22:20:38.620  3267  3325 I jxcore-log: 
,03-30 22:20:38.905  2148  2224 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,03-30 22:20:39.591  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 48449, start advertisements: true
,03-30 22:20:39.591  3267  3325 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:39.591  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-30 22:20:39.592  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 22:20:39.592  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 22:20:39.592  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 22:20:39.592  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 22:20:39.592  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 22:20:39.592  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 22:20:39.592  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-30 22:20:39.592  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:39.592  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:39.592  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 22:20:39.592  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 22:20:39.598  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 22:20:39.598  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 22:20:39.599  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 22:20:39.599  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 22:20:39.604  2148  2994 D BtGatt.GattService: registerClient() - UUID=fbae3bb8-9d0d-4988-87d2-c64bf6d6d7c9
,03-30 22:20:39.605  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=fbae3bb8-9d0d-4988-87d2-c64bf6d6d7c9, clientIf=5
,03-30 22:20:39.606  3267  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 22:20:39.607  2148  2163 D BtGatt.GattService: start scan with filters
03-30 22:20:39.608  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 22:20:39.608  2148  2221 D BtGatt.ScanManager: handling starting scan,
03-30 22:20:39.610  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 22:20:39.610  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 22:20:39.610  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 22:20:39.611  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 22:20:39.611  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:39.611  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-30 22:20:39.611  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:39.611  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 22:20:39.612  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-30 22:20:39.613  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:39.613  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:39.613  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan,
03-30 22:20:39.613  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-30 22:20:39.614  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-30 22:20:39.615  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:39.615  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 22:20:39.615  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:39.616  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:39.616  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 22:20:39.617  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 22:20:39.617  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:39.624  2148  2163 D BtGatt.GattService: registerClient() - UUID=b9263d61-ab8c-40af-a04c-3bc743944431
,03-30 22:20:39.624  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=b9263d61-ab8c-40af-a04c-3bc743944431, clientIf=6
03-30 22:20:39.624  3267  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 22:20:39.625  2148  2220 D BtGatt.AdvertiseManager: message : 0,
03-30 22:20:39.627  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 22:20:39.629  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
03-30 22:20:39.630  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 22:20:39.631  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 22:20:39.631  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 22:20:39.631   823  2549 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:39.633  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-30 22:20:39.633  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-30 22:20:39.633  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 22:20:39.633  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:39.634  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 22:20:39.634  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-30 22:20:39.634  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 22:20:39.634  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 22:20:39.634  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK,
03-30 22:20:39.634  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 22:20:39.634  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 22:20:39.634  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 22:20:39.634  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 22:20:39.634  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING],
03-30 22:20:39.634  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 22:20:39.634  3267  3267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 22:20:39.634  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:20:39.634  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 22:20:39.634  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-30 22:20:39.635  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 22:20:39.635  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 22:20:39.635   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 22:20:39.636  3267  3852 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-30 22:20:39.636  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-30 22:20:39.636  3267  3325 I jxcore-log: 
03-30 22:20:39.637  3267  3325 I jxcore-log: ok 175 Can call startUpdateAdvertisingAndListening without error
03-30 22:20:39.637  3267  3325 I jxcore-log: 
03-30 22:20:39.637  3267  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-30 22:20:39.639  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 48449, start advertisements: false,
03-30 22:20:39.639  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:39.639  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-30 22:20:39.639  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:20:39.639  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:39.640  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:39.640  3267  3325 I jxcore-log: 
03-30 22:20:39.641  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 22:20:39.641  3267  3325 I jxcore-log: 
,03-30 22:20:39.642  3267  3325 I jxcore-log: ok 176 Can call startListeningForAdvertisements without error
03-30 22:20:39.642  3267  3325 I jxcore-log: 
,03-30 22:20:43.559  2148  2224 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-30 22:20:43.565  2148  2148 D BluetoothMapService: onReceive
,03-30 22:20:43.585   823   858 D BluetoothManagerService: Message: 20
03-30 22:20:43.585   823   858 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d2c36a3:true
,03-30 22:20:43.598  1526  1526 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-30 22:20:43.601  1526  1526 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-30 22:20:44.434  2148  2148 D BtGatt.ScanManager: awakened up at time 237931
,03-30 22:20:44.436  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 22:20:44.447  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-30 22:20:44.447  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:44.447  2148  2211 D BtGatt.GattService: current time is 237944567719
03-30 22:20:44.448  2148  2211 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -55, 28, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 24, 109, 17, -85, 44, 99, 1, -128, -76, 28, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-30 22:20:44.448  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 22:20:44.449  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 22:20:44.452  3267  3267 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-30 22:20:44.454  3267  3267 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
,03-30 22:20:44.454  3267  3267 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-30 22:20:44.456  3267  3267 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-30 22:20:44.470  3267  3325 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-30 22:20:44.470  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
03-30 22:20:44.476  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
03-30 22:20:44.476  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-30 22:20:44.476  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-30 22:20:44.477  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
,03-30 22:20:44.477  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
03-30 22:20:44.477  3267  3325 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
03-30 22:20:44.479  3267  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 359)
,03-30 22:20:44.480  3267  3854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 22:20:44.485  2148  2994 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-30 22:20:44.971  2148  2224 W bt-btif : info:x10,
03-30 22:20:44.971  2148  2211 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,03-30 22:20:45.007  1526  1526 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-30 22:20:45.014  1526  1526 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-30 22:20:45.044  2148  2224 W bt-sdp  : process_service_search_attr_rsp
,03-30 22:20:45.888  2148  2211 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-30 22:20:45.894  2148  2211 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-30 22:20:45.895  2148  2211 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-30 22:20:45.900  2148  2212 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-30 22:20:45.901  2148  2212 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-30 22:20:46.350  2148  2211 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-30 22:20:46.351  2148  2212 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-30 22:20:46.357  2148  2212 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-30 22:20:46.374  2148  2212 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-30 22:20:47.497  2148  2224 W bt-btif : new conn_srvc id:26, app_id:1,
03-30 22:20:47.497  2148  2224 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-30 22:20:47.497  2148  2224 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-30 22:20:47.498  3267  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 359)
03-30 22:20:47.498  3267  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 359)
,03-30 22:20:47.500  3267  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 360)
03-30 22:20:47.500  3267  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 360)
03-30 22:20:47.500  3267  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 359)
,03-30 22:20:47.505  3267  3855 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 360)
,03-30 22:20:47.772  3267  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 360)
,03-30 22:20:47.776  3267  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-30 22:20:47.777  3267  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 359)
03-30 22:20:47.777  3267  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 359)
,03-30 22:20:47.777  3267  3855 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 360)
,03-30 22:20:47.777  3267  3267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-30 22:20:47.778  3267  3267 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-30 22:20:47.778  3267  3267 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-30 22:20:47.778  3267  3267 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-30 22:20:47.778  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-30 22:20:47.779  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 22:20:47.779  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 22:20:47.779  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 22:20:47.779  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 22:20:47.779  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 22:20:47.779  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 22:20:47.784  2148  2220 D BtGatt.AdvertiseManager: message : 1
03-30 22:20:47.785  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-30 22:20:47.789  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 22:20:47.790  2148  2211 D BtGatt.GattService: Client app is not null!
,03-30 22:20:47.791  2148  2994 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-30 22:20:47.793  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:47.793  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-30 22:20:47.793  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false,
03-30 22:20:47.793  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-30 22:20:47.793  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-30 22:20:47.793  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61,
03-30 22:20:47.794  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:47.794  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 22:20:47.794  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 22:20:47.802  2148  2994 D BtGatt.GattService: registerClient() - UUID=6255d39c-e463-42a1-8de5-bbf05205f75c
,03-30 22:20:47.803  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=6255d39c-e463-42a1-8de5-bbf05205f75c, clientIf=6
03-30 22:20:47.804  3267  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 22:20:47.805  2148  2220 D BtGatt.AdvertiseManager: message : 0
,03-30 22:20:47.809  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising,
,03-30 22:20:47.812  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 22:20:47.815  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 22:20:47.816  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 22:20:47.818  2148  3816 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:20:47.820  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 22:20:47.820  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:47.821  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
,03-30 22:20:47.821  2148  2994 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 22:20:47.822  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:47.822  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:47.822  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:47.822  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 22:20:47.822  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:47.822  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:47.822  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 22:20:47.823  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-30 22:20:47.823  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 22:20:47.825  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-30 22:20:47.825  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:47.826  2148  2211 D BtGatt.GattService: current time is 241322881520
,03-30 22:20:47.826  2148  2211 D BtGatt.GattService: Batch record : [0, -101, -28, 65, -114, 85, 1, -128, -96, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -76, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-30 22:20:47.826  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-30 22:20:47.827  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 22:20:47.831  2148  2994 D BtGatt.GattService: registerClient() - UUID=d2f93d3c-cf7a-4bd7-8da9-ce7d04c7d578
03-30 22:20:47.831  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=d2f93d3c-cf7a-4bd7-8da9-ce7d04c7d578, clientIf=5
,03-30 22:20:47.832  3267  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 22:20:47.833  2148  2163 D BtGatt.GattService: start scan with filters
03-30 22:20:47.834  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 22:20:47.834  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 22:20:47.834  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-30 22:20:47.834  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:20:47.834  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 22:20:47.834  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 22:20:47.834  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 22:20:47.834  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 22:20:47.834  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 22:20:47.834  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-30 22:20:47.839  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 22:20:47.839  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:47.840  2148  2220 D BtGatt.AdvertiseManager: message : 1
03-30 22:20:47.840  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 22:20:47.841  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:47.841  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:47.842  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:47.842  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 22:20:47.843  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 22:20:47.843  2148  2211 D BtGatt.GattService: Client app is not null!
,03-30 22:20:47.846  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 22:20:47.846  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:47.846  2148  2994 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 22:20:47.847  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 22:20:47.847  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:47.847  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:47.848  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-30 22:20:47.848  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-30 22:20:47.848  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-30 22:20:47.848  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-30 22:20:47.848  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 22:20:47.849  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:47.849  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:47.849  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 22:20:47.856  2148  2994 D BtGatt.GattService: registerClient() - UUID=6bd98e6e-c74a-473b-8ae9-97f78d805dfd
,03-30 22:20:47.857  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=6bd98e6e-c74a-473b-8ae9-97f78d805dfd, clientIf=6
03-30 22:20:47.857  3267  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 22:20:47.859  2148  2220 D BtGatt.AdvertiseManager: message : 0
,03-30 22:20:47.863  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 22:20:47.866  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 22:20:47.869  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 22:20:47.870  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 22:20:47.872  2148  3816 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:20:47.874  2148  2994 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 22:20:47.875  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:47.875  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:47.875  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:47.875  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 22:20:47.875  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-30 22:20:47.875  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-30 22:20:47.875  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:20:47.875  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:47.876  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
,03-30 22:20:47.877  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:47.877  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:47.878  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:20:47.879  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 22:20:47.879  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:47.881  2148  2994 D BtGatt.GattService: registerClient() - UUID=db80bad1-6ce0-43f7-8a2a-e13ed7f8999b
03-30 22:20:47.882  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=db80bad1-6ce0-43f7-8a2a-e13ed7f8999b, clientIf=5
03-30 22:20:47.882  3267  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 22:20:47.883  2148  2163 D BtGatt.GattService: start scan with filters
03-30 22:20:47.884  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 22:20:47.884  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 22:20:47.884  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
,03-30 22:20:47.884  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 22:20:47.884  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 22:20:47.884  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 22:20:47.884  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 22:20:47.884  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 22:20:47.884  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 22:20:47.885  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:20:47.887  2148  2220 D BtGatt.AdvertiseManager: message : 1
,03-30 22:20:47.890  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 22:20:47.891  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 22:20:47.891  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:47.893  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:47.893  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:47.893  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:47.894  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 22:20:47.894  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 22:20:47.894  2148  2211 D BtGatt.GattService: Client app is not null!,
03-30 22:20:47.896  2148  2994 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-30 22:20:47.897  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-30 22:20:47.897  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 22:20:47.897  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-30 22:20:47.897  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:47.897  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-30 22:20:47.897  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 22:20:47.897  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-30 22:20:47.897  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 22:20:47.897  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:47.897  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:47.898  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 22:20:47.898  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 22:20:47.898  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:47.903  2148  2163 D BtGatt.GattService: registerClient() - UUID=0f113018-1789-4598-b4cc-dc5c49d52c62
03-30 22:20:47.903  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=0f113018-1789-4598-b4cc-dc5c49d52c62, clientIf=6
03-30 22:20:47.904  3267  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-30 22:20:47.905  2148  2220 D BtGatt.AdvertiseManager: message : 0
,03-30 22:20:47.909  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 22:20:47.911  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 22:20:47.914  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 22:20:47.915  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 22:20:47.917  2148  2994 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:20:47.918  2148  2163 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 22:20:47.919  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:47.919  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:47.919  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:47.919  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 22:20:47.919  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 22:20:47.919  3267  3267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 22:20:47.920  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:20:47.921  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:47.921  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:20:47.922  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:47.922  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:47.922  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 22:20:47.924  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 22:20:47.924  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:47.924  2148  2163 D BtGatt.GattService: registerClient() - UUID=7841b456-8538-4212-9f04-2c0d9b138aa9
,03-30 22:20:47.925  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=7841b456-8538-4212-9f04-2c0d9b138aa9, clientIf=5
03-30 22:20:47.925  3267  3282 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 22:20:47.925  2148  2164 D BtGatt.GattService: start scan with filters
03-30 22:20:47.927  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 22:20:47.927  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 22:20:47.927  3267  3267 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-30 22:20:47.927  3267  3267 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-30 22:20:47.927  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 22:20:47.927  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 22:20:47.927  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 22:20:47.927  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 22:20:47.927  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-30 22:20:47.929  3267  3856 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 361)
03-30 22:20:47.929  3267  3856 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46317
03-30 22:20:47.929  3267  3856 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-30 22:20:47.929  3267  3856 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 46317 (peer ID: F8:95:C7:87:3C:51)
03-30 22:20:47.930  3267  3856 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-30 22:20:47.930  2148  2221 D BtGatt.ScanManager: handling starting scan
,03-30 22:20:47.932  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
,03-30 22:20:47.932  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:47.933  3267  3325 I jxcore-log: INFO testThaliMobileNative: ,
03-30 22:20:47.933  3267  3325 I jxcore-log: 
03-30 22:20:47.934  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-30 22:20:47.934  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:47.934  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan,
,03-30 22:20:47.934  3267  3325 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-30 22:20:47.934  3267  3325 I jxcore-log: 
03-30 22:20:47.934  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 22:20:47.936  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 22:20:47.936  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-30 22:20:47.937  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 22:20:47.937  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:47.938  3267  3856 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 46317
03-30 22:20:47.938  3267  3856 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,03-30 22:20:47.938  3267  3856 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-30 22:20:47.938  3267  3856 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-30 22:20:47.939  3267  3856 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 361)
03-30 22:20:47.939  3267  3856 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 361)
,03-30 22:20:47.941  3267  3325 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-30 22:20:47.941  3267  3325 I jxcore-log: 
03-30 22:20:47.944  3267  3858 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 363, name: Receiver)
03-30 22:20:47.946  3267  3857 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 362, name: Sender)
,03-30 22:20:48.077  3267  3325 I jxcore-log: INFO testThaliMobileNative: forwardData
03-30 22:20:48.077  3267  3325 I jxcore-log: 
,03-30 22:20:48.218  3267  3325 I jxcore-log: INFO testThaliMobileNative: forwardData
03-30 22:20:48.218  3267  3325 I jxcore-log: 
,03-30 22:20:48.226  3267  3325 I jxcore-log: INFO testThaliMobileNative: forwardData
03-30 22:20:48.226  3267  3325 I jxcore-log: 
,03-30 22:20:48.294  3267  3325 I jxcore-log: INFO testThaliMobileNative: forwardData
03-30 22:20:48.294  3267  3325 I jxcore-log: 
,03-30 22:20:48.362  3267  3325 I jxcore-log: INFO testThaliMobileNative: forwardData
03-30 22:20:48.362  3267  3325 I jxcore-log: 
,03-30 22:20:48.364  3267  3325 I jxcore-log: ok 177 received should match sent forward
03-30 22:20:48.364  3267  3325 I jxcore-log: 
,03-30 22:20:48.379  3267  3325 I jxcore-log: # teardown
03-30 22:20:48.379  3267  3325 I jxcore-log: 
,03-30 22:20:48.580  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:20:48.581  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 22:20:48.581  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 22:20:48.581  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 22:20:48.585  2148  2994 D BtGatt.GattService: stopScan() - queue size =1
03-30 22:20:48.587  2148  2994 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 22:20:48.591  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 22:20:48.591  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:48.591  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:20:48.593  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:48.593  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:48.593  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-30 22:20:48.593  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 22:20:48.593  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-30 22:20:48.593  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 22:20:48.593  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 22:20:48.593  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 22:20:48.593  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:48.595  3267  3325 I jxcore-log: ok 178 Should be able to call stopListeningForAdvertisments in teardown
03-30 22:20:48.595  3267  3325 I jxcore-log: 
03-30 22:20:48.595  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:48.595  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:48.595  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 22:20:48.595  3267  3325 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-30 22:20:48.596  3267  3325 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 361)
,03-30 22:20:48.596  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:20:48.596  3267  3325 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 361)
03-30 22:20:48.596  3267  3325 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-30 22:20:48.596  3267  3325 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-30 22:20:48.596  3267  3325 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 363
03-30 22:20:48.596  3267  3325 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-30 22:20:48.596  3267  3325 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 362
03-30 22:20:48.596  3267  3325 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 361)
03-30 22:20:48.596  3267  3325 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 361)
03-30 22:20:48.596  3267  3858 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 363, thread name: Receiver): bt socket closed, read return: -1
03-30 22:20:48.596  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-30 22:20:48.596  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-30 22:20:48.596  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 22:20:48.596  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 22:20:48.596  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 22:20:48.596  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 22:20:48.597  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 22:20:48.597  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 22:20:48.597  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 22:20:48.597  3267  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 22:20:48.597  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 22:20:48.597  3267  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 22:20:48.597  3267  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 22:20:48.597  3267  3857 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 362, thread name: Sender): Socket closed
,03-30 22:20:48.597  3267  3857 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 362, name: Sender)
03-30 22:20:48.598  3267  3858 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 363, name: Receiver)
03-30 22:20:48.598  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-30 22:20:48.599  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:48.599  2148  2211 D BtGatt.GattService: current time is 242095993655
03-30 22:20:48.599  2148  2211 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -70, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-30 22:20:48.600  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-30 22:20:48.606  3267  3325 D BluetoothLeScanner: could not find callback wrapper
03-30 22:20:48.606  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:48.606  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-30 22:20:48.609  2148  2220 D BtGatt.AdvertiseManager: message : 1
03-30 22:20:48.610  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-30 22:20:48.612  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 22:20:48.612  2148  2211 D BtGatt.GattService: Client app is not null!
03-30 22:20:48.614  2148  2164 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 22:20:48.615  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:48.615  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:48.615  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 22:20:48.615  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 22:20:48.615  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-30 22:20:48.615  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:48.616  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 22:20:48.616  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 22:20:48.617  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 22:20:48.617  3267  3325 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-30 22:20:48.617  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:48.617  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 22:20:48.617  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:48.617  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 22:20:48.619  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 22:20:48.619  3267  3325 I jxcore-log: 
03-30 22:20:48.625  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 22:20:48.626   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:48.635  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
,03-30 22:20:48.636  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-30 22:20:48.637  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:48.642  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-30 22:20:48.643  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 22:20:48.643  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:48.643  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:48.643  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 22:20:48.643  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 22:20:48.644  3267  3325 I jxcore-log: ok 179 Should be able to call stopAdvertisingAndListening in teardown
03-30 22:20:48.644  3267  3325 I jxcore-log: 
03-30 22:20:48.644  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-30 22:20:48.648  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:48.648  3267  3325 I jxcore-log: 
03-30 22:20:48.649  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:48.649  3267  3325 I jxcore-log: 
03-30 22:20:48.650  3267  3325 I jxcore-log: # setup
03-30 22:20:48.650  3267  3325 I jxcore-log: 
,03-30 22:20:48.654  2148  2224 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,03-30 22:20:50.973  2148  2209 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,03-30 22:20:52.004  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-30 22:20:52.004  3267  3325 I jxcore-log: 
03-30 22:20:52.005  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 22:20:52.005  3267  3325 I jxcore-log: 
,03-30 22:20:52.014  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-30 22:20:52.014  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:20:52.014  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:20:52.014  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:20:52.014  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:20:52.014  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:20:52.014  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
03-30 22:20:52.014  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:20:52.019  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 22:20:52.021  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-30 22:20:52.021  3267  3325 I jxcore-log: 
,03-30 22:20:52.024  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 22:20:52.024  3267  3325 I jxcore-log: ,
,03-30 22:20:52.028  3267  3325 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called,
03-30 22:20:52.028  3267  3325 I jxcore-log: 
,03-30 22:20:52.030  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:20:52.030  3267  3325 I jxcore-log: 
,03-30 22:20:52.145  3267  3325 I jxcore-log: ok 180 specific error should be returned
03-30 22:20:52.145  3267  3325 I jxcore-log: 
03-30 22:20:52.151  3267  3325 I jxcore-log: # teardown
03-30 22:20:52.151  3267  3325 I jxcore-log: 
,03-30 22:20:52.748  2148  2224 E bt-btm  : btm_sec_disconnected - Clearing Pending flag,
,03-30 22:20:52.755  2148  2148 D BluetoothMapService: onReceive,
,03-30 22:20:52.782  1526  1526 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-30 22:20:52.787  1526  1526 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-30 22:20:53.019  3267  3325 I jxcore-log: ok 181 must be stopped
03-30 22:20:53.019  3267  3325 I jxcore-log: 
,03-30 22:20:53.025  3267  3325 I jxcore-log: # setup
03-30 22:20:53.025  3267  3325 I jxcore-log: 
,03-30 22:20:53.138  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 22:20:53.138  3267  3325 I jxcore-log: 
,03-30 22:20:53.142  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 22:20:53.142  3267  3325 I jxcore-log: 
,03-30 22:20:53.151  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 22:20:53.151  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:20:53.151  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:20:53.151  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:20:53.151  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:20:53.151  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:20:53.151  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:20:53.151  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:20:53.156  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 22:20:53.158  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 22:20:53.158  3267  3325 I jxcore-log: 
,03-30 22:20:53.159  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 22:20:53.159  3267  3325 I jxcore-log: 
,03-30 22:20:53.162  3267  3325 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
03-30 22:20:53.162  3267  3325 I jxcore-log: 
,03-30 22:20:53.164  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:20:53.164  3267  3325 I jxcore-log: 
,03-30 22:20:53.424  3267  3325 I jxcore-log: ok 182 specific error should be returned
03-30 22:20:53.424  3267  3325 I jxcore-log: 
,03-30 22:20:53.427  3267  3325 I jxcore-log: # teardown
03-30 22:20:53.427  3267  3325 I jxcore-log: 
,03-30 22:20:53.614  3267  3325 I jxcore-log: ok 183 must be stopped
03-30 22:20:53.614  3267  3325 I jxcore-log: 
,03-30 22:20:53.617  3267  3325 I jxcore-log: # setup
03-30 22:20:53.617  3267  3325 I jxcore-log: 
,03-30 22:20:53.735  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 22:20:53.735  3267  3325 I jxcore-log: 
,03-30 22:20:53.736  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 22:20:53.736  3267  3325 I jxcore-log: 
,03-30 22:20:53.743  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 22:20:53.743  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:20:53.743  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:20:53.743  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:20:53.743  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:20:53.743  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:20:53.743  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:20:53.743  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:20:53.746  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 22:20:53.748  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 22:20:53.748  3267  3325 I jxcore-log: 
,03-30 22:20:53.749  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 22:20:53.749  3267  3325 I jxcore-log: 
,03-30 22:20:53.752  3267  3325 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-30 22:20:53.752  3267  3325 I jxcore-log: 
,03-30 22:20:53.754  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:20:53.754  3267  3325 I jxcore-log: 
,03-30 22:20:53.942  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:20:53.942  3267  3325 I jxcore-log: 
,03-30 22:20:53.944  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 57087
03-30 22:20:53.944  3267  3325 I jxcore-log: 
,03-30 22:20:53.946  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:20:53.946  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:53.946  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:53.949  3267  3325 I jxcore-log: ok 184 no errors
03-30 22:20:53.949  3267  3325 I jxcore-log: 
,03-30 22:20:53.949  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:20:53.949  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:53.949  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:53.952  3267  3325 I jxcore-log: ok 185 still no errors
03-30 22:20:53.952  3267  3325 I jxcore-log: 
03-30 22:20:53.957  3267  3325 I jxcore-log: # teardown
03-30 22:20:53.957  3267  3325 I jxcore-log: 
,03-30 22:20:54.086  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:20:54.087  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 22:20:54.087  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:20:54.091  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:20:54.091  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 22:20:54.092  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:54.097  3267  3325 I jxcore-log: ok 186 must be stopped
03-30 22:20:54.097  3267  3325 I jxcore-log: 
,03-30 22:20:54.105  3267  3325 I jxcore-log: # setup
03-30 22:20:54.105  3267  3325 I jxcore-log: 
,03-30 22:20:54.109  2148  2213 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-30 22:20:54.251  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 22:20:54.251  3267  3325 I jxcore-log: 
,03-30 22:20:54.254  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 22:20:54.254  3267  3325 I jxcore-log: 
,03-30 22:20:54.261  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 22:20:54.261  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:20:54.261  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:20:54.261  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:20:54.261  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:20:54.261  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:20:54.261  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:20:54.261  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:20:54.263  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 22:20:54.265  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 22:20:54.265  3267  3325 I jxcore-log: 
,03-30 22:20:54.267  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 22:20:54.267  3267  3325 I jxcore-log: 
,03-30 22:20:54.270  3267  3325 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-30 22:20:54.270  3267  3325 I jxcore-log: 
,03-30 22:20:54.272  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:20:54.272  3267  3325 I jxcore-log: 
,03-30 22:20:54.485  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:20:54.485  3267  3325 I jxcore-log: 
,03-30 22:20:54.487  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 36848
03-30 22:20:54.487  3267  3325 I jxcore-log: 
,03-30 22:20:54.493  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 48449, start advertisements: false
,03-30 22:20:54.493  3267  3325 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-30 22:20:54.493  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-30 22:20:54.495  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 22:20:54.495  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 22:20:54.495  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 22:20:54.495  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1,
03-30 22:20:54.495  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 22:20:54.495  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 22:20:54.495  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3,
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
,03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 22:20:54.496  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:54.496  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 22:20:54.496  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-30 22:20:54.500  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 22:20:54.500  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-30 22:20:54.501  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-30 22:20:54.506  2148  2994 D BtGatt.GattService: registerClient() - UUID=3bedbb23-3c71-4d02-869d-3cc42db07745
03-30 22:20:54.507  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=3bedbb23-3c71-4d02-869d-3cc42db07745, clientIf=5
03-30 22:20:54.508  3267  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 22:20:54.509  2148  2163 D BtGatt.GattService: start scan with filters
03-30 22:20:54.512  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 22:20:54.513  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 22:20:54.513  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:20:54.514  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 22:20:54.514  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 22:20:54.514  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:54.514  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:54.514  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 22:20:54.515   823  1102 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:54.520  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 22:20:54.521  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-30 22:20:54.521  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 22:20:54.521  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:54.521  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 22:20:54.521  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 22:20:54.521  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:20:54.521  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 22:20:54.522  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:54.522  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:54.522  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
,03-30 22:20:54.522  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 22:20:54.523  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:54.523  3267  3325 I jxcore-log: 
,03-30 22:20:54.524  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 22:20:54.524  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:54.524  3267  3325 I jxcore-log: 
,03-30 22:20:54.524  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:54.525  3267  3325 I jxcore-log: ok 187 no errors
03-30 22:20:54.525  3267  3325 I jxcore-log: 
03-30 22:20:54.526  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-30 22:20:54.526  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:54.529  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 48449, start advertisements: false
,03-30 22:20:54.529  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:54.529  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 22:20:54.529  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:54.530  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:54.532  3267  3325 I jxcore-log: ok 188 still no errors
03-30 22:20:54.532  3267  3325 I jxcore-log: 
,03-30 22:20:54.538  3267  3325 I jxcore-log: # teardown
,03-30 22:20:54.538  3267  3325 I jxcore-log: 
,03-30 22:20:54.834  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 22:20:54.834  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:54.834  3267  3325 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-30 22:20:54.834  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-30 22:20:54.834  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 22:20:54.834  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 22:20:54.834  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 22:20:54.835  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 22:20:54.835  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 22:20:54.837  2148  2164 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:20:54.843  2148  2994 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 22:20:54.845  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:54.845  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:54.845  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:20:54.845  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 22:20:54.845  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:54.845  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:20:54.845  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-30 22:20:54.845  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-30 22:20:54.845  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:54.847  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:54.847  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 22:20:54.848  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 22:20:54.849  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:20:54.849  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:54.849  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:20:54.850  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 22:20:54.851  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:54.851  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 22:20:54.851  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:54.851  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:54.851  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:54.852  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 22:20:54.874  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 22:20:54.874   823  1260 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:54.879  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 22:20:54.879  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:54.879  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:54.882  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 22:20:54.882  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:54.882  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:54.882  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:54.884  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:20:54.884  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:54.884  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:20:54.885  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:54.885  3267  3325 I jxcore-log: 
03-30 22:20:54.886  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:54.886  3267  3325 I jxcore-log: 
,03-30 22:20:54.890  3267  3325 I jxcore-log: ok 189 must be stopped,
03-30 22:20:54.890  3267  3325 I jxcore-log: 
,03-30 22:20:54.896  3267  3325 I jxcore-log: # setup,
03-30 22:20:54.896  3267  3325 I jxcore-log: 
,03-30 22:20:55.045  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-30 22:20:55.045  3267  3325 I jxcore-log: 
,03-30 22:20:55.046  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-30 22:20:55.046  3267  3325 I jxcore-log: 
,03-30 22:20:55.055  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 22:20:55.055  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:20:55.055  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:20:55.055  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:20:55.055  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:20:55.055  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:20:55.055  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:20:55.055  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
03-30 22:20:55.058  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 22:20:55.059  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 22:20:55.059  3267  3325 I jxcore-log: 
,03-30 22:20:55.061  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 22:20:55.061  3267  3325 I jxcore-log: 
,03-30 22:20:55.064  3267  3325 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
03-30 22:20:55.064  3267  3325 I jxcore-log: 
,03-30 22:20:55.066  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:20:55.066  3267  3325 I jxcore-log: 
,03-30 22:20:55.277  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:20:55.277  3267  3325 I jxcore-log: 
,03-30 22:20:55.280  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 55891
03-30 22:20:55.280  3267  3325 I jxcore-log: 
,03-30 22:20:55.286  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 55891, start advertisements: true
03-30 22:20:55.286  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:55.286  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 22:20:55.286  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 22:20:55.292  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 22:20:55.292  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-30 22:20:55.292  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 22:20:55.292  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 22:20:55.297  2148  2163 D BtGatt.GattService: registerClient() - UUID=c8853052-7c33-4a09-834e-89e5d798f70f,
03-30 22:20:55.298  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=c8853052-7c33-4a09-834e-89e5d798f70f, clientIf=5
03-30 22:20:55.298  3267  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 22:20:55.299  2148  2164 D BtGatt.GattService: start scan with filters,
03-30 22:20:55.300  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:20:55.300  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 22:20:55.300  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 22:20:55.300  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 22:20:55.300  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 22:20:55.300  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 22:20:55.301  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 22:20:55.301  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 22:20:55.301  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:55.301  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 22:20:55.301  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:55.302  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:55.302  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 22:20:55.302  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 22:20:55.303  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:55.304  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:55.305  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:55.305  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:55.305  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-30 22:20:55.308  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-30 22:20:55.308  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:55.310  2148  2164 D BtGatt.GattService: registerClient() - UUID=a7624200-667c-41e1-95bf-a22d24a75683
,03-30 22:20:55.310  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 22:20:55.310  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:55.311  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=a7624200-667c-41e1-95bf-a22d24a75683, clientIf=6
03-30 22:20:55.312  3267  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 22:20:55.314  2148  2220 D BtGatt.AdvertiseManager: message : 0
03-30 22:20:55.318  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 22:20:55.322  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 22:20:55.324  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-30 22:20:55.325  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 22:20:55.325  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,03-30 22:20:55.326   823  1102 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 22:20:55.331  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-30 22:20:55.332  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 22:20:55.332  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 22:20:55.332  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 22:20:55.333  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 22:20:55.334  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 22:20:55.334  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 22:20:55.334  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-30 22:20:55.334  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:55.335  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 22:20:55.335  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 22:20:55.335  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-30 22:20:55.335  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 22:20:55.335  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 22:20:55.335  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 22:20:55.336  3267  3267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 22:20:55.336  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:20:55.336  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 22:20:55.336  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:55.336   823  3512 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 22:20:55.336  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-30 22:20:55.337  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 22:20:55.339  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:55.339  3267  3325 I jxcore-log: 
03-30 22:20:55.340  3267  3861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 22:20:55.343  3267  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-30 22:20:55.344  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:55.344  3267  3325 I jxcore-log: 
03-30 22:20:55.345  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 22:20:55.345  3267  3325 I jxcore-log: 
03-30 22:20:55.346  3267  3325 I jxcore-log: ok 190 no errors
03-30 22:20:55.346  3267  3325 I jxcore-log: 
,03-30 22:20:55.350  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 55891, start advertisements: true
03-30 22:20:55.350  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:55.350  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 22:20:55.350  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:20:55.350  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:55.352  3267  3325 I jxcore-log: ok 191 still no errors
03-30 22:20:55.352  3267  3325 I jxcore-log: 
,03-30 22:20:55.358  3267  3325 I jxcore-log: # teardown
03-30 22:20:55.358  3267  3325 I jxcore-log: 
,03-30 22:20:55.815  2148  2148 D BtGatt.ScanManager: awakened up at time 249312
,03-30 22:20:55.823  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,03-30 22:20:55.832  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
03-30 22:20:55.833  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:55.833  2148  2211 D BtGatt.GattService: current time is 249330310215
,03-30 22:20:55.833  2148  2211 D BtGatt.GattService: Batch record : [-29, -87, -24, -70, 98, 84, 1, -128, -81, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -58, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-30 22:20:55.834  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 22:20:55.835  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 22:20:55.838  3267  3267 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 1
03-30 22:20:55.839  3267  3267 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-30 22:20:55.840  3267  3267 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-30 22:20:55.840  3267  3267 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-30 22:20:55.846  3267  3325 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-30 22:20:55.846  3267  3325 I jxcore-log: 
,03-30 22:20:55.855  3267  3325 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-30 22:20:55.855  3267  3325 I jxcore-log: 
,03-30 22:20:55.861  3267  3325 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-30 22:20:55.861  3267  3325 I jxcore-log: 
,03-30 22:20:55.869  3267  3325 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-30 22:20:55.869  3267  3325 I jxcore-log: 
,03-30 22:20:56.196  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 22:20:56.196  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-30 22:20:56.196  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 22:20:56.196  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-30 22:20:56.196  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 22:20:56.197  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
03-30 22:20:56.197  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 22:20:56.197  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-30 22:20:56.197  3267  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 22:20:56.197  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-30 22:20:56.197  3267  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 22:20:56.197  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 22:20:56.197  3267  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-30 22:20:56.198  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
03-30 22:20:56.198  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 22:20:56.204  2148  2163 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:20:56.206  2148  3816 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 22:20:56.206  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 22:20:56.206  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:56.206  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 22:20:56.206  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-30 22:20:56.206  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-30 22:20:56.207  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 22:20:56.207  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 22:20:56.207  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:20:56.207  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-30 22:20:56.207  2148  2221 D BtGatt.ScanManager: stopping BLe Batch,
03-30 22:20:56.209  2148  2220 D BtGatt.AdvertiseManager: message : 1
03-30 22:20:56.210  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 22:20:56.210  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-30 22:20:56.210  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:56.210  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:20:56.214  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-30 22:20:56.214  2148  2211 D BtGatt.GattService: Client app is not null!
,03-30 22:20:56.215  2148  2164 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 22:20:56.216  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-30 22:20:56.216  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:56.216  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-30 22:20:56.216  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:56.216  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 22:20:56.216  2148  2211 D BtGatt.GattService: current time is 249713406256
,03-30 22:20:56.216  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 22:20:56.216  2148  2211 D BtGatt.GattService: Batch record : [-29, -87, -24, -70, 98, 84, 1, -128, -81, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -65, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-30 22:20:56.216  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
03-30 22:20:56.217  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:56.217  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 22:20:56.217  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 22:20:56.217  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 22:20:56.218  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-30 22:20:56.218  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 22:20:56.218  3267  3325 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-30 22:20:56.218  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:56.219  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 22:20:56.219  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 22:20:56.219  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 22:20:56.227  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-30 22:20:56.228   823  1236 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:56.237  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 22:20:56.238  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:56.238  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 22:20:56.238  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-30 22:20:56.238  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:56.242  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-30 22:20:56.242  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:56.242  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:56.242  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:56.243  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-30 22:20:56.243  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-30 22:20:56.244  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 22:20:56.244  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:56.244  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:56.245  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 22:20:56.245  3267  3325 I jxcore-log: 
,03-30 22:20:56.246  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-30 22:20:56.246  3267  3325 I jxcore-log: 
03-30 22:20:56.247  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:56.247  3267  3325 I jxcore-log: 
,03-30 22:20:56.251  3267  3325 I jxcore-log: ok 192 must be stopped
03-30 22:20:56.251  3267  3325 I jxcore-log: 
,03-30 22:20:56.258  3267  3325 I jxcore-log: # setup
,03-30 22:20:56.258  3267  3325 I jxcore-log: 
,03-30 22:20:56.342  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 22:20:56.342  3267  3325 I jxcore-log: 
,03-30 22:20:56.347  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 22:20:56.347  3267  3325 I jxcore-log: 
,03-30 22:20:56.358  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 22:20:56.358  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:20:56.358  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:20:56.358  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:20:56.358  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:20:56.358  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:20:56.358  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:20:56.358  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:20:56.362  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 22:20:56.364  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 22:20:56.364  3267  3325 I jxcore-log: 
,03-30 22:20:56.365  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 22:20:56.365  3267  3325 I jxcore-log: 
,03-30 22:20:56.368  3267  3325 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
03-30 22:20:56.368  3267  3325 I jxcore-log: 
,03-30 22:20:56.370  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:20:56.370  3267  3325 I jxcore-log: 
,03-30 22:20:56.542  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:20:56.542  3267  3325 I jxcore-log: 
,03-30 22:20:56.550  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 46434
03-30 22:20:56.550  3267  3325 I jxcore-log: 
,03-30 22:20:56.555  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:20:56.556  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:56.556  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
03-30 22:20:56.560  3267  3325 I jxcore-log: ok 193 no errors
03-30 22:20:56.560  3267  3325 I jxcore-log: 
03-30 22:20:56.562  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 22:20:56.563  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:56.563  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:56.566  3267  3325 I jxcore-log: ok 194 still no errors
03-30 22:20:56.566  3267  3325 I jxcore-log: 
,03-30 22:20:56.576  3267  3325 I jxcore-log: # teardown
03-30 22:20:56.576  3267  3325 I jxcore-log: 
,03-30 22:20:56.847  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:20:56.848  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:56.848  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:56.852  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:20:56.852  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:20:56.853  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:20:56.864  3267  3325 I jxcore-log: ok 195 must be stopped
03-30 22:20:56.864  3267  3325 I jxcore-log: 
,03-30 22:20:56.878  3267  3325 I jxcore-log: # setup
03-30 22:20:56.878  3267  3325 I jxcore-log: 
,03-30 22:20:57.043  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 22:20:57.043  3267  3325 I jxcore-log: 
,03-30 22:20:57.048  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 22:20:57.048  3267  3325 I jxcore-log: 
,03-30 22:20:57.059  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-30 22:20:57.059  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,03-30 22:20:57.059  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:20:57.059  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:20:57.059  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:20:57.059  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:20:57.059  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:20:57.059  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:20:57.063  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 22:20:57.066  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-30 22:20:57.066  3267  3325 I jxcore-log: 
,03-30 22:20:57.070  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-30 22:20:57.070  3267  3325 I jxcore-log: 
,03-30 22:20:57.077  3267  3325 I jxcore-log: # 48. can get the network status before starting,
03-30 22:20:57.077  3267  3325 I jxcore-log: 
,03-30 22:20:57.080  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
03-30 22:20:57.080  3267  3325 I jxcore-log: 
,03-30 22:20:58.555  3267  3325 I jxcore-log: ok 196 network status should have certain non-empty properties
03-30 22:20:58.555  3267  3325 I jxcore-log: 
,03-30 22:20:58.558  3267  3325 I jxcore-log: # teardown
,03-30 22:20:58.558  3267  3325 I jxcore-log: 
,03-30 22:20:58.757  3267  3325 I jxcore-log: ok 197 must be stopped,
,03-30 22:20:58.757  3267  3325 I jxcore-log: ,
,03-30 22:20:58.762  3267  3325 I jxcore-log: # setup
03-30 22:20:58.762  3267  3325 I jxcore-log: 
,03-30 22:20:58.954  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 22:20:58.954  3267  3325 I jxcore-log: 
,03-30 22:20:58.955  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 22:20:58.955  3267  3325 I jxcore-log: 
,03-30 22:20:58.963  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 22:20:58.963  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:20:58.963  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:20:58.963  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:20:58.963  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:20:58.963  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:20:58.963  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:20:58.963  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:20:58.967  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 22:20:58.970  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 22:20:58.970  3267  3325 I jxcore-log: 
,03-30 22:20:58.974  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 22:20:58.974  3267  3325 I jxcore-log: 
,03-30 22:20:58.980  3267  3325 I jxcore-log: # 49. error returned with bad router
03-30 22:20:58.980  3267  3325 I jxcore-log: 
,03-30 22:20:58.984  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:20:58.984  3267  3325 I jxcore-log: 
,03-30 22:20:59.211  3267  3325 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-30 22:20:59.211  3267  3325 I jxcore-log: 
,03-30 22:20:59.214  3267  3325 I jxcore-log: ok 198 specific error expected
03-30 22:20:59.214  3267  3325 I jxcore-log: 
,03-30 22:20:59.216  3267  3325 I jxcore-log: # teardown
03-30 22:20:59.216  3267  3325 I jxcore-log: 
,03-30 22:20:59.348  3267  3325 I jxcore-log: ok 199 must be stopped
03-30 22:20:59.348  3267  3325 I jxcore-log: 
,03-30 22:20:59.355  3267  3325 I jxcore-log: # setup
03-30 22:20:59.355  3267  3325 I jxcore-log: 
,03-30 22:20:59.551  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 22:20:59.551  3267  3325 I jxcore-log: 
,03-30 22:20:59.557  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 22:20:59.557  3267  3325 I jxcore-log: 
,03-30 22:20:59.568  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 22:20:59.568  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:20:59.568  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:20:59.568  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:20:59.568  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:20:59.568  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:20:59.568  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:20:59.568  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:20:59.572  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-30 22:20:59.574  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 22:20:59.574  3267  3325 I jxcore-log: 
,03-30 22:20:59.575  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 22:20:59.575  3267  3325 I jxcore-log: 
,03-30 22:20:59.578  3267  3325 I jxcore-log: # 50. all services are stopped when we call stop
03-30 22:20:59.578  3267  3325 I jxcore-log: 
,03-30 22:20:59.580  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:20:59.580  3267  3325 I jxcore-log: 
,03-30 22:20:59.789  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:20:59.789  3267  3325 I jxcore-log: 
,03-30 22:20:59.792  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 58154
03-30 22:20:59.792  3267  3325 I jxcore-log: 
,03-30 22:20:59.798  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 55891, start advertisements: false
,03-30 22:20:59.798  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:59.798  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 22:20:59.798  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 22:20:59.804  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 22:20:59.804  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 22:20:59.805  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 22:20:59.809  2148  2163 D BtGatt.GattService: registerClient() - UUID=7bbc5a12-1038-432f-9828-0fa9def82ad2
,03-30 22:20:59.809  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=7bbc5a12-1038-432f-9828-0fa9def82ad2, clientIf=5
03-30 22:20:59.810  3267  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-30 22:20:59.810  2148  2164 D BtGatt.GattService: start scan with filters
03-30 22:20:59.811  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 22:20:59.811  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 22:20:59.811  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-30 22:20:59.811  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 22:20:59.811  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:59.811  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 22:20:59.812  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:20:59.812   823   839 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 22:20:59.812  2148  2221 D BtGatt.ScanManager: handling starting scan
,03-30 22:20:59.821  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 22:20:59.821  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:59.824  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:20:59.824  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:59.824  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:20:59.824  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-30 22:20:59.827  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 22:20:59.827  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:59.830  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-30 22:20:59.830  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:59.832  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:20:59.832  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 22:20:59.832  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:59.832  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 22:20:59.832  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:59.833  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 22:20:59.839  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:59.839  3267  3325 I jxcore-log: 
,03-30 22:20:59.842  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:20:59.842  3267  3325 I jxcore-log: 
,03-30 22:20:59.850  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 58154, start advertisements: true
,03-30 22:20:59.850  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:20:59.850  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 22:20:59.850  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 22:20:59.854  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 22:20:59.854  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-30 22:20:59.854  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 22:20:59.854  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 22:20:59.855  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 22:20:59.855  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:59.855  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:20:59.855  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 22:20:59.859  2148  2163 D BtGatt.GattService: registerClient() - UUID=c3a99c55-740a-4269-9819-106e8c7865d7
,03-30 22:20:59.860  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=c3a99c55-740a-4269-9819-106e8c7865d7, clientIf=6
03-30 22:20:59.861  3267  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 22:20:59.862  2148  2220 D BtGatt.AdvertiseManager: message : 0
,03-30 22:20:59.866  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 22:20:59.870  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-30 22:20:59.873  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-30 22:20:59.874  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 22:20:59.874  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 22:20:59.874  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 22:20:59.874  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 22:20:59.874  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 22:20:59.874  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 22:20:59.874   823  1230 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:59.874  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 22:20:59.878  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 22:20:59.878  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 22:20:59.878  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-30 22:20:59.878  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:59.878  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 22:20:59.881  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 22:20:59.881  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 22:20:59.882  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 22:20:59.882  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 22:20:59.882  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:20:59.882  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 22:20:59.882  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:59.882  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-30 22:20:59.885   823  1236 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:59.885  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 22:20:59.885  3267  3325 I jxcore-log: 
,03-30 22:20:59.887  3267  3864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 22:20:59.890  3267  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 22:20:59.892  3267  3325 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 22:20:59.892  3267  3325 I jxcore-log: 
,03-30 22:20:59.895  3267  3325 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 22:20:59.895  3267  3325 I jxcore-log: 
,03-30 22:20:59.898  3267  3325 I jxcore-log: DEBUG createNativeListener: new mux
03-30 22:20:59.898  3267  3325 I jxcore-log: 
,03-30 22:20:59.903  3267  3325 I jxcore-log: ok 200 connection to servers manager should succeed after starting
03-30 22:20:59.903  3267  3325 I jxcore-log: 
,03-30 22:20:59.924  3267  3325 I jxcore-log: ok 201 connection to router server should succeed after starting
03-30 22:20:59.924  3267  3325 I jxcore-log: 
03-30 22:20:59.925  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:20:59.926  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-30 22:20:59.926  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 22:20:59.926  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 22:20:59.926  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 22:20:59.926  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-30 22:20:59.926  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 22:20:59.926  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-30 22:20:59.926  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 22:20:59.926  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 22:20:59.926  3267  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 22:20:59.926  3267  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 22:20:59.926  3267  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 22:20:59.927  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 22:20:59.927  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 22:20:59.928  2148  2994 D BtGatt.GattService: stopScan() - queue size =1
03-30 22:20:59.929  2148  2163 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-30 22:20:59.929  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 22:20:59.929  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-30 22:20:59.929  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-30 22:20:59.929  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 22:20:59.929  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-30 22:20:59.929  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 22:20:59.929  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 22:20:59.932  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 22:20:59.932  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:59.932  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:20:59.934  2148  2220 D BtGatt.AdvertiseManager: message : 1
03-30 22:20:59.935  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-30 22:20:59.935  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:20:59.935  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
03-30 22:20:59.936  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-30 22:20:59.938  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
03-30 22:20:59.938  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:20:59.938  2148  2211 D BtGatt.GattService: current time is 253435745682
,03-30 22:20:59.939  2148  2211 D BtGatt.GattService: Batch record : [-126, -9, 38, -73, 51, 82, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-30 22:20:59.939  2148  2211 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-30 22:20:59.945  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-30 22:20:59.945  2148  2211 D BtGatt.GattService: Client app is not null!
03-30 22:20:59.946  2148  2163 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 22:20:59.947  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:20:59.947  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 22:20:59.947  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 22:20:59.947  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 22:20:59.947  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 22:20:59.947  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:20:59.947  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-30 22:20:59.947  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 22:20:59.948  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 22:20:59.948  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:59.948  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 22:20:59.948  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:20:59.948  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 22:20:59.955  3267  3325 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 22:20:59.955  3267  3325 I jxcore-log: 
,03-30 22:20:59.964  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 22:20:59.964   823  1433 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:20:59.973  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-30 22:20:59.975  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 22:20:59.975  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 22:20:59.975  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-30 22:20:59.975  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:20:59.980  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-30 22:20:59.980  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:20:59.980  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:20:59.980  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 22:20:59.981  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:20:59.981  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-30 22:20:59.988  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 22:20:59.988  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-30 22:20:59.988  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:20:59.989  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 22:20:59.989  3267  3325 I jxcore-log: 
,03-30 22:20:59.990  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:59.990  3267  3325 I jxcore-log: 
,03-30 22:20:59.991  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:20:59.991  3267  3325 I jxcore-log: 
,03-30 22:20:59.997  3267  3325 I jxcore-log: ok 202 is stopped after calling stop
03-30 22:20:59.997  3267  3325 I jxcore-log: 
,03-30 22:21:00.003  3267  3325 I jxcore-log: ok 203 connection to servers manager should fail after stopping
03-30 22:21:00.003  3267  3325 I jxcore-log: 
,03-30 22:21:00.007  3267  3325 I jxcore-log: ok 204 connection to router server should fail after stopping
03-30 22:21:00.007  3267  3325 I jxcore-log: 
,03-30 22:21:00.012  3267  3325 I jxcore-log: # teardown
03-30 22:21:00.012  3267  3325 I jxcore-log: 
,03-30 22:21:00.314  3267  3325 I jxcore-log: ok 205 must be stopped
03-30 22:21:00.314  3267  3325 I jxcore-log: 
,03-30 22:21:00.321  3267  3325 I jxcore-log: # setup
03-30 22:21:00.321  3267  3325 I jxcore-log: 
,03-30 22:21:01.218  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 22:21:01.218  3267  3325 I jxcore-log: 
,03-30 22:21:01.222  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-30 22:21:01.222  3267  3325 I jxcore-log: 
,03-30 22:21:01.231  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 22:21:01.231  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:21:01.231  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:21:01.231  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:21:01.231  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:21:01.231  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:21:01.231  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:21:01.231  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:21:01.236  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 22:21:01.238  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 22:21:01.238  3267  3325 I jxcore-log: 
,03-30 22:21:01.239  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 22:21:01.239  3267  3325 I jxcore-log: 
,03-30 22:21:01.242  3267  3325 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
03-30 22:21:01.242  3267  3325 I jxcore-log: 
,03-30 22:21:01.245  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:21:01.245  3267  3325 I jxcore-log: 
,03-30 22:21:01.426  3267  3325 I jxcore-log: ok 206 called with right arguments
03-30 22:21:01.426  3267  3325 I jxcore-log: 
,03-30 22:21:01.428  3267  3325 I jxcore-log: # teardown
03-30 22:21:01.428  3267  3325 I jxcore-log: 
,03-30 22:21:02.344  3267  3325 I jxcore-log: ok 207 must be stopped
03-30 22:21:02.344  3267  3325 I jxcore-log: 
,03-30 22:21:02.347  3267  3325 I jxcore-log: # setup
03-30 22:21:02.347  3267  3325 I jxcore-log: 
,03-30 22:21:02.501  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 22:21:02.501  3267  3325 I jxcore-log: 
,03-30 22:21:02.504  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 22:21:02.504  3267  3325 I jxcore-log: 
,03-30 22:21:02.511  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-30 22:21:02.511  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:21:02.511  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:21:02.511  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:21:02.511  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:21:02.511  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:21:02.511  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:21:02.511  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:21:02.515  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 22:21:02.518  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 22:21:02.518  3267  3325 I jxcore-log: 
,03-30 22:21:02.522  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 22:21:02.522  3267  3325 I jxcore-log: 
,03-30 22:21:02.528  3267  3325 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-30 22:21:02.528  3267  3325 I jxcore-log: 
,03-30 22:21:02.532  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:21:02.532  3267  3325 I jxcore-log: 
,03-30 22:21:02.864  3267  3325 I jxcore-log: ok 208 called with right arguments
03-30 22:21:02.864  3267  3325 I jxcore-log: 
,03-30 22:21:02.867  3267  3325 I jxcore-log: # teardown
03-30 22:21:02.867  3267  3325 I jxcore-log: 
,03-30 22:21:02.988  3267  3325 I jxcore-log: ok 209 must be stopped
03-30 22:21:02.988  3267  3325 I jxcore-log: 
,03-30 22:21:02.990  3267  3325 I jxcore-log: # setup
03-30 22:21:02.990  3267  3325 I jxcore-log: 
,03-30 22:21:03.129  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 22:21:03.129  3267  3325 I jxcore-log: 
,03-30 22:21:03.134  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 22:21:03.134  3267  3325 I jxcore-log: 
,03-30 22:21:03.148  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 22:21:03.148  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:21:03.148  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:21:03.148  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:21:03.148  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:21:03.148  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:21:03.148  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:21:03.148  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:21:03.154  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-30 22:21:03.158  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 22:21:03.158  3267  3325 I jxcore-log: 
,03-30 22:21:03.163  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 22:21:03.163  3267  3325 I jxcore-log: 
,03-30 22:21:03.171  3267  3325 I jxcore-log: # 53. make sure we actually call kill connections properly
03-30 22:21:03.171  3267  3325 I jxcore-log: 
,03-30 22:21:03.176  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:21:03.176  3267  3325 I jxcore-log: 
,03-30 22:21:03.338  3267  3325 I jxcore-log: ok 210 specific error expected
03-30 22:21:03.338  3267  3325 I jxcore-log: 
,03-30 22:21:03.346  3267  3325 I jxcore-log: # teardown
03-30 22:21:03.346  3267  3325 I jxcore-log: 
,03-30 22:21:03.468  3267  3325 I jxcore-log: ok 211 must be stopped,
03-30 22:21:03.468  3267  3325 I jxcore-log: 
,03-30 22:21:03.470  3267  3325 I jxcore-log: # setup
03-30 22:21:03.470  3267  3325 I jxcore-log: 
,03-30 22:21:03.613  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 22:21:03.613  3267  3325 I jxcore-log: 
,03-30 22:21:03.618  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 22:21:03.618  3267  3325 I jxcore-log: 
,03-30 22:21:03.629  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 22:21:03.629  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:21:03.629  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:21:03.629  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:21:03.629  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:21:03.629  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:21:03.629  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:21:03.629  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:21:03.632  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 22:21:03.634  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 22:21:03.634  3267  3325 I jxcore-log: 
,03-30 22:21:03.635  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 22:21:03.635  3267  3325 I jxcore-log: 
,03-30 22:21:03.639  3267  3325 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-30 22:21:03.639  3267  3325 I jxcore-log: 
,03-30 22:21:03.640  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:21:03.640  3267  3325 I jxcore-log: 
,03-30 22:21:03.827  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:21:03.827  3267  3325 I jxcore-log: 
,03-30 22:21:03.835  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 39772
03-30 22:21:03.835  3267  3325 I jxcore-log: 
,03-30 22:21:03.838  3267  3325 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":44896,"error":{}}
03-30 22:21:03.838  3267  3325 I jxcore-log: 
,03-30 22:21:03.839  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:21:03.839  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:21:03.839  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:21:03.841  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 22:21:03.841  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 22:21:03.841  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:21:03.846  3267  3325 I jxcore-log: ok 212 failure reason is as expected
03-30 22:21:03.846  3267  3325 I jxcore-log: 
,03-30 22:21:03.847  3267  3325 I jxcore-log: ok 213 error description is as expected
03-30 22:21:03.847  3267  3325 I jxcore-log: 
03-30 22:21:03.847  3267  3325 I jxcore-log: ok 214 must be stopped
03-30 22:21:03.847  3267  3325 I jxcore-log: 
,03-30 22:21:03.854  3267  3325 I jxcore-log: # teardown
03-30 22:21:03.854  3267  3325 I jxcore-log: 
,03-30 22:21:04.169  3267  3325 I jxcore-log: ok 215 must be stopped
03-30 22:21:04.169  3267  3325 I jxcore-log: 
,03-30 22:21:04.177  3267  3325 I jxcore-log: # setup
03-30 22:21:04.177  3267  3325 I jxcore-log: 
,03-30 22:21:04.370  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 22:21:04.370  3267  3325 I jxcore-log: 
,03-30 22:21:04.374  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 22:21:04.374  3267  3325 I jxcore-log: 
,03-30 22:21:04.381  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-30 22:21:04.381  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:21:04.381  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:21:04.381  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:21:04.381  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,03-30 22:21:04.381  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-30 22:21:04.381  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,03-30 22:21:04.381  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:21:04.384  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-30 22:21:04.387  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
03-30 22:21:04.387  3267  3325 I jxcore-log: ,
,03-30 22:21:04.388  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
03-30 22:21:04.388  3267  3325 I jxcore-log: ,
03-30 22:21:04.391  3267  3325 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
,03-30 22:21:04.391  3267  3325 I jxcore-log: 
03-30 22:21:04.392  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:21:04.392  3267  3325 I jxcore-log: 
,03-30 22:21:04.621  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:21:04.621  3267  3325 I jxcore-log: 
,03-30 22:21:04.624  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 59600,
03-30 22:21:04.624  3267  3325 I jxcore-log: 
,03-30 22:21:04.627  3267  3325 I jxcore-log: ok 216 peerIdentifier matches,
03-30 22:21:04.627  3267  3325 I jxcore-log: 
,03-30 22:21:04.628  3267  3325 I jxcore-log: ok 217 error description matches
03-30 22:21:04.628  3267  3325 I jxcore-log: 
,03-30 22:21:04.631  3267  3325 I jxcore-log: # teardown
03-30 22:21:04.631  3267  3325 I jxcore-log: 
,03-30 22:21:04.762  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-30 22:21:04.762  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:21:04.762  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:21:04.766  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:21:04.767  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 22:21:04.767  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 22:21:04.776  3267  3325 I jxcore-log: ok 218 must be stopped
03-30 22:21:04.776  3267  3325 I jxcore-log: 
,03-30 22:21:04.783  3267  3325 I jxcore-log: # setup
03-30 22:21:04.783  3267  3325 I jxcore-log: 
,03-30 22:21:05.087  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 22:21:05.087  3267  3325 I jxcore-log: 
,03-30 22:21:05.092  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-30 22:21:05.092  3267  3325 I jxcore-log: 
,03-30 22:21:05.100  3267  3325 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-30 22:21:05.100  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 22:21:05.100  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 22:21:05.100  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 22:21:05.100  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 22:21:05.100  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 22:21:05.100  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 22:21:05.100  3267  3325 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 22:21:05.104  3267  3325 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
03-30 22:21:05.105  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 22:21:05.105  3267  3325 I jxcore-log: 
,03-30 22:21:05.107  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 22:21:05.107  3267  3325 I jxcore-log: 
,03-30 22:21:05.116  3267  3325 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate
03-30 22:21:05.116  3267  3325 I jxcore-log: 
,03-30 22:21:05.118  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 22:21:05.118  3267  3325 I jxcore-log: 
,03-30 22:21:05.331  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:21:05.331  3267  3325 I jxcore-log: 
,03-30 22:21:05.334  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 56583
03-30 22:21:05.334  3267  3325 I jxcore-log: 
,03-30 22:21:05.341  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 58154, start advertisements: false
,03-30 22:21:05.341  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:21:05.341  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 22:21:05.341  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 22:21:05.346  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-30 22:21:05.346  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 22:21:05.346  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 22:21:05.352  2148  3816 D BtGatt.GattService: registerClient() - UUID=88efe9d7-07a8-4c90-ab6d-97a05d65272f,
,03-30 22:21:05.353  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=88efe9d7-07a8-4c90-ab6d-97a05d65272f, clientIf=5
03-30 22:21:05.353  3267  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 22:21:05.354  2148  2164 D BtGatt.GattService: start scan with filters
03-30 22:21:05.355  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:21:05.355  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 22:21:05.355  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 22:21:05.355  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 22:21:05.356  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 22:21:05.356  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:21:05.356  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 22:21:05.356  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:21:05.356   823  3512 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:21:05.361  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-30 22:21:05.362  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:21:05.364  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-30 22:21:05.364  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:21:05.364  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:21:05.364  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-30 22:21:05.367  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-30 22:21:05.367  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:21:05.367  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 22:21:05.367  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 22:21:05.368  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-30 22:21:05.368  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:21:05.369  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-30 22:21:05.369  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:21:05.369  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:21:05.369  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 22:21:05.374  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:21:05.374  3267  3325 I jxcore-log: 
,03-30 22:21:05.377  3267  3325 I jxcore-log: ok 219 discoveryActive matches,
03-30 22:21:05.377  3267  3325 I jxcore-log: 
,03-30 22:21:05.378  3267  3325 I jxcore-log: ok 220 advertisingActive matches,
03-30 22:21:05.378  3267  3325 I jxcore-log: 
,03-30 22:21:05.381  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:21:05.381  3267  3325 I jxcore-log: 
,03-30 22:21:05.384  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:21:05.384  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-30 22:21:05.384  3267  3325 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-30 22:21:05.384  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 22:21:05.384  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 22:21:05.384  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 22:21:05.384  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 22:21:05.384  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 22:21:05.384  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 22:21:05.386  2148  3816 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:21:05.388  2148  2164 D BtGatt.GattService: unregisterClient() - clientIf=5,
,03-30 22:21:05.388  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-30 22:21:05.388  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:21:05.388  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 22:21:05.388  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-30 22:21:05.388  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 22:21:05.388  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:21:05.389  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-30 22:21:05.389  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-30 22:21:05.389  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:21:05.389  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 22:21:05.389  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 22:21:05.390  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 22:21:05.390  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 22:21:05.390  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 22:21:05.390  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 22:21:05.390  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:21:05.390  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 22:21:05.391  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:21:05.391  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:21:05.392  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:21:05.393  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-30 22:21:05.393  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-30 22:21:05.398  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-30 22:21:05.398   823  3512 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:21:05.403  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-30 22:21:05.403  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 22:21:05.404  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:21:05.406  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-30 22:21:05.406  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 22:21:05.407  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 22:21:05.407  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 22:21:05.409  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
,03-30 22:21:05.410  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 22:21:05.410  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:21:05.412  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:21:05.412  3267  3325 I jxcore-log: 
,03-30 22:21:05.414  3267  3325 I jxcore-log: ok 221 discoveryActive matches
03-30 22:21:05.414  3267  3325 I jxcore-log: 
,03-30 22:21:05.415  3267  3325 I jxcore-log: ok 222 advertisingActive matches
03-30 22:21:05.415  3267  3325 I jxcore-log: 
03-30 22:21:05.420  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:21:05.420  3267  3325 I jxcore-log: 
,03-30 22:21:05.435  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 22:21:05.435  3267  3325 I jxcore-log: 
,03-30 22:21:05.437  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 48216
03-30 22:21:05.437  3267  3325 I jxcore-log: 
,03-30 22:21:05.444  3267  3325 I io.jxcore.node.ConnectionHelper: start: Port number: 48216, start advertisements: true
,03-30 22:21:05.444  3267  3325 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 22:21:05.444  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-30 22:21:05.444  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 22:21:05.449  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-30 22:21:05.449  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 22:21:05.449  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 22:21:05.449  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 22:21:05.454  2148  2994 D BtGatt.GattService: registerClient() - UUID=a4af2bfb-71b0-4677-b544-5c3eeef66816
,03-30 22:21:05.455  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=a4af2bfb-71b0-4677-b544-5c3eeef66816, clientIf=5
,03-30 22:21:05.455  3267  3283 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-30 22:21:05.455  2148  2164 D BtGatt.GattService: start scan with filters
03-30 22:21:05.457  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 22:21:05.457  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 22:21:05.457  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 22:21:05.457  2148  2221 D BtGatt.ScanManager: handling starting scan
03-30 22:21:05.457  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 22:21:05.457  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 22:21:05.458  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 22:21:05.458  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-30 22:21:05.458  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-30 22:21:05.458  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-30 22:21:05.459  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:21:05.459  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 22:21:05.459  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 22:21:05.460  2148  2211 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-30 22:21:05.460  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:21:05.462  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-30 22:21:05.462  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:21:05.462  2148  2221 D BtGatt.ScanManager: Starting BLE batch scan
03-30 22:21:05.462  2148  2221 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-30 22:21:05.465  2148  2211 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-30 22:21:05.465  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:21:05.467  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-30 22:21:05.467  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-30 22:21:05.468  2148  2164 D BtGatt.GattService: registerClient() - UUID=62157f6b-2638-4ab6-b7a2-bf5a6fa5b4bb
03-30 22:21:05.468  2148  2211 D BtGatt.GattService: onClientRegistered() - UUID=62157f6b-2638-4ab6-b7a2-bf5a6fa5b4bb, clientIf=6
03-30 22:21:05.468  3267  3282 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-30 22:21:05.470  2148  2220 D BtGatt.AdvertiseManager: message : 0
,03-30 22:21:05.474  2148  2220 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 22:21:05.477  2148  2211 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-30 22:21:05.479  2148  2211 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-30 22:21:05.480  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 22:21:05.480  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 22:21:05.481   823  2549 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:21:05.487  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:21:05.487  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 22:21:05.487  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-30 22:21:05.487  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 22:21:05.489  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 22:21:05.489  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 22:21:05.489  3267  3325 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-30 22:21:05.489  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 22:21:05.489  3267  3325 I io.jxcore.node.ConnectionHelper: start: OK
03-30 22:21:05.489  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-30 22:21:05.490  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 22:21:05.490  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 22:21:05.490  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-30 22:21:05.490  3267  3267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 22:21:05.490  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 22:21:05.490  3267  3267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 22:21:05.491  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 22:21:05.491  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 22:21:05.491  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 22:21:05.491   823  1236 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-30 22:21:05.491  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 22:21:05.491  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 22:21:05.492  3267  3866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-30 22:21:05.494  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 22:21:05.494  3267  3325 I jxcore-log: 
03-30 22:21:05.495  3267  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 22:21:05.509  3267  3325 I jxcore-log: not ok 223 discoveryActive matches
,03-30 22:21:05.509  3267  3325 I jxcore-log: 
03-30 22:21:05.509  3267  3325 I jxcore-log:   ---
03-30 22:21:05.509  3267  3325 I jxcore-log: 
03-30 22:21:05.509  3267  3325 I jxcore-log:     operator: equal,
03-30 22:21:05.509  3267  3325 I jxcore-log: 
03-30 22:21:05.510  3267  3325 I jxcore-log:     expected: false
03-30 22:21:05.510  3267  3325 I jxcore-log: 
,03-30 22:21:05.510  3267  3325 I jxcore-log:     actual:   true
03-30 22:21:05.510  3267  3325 I jxcore-log: 
03-30 22:21:05.510  3267  3325 I jxcore-log:   ...
,03-30 22:21:05.510  3267  3325 I jxcore-log: 
,03-30 22:21:05.516  3267  3325 I jxcore-log: not ok 224 advertisingActive matches
,03-30 22:21:05.516  3267  3325 I jxcore-log: 
03-30 22:21:05.516  3267  3325 I jxcore-log:   ---
03-30 22:21:05.516  3267  3325 I jxcore-log: 
03-30 22:21:05.516  3267  3325 I jxcore-log:     operator: equal
03-30 22:21:05.516  3267  3325 I jxcore-log: 
03-30 22:21:05.516  3267  3325 I jxcore-log:     expected: true,
03-30 22:21:05.516  3267  3325 I jxcore-log: 
03-30 22:21:05.517  3267  3325 I jxcore-log:     actual:   false
03-30 22:21:05.517  3267  3325 I jxcore-log: 
,03-30 22:21:05.517  3267  3325 I jxcore-log:   ...
03-30 22:21:05.517  3267  3325 I jxcore-log: 
,03-30 22:21:05.521  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-30 22:21:05.521  3267  3325 I jxcore-log: 
03-30 22:21:05.522  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 22:21:05.522  3267  3325 I jxcore-log: 
,03-30 22:21:05.526  3267  3325 I jxcore-log: not ok 225 discoveryActive matches
,03-30 22:21:05.526  3267  3325 I jxcore-log: 
03-30 22:21:05.527  3267  3325 I jxcore-log:   ---
03-30 22:21:05.527  3267  3325 I jxcore-log: 
03-30 22:21:05.527  3267  3325 I jxcore-log:     operator: equal,
03-30 22:21:05.527  3267  3325 I jxcore-log: 
03-30 22:21:05.527  3267  3325 I jxcore-log:     expected: false
03-30 22:21:05.527  3267  3325 I jxcore-log: 
03-30 22:21:05.527  3267  3325 I jxcore-log:     actual:   true
,03-30 22:21:05.527  3267  3325 I jxcore-log: 
03-30 22:21:05.527  3267  3325 I jxcore-log:   ...
03-30 22:21:05.527  3267  3325 I jxcore-log: 
,03-30 22:21:05.532  3267  3325 I jxcore-log: not ok 226 advertisingActive matches
,03-30 22:21:05.532  3267  3325 I jxcore-log: 
03-30 22:21:05.532  3267  3325 I jxcore-log:   ---
03-30 22:21:05.532  3267  3325 I jxcore-log: 
03-30 22:21:05.532  3267  3325 I jxcore-log:     operator: equal
03-30 22:21:05.532  3267  3325 I jxcore-log: 
,03-30 22:21:05.533  3267  3325 I jxcore-log:     expected: false
03-30 22:21:05.533  3267  3325 I jxcore-log: 
03-30 22:21:05.533  3267  3325 I jxcore-log:     actual:   true
03-30 22:21:05.533  3267  3325 I jxcore-log: 
03-30 22:21:05.533  3267  3325 I jxcore-log:   ...
03-30 22:21:05.533  3267  3325 I jxcore-log: 
,03-30 22:21:05.536  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 22:21:05.536  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-30 22:21:05.537  3267  3325 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 22:21:05.537  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-30 22:21:05.537  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 22:21:05.537  3267  3325 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 22:21:05.537  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-30 22:21:05.537  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 22:21:05.537  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 22:21:05.537  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 22:21:05.537  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 22:21:05.537  3267  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
03-30 22:21:05.537  3267  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 22:21:05.537  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 22:21:05.537  3267  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 22:21:05.540  2148  2164 D BtGatt.GattService: stopScan() - queue size =1
,03-30 22:21:05.542  2148  2994 D BtGatt.GattService: unregisterClient() - clientIf=5
03-30 22:21:05.542  2148  2211 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-30 22:21:05.543  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-30 22:21:05.543  2148  2221 D BtGatt.ScanManager: stopping BLe Batch
03-30 22:21:05.545  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 22:21:05.545  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-30 22:21:05.545  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-30 22:21:05.545  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-30 22:21:05.545  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 22:21:05.546  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-30 22:21:05.546  2148  2211 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-30 22:21:05.546  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 22:21:05.546  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-30 22:21:05.546  2148  2221 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-30 22:21:05.548  2148  2211 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-30 22:21:05.548  2148  2211 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-30 22:21:05.549  2148  2220 D BtGatt.AdvertiseManager: message : 1
,03-30 22:21:05.550  2148  2220 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-30 22:21:05.556  2148  2211 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-30 22:21:05.556  2148  2211 D BtGatt.GattService: Client app is not null!
,03-30 22:21:05.558  2148  2163 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 22:21:05.559  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-30 22:21:05.559  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
,03-30 22:21:05.559  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 22:21:05.559  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 22:21:05.559  3267  3325 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-30 22:21:05.559  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 22:21:05.560  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-30 22:21:05.560  3267  3325 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 22:21:05.561  3267  3325 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-30 22:21:05.561  3267  3325 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-30 22:21:05.562  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 22:21:05.562  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 22:21:05.562  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 22:21:05.571  3267  3267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 22:21:05.572   823  1260 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-30 22:21:05.584  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 22:21:05.585  3267  3267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-30 22:21:05.585  3267  3267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 22:21:05.593  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 22:21:05.593  3267  3267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 22:21:05.594  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 22:21:05.594  3267  3267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 22:21:05.594  3267  3267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 22:21:05.594  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 22:21:05.595  3267  3267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 22:21:05.595  3267  3267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-30 22:21:05.599  3267  3325 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 22:21:05.599  3267  3325 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 22:21:05.599  3267  3325 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 22:21:05.602  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-30 22:21:05.602  3267  3325 I jxcore-log: 
03-30 22:21:05.605  3267  3325 I jxcore-log: ok 227 discoveryActive matches
03-30 22:21:05.605  3267  3325 I jxcore-log: ,
,03-30 22:21:05.614  3267  3325 I jxcore-log: not ok 228 advertisingActive matches,
03-30 22:21:05.614  3267  3325 I jxcore-log: 
03-30 22:21:05.614  3267  3325 I jxcore-log:   ---
03-30 22:21:05.614  3267  3325 I jxcore-log: ,
03-30 22:21:05.614  3267  3325 I jxcore-log:     operator: equal
03-30 22:21:05.614  3267  3325 I jxcore-log: ,
03-30 22:21:05.614  3267  3325 I jxcore-log:     expected: false
03-30 22:21:05.614  3267  3325 I jxcore-log: ,
03-30 22:21:05.615  3267  3325 I jxcore-log:     actual:   true
03-30 22:21:05.615  3267  3325 I jxcore-log: 
,03-30 22:21:05.615  3267  3325 I jxcore-log:   ...
03-30 22:21:05.615  3267  3325 I jxcore-log: 
03-30 22:21:05.617  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-30 22:21:05.617  3267  3325 I jxcore-log: 
,03-30 22:21:05.617  3267  3325 I jxcore-log: ok 229 discoveryActive matches,
03-30 22:21:05.617  3267  3325 I jxcore-log: 
03-30 22:21:05.618  3267  3325 I jxcore-log: ok 230 advertisingActive matches
03-30 22:21:05.618  3267  3325 I jxcore-log: 
03-30 22:21:05.620  3267  3325 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 22:21:05.620  3267  3325 I jxcore-log: 
,03-30 22:21:05.632  3267  3325 I jxcore-log: DEBUG createNativeListener: creating native server,
03-30 22:21:05.632  3267  3325 I jxcore-log: 
,03-30 22:21:05.634  3267  3325 I jxcore-log: DEBUG createNativeListener: listening 47699,
03-30 22:21:05.634  3267  3325 I jxcore-log: 
03-30 22:21:05.642  3267  3325 I jxcore-log: Uncaught Promise Rejection: {}
03-30 22:21:05.642  3267  3325 I jxcore-log: 
,03-30 22:21:05.646  3267  3325 E jxcore-log: Trace: [Error: Call Stop!]
03-30 22:21:05.646  3267  3325 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-30 22:21:05.646  3267  3325 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-30 22:21:05.646  3267  3325 E jxcore-log:     at emit@events.js:98:1
03-30 22:21:05.646  3267  3325 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-30 22:21:05.646  3267  3325 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-30 22:21:05.646  3267  3325 E jxcore-log:     at $0a@node.js:917:1
03-30 22:21:05.646  3267  3325 E jxcore-log: 
,03-30 22:21:05.646  3267  3325 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-30 22:21:05.646  3267  3325 I jxcore-log: 
03-30 22:21:05.649  3267  3325 I jxcore-log: # teardown
03-30 22:21:05.649  3267  3325 I jxcore-log: 
,03-30 22:21:05.943  3867  3867 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-30 22:21:05.946  3867  3867 D AndroidRuntime: CheckJNI is OFF
,03-30 22:21:06.062  3867  3867 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-30 22:21:06.069   823   854 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
,03-30 22:21:06.070   823   854 I ActivityManager: Killing 3267:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-30 22:21:06.143   823   864 W PackageSettings: Skipping PackageSetting{3c52f7f6 com.example.hello/10273} due to missing metadata
,03-30 22:21:06.259   823  1230 I WindowState: WIN DEATH: Window{2cf2ebca u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-30 22:21:06.266   823  1013 D WifiService: Client connection lost with reason: 4
,03-30 22:21:06.280   823   854 E libprocessgroup: failed to kill 1 processes for processgroup 3267
,03-30 22:21:06.281   823   854 W ActivityManager: Force removing ActivityRecord{10b2bcdc u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-30 22:21:06.300   823   823 V ActivityManager: Display changed displayId=0
,03-30 22:21:06.305   823   864 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-30 22:21:06.327   823  1242 W ActivityManager: Spurious death for ProcessRecord{a0bd0b 3267:com.test.thalitest/u0a95}, curProc for 3267: null
,03-30 22:21:06.336  1258  1258 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-30 22:21:06.342   823  1001 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-30 22:21:06.344   823  1048 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-30 22:21:06.353  2977  2977 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-30 22:21:06.361  1258  3883 I Keyboard.Facilitator.DecoderInitializer: run()
,03-30 22:21:06.389  1069  1069 I art     : Explicit concurrent mark sweep GC freed 50703(2MB) AllocSpace objects, 0(0B) LOS objects, 20% free, 61MB/77MB, paused 996us total 68.610ms
,03-30 22:21:06.392  1258  3883 I Decoder : createOrResetDecoder
,03-30 22:21:06.400   823  1260 I ActivityManager: Start proc 3884:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-30 22:21:06.410   823  3512 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3267 uid 10095
03-30 22:21:06.411  1258  1258 I Keyboard.Facilitator: onFinishInput()
,03-30 22:21:06.415  1526  1526 I art     : Explicit concurrent mark sweep GC freed 6049(331KB) AllocSpace objects, 1(16KB) LOS objects, 36% free, 27MB/43MB, paused 1.185ms total 100.186ms
03-30 22:21:06.417   823   823 I art     : Explicit concurrent mark sweep GC freed 25521(2MB) AllocSpace objects, 4(158KB) LOS objects, 32% free, 33MB/49MB, paused 2.013ms total 92.952ms
,03-30 22:21:06.419   823   864 I art     : WaitForGcToComplete blocked for 90.891ms for cause Explicit
,03-30 22:21:06.444  1239  1239 I ConfigService: onCreate
,03-30 22:21:06.460  1258  3883 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-30 22:21:06.464  1361  1361 I art     : Explicit concurrent mark sweep GC freed 4978(363KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 2.077ms total 23.487ms
,03-30 22:21:06.480  1526  1526 W LocationOracleImpl: Best location was null
,03-30 22:21:06.498  1526  3905 I HotwordRecognitionRnr: Starting hotword detection.
03-30 22:21:06.498  1526  3906 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@ea63d96
,03-30 22:21:06.502   357  3908 I AudioFlinger: AudioFlinger's thread 0xb4d52000 ready to run
,03-30 22:21:06.503   357  1031 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-30 22:21:06.504  1526  3906 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@ea63d96
,03-30 22:21:06.505  1258  3883 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-30 22:21:06.506  1258  3883 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-30 22:21:06.506  1258  3883 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-30 22:21:06.514   357  3908 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-30 22:21:06.514   357  3908 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-30 22:21:06.514   357  3908 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-30 22:21:06.514   357  3908 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-30 22:21:06.515  1258  3883 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-30 22:21:06.515  1258  3883 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-30 22:21:06.516  1258  3883 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-30 22:21:06.516  1258  3883 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-30 22:21:06.519  1258  3883 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-30 22:21:06.519  1258  3883 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-30 22:21:06.519  1258  3883 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-30 22:21:06.519  1258  3883 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-30 22:21:06.519  1258  3883 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-30 22:21:06.519  1258  3883 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-30 22:21:06.525   357  3908 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-30 22:21:06.528   823   823 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-30 22:21:06.528   823   823 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-30 22:21:06.555  3884  3919 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-30 22:21:06.572   823  1242 I ActivityManager: Start proc 3920:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-30 22:21:06.585  3884  3913 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-30 22:21:06.585   823   864 I art     : Explicit concurrent mark sweep GC freed 7944(385KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 3.350ms total 164.142ms
,03-30 22:21:06.596  1526  1526 I HotwordWorker: onReady
,03-30 22:21:06.610   823   839 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2e348177}
,03-30 22:21:06.614   823  1011 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.25 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-30 22:21:06.635   823  1236 I ActivityManager: Start proc 3939:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-30 22:21:06.645  1361  1361 D Launcher.Workspace: 11683562 - stripEmptyScreens()
03-30 22:21:06.646  1361  1361 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-30 22:21:06.658  3939  3939 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-30 22:21:06.665  3867  3867 I art     : System.exit called, status: 0
03-30 22:21:06.665  3867  3867 I AndroidRuntime: VM exiting with result code 0.
,03-30 22:21:06.668  1239  1239 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-30 22:21:06.668  1239  1239 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-30 22:21:06.679   823  1278 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658545427
03-30 22:21:06.679   823  1278 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-30 22:21:06.687   823   864 I ActivityManager: Start proc 3960:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-30 22:21:06.690   823  1236 I ActivityManager: Killing 3604:com.qualcomm.timeservice/1000 (adj 15): empty #17
,03-30 22:21:06.842  1804  3980 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-30 22:21:06.842  1804  1804 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-30 22:21:06.842  1804  1804 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-30 22:21:06.844  1804  3980 D AccountUtils: Clearing selected account for com.test.thalitest
,03-30 22:21:06.847  1804  1804 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,03-30 22:21:06.848  1804  1804 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-30 22:21:06.854  1804  3983 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-30 22:21:06.856  1526  3984 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-30 22:21:06.864  1804  3980 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-30 22:21:06.866  1804  3985 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-30 22:21:06.867  1804  3985 E DriveAsyncService: disk I/O error (code 3850)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:06.867  1804  3985 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,03-30 22:21:06.873  1361  1361 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@17385fbd new=com.google.android.velvet.VelvetApplication@17385fbd
,03-30 22:21:06.876   823  3512 I ActivityManager: Killing 3623:com.google.android.deskclock/u0a44 (adj 15): empty #17
,03-30 22:21:06.877  1804  3986 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-30 22:21:06.877  1804  3986 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-30 22:21:06.878  1361  1579 E SQLiteLog: (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:06.878  1804  3986 E SQLiteO,penHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
03-30 22:21:06.878  1804  3986 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-30 22:21:06.881  1804  3986 W SQLiteOpenHelper: Opened metrics.db in read-only mode
03-30 22:21:06.881  1804  3986 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-30 22:21:06.881  1804  3986 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
03-30 22:21:06.882  1804  3986 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
03-30 22:21:06.882  1804  3986 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
03-30 22:21:06.882  1804  3986 I Process : Sending signal. PID: 1804 SIG: 9
03-30 22:21:06.888  3884  3913 E SQLiteLog: (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
03-30 22:21:06.890  1526  3984 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
03-30 22:21:06.890  3884  3913 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
03-30 22:21:06.890  3884  3913 E AndroidRuntime: Process: android.process.acore, PID: 3884
03-30 22:21:06.890  3884  3913 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-30 22:21:06.890  3884  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-30 22:21:06.890  3884  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-30 22:21:06.890  3884  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-30 22:21:06.890  3884  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-30 22:21:06.890  3884  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-30 22:21:06.890  3884  3913 E AndroidRuntime: 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
03-30 22:21:06.890  3884  3913 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
03-30 22:21:06.890  3884  3913 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
03-30 22:21:06.890  3884  3913 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 22:21:06.890  3884  3913 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-30 22:21:06.890  3884  3913 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-30 22:21:06.973   823  1013 D WifiService: Client connection lost with reason: 4
,03-30 22:21:07.149   823  3512 I ActivityManager: Start proc 3992:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,03-30 22:21:07.223   823   839 I ActivityManager: Start proc 4009:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,03-30 22:21:07.225   823  2549 I ActivityManager: Process com.google.android.gms (pid 1804) has died
,03-30 22:21:07.226  1526  3984 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
03-30 22:21:07.226   823  2549 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
03-30 22:21:07.226   823  2549 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 11000ms
03-30 22:21:07.226  1526  3984 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
03-30 22:21:07.226  1526  3984 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1526
03-30 22:21:07.226  1526  3984 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1333)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-30 22:21:07.226  1526  3984 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-30 22:21:07.226   823  2549 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 11000ms
03-30 22:21:07.226   823  2549 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 21000ms
03-30 22:21:07.226   823  2549 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 31000ms
03-30 22:21:07.227   823  2549 W Activit,yManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 31000ms
03-30 22:21:07.227   823  2549 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 31000ms
,03-30 22:21:07.231   823  1260 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@2340580
,03-30 22:21:07.242   823  4020 E DropBoxManagerService: Can't write: system_app_crash
03-30 22:21:07.242   823  4020 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
03-30 22:21:07.242   823  4020 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-30 22:21:07.242   823  4020 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-30 22:21:07.242   823  4020 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-30 22:21:07.242   823  4020 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-30 22:21:07.242   823  4020 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-30 22:21:07.242   823  4020 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-30 22:21:07.242   823  4020 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-30 22:21:07.242   823  4020 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-30 22:21:07.242   823  4020 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-30 22:21:07.242   823  4020 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-30 22:21:07.242   823  4020 E DropBoxManagerService: 	... 5 more
,03-30 22:21:07.263   823  4027 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-30 22:21:07.264   823   854 D Atlas   : Validating map...
,03-30 22:21:07.274   823  4028 E DropBoxManagerService: Can't write: system_app_crash
03-30 22:21:07.274   823  4028 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
03-30 22:21:07.274   823  4028 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-30 22:21:07.274   823  4028 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-30 22:21:07.274   823  4028 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-30 22:21:07.274   823  4028 E DropBoxManagerService: ,	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-30 22:21:07.274   823  4028 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-30 22:21:07.274   823  4028 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-30 22:21:07.274   823  4028 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-30 22:21:07.274   823  4028 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-30 22:21:07.274   823  4028 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-30 22:21:07.274   823  4028 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-30 22:21:07.274   823  4028 E DropBoxManagerService: 	... 5 more
,03-30 22:21:07.313   823  4027 I OpenGLRenderer: Initialized EGL, version 1.4
,03-30 22:21:07.319   823  4027 D OpenGLRenderer: Enabling debug mode 0
,03-30 22:21:07.398   823  1236 I ActivityManager: Start proc 4033:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,03-30 22:21:07.444  4033  4033 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-30 22:21:07.444  4033  4033 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-30 22:21:07.472  4033  4033 I MultiDex: VM with version 2.1.0 has multidex support
03-30 22:21:07.472  4033  4033 I MultiDex: install
03-30 22:21:07.472  4033  4033 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-30 22:21:07.513  4033  4052 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:07.513  4033  4052 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-30 22:21:07.517  1526  1526 I HotwordDetector: Closing mic
,03-30 22:21:07.518  1526  1795 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@ea63d96
,03-30 22:21:07.520  4033  4052 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:07.520  4033  4052 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-30 22:21:07.539  1526  4053 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-30 22:21:07.556  1258  3883 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-30 22:21:07.556  1258  3883 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-30 22:21:07.567  1258  3883 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-30 22:21:07.567  1258  3883 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-30 22:21:07.572  1258  3883 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-30 22:21:07.572  1258  3883 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-30 22:21:07.573  1258  3883 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-30 22:21:07.573  1258  3883 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-30 22:21:07.573  4033  4033 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-30 22:21:07.580   357  3908 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,03-30 22:21:07.580   357  3908 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
,03-30 22:21:07.585   357  1031 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-30 22:21:07.587  1526  3905 I HotwordRecognitionRnr: Hotword detection finished
03-30 22:21:07.587  1526  1797 I HotwordRecognitionRnr: Stopping hotword detection.
,03-30 22:21:07.602  4033  4033 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-30 22:21:07.611  4033  4059 W NativeLibraryUtils: Failed to open lock file
03-30 22:21:07.611  4033  4059 W NativeLibraryUtils: java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
03-30 22:21:07.611  4033  4059 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-30 22:21:07.611  4033  4059 W NativeLibraryUtils: 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
03-30 22:21:07.611  4033  4059 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
03-30 22:21:07.611  4033  4059 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:136)
03-30 22:21:07.611  4033  4059 W NativeLibraryUtils: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-30 22:21:07.611  4033  4059 W NativeLibraryUtils: 	at libcore.io.Posix.open(Native Method)
03-30 22:21:07.611  4033  4059 W NativeLibraryUtils: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-30 22:21:07.611  4033  4059 W NativeLibraryUtils: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-30 22:21:07.611  4033  4059 W NativeLibraryUtils: 	... 3 more
,03-30 22:21:07.638  3992  3992 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-30 22:21:07.638  3992  3992 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-30 22:21:07.638  3992  3992 I GAv4    :   adb logcat -s GAv4
,03-30 22:21:07.652   823  1242 I ActivityManager: Killing 3586:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,03-30 22:21:07.654  4033  4064 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:966)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:478)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:422)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:07.654  4033  4064 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: Couldn't open reminders.db for writing (will try read-only):
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:07.654  40,33  4064 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:966)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:478)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:422)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:07.654  4033  4064 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:07.656  4033  4064 W SQLiteOpenHelper: Opened reminders.db in read-only mode
,03-30 22:21:07.662  4033  4065 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:07.662  4033  4065 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-30 22:21:07.664  4033  4065 E AndroidRuntime: FATAL EXCEPTION: AsyncTask #3
03-30 22:21:07.664  4033  4065 E AndroidRuntime: Process: com.google.android.gms, PID: 4033
03-30 22:21:07.664  4033  4065 E AndroidRuntime: java.lang.RuntimeException: An error occured while executing doInBackground()
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:18,5)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:21:07.664  4033  4065 E AndroidRuntime: 	... 4 more
,03-30 22:21:07.709  3992  3992 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
03-30 22:21:07.709   823  4067 E DropBoxManagerService: Can't write: system_app_crash
03-30 22:21:07.709   823  4067 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
03-30 22:21:07.709   823  4067 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-30 22:21:07.709   823  4067 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-30 22:21:07.709   823  4067 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-30 22:21:07.709   823  4067 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-30 22:21:07.709   823  4067 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-30 22:21:07.709   823  4067 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-30 22:21:07.709   823  4067 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-30 22:21:07.709   823  4067 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-30 22:21:07.709   823  4067 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-30 22:21:07.709   823  4067 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-30 22:21:07.709   823  4067 E DropBoxManagerService: 	... 5 more
,03-30 22:21:07.709   823   854 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-30 22:21:07.709   823   854 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-30 22:21:07.726  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:07.727  3992  3992 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-30 22:21:07.728  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:07.730  3992  4069 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-30 22:21:07.731  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:07.745  4033  4033 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
,03-30 22:21:07.747  3992  3992 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-30 22:21:07.759  3992  4069 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:07.759  3992  4069 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
03-30 22:21:07.759  3992  4069 E GAv4    : Opening the database failed, dropping the table and recreating it
,03-30 22:21:07.759  4033  4062 I Icing   : Storage manager: low false usage 1.98MB avail 20.70GB capacity 22.09GB
,03-30 22:21:07.760  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:07.762  3992  4069 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:07.762  3992  4069 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
03-30 22:21:07.762  3992  4069 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:07.764  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:07.764  3992  4069 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,03-30 22:21:07.773  3992  4069 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,03-30 22:21:07.773  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:07.774  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:07.777  3992  4074 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at ael.a(PG:1521)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-30 22:21:07.777  3992  4074 E SQLiteDatabase: 	at aen.run(PG:536)
,03-30 22:21:07.799  4033  4062 W Icing   : Received bad json for section weights override -- ignoring.
,03-30 22:21:07.801  4033  4062 W Icing   : Received bad json for corpus context scoring override -- ignoring.
03-30 22:21:07.801  4033  4062 W Icing   : Received bad json for section weights override -- ignoring.
,03-30 22:21:07.801  4033  4062 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,03-30 22:21:07.806  4033  4078 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,03-30 22:21:07.806  4033  4078 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,03-30 22:21:07.834  3992  4083 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at ael.a(PG:1521)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at aej.c(PG:139)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at aej.b(PG:398)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at agf.f(PG:417)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at oe.run(PG:1112)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:07.834  3992  4083 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: Failed to delete from CachedSearch133
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at aej.c(PG:139)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at aej.b(PG:398)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at agf.f(PG:417)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at oe.run(PG:1112)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:07.836  3992  4083 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
,03-30 22:21:07.837  3992  4069 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:07.837  3992  4069 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:07.838  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:07.839  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:07.840  3992  4069 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
,03-30 22:21:07.840  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:07.840  3992  4069 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
,03-30 22:21:07.841  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:07.841  3992  4069 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:07.841  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:07.842  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:07.842  3992  4069 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
,03-30 22:21:07.843  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:07.843  3992  4069 E GAv4    : Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:07.844  3992  4069 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:07.844  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:07.844  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:07.844  3992  4074 E GAv4    : syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at aev.getWritableDatabase(PG:238)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at ael.a(PG:1521)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at hix$a.a(PG:125)
03-30 22:21:07.845  3992  4074 E CAKEMIX_CRASHED: 	at aen.run(PG:536)
03-30 22:21:07.846  3992  4068 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:07.856  3992  4084 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-30 22:21:07.856  3992  4084 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-30 22:21:07.857  4033  4062 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids for write failed: Read-only file system
03-30 22:21:07.857  4033  4062 E Icing   : Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids
03-30 22:21:07.857  4033  4062 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata for write failed: Read-only file system
03-30 22:21:07.857  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
03-30 22:21:07.857  4033  4062 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring for write failed: Read-only file system
03-30 22:21:07.857  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
03-30 22:21:07.858  4033  4062 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs for write failed: Read-only file system
03-30 22:21:07.858  4033  4062 E Icing   : Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs
,03-30 22:21:07.858  4033  4062 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.tags.h for write failed: Read-only file system
03-30 22:21:07.858  4033  4062 E Icing   : Trie initialize fail
03-30 22:21:07.858  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
03-30 22:21:07.858  4033  4062 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h for write failed: Read-only file system
,03-30 22:21:07.858  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
03-30 22:21:07.858  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
03-30 22:21:07.858  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
03-30 22:21:07.858  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
03-30 22:21:07.858  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
03-30 22:21:07.858  4033  4062 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage for write failed: Read-only file system
03-30 22:21:07.858  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
03-30 22:21:07.858  4033  4062 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage for write failed: Read-only file system
03-30 22:21:07.858  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
,03-30 22:21:07.858  4033  4062 E Icing   : Init docstore failed
03-30 22:21:07.858  4033  4062 E Icing   : Index init failed, resetting corpora
,03-30 22:21:07.881   823   823 I ActivityManager: Start proc 4087:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,03-30 22:21:07.882   823  1102 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
03-30 22:21:07.883   823  1102 V WindowManager: addAppToken: AppWindowToken{23d79035 token=Token{3e31326c ActivityRecord{735af1f u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t18}}} to stack=1 task=18 at 0
,03-30 22:21:07.885  3992  4074 I Process : Sending signal. PID: 3992 SIG: 9
,03-30 22:21:07.887   823  1236 I ActivityManager: Killing 3151:com.google.android.talk/u0a61 (adj 15): empty #17
,03-30 22:21:07.943   276   276 E lowmemorykiller: Error writing /proc/3992/oom_score_adj; errno=22
03-30 22:21:07.943   823  1242 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,03-30 22:21:07.946   823  1242 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!,
,03-30 22:21:07.947   823  1242 W ActivityManager: Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
03-30 22:21:07.947   823  1242 W ActivityManager: android.os.TransactionTooLargeException
03-30 22:21:07.947   823  1242 W ActivityManager: ,	at android.os.BinderProxy.transactNative(Native Method)
03-30 22:21:07.947   823  1242 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
03-30 22:21:07.947   823  1242 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
03-30 22:21:07.947   823  1242 W ActivityManager: 	,at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
03-30 22:21:07.947   823  1242 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
03-30 22:21:07.947   823  1242 W ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
03-30 22:21:07.947   823  1242 W ActivityManager: 	,at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
03-30 22:21:07.947   823  1242 W ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
03-30 22:21:07.947   823  1242 W ActivityManager: 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
03-30 22:21:07.947   823  1242 W ActivityManager: 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896),
03-30 22:21:07.947   823  1242 W ActivityManager: 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
03-30 22:21:07.947   823  1242 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
03-30 22:21:07.947   823  1242 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208),
03-30 22:21:07.947   823  1242 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
,03-30 22:21:08.040   823  1242 I ActivityManager: Start proc 4104:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,03-30 22:21:08.056   823   838 W ActivityManager: Spurious death for ProcessRecord{1d18a227 4104:com.google.android.apps.docs/u0a46}, curProc for 3992: null
,03-30 22:21:08.066  1361  1648 W OpenGLRenderer: Incorrectly called buildLayer on View: ew, destroying layer...
,03-30 22:21:08.108  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/idx.index failed: Read-only file system
,03-30 22:21:08.108  4033  4062 E Icing   : Clearing index failed
03-30 22:21:08.108  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids failed: Read-only file system
,03-30 22:21:08.108  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
03-30 22:21:08.108  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
03-30 22:21:08.108  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs failed: Read-only file system
03-30 22:21:08.108  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-0 failed: Read-only file system
03-30 22:21:08.108  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-24 failed: Read-only file system
,03-30 22:21:08.108  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-30 failed: Read-only file system
03-30 22:21:08.108  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user.__unseen__i.43133bd20a9b3232 failed: Read-only file system
,03-30 22:21:08.108  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e failed: Read-only file system
03-30 22:21:08.108  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 failed: Read-only file system
03-30 22:21:08.108  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f failed: Read-only file system,
03-30 22:21:08.108  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f failed: Read-only file system
03-30 22:21:08.109  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e failed: Read-only file system
,03-30 22:21:08.109  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e failed: Read-only file system
03-30 22:21:08.109  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e failed: Read-only file system
,03-30 22:21:08.109  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e failed: Read-only file system
03-30 22:21:08.109  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted failed: Read-only file system
03-30 22:21:08.109  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
,03-30 22:21:08.109  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
03-30 22:21:08.109  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
03-30 22:21:08.109  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
,03-30 22:21:08.109  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
03-30 22:21:08.109  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
,03-30 22:21:08.109  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
03-30 22:21:08.109  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
03-30 22:21:08.109  4033  4062 E Icing   : Clearing docstore failed
,03-30 22:21:08.109  4033  4062 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/compact_status failed: Read-only file system
03-30 22:21:08.109  4033  4062 E Icing   : Deleting compact status failed
,03-30 22:21:08.131  1239  4122 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at com.google.android.gms.playlog.store.g.b(SourceFile:384)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at com.google.android.gms.playlog.store.g.a(SourceFile:352)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at com.google.android.gms.playlog.service.d.a(SourceFile:136)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.131  1239  4122 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at com.google.android.gms.playlog.store.g.b(SourceFile:384)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at com.google.android.gms.playlog.store.g.a(SourceFile:352)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at com.google.android.gms.playlog.service.d.a(SourceFile:136)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.132  1239  4122 E PlayLogIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-30 22:21:08.160  4087  4087 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1372)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-30 22:21:08.160  4087  4087 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,03-30 22:21:08.162  4087  4087 D AndroidRuntime: Shutting down VM
03-30 22:21:08.164  4087  4087 E AndroidRuntime: FATAL EXCEPTION: main
03-30 22:21:08.164  4087  4087 E AndroidRuntime: Process: com.android.documentsui, PID: 4087
03-30 22:21:08.164  4087  4087 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1372)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-30 22:21:08.164  4087  4087 E AndroidRuntime: 	... 9 more
03-30 22:21:08.166  1090  2266 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10095)] disk I/O error
03-30 22:21:08.168  1090  2266 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
03-30 22:21:08.168  1090  2266 E AndroidRuntime: Process: android.process.media, PID: 1090
03-30 22:21:08.168  1090  2266 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1175)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:117)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:85)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-30 22:21:08.168  1090  2266 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-30 22:21:08.215   823  1102 I ActivityManager: Start proc 4125:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
03-30 22:21:08.224   823  4134 E DropBoxManagerService: Can't write: system_app_crash
03-30 22:21:08.224   823  4134 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
03-30 22:21:08.224   823  4134 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-30 22:21:08.224   823  4134 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-30 22:21:08.224   823  4134 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-30 22:21:08.224   823  4134 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-30 22:21:08.224   823  4134 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-30 22:21:08.224   823  4134 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-30 22:21:08.224   823  4134 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-30 22:21:08.224   823  4134 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-30 22:21:08.224   823  4134 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-30 22:21:08.224   823  4134 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-30 22:21:08.224   823  4134 E DropBoxManagerService: 	... 5 more
03-30 22:21:08.237   369   369 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 348us total 22.377ms
,03-30 22:21:08.244   823  4142 E DropBoxManagerService: Can't write: system_app_crash
03-30 22:21:08.244   823  4142 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
03-30 22:21:08.244   823  4142 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-30 22:21:08.244   823  4142 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-30 22:21:08.244   823  4142 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-30 22:21:08.244   823  4142 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-30 22:21:08.244   823  4142 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-30 22:21:08.244   823  4142 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-30 22:21:08.244   823  4142 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-30 22:21:08.244   823  4142 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-30 22:21:08.244   823  4142 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-30 22:21:08.244   823  4142 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-30 22:21:08.244   823  4142 E DropBoxManagerService: 	... 5 more
,03-30 22:21:08.254   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 328us total 15.525ms
,03-30 22:21:08.256  1239  2528 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
03-30 22:21:08.259   823  2549 I ActivityManager: Killing 2374:com.google.android.calendar/u0a37 (adj 15): empty #17
,03-30 22:21:08.269   369   369 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 318us total 13.538ms
,03-30 22:21:08.406  1239  1239 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-30 22:21:08.416  4033  4033 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-30 22:21:08.433   823  4146 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2e348177}
,03-30 22:21:08.448  3757  3757 D WearableService: callingUid 10011, callindPid: 3757
,03-30 22:21:08.452  1842  2107 E MDM     : [148] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-30 22:21:08.456  4125  4125 D ExternalStorage: After updating volumes, found 1 active roots
,03-30 22:21:08.458  4104  4104 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-30 22:21:08.458  4104  4104 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-30 22:21:08.458  4104  4104 I GAv4    :   adb logcat -s GAv4
,03-30 22:21:08.464   823   838 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@f4c682a}
,03-30 22:21:08.467  4104  4104 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-30 22:21:08.475  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:08.475  4104  4104 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
03-30 22:21:08.477  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:08.480  4104  4153 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-30 22:21:08.484  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:08.491  4104  4153 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.491  4104  4153 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
,03-30 22:21:08.491  4104  4153 E GAv4    : Opening the database failed, dropping the table and recreating it
03-30 22:21:08.491  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.492  4104  4153 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
03-30 22:21:08.493  4104  4153 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,03-30 22:21:08.497  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:08.497  4104  4153 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,03-30 22:21:08.498  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:08.499  4104  4153 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,03-30 22:21:08.500  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-30 22:21:08.505  4104  4104 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-30 22:21:08.525  4104  4154 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at ael.a(PG:1521)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-30 22:21:08.525  4104  4154 E SQLiteDatabase: 	at aen.run(PG:536)
,03-30 22:21:08.549   823  3990 I art     : Explicit concurrent mark sweep GC freed 25065(1361KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 1.899ms total 58.082ms
,03-30 22:21:08.585  4104  4159 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at ael.a(PG:1521)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at aej.c(PG:139)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at aej.b(PG:398)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at agf.f(PG:417)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at oe.run(PG:1112)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.585  4104  4159 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: Failed to delete from CachedSearch133
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at aej.c(PG:139)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at aej.b(PG:398)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at agf.f(PG:417)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at oe.run(PG:1112)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.585  4104  4159 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
,03-30 22:21:08.594  4104  4160 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-30 22:21:08.595  4104  4160 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-30 22:21:08.602  4033  4163 D LocationInitializer: Restart initialization of location
,03-30 22:21:08.635  1239  4170 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.635  1239  4170 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	a,t android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.636  1239  4170 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.636  1239  4170 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
03-30 22:21:08.636  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.637  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Th,read.run(Thread.java:818)
03-30 22:21:08.638  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.639  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.641  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.642  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.643  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.644  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.645  4104  4104 E ErrorNotificationActivity: Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
03-30 22:21:08.645  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.646  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.647  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.647  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.648  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.648  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.649  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.649  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.650  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.651  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.652  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.653  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.655  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.660  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.661  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.661  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.663  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.666  4104  4160 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.667  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.668  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.669  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.670  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.670  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.672  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.672  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.673  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.674  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.675  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.675  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.678  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.679  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.681  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.682  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.683  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.684  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.685  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.685  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.686  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.687  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.688  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.688  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.689  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.690  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.691  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.691  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.692  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.693  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.694  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.694  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.695  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.695  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.696  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
,03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.697  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.704  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:08.704  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
03-30 22:21:08.707  4104  4174 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-30 22:21:08.709  4104  4104 D Atlas   : Validating map...
03-30 22:21:08.713   823  1102 V WindowManager: Adding window Window{2c57003d u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 12 (after Window{1c652414 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-30 22:21:08.719   823   838 V WindowManager: Adding window Window{3a49e183 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 13 (before Window{2c57003d u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
03-30 22:21:08.721  4104  4153 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:08.722  4104  4153 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:08.722  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:08.722  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:08.723  4104  4153 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:08.723  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:08.724  4104  4153 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:08.724  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:08.725  4104  4153 E GAv4    : Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:08.725  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:08.726  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:08.727  4104  4153 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:08.728  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:08.728  4104  4153 E GAv4    : Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:08.728  4104  4153 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:08.728  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:08.728  4104  4154 E GAv4    : syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at aev.getWritableDatabase(PG:238)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at ael.a(PG:1521)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at hix$a.a(PG:125)
03-30 22:21:08.729  4104  4154 E CAKEMIX_CRASHED: 	at aen.run(PG:536)
03-30 22:21:08.730  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:08.730  4104  4152 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-30 22:21:08.740  4104  4160 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-30 22:21:08.745   823  1236 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
03-30 22:21:08.748  4104  4154 I Process : Sending signal. PID: 4104 SIG: 9
,03-30 22:21:08.869   823   838 I WindowState: WIN DEATH: Window{2c57003d u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,03-30 22:21:08.870   823  1000 W InputDispatcher: channel '3a49e183 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
03-30 22:21:08.871   823  1000 E InputDispatcher: channel '3a49e183 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
03-30 22:21:08.871   823  2549 I ActivityManager: Process com.google.android.apps.docs (pid 4104) has died
,03-30 22:21:08.874  4087  4124 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@6878126
,03-30 22:21:08.879   823  2549 W ActivityManager: Force removing ActivityRecord{735af1f u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t18}: app died, no saved state
,03-30 22:21:08.881   823  1236 I WindowState: WIN DEATH: Window{3a49e183 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
03-30 22:21:08.881   823  1236 W InputDispatcher: Attempted to unregister already unregistered input channel '3a49e183 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
,03-30 22:21:08.910  4087  4124 W Documents: Failed to load some roots from com.google.android.apps.docs.storage: android.os.DeadObjectException
03-30 22:21:08.911  4087  4124 D Documents: Update found 6 roots in 756ms
,03-30 22:21:09.082  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:09.085  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-30 22:21:09.095  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database,
,03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:09.097  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-30 22:21:09.137  1239  1754 I art     : Explicit concurrent mark sweep GC freed 29141(2MB) AllocSpace objects, 9(803KB) LOS objects, 37% free, 26MB/42MB, paused 1.950ms total 52.152ms
,03-30 22:21:09.142  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
,03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:09.146  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,03-30 22:21:09.154  1239  4170 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
,03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: 	,at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: 	,at com.google.android.gms.common.service.g.run(SourceFile:178)
03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 22:21:09.156  1239  4170 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818),
,03-30 22:21:11.509  1526  4180 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-30 22:21:11.533  1239  1239 I ConfigService: onDestroy
,03-30 22:21:11.929   823  1278 E QMI_FW  : xport_send: Sendto failed for port 4608
,03-30 22:21:11.929   823  1278 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1,
03-30 22:21:11.929   823  1278 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1658545427
03-30 22:21:11.929   823  1278 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
03-30 22:21:11.929   823  1278 E QMI_FW  : xport_send: Sendto failed for port 4608,
03-30 22:21:11.929   823  1278 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-30 22:21:11.929   823  1278 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-30 22:21:11.929   823  1278 E QMI_FW  : xport_send: Sendto failed for port 4608
03-30 22:21:11.929   823  1278 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-30 22:21:11.929   823  1278 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02
,03-30 22:21:11.930   823  1278 E QMI_FW  : xport_send: Sendto failed for port 4608
03-30 22:21:11.930   823  1278 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-30 22:21:11.930   823  1278 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02,
03-30 22:21:11.930   823  1278 E QMI_FW  : xport_send: Sendto failed for port 4608
03-30 22:21:11.930   823  1278 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
,03-30 22:21:11.930   823  1278 E LocSvc_api_v02: E/locClientRegisterEventMask:1552] status eLOC_CLIENT_FAILURE_INTERNAL
03-30 22:21:11.936   279   319 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-30 22:21:11.942   870   870 E kickstart: ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
,03-30 22:21:11.942   870   870 E kickstart: ERROR: function: sahara_main:1143 Sahara protocol error
03-30 22:21:11.942   870   870 E kickstart: ERROR: function: main:268 Uploading  Image using Sahara protocol failed
03-30 22:21:11.942   870   870 I kickstart: STATUS: Wrote to /sys/power/wake_unlock,

```
