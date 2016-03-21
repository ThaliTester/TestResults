#### Test 62548124e8057a0_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
03-21 14:21:29.178  1557  2400 I CheckinService: Done disabling old GoogleServicesFramework version
,03-21 14:21:29.438  3486  3486 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-21 14:21:29.440  3486  3486 D AndroidRuntime: CheckJNI is OFF
03-21 14:21:29.550  3486  3486 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-21 14:21:29.553   759  1282 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-21 14:21:29.559   759  1282 V WindowManager: addAppToken: AppWindowToken{11bd7dc0 token=Token{e698343 ActivityRecord{2d01f0f2 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-21 14:21:29.563  1400  1424 W SearchService: Abort, client detached.
03-21 14:21:29.567   759   832 V WindowManager: Adding window Window{fe617bb u0 Starting com.test.thalitest} at 2 of 7 (after Window{2154949b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-21 14:21:29.570  3486  3486 D AndroidRuntime: Shutting down VM
03-21 14:21:29.593   759   775 I ActivityManager: Start proc 3507:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-21 14:21:29.609  1400  1583 I DeviceStateChecker: DeviceStateChecker cancelled
03-21 14:21:29.611  1400  1400 I MicroDetector: Keeping mic open: false
03-21 14:21:29.611  1400  1400 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@3a3e2369
03-21 14:21:29.672   188  1597 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-21 14:21:29.672   188  1597 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-21 14:21:29.677  1400  1594 I MicroRecognitionRunner: Detection finished
03-21 14:21:29.679  1400  1582 I MicroRecognitionRunner: Stopping hotword detection.
03-21 14:21:29.720   759  1118 I ActivityManager: Killing 3004:com.quickoffice.android/u0a65 (adj 15): empty #17
03-21 14:21:29.730  3507  3507 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
03-21 14:21:29.757  3507  3507 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 7866-7867)
03-21 14:21:29.758  3507  3507 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
03-21 14:21:29.767  3507  3507 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ef63dcb}
03-21 14:21:29.767  3507  3507 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
03-21 14:21:29.767  3507  3507 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
03-21 14:21:29.776  3507  3507 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,03-21 14:21:29.792  3507  3507 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-21 14:21:29.841   759   831 D BluetoothManagerService: Message: 20
,03-21 14:21:29.841   759   831 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ceebbfa:true
,03-21 14:21:29.842  3507  3507 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-21 14:21:29.842  3507  3507 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-21 14:21:29.927  3507  3507 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
03-21 14:21:29.928  3507  3507 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-21 14:21:29.941  3507  3507 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,03-21 14:21:29.942  3507  3507 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 14:21:29.948  3507  3507 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
03-21 14:21:29.949  3507  3507 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
03-21 14:21:29.949  3507  3507 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,03-21 14:21:29.950  3507  3507 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
03-21 14:21:29.959  3507  3507 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,03-21 14:21:29.966  3507  3507 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-21 14:21:29.971  3507  3507 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 14:21:29.971  3507  3507 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 14:21:30.003  3507  3569 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-21 14:21:30.015  3507  3507 D Atlas   : Validating map...
,03-21 14:21:30.022   759  1240 V WindowManager: Adding window Window{383dbb11 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{fe617bb u0 Starting com.test.thalitest})
,03-21 14:21:30.030   759   857 D WifiService: New client listening to asynchronous messages
,03-21 14:21:30.044   759  1120 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-21 14:21:30.045   759   858 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-21 14:21:30.045   759   858 D ConnectivityService: apparently satisfied.  currentScore=60
,03-21 14:21:30.046  3507  3572 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-21 14:21:30.084  3507  3569 I OpenGLRenderer: Initialized EGL, version 1.4
,03-21 14:21:30.088  3507  3569 D OpenGLRenderer: Enabling debug mode 0
,03-21 14:21:30.149  3507  3507 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-21 14:21:30.150   759   832 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +579ms
,03-21 14:21:30.154  1098  1098 I Keyboard.Facilitator: onFinishInput()
,03-21 14:21:30.163  3507  3507 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-21 14:21:30.180  3507  3575 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-21 14:21:30.219  3507  3507 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3507
,03-21 14:21:30.448  3507  3507 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-21 14:21:30.476  1645  1702 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-21 14:21:30.478  1645  1645 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-21 14:21:30.560  3507  3585 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1265506560
,03-21 14:21:30.563  3507  3585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 14:21:30.563  3507  3585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 14:21:30.563  3507  3585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 14:21:30.563  3507  3585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 14:21:30.563  3507  3585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 14:21:30.563  3507  3585 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18eb8faa added. We now have 1 listener(s)
,03-21 14:21:30.563   759  1120 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-21 14:21:30.565  3507  3585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,03-21 14:21:30.566  3507  3585 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,03-21 14:21:30.567  3507  3585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-21 14:21:30.567  3507  3585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-21 14:21:30.570  3507  3585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 14:21:30.570  3507  3585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 14:21:30.570  3507  3585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 14:21:30.570  3507  3585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-21 14:21:30.570  3507  3585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 14:21:30.570  3507  3585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 14:21:30.570  3507  3585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 14:21:30.570  3507  3585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 14:21:30.570  3507  3585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 14:21:30.570  3507  3585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 14:21:30.570  3507  3585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 14:21:30.570  3507  3585 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29139311 added. We now have 1 listener(s)
03-21 14:21:30.570  3507  3585 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-21 14:21:30.572  3507  3585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-21 14:21:30.574  3507  3585 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-21 14:21:30.574  3507  3585 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-21 14:21:30.576  3507  3585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 14:21:30.577   759  1187 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-21 14:21:30.577  3507  3585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-21 14:21:30.582  3507  3585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 14:21:30.582  3507  3585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 14:21:30.582  3507  3585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-21 14:21:30.582  3507  3585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 14:21:30.582  3507  3585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 14:21:30.582  3507  3585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 14:21:30.582  3507  3585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 14:21:30.582  3507  3585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 14:21:30.583  3507  3585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 14:21:30.583  3507  3585 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-21 14:21:30.585  3507  3585 I io.jxcore.node.LifeCycleMonitor: start: OK
03-21 14:21:30.585  3507  3507 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 14:21:30.586  3507  3507 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 14:21:30.609  3507  3507 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 14:21:30.843   759   856 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-53
,03-21 14:21:31.223  3507  3588 W jxcore-log: Initializing JXcore engine
03-21 14:21:31.223  3507  3588 W jxcore-log: JXcore engine is ready
,03-21 14:21:31.254  3588  3588 W Thread-362: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9352]" dev="sockfs" ino=9352 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-21 14:21:31.254  3588  3588 W Thread-362: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,03-21 14:21:31.254  3588  3588 W Thread-362: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[8433]" dev="sockfs" ino=8433 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-21 14:21:31.254  3588  3588 W Thread-362: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[18825]" dev="sockfs" ino=18825 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-21 14:21:31.283  3507  3588 W jxcore-log: Starting JXcore engine
,03-21 14:21:31.388  3507  3588 W jxcore-log: Platform android
03-21 14:21:31.388  3507  3588 W jxcore-log: 
03-21 14:21:31.388  3507  3588 W jxcore-log: Process ARCH arm
03-21 14:21:31.388  3507  3588 W jxcore-log: 
,03-21 14:21:31.599  3507  3588 I jxcore-log: JXcore Cordova bridge is ready!
03-21 14:21:31.599  3507  3588 I jxcore-log: 
,03-21 14:21:31.600  3507  3588 W jxcore-log: JXcore engine is started
,03-21 14:21:31.607  3507  3585 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 14:21:31.608  3507  3507 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 14:21:33.937  3382  3416 W Babel   : aye TOOK TOO LONG! (15030ms > 10000ms)
,03-21 14:21:33.938  3382  3414 W Babel   : aye TOOK TOO LONG! (15039ms > 10000ms)
,03-21 14:21:33.941   759  1282 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-21 14:21:33.945   759   775 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-21 14:21:33.948  3382  3382 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-21 14:21:33.948  3382  3382 W Babel   : BAM#gBA: invalid account id: -1
03-21 14:21:33.948  3382  3382 W Babel   : BAM#gBA: invalid account id: -1
03-21 14:21:33.948  3382  3382 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-21 14:21:33.950   759  3274 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-21 14:21:33.952   759  1240 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-21 14:21:33.992  3382  3424 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,03-21 14:21:39.548  1645  1645 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-21 14:21:39.572  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:21:39.577  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:21:39.578  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:21:40.269  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:21:40.416  1645  1686 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-21 14:21:40.416  1645  1686 I qtaguid : Untagging socket 37 failed errno=-22
03-21 14:21:40.416  1645  1686 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-21 14:21:40.419  1645  1645 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-21 14:21:40.461  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:21:40.494   759  1240 I ActivityManager: Start proc 3633:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-21 14:21:40.524  3633  3633 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 14:21:40.524  3633  3633 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 14:21:40.553  3633  3633 I MultiDex: VM with version 2.1.0 has multidex support
03-21 14:21:40.553  3633  3633 I MultiDex: install
03-21 14:21:40.553  3633  3633 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-21 14:21:40.567  3633  3633 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-21 14:21:40.599  3633  3633 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 14:21:40.612  1516  1516 D WearableService: callingUid 10007, callindPid: 1516
,03-21 14:21:40.615  1557  3664 D LocationInitializer: Restart initialization of location
,03-21 14:21:40.615  1516  1954 E MDM     : [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-21 14:21:40.617  1516  1516 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-21 14:21:40.622  3633  3633 D ChimeraCfgMgr: Reading stored module config
03-21 14:21:40.624  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:21:40.640  1516  1620 W GCoreFlp: No location to return for getLastLocation()
03-21 14:21:40.640  1516  3666 W FusedLocationProvider: location=null
,03-21 14:21:40.703  3633  3663 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-21 14:21:40.732  3633  3633 D CAR.SERVICE: Connecting to CarCallService...
,03-21 14:21:40.742  3633  3633 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
03-21 14:21:40.742  3633  3633 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-21 14:21:40.748  3633  3633 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-21 14:21:40.752  3633  3633 D CAR.TEL.Service: Creating a new CarCallService.
,03-21 14:21:40.755  3633  3633 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,03-21 14:21:40.757   759  1187 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-21 14:21:40.757  3633  3633 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@27a9ee68
03-21 14:21:40.758   759  3274 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-21 14:21:40.758  3633  3633 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-21 14:21:40.758  3633  3633 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-21 14:21:40.820  3633  3655 D CAR.SERVICE: Package validated; name: com.android.vending
,03-21 14:21:40.844  1645  1685 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-21 14:21:40.844  1645  1685 I qtaguid : Untagging socket 37 failed errno=-22
03-21 14:21:40.844  1645  1685 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-21 14:21:40.894  3507  3588 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 14:21:40.894  3507  3588 I jxcore-log: 
03-21 14:21:40.896  3507  3588 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 14:21:40.896  3507  3588 I jxcore-log: 
,03-21 14:21:40.899  3507  3588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 14:21:40.899  3507  3588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 14:21:40.899  3507  3588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-21 14:21:40.899  3507  3588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 14:21:40.899  3507  3588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 14:21:40.899  3507  3588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 14:21:40.899  3507  3588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 14:21:40.899  3507  3588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 14:21:40.900  3507  3588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-21 14:21:40.902  3507  3588 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 14:21:40.902  3507  3588 I jxcore-log: 
03-21 14:21:40.903  3507  3588 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 14:21:40.903  3507  3588 I jxcore-log: 
,03-21 14:21:41.362  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:21:41.410  3507  3588 I jxcore-log: Unit Test app is loaded
03-21 14:21:41.410  3507  3588 I jxcore-log: 
,03-21 14:21:41.416  3507  3507 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-21 14:21:41.418  3507  3588 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 14:21:41.418  3507  3588 I jxcore-log: 
,03-21 14:21:41.423  3507  3588 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,03-21 14:21:41.425  3507  3588 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-21 14:21:41.425  3507  3588 I jxcore-log: 
,03-21 14:21:41.430  3507  3507 I chromium: [INFO:CONSOLE(86)] "logCallback Device did not have required hardware capabilities!", source: file:///android_asset/www/js/thali_main.js (86)
,03-21 14:21:41.432  3507  3588 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-21 14:21:41.432  3507  3588 I jxcore-log:   bluetooth: 'on',
03-21 14:21:41.432  3507  3588 I jxcore-log:   wifi: 'on',
03-21 14:21:41.432  3507  3588 I jxcore-log:   cellular: 'doNotCare',
03-21 14:21:41.432  3507  3588 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-21 14:21:41.432  3507  3588 I jxcore-log: 
03-21 14:21:41.432  3507  3588 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-21 14:21:41.432  3507  3588 I jxcore-log: 
,03-21 14:21:41.675   759  1118 I ActivityManager: Killing 3048:com.google.android.apps.magazines/u0a56 (adj 15): empty #17
,03-21 14:21:41.702   759   928 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@39008e72)
,03-21 14:21:41.703   759   858 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-21 14:21:41.703   759   858 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-21 14:21:41.714  3683  3683 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-21 14:21:41.716  3683  3683 D AndroidRuntime: CheckJNI is OFF
,03-21 14:21:41.759  1645  1686 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-21 14:21:41.759  1645  1686 I qtaguid : Untagging socket 37 failed errno=-22
03-21 14:21:41.759  1645  1686 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-21 14:21:41.808  3683  3683 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-21 14:21:41.877   759   838 W PackageSettings: Skipping PackageSetting{7ef284e com.example.hello/10116} due to missing metadata
,03-21 14:21:41.890   759   827 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
,03-21 14:21:41.890   759   827 I ActivityManager: Killing 3507:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-21 14:21:41.922   759  1014 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@ecf92c3)
,03-21 14:21:41.923   759   857 D WifiService: Client connection lost with reason: 4
03-21 14:21:41.923   759  1187 I WindowState: WIN DEATH: Window{383dbb11 u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-21 14:21:41.924   759   858 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-21 14:21:41.924   759   858 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-21 14:21:42.098   759   827 W ActivityManager: Force removing ActivityRecord{2d01f0f2 u0 com.test.thalitest/.MainActivity t19}: app died, no saved state
,03-21 14:21:42.110   759  1014 W ActivityManager: Spurious death for ProcessRecord{12eb1740 3507:com.test.thalitest/u0a49}, curProc for 3507: null
,03-21 14:21:42.112   759   838 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-21 14:21:42.150  1557  1568 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-21 14:21:42.150  1557  1557 I art     : Explicit concurrent mark sweep GC freed 4887(219KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 23MB/38MB, paused 972us total 32.766ms
,03-21 14:21:42.170  1400  1400 I art     : Explicit concurrent mark sweep GC freed 2989(270KB) AllocSpace objects, 7(154KB) LOS objects, 25% free, 22MB/30MB, paused 489us total 50.814ms
,03-21 14:21:42.183   905   905 I art     : Explicit concurrent mark sweep GC freed 6559(307KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 1.088ms total 25.308ms
,03-21 14:21:42.189  1516  1633 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-21 14:21:42.192   759   848 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 14:21:42.195  1098  1098 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-21 14:21:42.197  1098  3701 I Keyboard.Facilitator.DecoderInitializer: run()
,03-21 14:21:42.200   759   883 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
,03-21 14:21:42.215  1098  3701 I Decoder : createOrResetDecoder
,03-21 14:21:42.224  1645  1645 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10426): Logging device features
,03-21 14:21:42.232  2831  3713 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-21 14:21:42.258   759  1120 I ActivityManager: Start proc 3716:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-21 14:21:42.264   759   759 I art     : Explicit concurrent mark sweep GC freed 33908(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 2.236ms total 90.517ms
,03-21 14:21:42.266  1516  1516 I ConfigService: onCreate
,03-21 14:21:42.269   759   838 I art     : WaitForGcToComplete blocked for 58.327ms for cause Explicit
,03-21 14:21:42.313  1098  3701 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-21 14:21:42.324   759  1240 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3507 uid 10049
,03-21 14:21:42.325  1098  1098 I Keyboard.Facilitator: onFinishInput()
,03-21 14:21:42.335  1516  1545 D DeviceConnectionService: client connected with version: 8298000
,03-21 14:21:42.356  1098  3701 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-21 14:21:42.357   759  1118 I ActivityManager: Start proc 3737:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-21 14:21:42.366  1098  3701 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-21 14:21:42.366  1098  3701 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
03-21 14:21:42.368  1400  1400 W LocationOracle: Best location was null
03-21 14:21:42.368  1220  1220 I art     : Explicit concurrent mark sweep GC freed 2790(158KB) AllocSpace objects, 6(531KB) LOS objects, 38% free, 25MB/41MB, paused 1.930ms total 24.691ms
,03-21 14:21:42.375   759   759 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-21 14:21:42.375   759   759 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-21 14:21:42.376  1098  3701 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-21 14:21:42.376  1098  3701 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-21 14:21:42.378  1098  3701 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-21 14:21:42.378  1098  3701 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-21 14:21:42.379  1098  3701 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-21 14:21:42.379  1098  3701 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-21 14:21:42.379  1098  3701 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-21 14:21:42.380  1098  3701 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,03-21 14:21:42.380  1098  3701 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-21 14:21:42.380  1098  3701 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-21 14:21:42.381  1645  1645 E Finsky  : [1] com.google.android.finsky.wear.ba.a(689): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-21 14:21:42.382  1645  1645 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6302): Dropping command=hygiene due to Gms not connected
,03-21 14:21:42.384  1400  1400 I MicroDetectionWorker: Micro detection mode: [mDetectionMode: [1]].
,03-21 14:21:42.397  3737  3737 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-21 14:21:42.405  1400  3758 I MicroRecognitionRunner: Starting detection.
03-21 14:21:42.406  1400  3759 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.ae@3a0bab50
,03-21 14:21:42.408   188  3761 I AudioFlinger: AudioFlinger's thread 0xb447d000 ready to run
,03-21 14:21:42.416  1400  3759 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.ae@3a0bab50
,03-21 14:21:42.424   759  1186 I ActivityManager: Start proc 3763:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,03-21 14:21:42.425   188  3761 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-21 14:21:42.425   188  3761 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-21 14:21:42.425   188  3761 D         : Failed to fetch the lookup information of the device 0000003E 
03-21 14:21:42.425   188  3761 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-21 14:21:42.425   188  3761 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-21 14:21:42.435   188  3761 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-21 14:21:42.444   759  1118 I ActivityManager: Killing 3232:com.qualcomm.timeservice/u0a68 (adj 15): empty #17
,03-21 14:21:42.475   759   838 I art     : Explicit concurrent mark sweep GC freed 13991(872KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.344ms total 205.943ms
,03-21 14:21:42.521  1400  1400 I MicroDetectionWorker: onReady
,03-21 14:21:42.537  3683  3683 I art     : System.exit called, status: 0
03-21 14:21:42.537  3683  3683 I AndroidRuntime: VM exiting with result code 0.
,03-21 14:21:42.575   759   838 I ActivityManager: Start proc 3783:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-21 14:21:42.581  1516  1620 W GCoreFlp: No location to return for getLastLocation()
,03-21 14:21:42.583  1516  1620 W GCoreFlp: No location to return for getLastLocation()
,03-21 14:21:42.596  1220  1452 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 14:21:42.598  1516  1620 W GCoreFlp: No location to return for getLastLocation()
,03-21 14:21:42.613  1516  1620 W GCoreFlp: No location to return for getLastLocation()
,03-21 14:21:42.626  1516  1620 W GCoreFlp: No location to return for getLastLocation()
,03-21 14:21:42.629  1516  1620 W GCoreFlp: No location to return for getLastLocation()
,03-21 14:21:42.633   759  1014 I ActivityManager: Killing 3252:com.google.android.gm.exchange/u0a84 (adj 15): empty #17
,03-21 14:21:42.775  3763  3806 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
03-21 14:21:42.775  3763  3806 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 14:21:42.775  3763  3806 I GAv4    :   adb logcat -s GAv4
,03-21 14:21:42.786  3763  3806 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:21:42.794  3763  3806 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
03-21 14:21:42.794  3763  3812 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-21 14:21:42.794  3763  3812 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-21 14:21:42.839  3763  3813 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 14:21:42.841  3763  3812 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-21 14:21:42.845  1220  1505 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
03-21 14:21:42.846  1220  1505 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-21 14:21:42.863   179   179 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
03-21 14:21:42.863   179   179 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
03-21 14:21:42.863   179   179 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
03-21 14:21:42.863   179   179 E qdoverlay: MdpData failed to play
03-21 14:21:42.863   179   179 E qdoverlay: == Dump MdpData start ==
03-21 14:21:42.863   179   179 E qdoverlay: == Dump OvFD fd=33 path=/dev/graphics/fb0 start/end ==
03-21 14:21:42.863   179   179 E qdoverlay: mOvData msmfb_overlay_data id=64
03-21 14:21:42.863   179   179 E qdoverlay: data msmfb_data offset=0 memid=53 id=0 flags=0x0 priv=0
03-21 14:21:42.863   179   179 E qdoverlay: == Dump MdpData end ==
03-21 14:21:42.863   179   179 E qdhwcomposer: draw: queueBuffer failed for display:0 
03-21 14:21:42.863   179   179 E qdhwcomposer: hwc_set_primary: MDPComp draw failed
03-21 14:21:42.863   179   179 E qdhwcomposer: display_commit: MSMFB_DISPLAY_COMMIT for primary failed
03-21 14:21:42.863   179   179 E qdhwcomposer: hwc_set_primary: display commit fail!
,03-21 14:21:42.930   179   179 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
03-21 14:21:42.930   179   179 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
03-21 14:21:42.930   179   179 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
03-21 14:21:42.930   179   179 E qdoverlay: MdpData failed to play
03-21 14:21:42.930   179   179 E qdoverlay: == Dump MdpData start ==
03-21 14:21:42.930   179   179 E qdoverlay: == Dump OvFD fd=33 path=/dev/graphics/fb0 start/end ==
03-21 14:21:42.930   179   179 E qdoverlay: mOvData msmfb_overlay_data id=64
03-21 14:21:42.930   179   179 E qdoverlay: data msmfb_data offset=0 memid=53 id=0 flags=0x0 priv=0
03-21 14:21:42.930   179   179 E qdoverlay: == Dump MdpData end ==
03-21 14:21:42.931   179   179 E qdhwcomposer: draw: queueBuffer failed for display:0 
03-21 14:21:42.931   179   179 E qdhwcomposer: hwc_set_primary: MDPComp draw failed
03-21 14:21:42.931   179   179 E qdhwcomposer: display_commit: MSMFB_DISPLAY_COMMIT for primary failed
03-21 14:21:42.931   179   179 E qdhwcomposer: hwc_set_primary: display commit fail!

```
