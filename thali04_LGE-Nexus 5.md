#### Test 72145431744cc2c_thali04_LGE-Nexus 5 Logs


```
--------- beginning of main
07-12 11:36:35.913  2378  2378 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(17227): Beginning daily hygiene, foreground = false
,07-12 11:36:36.053  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-12 11:36:36.099  2378  2378 W Finsky  : [1] com.google.android.finsky.services.n.a(313): Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
--------- beginning of system
07-12 11:36:36.104   793   896 D WifiService: New client listening to asynchronous messages
07-12 11:36:36.105  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-12 11:36:36.108  1400  2939 W EventLoggerService: Unable to send logs
07-12 11:36:36.108  1400  2939 W EventLoggerService: com.google.android.apps.gsa.shared.exception.GsaIOException: Error code: 262160 | The connection was not attempted due to lack of network connectivity.
07-12 11:36:36.108  1400  2939 W EventLoggerService: 	at com.google.android.apps.gsa.search.core.j.a.c(AbstractHttpEngine.java:309)
07-12 11:36:36.108  1400  2939 W EventLoggerService: 	at com.google.android.apps.gsa.search.core.j.a.a(AbstractHttpEngine.java:94)
07-12 11:36:36.108  1400  2939 W EventLoggerService: 	at com.google.android.apps.gsa.shared.io.k.a(HttpHelper.java:209)
07-12 11:36:36.108  1400  2939 W EventLoggerService: 	at com.google.android.apps.gsa.speech.i.b.a(S3LogSender.java:104)
07-12 11:36:36.108  1400  2939 W EventLoggerService: 	at com.google.android.apps.gsa.speech.i.b.br(S3LogSender.java:79)
07-12 11:36:36.108  1400  2939 W EventLoggerService: 	at com.google.android.apps.gsa.eventlogger.EventLoggerService.a(EventLoggerService.java:575)
07-12 11:36:36.108  1400  2939 W EventLoggerService: 	at com.google.android.apps.gsa.eventlogger.EventLoggerService.i(EventLoggerService.java:320)
07-12 11:36:36.108  1400  2939 W EventLoggerService: 	at com.google.android.apps.gsa.eventlogger.EventLoggerService.gB(EventLoggerService.java:245)
07-12 11:36:36.108  1400  2939 W EventLoggerService: 	at com.google.android.apps.gsa.eventlogger.EventLoggerService.onHandleIntent(EventLoggerService.java:236)
07-12 11:36:36.108  1400  2939 W EventLoggerService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-12 11:36:36.108  1400  2939 W EventLoggerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:36.108  1400  2939 W EventLoggerService: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:36.108  1400  2939 W EventLoggerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:36:36.111  1400  2939 W ErrorReporter: reportError [type: 211, code: 262160]: Error code: 262160 | The connection was not attempted due to lack of network connectivity.
07-12 11:36:36.120  2378  2378 W Finsky  : [1] com.google.android.finsky.services.q.a(413): Self-update check failed with error: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
07-12 11:36:36.153   793  1328 I ActivityManager: Start proc 2976:com.google.android.gms:car/u0a8 for service com.google.android.gms/.car.CarService
07-12 11:36:36.156  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-12 11:36:36.165   793   887 I PowerManagerService: Waking up from sleep (uid 1000)...
07-12 11:36:36.166   793   813 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-12 11:36:36.167   793   793 V KeyguardServiceDelegate: onStartedWakingUp()
07-12 11:36:36.173   793   813 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@ca46bf2)
07-12 11:36:36.175   793   895 D WifiConfigStore: Retrieve network priorities after PNO.
07-12 11:36:36.175   793   895 E WifiStateMachine:  Fail to set up pno, want false now false
07-12 11:36:36.175   200   830 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-12 11:36:36.182  1240  1240 I Keyboard.Facilitator: onFinishInput()
07-12 11:36:36.194   793  1295 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-12 11:36:36.210  1739  1739 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver }.
07-12 11:36:36.213  1277  1383 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
07-12 11:36:36.213  1277  1383 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
07-12 11:36:36.224  1277  1383 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
07-12 11:36:36.225  1277  1634 D BrcmNfcJni: RoutingManager::commitRouting
07-12 11:36:36.225  1277  1383 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
07-12 11:36:36.239  1277  1634 D NfcService: Discovery configuration equal, not updating.
07-12 11:36:36.254  1916  1927 E ANDR-PERF-LOCK: Failed to reset optimization for resource: 4 level: 0
07-12 11:36:36.254   793   811 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
07-12 11:36:36.255   192   192 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6ae4000
07-12 11:36:36.255   192   192 D qdhwcomposer: hwc_blank: Unblanking display: 0
07-12 11:36:36.266  2378  2378 W Finsky  : [1] com.google.android.finsky.j.ac.a(562): Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
07-12 11:36:36.270  1400  2995 I MicroRecognitionRnrImpl: Starting detection.
07-12 11:36:36.271  1400  2996 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@d3fc813
07-12 11:36:36.274   200  2998 I AudioFlinger: AudioFlinger's thread 0xb2700000 ready to run
07-12 11:36:36.280  2976  2976 I MultiDex: VM with version 2.1.0 has multidex support
07-12 11:36:36.280  2976  2976 I MultiDex: install
07-12 11:36:36.280  2976  2976 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-12 11:36:36.283  1400  2996 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@d3fc813
07-12 11:36:36.292   200  2998 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
07-12 11:36:36.292   200  2998 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
07-12 11:36:36.292   200  2998 D         : Failed to fetch the lookup information of the device 0000003E 
07-12 11:36:36.292   200  2998 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
07-12 11:36:36.292   200  2998 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
07-12 11:36:36.297   200  2998 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
07-12 11:36:36.315  2976  2976 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
07-12 11:36:36.328  2976  2976 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-12 11:36:36.328  2976  2976 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
07-12 11:36:36.332  2976  2976 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
07-12 11:36:36.361  2976  2976 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-12 11:36:36.370  2976  2976 D ChimeraCfgMgr: Reading stored module config
07-12 11:36:36.381  1400  1400 I HotwordWorkerImpl: onReady
07-12 11:36:36.403   793   813 I DisplayPowerController: Unblocked screen on after 236 ms
07-12 11:36:36.403   793   813 V KeyguardServiceDelegate: onScreenTurnedOn()
07-12 11:36:36.437  2976  2976 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
07-12 11:36:36.437  2976  2976 D CAR.SERVICE: onBind
07-12 11:36:36.438  2976  2976 D CAR.SERVICE: CSB onClientsConnected
07-12 11:36:36.439  2976  2976 D CAR.TEL.Service: Binding to InCallService
07-12 11:36:36.443   793   803 W ActivityManager: Unable to start service Intent { act=local_action cmp=com.google.android.gms/.car.InCallService2 } U=0: not found
07-12 11:36:36.443  2976  2976 E CAR.TEL.Service: Failed to bind to InCallService
07-12 11:36:36.444  2976  3002 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
07-12 11:36:36.490   192   192 D qdhwcomposer: hwc_blank: Done unblanking display: 0
07-12 11:36:36.490   793   911 D SurfaceControl: Excessive delay in setPowerMode(): 235ms
07-12 11:36:36.502  2976  2986 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
07-12 11:36:36.502  2976  2986 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
07-12 11:36:36.508  2976  2986 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000003/n/armeabi
07-12 11:36:36.509  2976  2986 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
07-12 11:36:36.510  2976  2986 D ChimeraFileApk: Classloading successful. Optimized code found.
07-12 11:36:36.512  2976  2986 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
07-12 11:36:36.572  2976  2986 D GoogleCertificatesImpl: Fetched 163 Google release certificates
07-12 11:36:36.575  2976  2986 D CAR.SERVICE: Package validated; name: com.android.vending
07-12 11:36:36.576  2976  2986 D CAR.SERVICE: Android Auto doesn't have car home but we  have at least on alias in default or enabled state. Nothing to do.
07-12 11:36:36.688  2958  2958 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 11:36:36.692  2958  2958 D AndroidRuntime: CheckJNI is OFF
07-12 11:36:36.703  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-12 11:36:36.728  2958  2958 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 11:36:36.729  2378  2378 W Finsky  : [1] com.google.android.finsky.autoupdate.t.a(243): Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
07-12 11:36:36.734  2378  2378 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(590): Logging device features
07-12 11:36:36.760  2378  2378 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(57): Cancelling accelerated self-Update check
07-12 11:36:36.765  2378  2378 W InstanceID/Rpc: Found 10008
07-12 11:36:36.765  2958  2958 I Radio-JNI: register_android_hardware_Radio DONE
07-12 11:36:36.770  2378  2378 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(783): Scheduling new run in 791 minutes (failures=5)
07-12 11:36:36.784  2958  2958 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-12 11:36:36.787   793  1281 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-12 11:36:36.802  1400  1413 W SearchService: Abort, client detached.
07-12 11:36:36.805  1400  1400 I HotwordDetector: Closing mic
07-12 11:36:36.806  1400  1688 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d3fc813
07-12 11:36:36.806  1400  2996 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-12 11:36:36.810  2958  2958 D AndroidRuntime: Shutting down VM
07-12 11:36:36.834   793   804 I ActivityManager: Start proc 3023:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-12 11:36:36.843  1739  1751 D DeviceConnectionService: client connected with version: 8486000
07-12 11:36:36.859  1739  1739 D WearableService: callingUid 10008, callindPid: 1739
07-12 11:36:36.869  2378  3034 I Finsky  : [220] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
07-12 11:36:36.869   200  2998 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-12 11:36:36.870   200  2998 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
07-12 11:36:36.875  1400  1690 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-12 11:36:36.876  1400  2995 I MicroRecognitionRnrImpl: Detection finished
07-12 11:36:36.876  2378  2410 I PlayCommon: [207] com.google.android.play.a.ak.a(33603): Starting to flush logs
07-12 11:36:36.888  2378  2378 E Finsky  : [1] com.google.android.finsky.wear.bk.a(752): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
07-12 11:36:36.889  2378  2378 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6355): Dropping command=hygiene due to Gms not connected
07-12 11:36:36.900  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-12 11:36:36.910  3023  3023 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-12 11:36:36.919  2378  2410 I PlayCommon: [207] com.google.android.play.a.ak.a(33613): Log flushed by 0 successful uploads
07-12 11:36:36.940  3023  3023 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9090-9093)
07-12 11:36:36.940  3023  3023 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:36:36.959  3023  3023 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bda17c5}
07-12 11:36:36.959  3023  3023 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:36:36.959  3023  3023 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 11:36:36.965  3023  3023 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-12 11:36:36.966  3023  3023 E SysUtils: ApplicationContext is null in ApplicationStatus
07-12 11:36:36.971  3023  3040 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
07-12 11:36:36.975  3023  3023 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-12 11:36:36.980  3023  3023 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 11:36:36.980  3023  3023 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 11:36:36.980  3023  3023 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
07-12 11:36:37.021   793   810 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33a60ab:true
,07-12 11:36:37.127  3023  3023 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 11:36:37.137  3023  3023 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-12 11:36:37.181  3023  3062 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-12 11:36:37.200  3023  3049 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-12 11:36:37.219  3023  3062 I OpenGLRenderer: Initialized EGL, version 1.4
,07-12 11:36:37.248  1240  1240 I Keyboard.Facilitator: onFinishInput()
,07-12 11:36:37.270   793   811 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +447ms
,07-12 11:36:37.361  3023  3023 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3023
,07-12 11:36:37.466  3023  3023 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-12 11:36:37.628   793   964 I ActivityManager: Killing 1418:com.google.android.gm/u0a70 (adj 15): empty #17
,07-12 11:36:37.633  3023  3066 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1643574992
,07-12 11:36:37.646  3023  3066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 11:36:37.646  3023  3066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 11:36:37.646  3023  3066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 11:36:37.646  3023  3066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 11:36:37.646  3023  3066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-12 11:36:37.647  3023  3066 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de57b00 added. We now have 1 listener(s)
07-12 11:36:37.649  3023  3066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:AE:67
,07-12 11:36:37.651  3023  3066 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
,07-12 11:36:37.651  3023  3066 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 11:36:37.651  3023  3066 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-12 11:36:37.656  3023  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 11:36:37.656  3023  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 11:36:37.656  3023  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 11:36:37.656  3023  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:AE:67
07-12 11:36:37.656  3023  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 11:36:37.656  3023  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 11:36:37.656  3023  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 11:36:37.656  3023  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 11:36:37.656  3023  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 11:36:37.656  3023  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 11:36:37.656  3023  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 11:36:37.656  3023  3066 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f981edf added. We now have 1 listener(s)
,07-12 11:36:37.656  3023  3066 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 11:36:37.662   793   896 D WifiService: New client listening to asynchronous messages
,07-12 11:36:37.662  3023  3066 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-12 11:36:37.663  3023  3066 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-12 11:36:37.664  3023  3066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 11:36:37.664  3023  3066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 11:36:37.664  3023  3066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 11:36:37.664  3023  3066 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-12 11:36:37.691  3023  3066 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 11:36:37.691  3023  3066 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:AE:67
,07-12 11:36:37.693  3023  3066 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:37.693  3023  3066 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:36:37.693  3023  3066 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:37.693  3023  3066 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:37.693  3023  3066 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:37.693  3023  3066 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:37.693  3023  3066 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:37.693  3023  3066 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:37.693  3023  3066 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:37.693  3023  3066 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 11:36:37.693  3023  3066 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 11:36:37.694  3023  3066 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-12 11:36:37.792  3023  3023 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 11:36:38.514  3023  3080 W jxcore-log: Initializing JXcore engine
,07-12 11:36:38.514  3023  3080 W jxcore-log: JXcore engine is ready
,07-12 11:36:38.540  3080  3080 W Thread-250: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[8565]" dev="sockfs" ino=8565 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-12 11:36:38.540  3080  3080 W Thread-250: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-12 11:36:38.540  3080  3080 W Thread-250: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17628]" dev="sockfs" ino=17628 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-12 11:36:38.566  3023  3080 W jxcore-log: Starting JXcore engine
,07-12 11:36:38.648  3023  3080 W jxcore-log: Platform android
07-12 11:36:38.648  3023  3080 W jxcore-log: 
07-12 11:36:38.648  3023  3080 W jxcore-log: Process ARCH arm
07-12 11:36:38.648  3023  3080 W jxcore-log: 
,07-12 11:36:38.837  3023  3080 I jxcore-log: JXcore Cordova bridge is ready!
07-12 11:36:38.837  3023  3080 I jxcore-log: 
,07-12 11:36:38.837  3023  3080 W jxcore-log: JXcore engine is started
,07-12 11:36:38.841  3023  3066 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 11:36:38.843  3023  3023 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 11:36:39.555   793   964 I ActivityManager: Killing 2248:com.google.android.youtube/u0a80 (adj 15): empty #17
,07-12 11:36:41.035   793   803 I ActivityManager: Killing 2360:com.google.android.deskclock/u0a38 (adj 15): empty #17
,07-12 11:36:41.649  2976  2976 D CAR.SERVICE: onUnbind
,07-12 11:36:41.649  2976  2976 D CAR.SERVICE: CSB onClientsDisconnected
07-12 11:36:41.649  2976  2976 D CAR.SERVICE: tearDown
07-12 11:36:41.649  2976  2976 D CAR.SERVICE: tearDownCarState
07-12 11:36:41.649  2976  2976 D CAR.SERVICE: Skip, car not connected.
07-12 11:36:41.649  2976  2976 D CAR.SERVICE: tearDownClientState
,07-12 11:36:41.650  2976  2976 D CAR.SERVICE: requestStop
,07-12 11:36:41.653  2976  2976 D CAR.SERVICE: onDestroy
,07-12 11:36:41.654  2976  2976 D CAR.SERVICE: tearDown
,07-12 11:36:41.654  2976  2976 D CAR.SERVICE: tearDownCarState
07-12 11:36:41.654  2976  2976 D CAR.SERVICE: Skip, car not connected.
07-12 11:36:41.654  2976  2976 D CAR.SERVICE: tearDownClientState
,07-12 11:36:41.654  2976  2976 D CAR.SERVICE: requestStop
,07-12 11:36:41.667  2976  2976 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.CarCallService@147fb0d that was originally bound here
07-12 11:36:41.667  2976  2976 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.CarCallService@147fb0d that was originally bound here
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1092)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:986)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1303)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1286)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at irv.a(:com.google.android.gms:120)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at irv.a(:com.google.android.gms:137)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at com.google.android.gms.car.CarCallService.h(:com.google.android.gms:76)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at com.google.android.gms.car.CarCallService.<init>(:com.google.android.gms:64)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at fgl.i(:com.google.android.gms:551)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:163)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:160)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2904)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at android.app.ActivityThread.-wrap2(ActivityThread.java)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1432)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:41.667  2976  2976 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-12 11:36:41.669   793  1281 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@ec60605
,07-12 11:36:46.881  1400  3099 W EventLoggerService: Unable to send logs
07-12 11:36:46.881  1400  3099 W EventLoggerService: com.google.android.apps.gsa.shared.exception.GsaIOException: Error code: 262160 | The connection was not attempted due to lack of network connectivity.
07-12 11:36:46.881  1400  3099 W EventLoggerService: 	at com.google.android.apps.gsa.search.core.j.a.c(AbstractHttpEngine.java:309)
07-12 11:36:46.881  1400  3099 W EventLoggerService: 	at com.google.android.apps.gsa.search.core.j.a.a(AbstractHttpEngine.java:94)
07-12 11:36:46.881  1400  3099 W EventLoggerService: 	at com.google.android.apps.gsa.shared.io.k.a(HttpHelper.java:209)
07-12 11:36:46.881  1400  3099 W EventLoggerService: 	at com.google.android.apps.gsa.speech.i.b.a(S3LogSender.java:104)
07-12 11:36:46.881  1400  3099 W EventLoggerService: 	at com.google.android.apps.gsa.speech.i.b.br(S3LogSender.java:79)
07-12 11:36:46.881  1400  3099 W EventLoggerService: 	at com.google.android.apps.gsa.eventlogger.EventLoggerService.a(EventLoggerService.java:575)
07-12 11:36:46.881  1400  3099 W EventLoggerService: 	at com.google.android.apps.gsa.eventlogger.EventLoggerService.i(EventLoggerService.java:320)
07-12 11:36:46.881  1400  3099 W EventLoggerService: 	at com.google.android.apps.gsa.eventlogger.EventLoggerService.gB(EventLoggerService.java:245)
07-12 11:36:46.881  1400  3099 W EventLoggerService: 	at com.google.android.apps.gsa.eventlogger.EventLoggerService.onHandleIntent(EventLoggerService.java:236)
07-12 11:36:46.881  1400  3099 W EventLoggerService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-12 11:36:46.881  1400  3099 W EventLoggerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:46.881  1400  3099 W EventLoggerService: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:46.881  1400  3099 W EventLoggerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:36:46.882  1400  3099 W ErrorReporter: reportError [type: 211, code: 262160]: Error code: 262160 | The connection was not attempted due to lack of network connectivity.
,07-12 11:36:48.831  3023  3080 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-12 11:36:48.831  3023  3080 I jxcore-log: 
07-12 11:36:48.833  3023  3080 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-12 11:36:48.833  3023  3080 I jxcore-log: 
,07-12 11:36:48.834  3023  3080 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:48.834  3023  3080 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:36:48.834  3023  3080 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:48.834  3023  3080 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:48.834  3023  3080 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:48.834  3023  3080 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:48.834  3023  3080 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:48.834  3023  3080 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:48.834  3023  3080 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 11:36:48.835  3023  3080 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:48.835  3023  3080 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:36:48.836  3023  3080 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-12 11:36:48.836  3023  3080 I jxcore-log: 
,07-12 11:36:48.837  3023  3080 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-12 11:36:48.837  3023  3080 I jxcore-log: 
,07-12 11:36:49.174  3023  3080 I jxcore-log: Unit Test app is loaded
07-12 11:36:49.174  3023  3080 I jxcore-log: 
,07-12 11:36:49.179  3023  3080 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 11:36:49.179  3023  3080 I jxcore-log: 
,07-12 11:36:49.182  3023  3023 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-12 11:36:49.183   793  1330 D WifiService: setWifiEnabled: true pid=3023, uid=10000
07-12 11:36:49.183   793  1330 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-12 11:36:49.187   196   788 D SoftapController: Softap fwReload - Ok
07-12 11:36:49.190  3023  3080 I jxcore-log: My device name is: LGE-Nexus 5
07-12 11:36:49.190  3023  3080 I jxcore-log: 
07-12 11:36:49.192   196   788 D CommandListener: Setting iface cfg
07-12 11:36:49.192   196   788 D CommandListener: Trying to bring down wlan0
07-12 11:36:49.197   196   788 D CommandListener: Clearing all IP addresses on wlan0
,07-12 11:36:49.200   793   895 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-12 11:36:49.209   793   810 I ActivityManager: Start proc 3108:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-12 11:36:49.368  3108  3108 D AdapterServiceConfig: Adding HeadsetService
,07-12 11:36:49.368  3108  3108 D AdapterServiceConfig: Adding A2dpService
07-12 11:36:49.368  3108  3108 D AdapterServiceConfig: Adding HidService
07-12 11:36:49.368  3108  3108 D AdapterServiceConfig: Adding HealthService
07-12 11:36:49.369  3108  3108 D AdapterServiceConfig: Adding PanService
07-12 11:36:49.369  3108  3108 D AdapterServiceConfig: Adding GattService
07-12 11:36:49.369  3108  3108 D AdapterServiceConfig: Adding BluetoothMapService
,07-12 11:36:49.389   793   810 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5a546b2:true
,07-12 11:36:49.390  3108  3108 D BluetoothAdapterState: make() - Creating AdapterState
,07-12 11:36:49.392  3108  3131 I BluetoothAdapterState: Entering OffState
07-12 11:36:49.392  3108  3108 I bt_bluedroid: init
,07-12 11:36:49.408  3108  3132 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-12 11:36:49.413  3108  3132 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-12 11:36:49.413  3108  3132 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 11:36:49.414  3108  3132 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-12 11:36:49.414  3108  3108 I bt_bluedroid: get_profile_interface socket
,07-12 11:36:49.417  3108  3136 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-12 11:36:49.418  3108  3136 D BluetoothAdapterProperties: Name is: Nexus 5
,07-12 11:36:49.420  3108  3108 I bt_bluedroid: get_profile_interface sdp
,07-12 11:36:49.423  3108  3118 I bt_bluedroid: config_hci_snoop_log
,07-12 11:36:49.424   793   810 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
,07-12 11:36:49.432  3108  3131 D BluetoothAdapterState: Current state: OFF, message: 0
,07-12 11:36:49.433  3108  3131 D BluetoothAdapterProperties: Setting state to 14
,07-12 11:36:49.433  3108  3131 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-12 11:36:49.435  3108  3131 D BluetoothBondStateMachine: make
,07-12 11:36:49.437  3108  3138 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-12 11:36:49.438  3108  3131 I BluetoothAdapterState: Entering PendingCommandState
,07-12 11:36:49.439  3108  3108 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-12 11:36:49.441  3108  3108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a02e27
07-12 11:36:49.441  3108  3108 D BtGatt.DebugUtils: handleDebugAction() action=null
07-12 11:36:49.441  3108  3108 D BtGatt.GattService: Received start request. Starting profile...
07-12 11:36:49.441  3108  3108 D BtGatt.GattService: start()
07-12 11:36:49.441  3108  3108 I bt_bluedroid: get_profile_interface gatt
,07-12 11:36:49.442  3108  3108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a02e27
07-12 11:36:49.442  3108  3108 D BtGatt.AdvertiseManager: advertise manager created
,07-12 11:36:49.446  3108  3108 V BluetoothAdapterState: isTurningOff()=false
,07-12 11:36:49.446  3108  3108 V BluetoothAdapterState: isTurningOn()=false
07-12 11:36:49.446  3108  3108 V BluetoothAdapterState: isBleTurningOn()=true
,07-12 11:36:49.448  3108  3108 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 11:36:49.449  3108  3131 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-12 11:36:49.449  3108  3131 I bt_bluedroid: enable
07-12 11:36:49.449  3108  3132 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-12 11:36:49.451  3108  3132 I bt_hci  : start_up
,07-12 11:36:49.456  3108  3132 I bt_vendor: alloc value 0xb39f2631
07-12 11:36:49.456  3108  3132 I bt_vendor: init
07-12 11:36:49.456  3108  3132 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-12 11:36:49.456  3108  3132 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-12 11:36:49.498  3108  3132 D bt_hci  : start_up starting async portion
07-12 11:36:49.498  3108  3141 I bt_hci  : event_finish_startup
07-12 11:36:49.498  3108  3141 I bt_hci_h4: hal_open
07-12 11:36:49.498  3108  3141 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-12 11:36:49.501  3108  3141 I bt_userial_vendor: device fd = 49 open
,07-12 11:36:49.583  3108  3141 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-12 11:36:49.614  3108  3141 D bt_hwcfg: Chipset BCM4335C0
,07-12 11:36:49.614  3108  3141 D bt_hwcfg: Target name = [BCM4335C0]
07-12 11:36:49.614  3108  3141 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-12 11:36:49.947  3108  3141 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-12 11:36:49.948  3108  3141 D bt_hwcfg: Settlement delay -- 100 ms
07-12 11:36:49.948  3108  3141 I bt_hwcfg: Setting fw settlement delay to 100 
,07-12 11:36:49.962   793   895 D wifi    : set interface wlan0 flags (UP)
,07-12 11:36:49.963   793   895 I WifiHAL : Initializing wifi
,07-12 11:36:49.963   793   895 I WifiHAL : Creating socket
07-12 11:36:49.963   793   810 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-12 11:36:49.965   793   895 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-12 11:36:49.965   793   895 D wifi    : Did set static halHandle = 0x99803c70
07-12 11:36:49.965   793   895 D wifi    : halHandle = 0x99803c70, mVM = 0xb4d3c000, mCls = 0x150a
,07-12 11:36:49.965   793   895 D wifi    : array field set
07-12 11:36:49.965   793   895 I WifiNative-HAL: interface[0] = p2p0
07-12 11:36:49.965   793   895 I WifiNative-HAL: interface[1] = wlan0
07-12 11:36:49.969   793   895 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-12 11:36:49.970  3023  3023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 11:36:49.978   793  3149 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1719649168
,07-12 11:36:49.978   793  3149 D wifi    : waitForHalEvents called, vm = 0xb4d3c000, obj = 0x150a, env = 0x96eaf6e0
,07-12 11:36:49.986   793   806 I ActivityManager: Start proc 3151:com.android.settings/1000 for broadcast com.android.settings/.widget.SettingsAppWidgetProvider
,07-12 11:36:50.006  3151  3151 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-12 11:36:50.027   793   810 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c27832d:true
,07-12 11:36:50.035  3151  3151 D LocalBluetoothProfileManager: Adding local MAP profile
,07-12 11:36:50.038  3151  3151 D BluetoothMap: Create BluetoothMap proxy object
,07-12 11:36:50.042  3150  3150 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-12 11:36:50.054  3151  3151 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-12 11:36:50.063  3108  3141 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-12 11:36:50.063  3108  3141 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:AE:67
,07-12 11:36:50.072   793  2528 I ActivityManager: Start proc 3168:com.google.android.apps.gcs/u0a82 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-12 11:36:50.073   793  2528 I ActivityManager: Killing 2124:com.google.android.calendar/u0a31 (adj 15): empty #17
,07-12 11:36:50.093  3108  3141 I bt_hwcfg: vendor lib fwcfg completed
,07-12 11:36:50.093  3108  3141 I bt_vendor: firmware callback
07-12 11:36:50.093  3108  3141 I bt_hci  : firmware_config_callback
,07-12 11:36:50.096  3150  3150 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 11:36:50.144  3108  3182 I bt_btu  : btu_task pending for preload complete event
07-12 11:36:50.144  3108  3182 I bt_btu_task: Bluetooth chip preload is complete
07-12 11:36:50.144  3108  3182 I bt_btu  : btu_task received preload complete event
,07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_HCI
,07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_AVDT
07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_AVRC
07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_A2D
,07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_BNEP
07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_BTM
07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_GAP
,07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_PAN
07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_SDP
07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_GATT
07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_SMP
07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-12 11:36:50.151  3108  3182 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-12 11:36:50.158  3168  3168 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-12 11:36:50.158  3150  3150 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 11:36:50.194  3168  3168 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-12 11:36:50.197   793  1328 I ActivityManager: Killing 2433:com.google.android.music:main/u0a60 (adj 15): empty #17
,07-12 11:36:50.260   793   895 D WifiConfigStore: Loading config and enabling all networks 
07-12 11:36:50.261  3023  3023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:50.261  3023  3023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:50.261  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:50.261  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:50.261  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:36:50.261  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:50.261  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:50.261  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:50.261  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:50.262  3023  3023 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:50.262  3023  3023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:36:50.267   793   896 D WifiService: New client listening to asynchronous messages
,07-12 11:36:50.272   793   895 D WifiConfigStore: loaded 0 passpoint configs
07-12 11:36:50.272   793   895 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-12 11:36:50.273   793   895 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-12 11:36:50.274   793   895 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-12 11:36:50.274   793   895 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-12 11:36:50.274   793   895 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-12 11:36:50.275   793   895 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-12 11:36:50.275   793   895 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-12 11:36:50.277  2164  2164 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 11:36:50.277   793   895 D WifiNative-HAL: Setting external_sim to 1
07-12 11:36:50.277   793   895 D wifi    : setting dfs flag to true, 0x9bd7d858
,07-12 11:36:50.278   793   895 D WifiStateMachine: Setting OUI to DA-A1-19
07-12 11:36:50.278   793   895 D wifi    : setting scan oui 0x9bd7d858
07-12 11:36:50.278   793   895 D WifiHAL : Sending mac address OUI
,07-12 11:36:50.286   793   895 E native  : do suspend false
,07-12 11:36:50.290   793   895 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-12 11:36:50.290   793   793 D RttService: SCAN_AVAILABLE : 3
07-12 11:36:50.290   793   908 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:50.291   196   788 D CommandListener: Setting iface cfg
07-12 11:36:50.291   196   788 D CommandListener: Trying to bring up p2p0
07-12 11:36:50.291   793   894 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-12 11:36:50.298   793   895 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:36:50.299   793   894 D WifiNative-HAL: p2pGetDeviceAddress
,07-12 11:36:50.307   793   894 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,07-12 11:36:50.366  3108  3182 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39709b5
,07-12 11:36:50.366  3108  3182 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39709b5 
,07-12 11:36:50.371  3108  3136 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-12 11:36:50.371  3108  3136 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-12 11:36:50.372  3108  3136 D BluetoothAdapterProperties: Name is: Nexus 5
,07-12 11:36:50.374  3023  3023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 11:36:50.374  3108  3136 D BluetoothAdapterProperties: Scan Mode:20
,07-12 11:36:50.374  3108  3136 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-12 11:36:50.374  3108  3136 D bt_hci  : do_postload posting postload work item
,07-12 11:36:50.374  3108  3141 I bt_hci  : event_postload
,07-12 11:36:50.374  3108  3141 I bt_vendor: sco_config_cb
,07-12 11:36:50.374  3108  3141 I bt_hci  : sco_config_callback postload finished.
,07-12 11:36:50.375  3108  3136 D bt_bte_conf: Device ID record 1 : primary
,07-12 11:36:50.375  3108  3136 D bt_bte_conf:   vendorId            = 000f
,07-12 11:36:50.375  3108  3136 D bt_bte_conf:   vendorIdSource      = 0001
,07-12 11:36:50.375  3108  3136 D bt_bte_conf:   product             = 1200
,07-12 11:36:50.375  3108  3136 D bt_bte_conf:   version             = 1436
07-12 11:36:50.375  3108  3136 D bt_bte_conf:   clientExecutableURL = 
07-12 11:36:50.375  3108  3136 D bt_bte_conf:   serviceDescription  = 
07-12 11:36:50.375  3108  3136 D bt_bte_conf:   documentationURL    = 
07-12 11:36:50.375  3108  3136 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-12 11:36:50.375  3108  3132 D bt_stack_manager: event_start_up_stack finished
,07-12 11:36:50.376  3108  3131 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-12 11:36:50.376  3108  3131 D BluetoothAdapterProperties: Setting state to 15
07-12 11:36:50.376  3108  3131 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-12 11:36:50.377  3108  3141 I bt_vendor: low_power_mode_cb
07-12 11:36:50.377  3108  3131 I BluetoothAdapterState: Entering BleOnState
07-12 11:36:50.379  3108  3131 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-12 11:36:50.379  3108  3131 D BluetoothAdapterProperties: Setting state to 11
,07-12 11:36:50.379  3108  3131 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-12 11:36:50.383  3108  3108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a02e27
07-12 11:36:50.386  3108  3108 D HeadsetService: Received start request. Starting profile...
07-12 11:36:50.395  3108  3131 I BluetoothAdapterState: Entering PendingCommandState
07-12 11:36:50.398  3108  3108 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-12 11:36:50.400  3108  3108 D HeadsetStateMachine: make
07-12 11:36:50.410  3108  3108 D HeadsetStateMachine: max_hf_connections = 1
07-12 11:36:50.410  3108  3108 I bt_bluedroid: get_profile_interface handsfree
07-12 11:36:50.411  3108  3136 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-12 11:36:50.411  3108  3136 E bt_btif : btif_hf_upstreams_evt: Invalid index 44646
07-12 11:36:50.417  3108  3108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a02e27
,07-12 11:36:50.417   793   793 D BluetoothA2dp: Proxy object connected
,07-12 11:36:50.418  3108  3108 D A2dpService: Received start request. Starting profile...
07-12 11:36:50.419  3108  3108 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-12 11:36:50.419  3108  3108 I bt_bluedroid: get_profile_interface avrcp
07-12 11:36:50.425  3108  3108 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-12 11:36:50.425  3108  3108 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-12 11:36:50.425  3108  3108 D A2dpStateMachine: make
07-12 11:36:50.426  3108  3108 I bt_bluedroid: get_profile_interface a2dp
,07-12 11:36:50.428  3108  3136 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-12 11:36:50.430  3108  3108 I BluetoothHidServiceJni: classInitNative: succeeds
07-12 11:36:50.430  3108  3207 D A2dpStateMachine: Enter Disconnected: -2
,07-12 11:36:50.436  3108  3108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a02e27
,07-12 11:36:50.437   930   930 D BluetoothInputDevice: Proxy object connected
07-12 11:36:50.438   930   930 D HidProfile: Bluetooth service connected
07-12 11:36:50.438  3108  3108 D HidService: Received start request. Starting profile...
07-12 11:36:50.438  3108  3108 I bt_bluedroid: get_profile_interface hidhost
07-12 11:36:50.438  3108  3136 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb3952099
07-12 11:36:50.438  3108  3108 D HidService: setHidService(): set to: null
07-12 11:36:50.438  3108  3136 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-12 11:36:50.439  3151  3151 D BluetoothInputDevice: Proxy object connected
07-12 11:36:50.439  3151  3151 D HidProfile: Bluetooth service connected
07-12 11:36:50.439  3108  3108 I BluetoothHealthServiceJni: classInitNative: succeeds
07-12 11:36:50.440  3108  3108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a02e27
,07-12 11:36:50.441  3108  3108 D HealthService: Received start request. Starting profile...
,07-12 11:36:50.442  3108  3108 I bt_bluedroid: get_profile_interface health
,07-12 11:36:50.443  3108  3108 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-12 11:36:50.449  3108  3108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a02e27
,07-12 11:36:50.449   930   930 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 11:36:50.450   930   930 D PanProfile: Bluetooth service connected
07-12 11:36:50.450  3108  3108 D PanService: Received start request. Starting profile...
07-12 11:36:50.450  3151  3151 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 11:36:50.450  3108  3108 D BluetoothPanServiceJni: initializeNative(L110): pan
07-12 11:36:50.450  3108  3108 I bt_bluedroid: get_profile_interface pan
,07-12 11:36:50.450  3108  3136 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-12 11:36:50.453  3151  3151 D PanProfile: Bluetooth service connected
,07-12 11:36:50.456  3108  3108 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a02e27
,07-12 11:36:50.458   930   930 D BluetoothMap: Proxy object connected
07-12 11:36:50.458  3151  3151 D BluetoothMap: Proxy object connected
,07-12 11:36:50.458   930   930 D MapProfile: Bluetooth service connected
07-12 11:36:50.458  3151  3151 D MapProfile: Bluetooth service connected
07-12 11:36:50.458   930   930 D BluetoothMap: getConnectedDevices()
07-12 11:36:50.458  3151  3151 D BluetoothMap: getConnectedDevices()
07-12 11:36:50.459   930   930 D BluetoothMap: Bluetooth is Not enabled
07-12 11:36:50.460  3151  3151 D BluetoothMap: Bluetooth is Not enabled
07-12 11:36:50.460  3108  3108 D BluetoothMapService: Received start request. Starting profile...
07-12 11:36:50.460  3108  3108 D BluetoothMapService: start()
,07-12 11:36:50.462  3108  3108 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-12 11:36:50.462  3108  3108 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-12 11:36:50.462  3108  3108 D BluetoothMapAppObserver: createReceiver()
,07-12 11:36:50.464  3108  3108 D BluetoothMapAppObserver: initObservers()
,07-12 11:36:50.464  3108  3108 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-12 11:36:50.475  3108  3108 V BluetoothAdapterState: isTurningOff()=false
,07-12 11:36:50.475  3108  3108 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:50.475  3108  3108 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:36:50.475  3108  3205 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-12 11:36:50.475  3108  3108 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isTurningOff()=false
,07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isTurningOff()=false
,07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isTurningOff()=false
07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isTurningOff()=false
07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 11:36:50.477  3108  3108 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:36:50.478  3108  3108 V BluetoothAdapterState: isTurningOff()=false
,07-12 11:36:50.478  3108  3108 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:50.478  3108  3108 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:36:50.478  3108  3108 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:36:50.478  3108  3131 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-12 11:36:50.478  3108  3131 D BluetoothAdapterProperties: ScanMode =  20
07-12 11:36:50.478  3108  3131 D BluetoothAdapterProperties: State =  11
07-12 11:36:50.478  3108  3131 D BluetoothAdapterProperties: Setting state to 12
07-12 11:36:50.478  3108  3131 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-12 11:36:50.478  1305  1585 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:50.479  3108  3136 D BluetoothAdapterProperties: Scan Mode:21
07-12 11:36:50.479  3108  3136 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 11:36:50.479  3108  3131 I BluetoothAdapterState: Entering OnState
07-12 11:36:50.481   793   810 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:50.482   930   956 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 11:36:50.482   793   810 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 11:36:50.482   793   810 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:50.482  3023  3023 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-12 11:36:50.483  3151  3162 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 11:36:50.484  3151  3160 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 11:36:50.484   793   810 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:50.484   930  1417 D BluetoothMap: onBluetoothStateChange: up=true
07-12 11:36:50.485  3151  3162 D BluetoothMap: onBluetoothStateChange: up=true
07-12 11:36:50.485  3151  3160 D BluetoothPan: onBluetoothStateChange on: true
07-12 11:36:50.485   930  1415 D BluetoothPan: onBluetoothStateChange on: true
07-12 11:36:50.486  3023  3023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:50.486  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:50.486  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 11:36:50.486  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:36:50.486  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:36:50.486  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:50.486  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:50.486  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 11:36:50.486   930   948 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 11:36:50.487  3023  3023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 11:36:50.488   793   793 I Telecom : BluetoothPhoneService: queryPhoneState
07-12 11:36:50.489  3108  3108 D BluetoothMapService: onReceive
07-12 11:36:50.489  3108  3108 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:50.489  3108  3108 D BluetoothMapService: STATE_ON
,07-12 11:36:50.490  3108  3108 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-12 11:36:50.491  3108  3108 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-12 11:36:50.493   930  1134 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-12 11:36:50.495  3151  3151 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-12 11:36:50.496   930   930 D BluetoothA2dp: Proxy object connected
07-12 11:36:50.496   930  1134 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-12 11:36:50.497  3108  3108 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 11:36:50.499  3151  3151 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-12 11:36:50.499  3108  3108 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:36:50.500  3108  3108 D ObexServerSockets: Succeed to create listening sockets 
07-12 11:36:50.501  3108  3108 D ObexServerSockets0: startAccept()
07-12 11:36:50.501  3108  3108 D ObexServerSockets0: prepareForNewConnect()
,07-12 11:36:50.502  3108  3108 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-12 11:36:50.502  3108  3108 D BluetoothSdpJni: SDP Create record success - handle: 0
07-12 11:36:50.503  3108  3221 D ObexServerSockets0: Accepting socket connection...
,07-12 11:36:50.503  3108  3222 D ObexServerSockets0: Accepting socket connection...
,07-12 11:36:50.510  3108  3108 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-12 11:36:50.510  3108  3108 D ObexServerSockets0: prepareForNewConnect()
,07-12 11:36:50.514   793  1297 I ActivityManager: Start proc 3223:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-12 11:36:50.530  3151  3151 D BluetoothA2dp: Proxy object connected
,07-12 11:36:50.579  1305  1583 D BluetoothHeadset: Proxy object connected
,07-12 11:36:50.581   793   810 D BluetoothHeadset: Proxy object connected
,07-12 11:36:50.582   793   810 D BluetoothHeadset: Proxy object connected
,07-12 11:36:50.584   793   810 D BluetoothHeadset: Proxy object connected
,07-12 11:36:50.601   930  1417 D BluetoothHeadset: Proxy object connected
07-12 11:36:50.602   930   930 D HeadsetProfile: Bluetooth service connected
07-12 11:36:50.602  3151  3162 D BluetoothHeadset: Proxy object connected
,07-12 11:36:50.603  3151  3151 D HeadsetProfile: Bluetooth service connected
,07-12 11:36:50.678  3223  3223 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:50.678  3223  3223 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:50.678  3223  3223 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:50.678  3223  3223 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.r.e.b(PG:170)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:50.678  3223  3223 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.r.k.d(PG:583)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.r.e.b(PG:170)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:50.678  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:50.679  3223  3223 D StrictMode: StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:50.679  3223  3223 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:50.679  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:50.680  3223  3223 D StrictMode: StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:50.680  3223  3223 D StrictMode: StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:50.680  3223  3223 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:50.682   793  2529 I ActivityManager: Killing 1992:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-12 11:36:50.735  3223  3242 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
07-12 11:36:50.740  1739  1739 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-12 11:36:50.748   793   810 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6438b6e:true
07-12 11:36:50.749  1739  1739 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 11:36:50.754  3151  3151 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 11:36:50.765  3151  3151 D DockEventReceiver: finishStartingService: stopping service
,07-12 11:36:50.769   930   930 D BluetoothPbap: Proxy object connected
07-12 11:36:50.770   930   930 D PbapServerProfile: Bluetooth service connected
,07-12 11:36:50.773  3108  3258 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:36:50.774  3151  3151 D BluetoothPbap: Proxy object connected
07-12 11:36:50.774  3151  3151 D PbapServerProfile: Bluetooth service connected
,07-12 11:36:50.794  1739  1739 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-12 11:36:50.799  1739  3265 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-12 11:36:50.800  3108  3264 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:36:50.801  1739  1739 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-12 11:36:50.804  3108  3264 I BtOppRfcommListener: Accept thread started.
,07-12 11:36:50.822  1739  3265 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-12 11:36:51.593  2378  2413 I Finsky  : [210] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-12 11:36:51.660  2378  2413 I Finsky  : [210] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-12 11:36:51.661  2378  2378 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-12 11:36:51.912  3150  3150 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,07-12 11:36:51.912  3150  3150 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,07-12 11:36:51.924   793   895 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-12 11:36:51.925   793   895 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,07-12 11:36:51.925   793   895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 11:36:51.945   793   895 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,07-12 11:36:51.973   793   895 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,07-12 11:36:51.975  3150  3150 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
,07-12 11:36:52.061  3150  3150 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-12 11:36:52.091  3150  3150 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-12 11:36:52.091  3150  3150 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-12 11:36:52.093   793   895 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:36:52.105   793   895 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 11:36:52.105   793   895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-12 11:36:52.105   793   897 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-12 11:36:52.120   793   895 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 11:36:52.132   196   788 D CommandListener: Setting iface cfg
,07-12 11:36:52.140   793   895 D WifiStateMachine: Start Dhcp Watchdog 1
,07-12 11:36:52.154   793   897 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-12 11:36:52.154   793   897 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,07-12 11:36:52.155   793   895 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{1}, ntable=[]
,07-12 11:36:52.189   793  3283 D DhcpClient: Receive thread started
,07-12 11:36:52.266   793   895 E native  : do suspend false
,07-12 11:36:52.272   793  3275 D DhcpClient: Broadcasting DHCPDISCOVER
,07-12 11:36:52.280   793  3283 D DhcpClient: Received packet: 50:55:27:f0:fd:0b OFFER, ip /192.168.1.118, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 170794, domain null
,07-12 11:36:52.280   793  3275 D DhcpClient: Got pending lease: IP address 192.168.1.118/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 170794 seconds
,07-12 11:36:52.281   793  3275 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.118 serverid=192.168.1.1
,07-12 11:36:52.289   793  3283 D DhcpClient: Received packet: 50:55:27:f0:fd:0b ACK: your new IP /192.168.1.118, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
07-12 11:36:52.289   793  3275 D DhcpClient: Confirmed lease: IP address 192.168.1.118/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-12 11:36:52.290   196   788 D CommandListener: Setting iface cfg
,07-12 11:36:52.293   793   895 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{2}, ntable=[]
,07-12 11:36:52.295   793  3275 D DhcpClient: Scheduling renewal in 86399s
,07-12 11:36:52.299   793   895 D IpReachabilityMonitor: watch: iface{wlan0/21}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-12 11:36:52.300   793   895 D WifiConfigStore: No blacklist allowed without epno enabled
07-12 11:36:52.301   793   897 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-12 11:36:52.302   793   897 D ConnectivityService: Adding iface wlan0 to network 100
,07-12 11:36:52.317   793   895 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-12 11:36:52.346   793   897 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-12 11:36:52.347   793   897 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,07-12 11:36:52.348   793   897 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,07-12 11:36:52.350   793   897 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,07-12 11:36:52.351   793   897 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,07-12 11:36:52.360   793   897 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:52.365   793   897 D ConnectivityService: scheduleUnvalidatedPrompt 100
,07-12 11:36:52.365   793   897 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
07-12 11:36:52.365   793   897 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
07-12 11:36:52.365   793   897 D ConnectivityService:    accepting network in place of null
07-12 11:36:52.365   793   895 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-12 11:36:52.366   793   895 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 11:36:52.367   793   897 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.118/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -61]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 11:36:52.380   793  3274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=94518, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:36:52.407   196   788 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 11:36:52.438   196   788 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 11:36:52.440   793   897 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
07-12 11:36:52.443   793  3273 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:802::200e
07-12 11:36:52.446   793   897 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-12 11:36:52.446   793   897 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:36:52.449   793   897 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:52.452   793   810 D Tethering: MasterInitialState.processMessage what=3
,07-12 11:36:52.461  3023  3023 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:52.461  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:52.461  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 11:36:52.461  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:36:52.461  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:36:52.461  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 11:36:52.461  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 11:36:52.461  3023  3023 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 11:36:52.463  1400  1400 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-12 11:36:52.463  3023  3023 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-12 11:36:52.477   793  2529 I ActivityManager: Start proc 3303:com.android.chrome/u0a34 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-12 11:36:52.512   793  3273 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jul 2016 09:36:53 GMT], X-Android-Received-Millis=[1468316212511], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1468316212479]}
07-12 11:36:52.513   793   897 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-12 11:36:52.513   793   897 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
07-12 11:36:52.513   793   897 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-12 11:36:52.515   793   897 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-12 11:36:52.526   793  1266 D AlarmManagerService: Setting time of day to sec=1468316213
,07-12 11:36:53.139   793  1266 W AlarmManagerService: Unable to set rtc to 1468316213: Invalid argument
,07-12 11:36:53.153   793  3323 D GpsLocationProvider: NTP server returned: 1468316213139 (Tue Jul 12 11:36:53 GMT+02:00 2016) reference: 94665 certainty: 18 system time offset: -14
,07-12 11:36:53.153   793  3323 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,07-12 11:36:53.163  1613  3324 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-12 11:36:53.166   793   805 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 22252, reason: UserStart, SyncResult: databaseError: true stats []
,07-12 11:36:53.167   793   805 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 126651, reason: UserStart
,07-12 11:36:53.248  1613  3322 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-12 11:36:53.325  1613  1613 E ConnectivityChangeReceiver: Ignoring connectivity change
,07-12 11:36:53.337   793  1328 D ConnectivityService: listenForNetwork for Listen from uid/pid:10008/1613 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:36:53.437  1613  3326 W DriveInitializer: Awaiting to be initialized
,07-12 11:36:53.437  1613  3336 W DriveInitializer: Background init thread started
,07-12 11:36:53.471   793  1276 I ActivityManager: Start proc 3340:com.google.android.apps.photos/u0a65 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-12 11:36:53.516  3340  3340 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-12 11:36:53.528  1613  3353 I RemindersSync: Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=205:priority=5:group=main]
,07-12 11:36:53.571  2164  3338 I Babel   : connection state changed from UNKNOWN to CONNECTED
,07-12 11:36:53.591  1613  3336 W DriveInitializer: Background init thread ended
,07-12 11:36:53.616   793  2529 D WifiService: acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@10992f2}
,07-12 11:36:53.677  2857  3366 W Flag    : Duration spec must be at least 2 characters long
,07-12 11:36:53.823  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:53.824  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:53.834  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:54.045  1613  3382 I iu.SyncManager: SYNC; picasa accounts
,07-12 11:36:54.048  1613  1613 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,07-12 11:36:54.051  1613  1613 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-12 11:36:54.073   793   966 I ActivityManager: Start proc 3383:com.google.android.apps.magazines/u0a61 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-12 11:36:54.073  1613  3382 I iu.UploadsManager: num queued entries: 0
,07-12 11:36:54.074  1613  3382 I iu.UploadsManager: num updated entries: 0
07-12 11:36:54.075  1613  3382 I iu.SyncManager: NEXT; no task
,07-12 11:36:54.098  3383  3383 W System  : ClassLoader referenced unknown path: /data/app/com.google.android.apps.magazines-1/lib/arm
,07-12 11:36:54.141  3383  3383 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-12 11:36:54.141  3383  3383 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 11:36:54.141  3383  3383 I GAv4    :   adb logcat -s GAv4
,07-12 11:36:54.149  3383  3383 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:54.153  3383  3383 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:54.158  1739  3379 I GCM     : GCM config loaded
,07-12 11:36:54.164  3383  3406 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:54.243  3383  3383 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-12 11:36:54.295  3383  3383 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 5831-5836)
,07-12 11:36:54.296  3383  3383 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 11:36:54.305  3383  3383 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {86c7dcf}
,07-12 11:36:54.305  3383  3383 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:36:54.306  3383  3383 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 11:36:54.312  3383  3383 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 11:36:54.314  3383  3383 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-12 11:36:54.332  3383  3383 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-12 11:36:54.338  3383  3383 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 11:36:54.338  3383  3383 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 11:36:54.339  3383  3383 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-12 11:36:54.394  3383  3437 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-12 11:36:54.403  3383  3383 I NSApplication: Starting up...
,07-12 11:36:54.463   793  1330 I ActivityManager: Start proc 3444:com.google.android.calendar/u0a31 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,07-12 11:36:54.499  3444  3444 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm
,07-12 11:36:54.549  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-12 11:36:54.549  3023  3080 I jxcore-log: 
,07-12 11:36:54.554   793  2529 I ActivityManager: Start proc 3459:com.android.providers.calendar/u0a2 for content provider com.android.providers.calendar/.CalendarProvider2
,07-12 11:36:54.583  3459  3459 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm
,07-12 11:36:54.604  3459  3459 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@bda17c5(com.android.providers.calendar.CalendarProvider2@678551a)
,07-12 11:36:54.630   793  2528 I ActivityManager: Start proc 3476:com.qualcomm.timeservice/u0a76 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,07-12 11:36:54.634   793  2528 I ActivityManager: Killing 2486:android.process.acore/u0a4 (adj 15): empty #17
,07-12 11:36:54.673   793   804 D WifiService: releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@10992f2}
,07-12 11:36:54.750   793  1330 I ActivityManager: Killing 2809:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,07-12 11:36:54.780  3476  3476 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm
,07-12 11:36:54.797  3476  3476 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1468316214797
,07-12 11:36:54.797  3476  3476 D         : TimeServiceNative: User Time to be set is 1468316214797
07-12 11:36:54.797  3476  3476 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-12 11:36:54.797  3476  3476 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
07-12 11:36:54.797  3476  3476 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1468316214797
,07-12 11:36:54.797  3476  3476 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
07-12 11:36:54.797   219   618 D QC-time-services: Daemon: Connection accepted:time_genoff
07-12 11:36:54.797   219  3491 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1468316214797
07-12 11:36:54.797   219  3491 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1468316214797, operation = 0
07-12 11:36:54.798   219  3491 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/27/70 3:6:23
07-12 11:36:54.798   219  3491 D QC-time-services: Daemon:Value read from RTC seconds = 2257583000
07-12 11:36:54.798   219  3491 D QC-time-services: Daemon:new time 1468316214797 
,07-12 11:36:54.798   219  3491 D QC-time-services: Daemon: delta 1466058631797 genoff 1466058631797 
07-12 11:36:54.798   219  3491 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466058631797 to memory
07-12 11:36:54.798   219  3491 D QC-time-services: Daemon:Opening File: /data/system/time/ats_2
07-12 11:36:54.798   219  3491 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-12 11:36:54.807   219  3491 D QC-time-services: Updating the TOD offset
,07-12 11:36:54.807   219  3491 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466058631797 to memory
07-12 11:36:54.807   219  3491 D QC-time-services: Daemon:Opening File: /data/system/time/ats_1
07-12 11:36:54.807   219  3491 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-12 11:36:54.823   219  3491 D QC-time-services: Daemon:Update to modem bit set
,07-12 11:36:54.823   219  3491 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
07-12 11:36:54.823  3476  3476 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
07-12 11:36:54.823   219  3491 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1152351414797
,07-12 11:36:54.825   219   618 D QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,07-12 11:36:54.826   219   616 D QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,07-12 11:36:54.842  3444  3444 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-12 11:36:54.854   793  1330 I ActivityManager: Start proc 3492:com.google.android.deskclock/u0a38 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,07-12 11:36:54.855   793  1330 I ActivityManager: Killing 2824:com.android.musicfx/u0a15 (adj 15): empty #17
,07-12 11:36:54.968  3492  3492 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,07-12 11:36:54.986  3492  3492 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-12 11:36:54.986  3492  3492 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 11:36:54.986  3492  3492 I GAv4    :   adb logcat -s GAv4
,07-12 11:36:54.999  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-12 11:36:54.999  3023  3080 I jxcore-log: 
,07-12 11:36:55.000  3492  3492 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:55.005  3492  3492 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:55.008  3492  3508 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:55.012   793  2529 I ActivityManager: Killing 1850:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,07-12 11:36:55.026  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-12 11:36:55.026  3023  3080 I jxcore-log: 
,07-12 11:36:55.030  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-12 11:36:55.030  3023  3080 I jxcore-log: 
,07-12 11:36:55.046  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-12 11:36:55.046  3023  3080 I jxcore-log: 
07-12 11:36:55.049  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-12 11:36:55.049  3023  3080 I jxcore-log: 
,07-12 11:36:55.173   793  2528 I ActivityManager: Killing 2762:com.android.defcontainer/u0a5 (adj 15): empty #17
,07-12 11:36:55.320  1613  3514 I PeopleSync: onPerformSync() [5005f081]
,07-12 11:36:55.431  1613  3516 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,07-12 11:36:55.447  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:55.613  1613  3514 I PeopleSync: Setting subscription: result=true [5005f081]
,07-12 11:36:55.614  1613  3514 I PeopleSync: Starting sync, feed=null [5005f081]
,07-12 11:36:55.650  3459  3459 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
07-12 11:36:55.651  3459  3459 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-12 11:36:55.668  1613  1760 D NetworkUsageDbReporter: Started reporting usage
,07-12 11:36:55.723  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:55.724  1613  3514 I PeopleSync: Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,07-12 11:36:55.761  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 29453
,07-12 11:36:55.761  1613  1760 D NetworkUsageDbReporter: keeping row: 300
,07-12 11:36:55.762  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 80003
,07-12 11:36:55.762  1613  1760 D NetworkUsageDbReporter: keeping row: 290
07-12 11:36:55.762  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 5455
07-12 11:36:55.762  1613  1760 D NetworkUsageDbReporter: keeping row: 299
07-12 11:36:55.762  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 13554
07-12 11:36:55.762  1613  1760 D NetworkUsageDbReporter: keeping row: 289
,07-12 11:36:55.763  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 14483
,07-12 11:36:55.763  1613  1760 D NetworkUsageDbReporter: keeping row: 288
07-12 11:36:55.763  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 19912
07-12 11:36:55.763  1613  1760 D NetworkUsageDbReporter: keeping row: 298
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 5854
,07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: keeping row: 301
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 59590
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: keeping row: 287
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 8187
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: keeping row: 286
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 269749
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: keeping row: 285
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 4478
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: keeping row: 297
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 10133
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: keeping row: 296
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 15286
,07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: keeping row: 295
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 323720
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: keeping row: 294
07-12 11:36:55.764  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 105260
,07-12 11:36:55.766  1613  1760 D NetworkUsageDbReporter: keeping row: 293
,07-12 11:36:55.766  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 31984
07-12 11:36:55.766  1613  1760 D NetworkUsageDbReporter: keeping row: 292
07-12 11:36:55.766  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 12749
07-12 11:36:55.766  1613  1760 D NetworkUsageDbReporter: keeping row: 291
07-12 11:36:55.767  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 420655
07-12 11:36:55.767  1613  1760 D NetworkUsageDbReporter: keeping row: 284
07-12 11:36:55.767  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1575578
07-12 11:36:55.767  1613  1760 D NetworkUsageDbReporter: keeping row: 283
07-12 11:36:55.767  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1369
07-12 11:36:55.767  1613  1760 D NetworkUsageDbReporter: keeping row: 279
07-12 11:36:55.767  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1577
07-12 11:36:55.767  1613  1760 D NetworkUsageDbReporter: keeping row: 236
07-12 11:36:55.767  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 2246
07-12 11:36:55.767  1613  1760 D NetworkUsageDbReporter: keeping row: 232
,07-12 11:36:55.767  1613  1760 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 11312
07-12 11:36:55.767  1613  1760 D NetworkUsageDbReporter: keeping row: 251
,07-12 11:36:55.779   793   897 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:55.812  1613  1760 D NetworkUsageDbReporter: Finished reporting usage.
,07-12 11:36:55.885  1613  3543 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,07-12 11:36:55.885  1613  3543 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-12 11:36:56.004   793  1295 I ActivityManager: Start proc 3546:com.google.android.gms.unstable/u0a8 for service com.google.android.gms/.droidguard.DroidGuardService
,07-12 11:36:56.049  3546  3546 I MultiDex: VM with version 2.1.0 has multidex support
07-12 11:36:56.049  3546  3546 I MultiDex: install
07-12 11:36:56.049  3546  3546 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:36:56.070  3546  3546 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-12 11:36:56.080  3546  3546 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,07-12 11:36:56.080  3546  3546 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-12 11:36:56.084  3546  3546 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-12 11:36:56.115  3546  3546 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 11:36:56.130  3546  3546 D ChimeraCfgMgr: Reading stored module config
,07-12 11:36:56.201  3546  3564 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-12 11:36:56.233   200   200 D WVCdm   : Instantiating CDM.
,07-12 11:36:56.233   200  1068 I WVCdm   : CdmEngine::OpenSession
07-12 11:36:56.234   200  1068 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-12 11:36:56.244   200  1068 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-12 11:36:56.246   200  1068 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,07-12 11:36:56.246   200  1068 D DrmWidevineDash: Service_Initialize: starts!
,07-12 11:36:56.246   200  1068 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,07-12 11:36:56.246   200  1068 D QSEECOMAPI: : App is not loaded in QSEE
,07-12 11:36:56.268   200  1068 D QSEECOMAPI: : Loaded image: APP id = 3
,07-12 11:36:56.270   200  1068 D DrmWidevineDash: Service_Initialize: ends! returns 0
,07-12 11:36:56.270   200  1068 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb33a6000
07-12 11:36:56.270   200  1068 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb33a6000
,07-12 11:36:56.293   200  1068 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-12 11:36:56.293   200  1068 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-12 11:36:56.302   200  1068 D DrmWidevineDash: hlos api version =  10
,07-12 11:36:56.302   200  1068 D DrmWidevineDash: tz api version =  10,
07-12 11:36:56.302   200  1068 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-12 11:36:56.302   200  1068 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-12 11:36:56.332   200  1068 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-12 11:36:56.332   200  1068 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-12 11:36:56.332   200  1068 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb353f134
,07-12 11:36:56.337   200  1068 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-12 11:36:56.337   200  1068 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-12 11:36:56.337   200  1068 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb46122c8, dataLength=8
,07-12 11:36:56.343   200  1068 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-12 11:36:56.350   200  1068 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb2461c00, wrapped_rsa_key_length=1280
,07-12 11:36:56.357   200  1068 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,07-12 11:36:56.357   200  1068 I WVCdm   : CdmEngine::QueryKeyControlInfo
07-12 11:36:56.358   200   200 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,07-12 11:36:56.358   200   200 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-12 11:36:56.358   200   200 I WVCdm   : CdmEngine::GenerateKeyRequest
07-12 11:36:56.358   200   200 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb387fc00, idLength=0xbe85b00c
,07-12 11:36:56.389   200   200 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
07-12 11:36:56.389   200   200 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-12 11:36:56.411   200   200 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,07-12 11:36:56.411   200   200 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-12 11:36:56.411   200   200 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-12 11:36:56.411   200   200 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-12 11:36:56.416   200   200 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
07-12 11:36:56.416   200   200 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-12 11:36:56.421   200   200 D DrmWidevineDash: hlos api version =  10
07-12 11:36:56.421   200   200 D DrmWidevineDash: tz api version =  10
07-12 11:36:56.421   200   200 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-12 11:36:56.421   200   200 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-12 11:36:56.426   200   200 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
07-12 11:36:56.426   200   200 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-12 11:36:56.426   200   200 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-12 11:36:56.432   200   200 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,07-12 11:36:56.432   200   200 D WVCdm   : PrepareKeyRequest: nonce=2637855144
07-12 11:36:56.432   200   200 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4782000
07-12 11:36:56.432   200   200 D DrmWidevineDash: message_length=1639, signature=0xb5ff65c0, signature_length=3196432612
,07-12 11:36:56.523  1739  1739 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=34014aba-c4d8-4a37-bd8c-8d0f575d81d8
,07-12 11:36:56.539   200   200 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-12 11:36:56.540   200   830 I WVCdm   : CdmEngine::CloseSession
,07-12 11:36:56.540   200   830 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-12 11:36:56.545   200   830 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,07-12 11:36:56.545   200   830 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-12 11:36:56.555   200   830 D DrmWidevineDash: Service_Uninitialize: starts!
07-12 11:36:56.555   200   830 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-12 11:36:56.555   200   830 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-12 11:36:56.556   200   830 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-12 11:36:56.556   200   830 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-12 11:36:56.652  1739  1771 W GCoreFlp: No location to return for getLastLocation()
,07-12 11:36:56.688  1739  1796 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-12 11:36:56.694  1739  1777 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-12 11:36:56.767  1613  3569 D UdcContextInitService: registered all accounts: true
,07-12 11:36:56.821  3587  3587 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-12 11:36:56.862  3587  3587 I dex2oat : dex2oat took 41.155ms (threads: 4) arena alloc=200KB java alloc=63KB native alloc=1662KB free=1409KB
07-12 11:36:56.867  3546  3557 W System  : ClassLoader referenced unknown path: 
07-12 11:36:56.872  3546  3557 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-12 11:36:56.935  3546  3557 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-12 11:36:56.975  3546  3557 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,07-12 11:36:57.309  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-12 11:36:57.309  3023  3080 I jxcore-log: 
,07-12 11:36:57.320  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-12 11:36:57.320  3023  3080 I jxcore-log: 
,07-12 11:36:57.327  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-12 11:36:57.327  3023  3080 I jxcore-log: 
,07-12 11:36:57.401  1739  1777 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:36:57.405  1739  1777 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,07-12 11:36:57.413  1739  1777 V BaseAppContext: GmsRequestQueue started.
,07-12 11:36:57.490  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-12 11:36:57.490  3023  3080 I jxcore-log: 
,07-12 11:36:57.689  1739  1783 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-12 11:36:57.699  1739  3617 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-12 11:36:57.700  1739  3607 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-12 11:36:57.724  1739  3617 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-12 11:36:57.724  1739  3607 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-12 11:36:57.764  1739  3617 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-12 11:36:57.764  1739  3607 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-12 11:36:57.764  1739  3607 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-12 11:36:57.770  1739  3607 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:36:57.802  1613  3514 I PeopleSync: Sync finished, successful=true, took 2069ms
,07-12 11:36:57.828  1613  3514 I PeopleContactsSync: CP2 sync start [5005f081]
,07-12 11:36:57.842  1613  3514 I PeopleContactsSync: CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,07-12 11:36:57.845  1613  3514 I PeopleContactsSync: Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,07-12 11:36:57.861   793  1295 I ActivityManager: Start proc 3620:android.process.acore/u0a4 for content provider com.android.providers.contacts/.ContactsProvider2
,07-12 11:36:57.894  3620  3620 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,07-12 11:36:57.941  3620  3620 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,07-12 11:36:57.974  3620  3633 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,07-12 11:36:58.019   793  1328 I ActivityManager: Killing 2976:com.google.android.gms:car/u0a8 (adj 15): empty #17
,07-12 11:36:58.120  3620  3633 D ContactDirectoryManager: Found com.google.contacts.gal.provider
07-12 11:36:58.120  3620  3633 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,07-12 11:36:58.192   793  1330 I ActivityManager: Start proc 3638:com.google.android.gm.exchange/u0a69 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,07-12 11:36:58.219  1613  3514 I PeopleContactsSync: CP2 cleanup done, kept= duration=373 ms
,07-12 11:36:58.223  1613  3514 I PeopleContactsSync: ===CP2 sync finished, success=true, time=385,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,07-12 11:36:58.229  3638  3638 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,07-12 11:36:58.234   793  2529 I ActivityManager: Killing 1400:com.google.android.googlequicksearchbox:search/u0a22 (adj 15): empty #17
,07-12 11:36:58.261   793   896 D WifiService: Client connection lost with reason: 4
,07-12 11:36:58.265  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-12 11:36:58.265  3023  3080 I jxcore-log: 
,07-12 11:36:58.319  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-12 11:36:58.319  3023  3080 I jxcore-log: 
,07-12 11:36:58.325  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-12 11:36:58.325  3023  3080 I jxcore-log: 
,07-12 11:36:58.468   793   966 I ActivityManager: Start proc 3658:com.google.android.gm/u0a70 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,07-12 11:36:58.491   793  1281 I ActivityManager: Start proc 3669:com.google.process.gapps/u0a85 for content provider com.google.android.syncadapters.contacts/.GalProvider
,07-12 11:36:58.498   793  1276 I ActivityManager: Killing 3168:com.google.android.apps.gcs/u0a82 (adj 15): empty #17
,07-12 11:36:58.512  1613  3514 I PeopleSync: ***Sync finished***, duration: 3185 [5005f081]
,07-12 11:36:58.540  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-12 11:36:58.540  3023  3080 I jxcore-log: 
,07-12 11:36:58.564  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-12 11:36:58.564  3023  3080 I jxcore-log: 
07-12 11:36:58.568  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-12 11:36:58.568  3023  3080 I jxcore-log: 
,07-12 11:36:58.573  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-12 11:36:58.573  3023  3080 I jxcore-log: 
,07-12 11:36:58.588  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-12 11:36:58.588  3023  3080 I jxcore-log: 
,07-12 11:36:58.606  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-12 11:36:58.606  3023  3080 I jxcore-log: 
,07-12 11:36:58.690  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-12 11:36:58.690  3023  3080 I jxcore-log: 
07-12 11:36:58.694  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-12 11:36:58.694  3023  3080 I jxcore-log: 
,07-12 11:36:58.700   793  2528 I ActivityManager: Killing 3151:com.android.settings/1000 (adj 15): empty #17
,07-12 11:36:58.711  3658  3658 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,07-12 11:36:58.713   793   896 D WifiService: Client connection lost with reason: 4
,07-12 11:36:58.721  3023  3080 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-12 11:36:58.721  3023  3080 I jxcore-log: 
,07-12 11:36:58.730  3023  3080 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-12 11:36:58.732  3023  3080 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-12 11:36:58.732  3023  3080 I jxcore-log: 
,07-12 11:36:58.781  3023  3080 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 11:36:58.781  3023  3080 I jxcore-log: 
,07-12 11:36:58.782  3023  3080 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 11:36:58.782  3023  3080 I jxcore-log: 
,07-12 11:36:58.782  3023  3080 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 11:36:58.782  3023  3080 I jxcore-log: 
,07-12 11:36:58.782  3658  3686 I Gmail   : getAccountsCursor
,07-12 11:36:58.792  3658  3687 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,07-12 11:36:58.799  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:58.812  3669  3669 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,07-12 11:36:58.832  3669  3669 I GoogleHttpClient: GMS http client unavailable, use old client
,07-12 11:36:58.847  3620  3633 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,07-12 11:36:58.859   793  2528 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-12 11:36:58.861  3620  3633 I ContactDirectoryManager: Discovered 0 contact directories in 835ms
,07-12 11:36:58.865  3658  3658 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-12 11:36:58.867  3658  3695 I Gmail   : Observing account changes for notifications
,07-12 11:36:58.885  3638  3638 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-12 11:36:58.911  3658  3702 E Gmail   : Error finding the version of the Email provider.....
07-12 11:36:58.911  3658  3702 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-12 11:36:58.911  3658  3702 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
07-12 11:36:58.911  3658  3702 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
07-12 11:36:58.911  3658  3702 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-12 11:36:58.911  3658  3702 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-12 11:36:58.911  3658  3702 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:58.911  3658  3702 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:58.911  3658  3702 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:36:58.911  3658  3702 W EmailMigration: We do not support migrating this version of the Email provider.
,07-12 11:36:58.912  3658  3703 I Gmail   : getAccountsCursor
,07-12 11:36:58.917  3638  3638 I Exchange: EasService.onCreate
,07-12 11:36:58.918  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:58.920  3638  3706 I Exchange: RestartPingTask
,07-12 11:36:58.933  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:58.936  3638  3638 I Exchange: RestartPingsTask did not start any pings.
,07-12 11:36:58.936  3638  3638 I Exchange: PSS stopIfIdle
07-12 11:36:58.937  3638  3638 I Exchange: PSS has no active accounts; stopping service.
,07-12 11:36:58.941  3638  3638 I Exchange: onDestroy
,07-12 11:36:58.950   793  2528 I ActivityManager: Killing 3223:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,07-12 11:36:58.993  3658  3713 I Gmail   : notifyAccountChanged
,07-12 11:36:58.994  3658  3687 I Gmail   : getAccountsCursor
,07-12 11:36:58.996  3658  3713 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-12 11:36:58.999  3658  3713 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-12 11:36:59.007  3658  3713 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-12 11:36:59.007  3658  3713 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-12 11:36:59.015  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:59.064  3658  3701 I Gmail   : getAccountsCursor
,07-12 11:36:59.067  1739  1739 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-12 11:36:59.624  3444  3471 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 11:36:59.846  1739  1777 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,07-12 11:36:59.888  1613  1760 V UdcCtxListenerSrv: handle intent
,07-12 11:37:00.837   793  2529 I ActivityManager: Killing 2378:com.android.vending/u0a16 (adj 15): empty #17
,07-12 11:37:00.981   793   897 D ConnectivityService: handlePromptUnvalidated 100
,07-12 11:37:02.137   793   803 I ActivityManager: Killing 3303:com.android.chrome/u0a34 (adj 15): empty #17
,07-12 11:37:03.889  3658  3694 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 11:37:03.921  3638  3697 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 11:37:05.921   793   895 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 4, 5 -> obsolete
,07-12 11:37:06.776   793   813 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-12 11:37:06.778   793   813 I PowerManagerService: Sleeping (uid 1000)...
07-12 11:37:06.854  3023  3023 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-12 11:37:06.854  3023  3023 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-12 11:37:06.900  1240  1240 I Keyboard.Facilitator: onFinishInput()
,07-12 11:37:06.917  3023  3023 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1d785c3 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3ed94f0, 16908290=android.view.AbsSavedState$1@3ed94f0}, android:focusedViewId=100}]}]
07-12 11:37:06.917  3023  3023 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,07-12 11:37:06.917  3023  3023 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-12 11:37:06.917  3023  3023 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-12 11:37:07.336   793   813 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-12 11:37:07.353   793   811 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-12 11:37:07.363   192   192 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
07-12 11:37:07.363   192   192 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-12 11:37:07.641   192   192 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-12 11:37:07.651   793   911 D SurfaceControl: Excessive delay in setPowerMode(): 297ms
,07-12 11:37:07.652  1916  1927 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
07-12 11:37:07.699   200   200 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-12 11:37:07.719   793   895 D WifiConfigStore: Retrieve network priorities after PNO.
07-12 11:37:07.721   793   895 E native  : do suspend true
,07-12 11:37:12.963   793   895 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 5, 6 -> obsolete
,07-12 11:37:28.911  1613  3782 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-12 11:37:29.083  1613  3790 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-12 11:37:29.088   793   805 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 126651, reason: UserStart, SyncResult: databaseError: true stats []
,07-12 11:37:29.089   793   805 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 194531, reason: UserStart
,07-12 11:37:32.440   793  3274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133967, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:37:42.740   793  3274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=144267, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:38:06.902  1240  1353 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-12 11:38:06.902  1240  1353 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-12 11:38:09.420   793  3274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=170947, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:38:25.285   193   193 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6c4a030
,07-12 11:38:25.285   193   193 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
07-12 11:38:25.285   193   193 I rmt_storage: wakelock acquired: 1, error no: 2
07-12 11:38:25.286   193   480 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229715152)
,07-12 11:38:25.405   193   480 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,07-12 11:38:25.405   193   480 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
07-12 11:38:25.405   193   480 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229715152) wakelock released: 1, error no: 0
07-12 11:38:25.405   193   480 I rmt_storage: 
,07-12 11:38:25.407   193   193 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6c4a030
,07-12 11:38:53.854  1739  1874 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 11:38:58.551  1613  3682 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 11:40:09.506   793   887 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-12 11:40:09.507   793   793 V KeyguardServiceDelegate: onStartedWakingUp()
07-12 11:40:09.509   793   813 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-12 11:40:09.519  1240  1240 I Keyboard.Facilitator: onFinishInput()
,07-12 11:40:09.522   793   813 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@ca46bf2)
,07-12 11:40:09.523  3023  3023 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-12 11:40:09.523  3023  3023 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-12 11:40:09.523  3023  3023 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-12 11:40:09.523  3023  3023 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-12 11:40:09.540   793   806 I ActivityManager: Start proc 3810:com.google.android.apps.fitness/u0a45 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,07-12 11:40:09.544   793   895 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:40:09.545   200  1068 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-12 11:40:09.551   793  1295 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-12 11:40:09.552   793   895 E native  : do suspend false
07-12 11:40:09.554  1277  1383 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
07-12 11:40:09.554  1277  1383 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
,07-12 11:40:09.554  1277  1383 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
,07-12 11:40:09.554  1277  2698 D BrcmNfcJni: RoutingManager::commitRouting
07-12 11:40:09.554  1277  1383 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
07-12 11:40:09.557   793   895 D WifiConfigStore: No blacklist allowed without epno enabled
,07-12 11:40:09.577  1277  2698 D NfcService: Discovery configuration equal, not updating.
,07-12 11:40:09.585  3810  3810 W System  : ClassLoader referenced unknown path: /system/app/FitnessPrebuilt/lib/arm
,07-12 11:40:09.602  1916  1927 E ANDR-PERF-LOCK: Failed to reset optimization for resource: 4 level: 0
,07-12 11:40:09.602   793   811 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
07-12 11:40:09.603   192   192 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6ae4000
07-12 11:40:09.603   192   192 D qdhwcomposer: hwc_blank: Unblanking display: 0
07-12 11:40:09.607   793  2528 I ActivityManager: Killing 3383:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,07-12 11:40:09.684  1739  1739 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver }.
,07-12 11:40:09.773   793   813 I DisplayPowerController: Unblocked screen on after 265 ms
,07-12 11:40:09.774   793   813 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-12 11:40:09.797  1739  1748 I art     : Background partial concurrent mark sweep GC freed 67154(4MB) AllocSpace objects, 56(1260KB) LOS objects, 40% free, 20MB/34MB, paused 1.161ms total 105.005ms
,07-12 11:40:09.833   192   192 D qdhwcomposer: hwc_blank: Done unblanking display: 0
,07-12 11:40:09.834   793   911 D SurfaceControl: Excessive delay in setPowerMode(): 231ms
,07-12 11:40:14.530   793  3274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=296056, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:40:15.593   793   897 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:40:18.637   793   897 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:40:21.680   793   897 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:40:24.726   793   897 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:40:30.048   793   895 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-12 11:40:33.835   793   897 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:40:36.884   793   897 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:40:39.501   793   813 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-12 11:40:39.502   793   813 I PowerManagerService: Sleeping (uid 1000)...
,07-12 11:40:39.582  3023  3023 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-12 11:40:39.582  3023  3023 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-12 11:40:39.616  1240  1240 I Keyboard.Facilitator: onFinishInput()
,07-12 11:40:39.629  3023  3023 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1d785c3 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3ed94f0, 16908290=android.view.AbsSavedState$1@3ed94f0}, android:focusedViewId=100}]}]
07-12 11:40:39.629  3023  3023 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,07-12 11:40:39.629  3023  3023 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-12 11:40:39.629  3023  3023 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-12 11:40:40.065   793   813 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-12 11:40:40.106   793   811 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-12 11:40:40.109   192   192 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
07-12 11:40:40.109   192   192 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-12 11:40:40.370   192   192 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-12 11:40:40.373   793   911 D SurfaceControl: Excessive delay in setPowerMode(): 267ms
,07-12 11:40:40.374  1916  1927 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,07-12 11:40:40.408   200   200 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-12 11:40:40.451   793   895 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:40:40.464   793   895 E native  : do suspend true
,07-12 11:40:41.180   793  3274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=322706, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:40:50.053   793   895 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,07-12 11:40:58.730   793  3274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=340257, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:41:39.617  1240  1353 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-12 11:41:39.617  1240  1353 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-12 11:41:42.140   793  3274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=383667, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:41:58.132   793  3274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=399659, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:42:09.691  1739  1874 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 11:42:29.740   793  3274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=431267, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:42:54.833   793  3274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=456359, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:43:26.460   793  3274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=487986, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:55:33.977   793   805 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms)
```
