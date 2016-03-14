#### Test 62509094588eeb1_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,D/TCMD    (  464): NL - Read 56 bytes from update socket.
D/TCMD    (  464): NL - message type is RTM_NEWLINK
D/TCMD    (  464): Listening for incoming client connection request
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 14 
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 14 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  889): [1,457,959,201,260 ms] noteScanEnd no scan source
--------- beginning of system
I/ActivityManager(  889): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5242 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
E/WifiStateMachine(  889): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@22d37767 sup_state=COMPLETED debouncing=false
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin ( 3416): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
D/PhoneMonitor( 5242): Register our PhoneStateListener
I/Gmail   ( 5165): getAccountsCursor
V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/SetupWizard( 5242): Connected to Gservices successfully
I/ActivityManager(  889): Killing 4050:com.android.defcontainer/u0a10 (adj 15): empty #7
I/art     ( 1746): Explicit concurrent mark sweep GC freed 40599(2MB) AllocSpace objects, 37(592KB) LOS objects, 40% free, 13MB/22MB, paused 1.030ms total 102.881ms
I/CalendarProvider2( 5144): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5144): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/libprocessgroup(  889): failed to open /acct/uid_10010/pid_4050/cgroup.procs: No such file or directory
I/ActivityManager(  889): Killing 5096:com.google.android.deskclock/u0a55 (adj 15): empty #7
W/libprocessgroup(  889): failed to open /acct/uid_10055/pid_5096/cgroup.procs: No such file or directory
D/GCM     ( 1746): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/GCM     ( 1746): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  889): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5270 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ResourcesManager( 5270): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/AndroidRuntime( 5263): 
D/AndroidRuntime( 5263): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5263): CheckJNI is OFF
I/Babel_SMS( 5270): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5270): MmsConfig.loadMmsSettings
I/Babel_SMS( 5270): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5270): MmsConfig.loadFromDatabase
E/Babel_SMS( 5270): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5270): MmsConfig.loadFromResources
E/Babel_SMS( 5270): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5270): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
D/AndroidRuntime( 5263): Calling main entry com.android.commands.am.Am
I/ActivityManager(  889): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (175 us)
W/art     ( 5270): Suspending all threads took: 5.887ms
W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5263): Shutting down VM
I/ActivityManager(  889): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5307 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/Settings( 5270): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5270): startup - clean
I/Babel   ( 5270): deleted: false for 0
W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  889): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=5331 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 5270): Unrecognized profile 2130706433 for video/avc
,I/WebViewFactory( 5307): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/AudioCapabilities( 5270): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5270): Unsupported mime video/mpeg2
,I/LibraryLoader( 5307): Time to load native libraries: 6 ms (timestamps 37-43)
,I/LibraryLoader( 5307): Expected native library version number "",actual native library version number ""
,I/VideoCapabilities( 5270): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5270): Unrecognized profile 2130706433 for video/avc
,V/WebViewChromiumFactoryProvider( 5307): Binding Chromium to main looper Looper (main, tid 1) {2841c663}
,I/LibraryLoader( 5307): Expected native library version number "",actual native library version number ""
,I/chromium( 5307): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/VideoCapabilities( 5270): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5270): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5270): Unrecognized profile 2130706433 for video/avc
,I/BrowserStartupController( 5307): Initializing chromium process, singleProcess=true
W/art     ( 5307): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5307): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  889): Killing 5187:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/chromium( 5307): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5307): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5307): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5307): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5307): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5307): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5307): Local Branch: 
I/Adreno-EGL( 5307): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5307): Local Patches: NONE
I/Adreno-EGL( 5307): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/SFPerfTracer(  280):      triggers: (rate: 13:301) (compose: 0:2) (post: 0:1) (render: 0:5) (6:1031 frames) (7:1108)
D/SFPerfTracer(  280):        layers: (5:12) (FocusedStackFrame (0xb7930ee0): 0:12)* (DimLayer (0xb7941e48): 0:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7946bb0): 0:38)- (StatusBar (0xb790ef28): 0:124) (NavigationBar (0xb7911318): 0:37) (com.android.systemui.ImageWallpaper (0xb7916ec0): 0:8)* (Starting com.motorola.ccc.ota (0xb7962180): 0:38)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7963df0): 7:48) (Starting com.test.thalitest (0xb7946bb0): 7:12) 
,D/BluetoothManagerService(  889): Message: 20
D/BluetoothManagerService(  889): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3666d773:true
,W/libprocessgroup(  889): failed to open /acct/uid_10060/pid_5187/cgroup.procs: No such file or directory
,I/vclib   ( 5270): onServiceConnected
,W/Babel   ( 5270): Attempted to change video mute state without an active call.
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/art     ( 5307): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  889): Explicit concurrent mark sweep GC freed 15895(791KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.602ms total 127.159ms
,W/AwContents( 5307): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5307): CordovaWebView is running on device made by: motorola
,I/ActivityManager(  889): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5374 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,W/art     ( 5307): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5307): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5307): Render dirty regions requested: true
,D/MMApiWSBase( 2970): doRequest(): v1/cs/checkin resp length: 4
,D/Atlas   ( 5307): Validating map...
D/CCE     ( 2970): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
D/CCE     ( 2970): AppWSProxy - sendAIDLWSResponse() sending reponse
,W/chromium( 5307): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  889): Killing 5165:com.google.android.gm/u0a63 (adj 15): empty #7
,I/global frequency( 2970): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 2970): publish the event [tag = MOT_CHECKIN event name = LOG]
,W/libprocessgroup(  889): failed to open /acct/uid_10063/pid_5165/cgroup.procs: No such file or directory
,I/SFPerfTracer(  280):      triggers: (rate: 0:1) (0 sw vsyncs) (0 skipped) (30:208 vsyncs) (32:1128)
,I/OpenGLRenderer( 5307): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5307): Enabling debug mode 0
,I/Keyboard.Facilitator( 1423): onFinishInput()
,I/LaunchCheckinHandler(  889): Displayed com.test.thalitest/.MainActivity,cp,ca,1213
I/ActivityManager(  889): Displayed com.test.thalitest/.MainActivity: +1s213ms
,D/CheckinProvider(  889): 58 events delete 0 left
,E/Adreno-ES20( 5307): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 5307): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5307): Cannot call determinedVisibility() - never saw a connection for the pid: 5307
,I/global frequency( 2970): BcsDSCheckin.events found events 0
,D/Checkin ( 2970): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2970): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2970): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2970): BcsTimer.onReceive checkin completed (-424621795:ERROR_OK)
,D/Checkin ( 2970): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ActivityManager(  889): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5420 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/JsMessageQueue( 5307): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  889): Killing 5144:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  889): failed to open /acct/uid_10005/pid_5144/cgroup.procs: No such file or directory
,I/ActivityManager(  889): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5440 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/ResourcesManager( 5270): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5270): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5270): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5270): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5270): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  889): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5462 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 5040:com.motorola.context/u0a8 (adj 15): empty #7
,I/ContactLocale( 5440): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/DataUsage( 2970): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2970): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  889): failed to open /acct/uid_10008/pid_5040/cgroup.procs: No such file or directory
,W/asset   ( 5462): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5462): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5462): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5462): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,E/Adreno-ES20( 5307): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5307): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 5307): JniHelper::setJavaVM(0xb787e310), pthread_self() = -1211995984
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5307): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5307):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5307):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5307):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5307):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5307): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e23af9f added. We now have 1 listener(s)
,D/BluetoothManagerService(  889): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5307): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5307): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5307): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5307): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5307): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5307): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5307):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5307):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5307):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5307):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5307):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5307):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5307):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5307):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5307):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5307): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdb174a added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5307): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  889): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5307): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5307): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
E/io.jxcore.node.ConnectionHelper( 5307): Constructor: Bluetooth LE discovery mode is not supported
,I/UpdateIcingCorporaServi( 5374): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1578): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,D/PkgBroadcastIntentOp( 1959): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PkgBroadcastIntentOp( 1959): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  889): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5490 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 335us total 26.319ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 356us total 20.808ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 21.990ms
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WearableController( 1959): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/Icing   ( 1959): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 5490): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/chromium( 5307): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 5307): Background partial concurrent mark sweep GC freed 7981(674KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 11MB/19MB, paused 5.239ms total 78.730ms
,I/UpdateIcingCorporaServi( 5374): UpdateCorporaTask done [took 333 ms] updated apps [took 332 ms] 
,I/ActivityManager(  889): Killing 5242:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  889): failed to open /acct/uid_10035/pid_5242/cgroup.procs: No such file or directory
,I/ActivityManager(  889): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5514 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5514): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  889): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5535 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CalendarProvider2( 5514): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,I/ActivityManager(  889): Killing 5331:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  889): failed to open /acct/uid_10088/pid_5331/cgroup.procs: No such file or directory
,D/Finsky  ( 5535): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,V/AlarmManager(  889): send {39caf9c6, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,D/Finsky  ( 5535): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5535): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5535): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Icing   ( 1959): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Ads     ( 5535): Skipping gmscore version check
,D/Finsky  ( 5535): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5535): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5535): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/TaskPersister(  889): removeObsoleteFile: deleting file=8_task_thumbnail.png
,D/Finsky  ( 5535): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1959): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/UpdateIcingCorporaServi( 5374): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/PkgBroadcastIntentOp( 1959): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/WearableController( 1959): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/art     ( 1959): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,W/jxcore-log( 5307): Initializing JXcore engine
W/jxcore-log( 5307): JXcore engine is ready
,I/CalendarProvider2( 5514): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5514): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/Thread-545( 5482): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[7338]" dev="sockfs" ino=7338 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-545( 5482): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-545( 5482): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[6954]" dev="sockfs" ino=6954 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-545( 5482): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[18285]" dev="sockfs" ino=18285 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5307): Starting JXcore engine
,I/ActivityManager(  889): Killing 5490:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  889): failed to open /acct/uid_10090/pid_5490/cgroup.procs: No such file or directory
,D/AsyncTaskServiceImpl( 1959): Submit a task: k
,W/jxcore-log( 5307): Platform android
W/jxcore-log( 5307): 
W/jxcore-log( 5307): Process ARCH arm
W/jxcore-log( 5307): 
,D/k       ( 1959): Processing package: com.test.thalitest
,D/GassUtils( 1959): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 1959): Found info for package com.test.thalitest in db.
,I/UpdateIcingCorporaServi( 5374): UpdateCorporaTask done [took 476 ms] updated apps [took 476 ms] 
,I/ActivityManager(  889): Killing 5514:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  889): failed to open /acct/uid_10005/pid_5514/cgroup.procs: No such file or directory
,I/ActivityManager(  889): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5602 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 1959): Using Auth Proxy for data requests.
W/BaseAppContext( 1959): Using Auth Proxy for data requests.
,W/BaseAppContext( 1959): Using Auth Proxy for data requests.
,W/BaseAppContext( 1959): Using Auth Proxy for data requests.
,W/BaseAppContext( 1959): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1959): cleanUpNonGplusAccounts done.
,I/art     (  889): Explicit concurrent mark sweep GC freed 14606(727KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.825ms total 121.845ms
,I/jxcore-log( 5307): JXcore Cordova bridge is ready!
I/jxcore-log( 5307): 
W/jxcore-log( 5307): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5307): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 5307): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,I/GAv4    ( 5602): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5602):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5602):   adb logcat -s GAv4
,W/GAv4    ( 5602): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5602): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Icing   ( 1959): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
W/GAv4    ( 5602): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5602): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,I/Icing   ( 1959): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5602): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 5602): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5602): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  889): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5637 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 5535:com.android.vending/u0a32 (adj 15): empty #7
,I/Icing   ( 1959): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1959): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,W/libprocessgroup(  889): failed to open /acct/uid_10032/pid_5535/cgroup.procs: No such file or directory
,I/ActivityManager(  889): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=5657 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  889): send {3ccbb268, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
V/AlarmManager(  889): send {2ed7b89e, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  889): done {3ccbb268, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [86ms]
,W/ResourcesManager( 5637): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 5602): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Finsky  ( 5657): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/System  ( 5602): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5602): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5657): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5657): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5657): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 5657): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/Ads     ( 5657): Skipping gmscore version check
,D/Finsky  ( 5657): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5657): [1] Libraries$2.run: Finished loading 1 libraries.
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  889): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5714 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 5657): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5657): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/ActivityManager(  889): Killing 5420:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,D/Finsky  ( 5657): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Gmail   ( 5714): getAccountsCursor
,W/libprocessgroup(  889): failed to open /acct/uid_10019/pid_5420/cgroup.procs: No such file or directory
,D/ActivityThread( 5714): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  889): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5737 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/GAV2    ( 5714): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  889): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Exchange( 5737): EasService.onCreate
,I/Exchange( 5737): RestartPingTask
,I/Gmail   ( 5714): Observing account changes for notifications
,I/Exchange( 5737): RestartPingsTask did not start any pings.
I/Exchange( 5737): PSS stopIfIdle
I/Exchange( 5737): PSS has no active accounts; stopping service.
,I/Gmail   ( 5714): getAccountsCursor
,I/Exchange( 5737): onDestroy
,I/ActivityManager(  889): Killing 5462:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:37000 mC
,W/libprocessgroup(  889): failed to open /acct/uid_10027/pid_5462/cgroup.procs: No such file or directory
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/3CDM.DeviceAdminSetupReceiver( 2970): received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,D/3CDM.DeviceAdminSetupReceiver( 2970): time to show notification
I/ActivityManager(  889): Killing 5270:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  889): failed to open /acct/uid_10070/pid_5270/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  889): Killing 5374:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/ResourcesManager( 1299): Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,I/ActivityManager(  889): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5784 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
W/libprocessgroup(  889): failed to open /acct/uid_10039/pid_5374/cgroup.procs: No such file or directory
,W/ResourcesManager( 5784): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,E/SQLiteLog( 5714): (283) recovered 143 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,E/ActivatableNotificationView( 1299):  oops Width=0 ActualHeight=128
,I/ActivityManager(  889): Killing 5602:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/Gmail   ( 5714): notifyAccountChanged
,I/Gmail   ( 5714): getAccountsCursor
,I/Gmail   ( 5714): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5714): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5714): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5714): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/qtaguid ( 5657): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5657): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5657): untagSocket(37) failed with errno -22
,D/Finsky  ( 5657): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,W/libprocessgroup(  889): failed to open /acct/uid_10057/pid_5602/cgroup.procs: No such file or directory
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  889): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5811 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SFPerfTracer(  280):      triggers: (rate: 13:304) (compose: 0:2) (post: 0:1) (render: 0:5) (16:1118 frames) (17:1209)
D/SFPerfTracer(  280):        layers: (3:11) (FocusedStackFrame (0xb7930ee0): 0:15)* (DimLayer (0xb7941e48): 0:6)* (StatusBar (0xb790ef28): 17:141) (NavigationBar (0xb7911318): 0:37) (com.android.systemui.ImageWallpaper (0xb7916ec0): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7963df0): 0:50)- (Starting com.test.thalitest (0xb7946bb0): 0:42)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb79617a0): 0:59) 
,I/art     (  889): Explicit concurrent mark sweep GC freed 11529(549KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 2.556ms total 136.429ms
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  889): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5829 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 5811): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 5829): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5829): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5811): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,V/AlarmManager(  889): done {39caf9c6, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [4822ms]
,E/SQLiteLog( 5811): (284) automatic index on view_events(_id)
,E/WifiStateMachine(  889): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=4.78 rxSuccessRate=4.63 targetRoamBSSID=any RSSI=-45
E/WifiStateMachine(  889): WifiStateMachine CMD_START_SCAN with age=22857 interval=30000 maxinterval=300000
E/WifiStateMachine(  889): WifiStateMachine CMD_START_SCAN full=false
,E/WifiStateMachine(  889): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1449): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  889): [1,457,959,210,284 ms] noteScanstart no scan source
,V/AlarmManager(  889): done {2ed7b89e, *alarm*:com.android.server.WifiManager.action.START_SCAN} [2631ms]
,I/MultiDex( 5829): VM with version 2.1.0 has multidex support
I/MultiDex( 5829): install
I/MultiDex( 5829): VM has multidex support, MultiDex support library is disabled.
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 6
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  464): NL - Read 56 bytes from update socket.
D/TCMD    (  464): NL - message type is RTM_NEWLINK
D/TCMD    (  464): Listening for incoming client connection request
,E/WifiStateMachine(  889): [1,457,959,210,341 ms] noteScanEnd no scan source
,E/WifiStateMachine(  889): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@22d37767 sup_state=COMPLETED debouncing=false
,V/JNIHelp ( 5829): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Gmail   ( 5714): getAccountsCursor
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityThread( 5829): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5829): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5829): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 5829): Reading stored module config
,D/WearableService( 1746): callingUid 10016, callindPid: 1746
,E/MDM     ( 1746): [178] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1959): Restart initialization of location
D/AuthorizationBluetoothService( 1746): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  889): send {1a3c46cd, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  889): done {1a3c46cd, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [10ms]
W/GCoreFlp( 1746): No location to return for getLastLocation()
W/FusedLocationProvider( 1746): location=null
,I/qtaguid ( 5657): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5657): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5657): untagSocket(37) failed with errno -22
,D/CAR.SERVICE( 5829): Connecting to CarCallService...
,I/art     ( 5829): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5829): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 5829): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 5829): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5829): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 5829): Creating a new PhoneAdapter instance
,W/ActivityManager(  889): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5829): setListener: com.google.android.gms.car.dn@1dd60e23
W/ActivityManager(  889): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5829): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5829): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 5829): Package validated; name: com.android.vending
,V/Finsky  ( 5657): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/CalendarProvider2( 5811): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5811): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  889): Killing 5440:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  889): failed to open /acct/uid_10007/pid_5440/cgroup.procs: No such file or directory
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/qtaguid ( 5657): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5657): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5657): untagSocket(37) failed with errno -22
,W/ActivityManager(  889): getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,W/ResourcesManager( 5657): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5657): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5657): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5657): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  889): send {2b4816f5, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,V/AlarmManager(  889): done {2b4816f5, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [35ms]
,D/DeviceConnectionService( 1746): client connected with version: 8296000
,D/Finsky  ( 5657): [604] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5657): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5657): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  889): Killing 5737:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,I/ActivityManager(  889): Killing 5637:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  889): failed to open /acct/uid_10060/pid_5737/cgroup.procs: No such file or directory
,W/libprocessgroup(  889): failed to open /acct/uid_10090/pid_5637/cgroup.procs: No such file or directory
,I/GAV2    ( 5714): Thread[GAThread,5,main]: No campaign data found.
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  889): Waited long enough for: ServiceRecord{3edf3152 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/jxcore-log( 5307): INFO testUtils Toggling radios to: true
I/jxcore-log( 5307): 
,D/BluetoothAdapter( 5307): enable(): BT is already enabled..!
I/jxcore-log( 5307): Unit Test app is loaded
I/jxcore-log( 5307): 
,D/WifiService(  889): setWifiEnabled: true pid=5307, uid=10109
E/WifiService(  889): Invoking mWifiStateMachine.setWifiEnabled
,I/chromium( 5307): [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,I/wpa_supplicant( 1449): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294):  STA Disconnected !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
,I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  294): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  464): NL - Read 1004 bytes from update socket.
D/TCMD    (  464): NL - message type is RTM_NEWLINK
D/TCMD    (  464): Listening for incoming client connection request
D/TCMD    (  464): NL - Read 68 bytes from update socket.
D/TCMD    (  464): NL - message type is RTM_NEWLINK
D/TCMD    (  464): Listening for incoming client connection request
D/TCMD    (  464): NL - Read 68 bytes from update socket.
D/TCMD    (  464): NL - message type is RTM_NEWLINK
D/TCMD    (  464): Listening for incoming client connection request
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 1449): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE ,
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
,I/wpa_supplicant( 1449): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  889): InitialState.processMessage what=4
E/WifiStateMachine(  889): WifiStateMachine: Leaving Connected state
,W/Settings(  889): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  889): ApnList is empty for checkDunConfigured()
D/Tethering(  889):  upstream interface types: 
,D/Tethering(  889):  1
,D/Tethering(  889):  5
D/Tethering(  889):  7
D/Tethering(  889):  0
,D/Tethering(  889): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  889): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  889): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  889): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  889): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  889): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  889): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  889): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1449): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  291): Clearing all IP addresses on wlan0
D/TCMD    (  464): NL - Read 60 bytes from update socket.
D/TCMD    (  464): NL - ignore NL message, type = 21
D/TCMD    (  464): Listening for incoming client connection request
,V/NativeCrypto( 1746): Read error: ssl=0xb7b40ae8: I/O error during system call, Connection timed out
,E/WifiStateMachine(  889): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  889): setDetailed state send new extra info<unknown ssid>
,V/NativeCrypto( 1746): SSL shutdown failed: ssl=0xb7b40ae8: I/O error during system call, Broken pipe
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  889): connected time updated 33051
,D/ConnectivityService(  889): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  889): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,I/SBar.MotoNetworkCtrlr( 1299): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  889): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  889): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 1449): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/Checkin (  889): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  889): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1449): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  294): Event received = Trying to associate with
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiMonitor(  889): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 1449): DSDS: eapol_sm_notify_config config->sim_num = 1
I/SBar.MotoNetworkCtrlr( 1299): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  889): ConnectModeState: Network connection lost 
,E/GCM     ( 1746): Wifi connection closed with errorCode 20
,D/ConnectivityService(  889): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,E/WifiStateMachine(  889): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  889): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/wpa_supplicant( 1449): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiP2pService(  889): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  889): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): DefaultState{ when=-9ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/SFPerfTracer(  280):      triggers: (rate: 0:1) (0 sw vsyncs) (0 skipped) (0:289 vsyncs) (1:1229)
,D/CommandListener(  291): Clearing all IP addresses on wlan0
D/ConnectivityService(  889): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/Nat464Xlat(  889): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  889): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
E/WifiStateMachine(  889): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 1299): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1959): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Disconnected - quitting
,I/ActivityManager(  889): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5926 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/AlarmManager(  889): send {319619a9, *walarm*:android.content.syncmanager.SYNC_ALARM}
D/ConnectivityService(  889): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  889): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1299): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=null
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1299): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1299): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  889): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  889): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  889): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 447us total 26.568ms
I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
,E/WifiStateMachine(  889): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  889): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  889): NetworkAgent: NetworkAgent channel lost
,D/Checkin (  889): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  889): setDetailed state, old =DISCONNECTED and new state=CONNECTING hidden=false
E/WifiStateMachine(  889): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 304us total 21.991ms
,D/TCMD    (  464): NL - Read 312 bytes from update socket.
D/TCMD    (  464): NL - message type is RTM_NEWLINK
,D/TCMD    (  464): Listening for incoming client connection request
D/TCMD    (  464): NL - Read 180 bytes from update socket.
D/TCMD    (  464): NL - message type is RTM_NEWLINK
D/TCMD    (  464): Listening for incoming client connection request
D/TCMD    (  464): NL - Read 68 bytes from update socket.
D/TCMD    (  464): NL - message type is RTM_NEWLINK
D/TCMD    (  464): Listening for incoming client connection request
D/TCMD    (  464): NL - Read 1004 bytes from update socket.
D/TCMD    (  464): NL - message type is RTM_NEWLINK
D/TCMD    (  464): Listening for incoming client connection request
D/TCMD    (  464): NL - Read 80 bytes from update socket.
D/TCMD    (  464): NL - message type is RTM_NEWLINK
D/TCMD    (  464): Listening for incoming client connection request
D/TCMD    (  464): NL - Read 80 bytes from update socket.
D/TCMD    (  464): NL - message type is RTM_NEWLINK
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  464): Listening for incoming client connection request
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,D/TCMD    (  464): NL - Read 68 bytes from update socket.
D/TCMD    (  464): NL - message type is RTM_NEWLINK
,I/wpa_supplicant( 1449): wlan0: Associated with f4:f2:6d:22:99:3e
D/TCMD    (  464): Listening for incoming client connection request
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with f4:f2:6d
D/MDMCTBK (  294): Event received = Associated with f4:f2:6d
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Tethering(  889): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  889): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  889): ApnList is empty for checkDunConfigured()
D/Tethering(  889):  upstream interface types: 
D/Tethering(  889):  0
D/Tethering(  889):  1
D/Tethering(  889):  5
D/Tethering(  889):  7
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1449): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
D/Tethering(  889): sendTetherStateChangedBroadcast 1, 0, 0
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  294): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1449): wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294):  STA Connected !!
,D/TCMD    (  464): NL - Read 1004 bytes from update socket.
D/TCMD    (  464): NL - message type is RTM_NEWLINK
D/TCMD    (  464): Listening for incoming client connection request
,E/MDMCTBK (  294): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2422, reply_len: 4, ret: 0
D/MDMCTBK (  294): get_freq !!, resp=2422
I/MDMCTBK (  294): get_freq !!, Strip data
I/MDMCTBK (  294): get_freq !!, band = 2, freq = 2422
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
,I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  294): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  294): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1211326224
I/MDMCTBK (  294): return from set_get_from_wpa_supplicant
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  294): wifi_set_tx_pwr: SETTXPOWER = 18
,E/MDMCTBK (  294): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  294): , reply_len: 3, ret: 0
E/MDMCTBK (  294): MdmCutbackHndler, resp=OK
E/MDMCTBK (  294): 
D/MDMCTBK (  294): wifi_set_tx_pwr: Exit
D/Checkin (  889): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 26.303ms
,E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  889): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  889): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  889): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  889): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  889): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  889): Network connection established
E/WifiStateMachine(  889): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  889): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
W/ResourcesManager( 5926): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  889): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  889): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  889): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  889): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  889): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  889): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  889): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  889): ObtainingIpAddress "NG700" nid=0
I/art     ( 1556): Explicit concurrent mark sweep GC freed 28896(1844KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.247ms total 98.288ms
E/WifiConfigStore(  889): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  291): Setting iface cfg
E/WifiStateMachine(  889): Start Dhcp Watchdog 2
E/WifiStateMachine(  889): calculateWifiScore() report new score 60
I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  889): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  889): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  889): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  889): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  889): do suspend false
E/wpa_supplicant( 1449): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  889): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1449): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  889): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1f05bbcc target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  889): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1f05bbcc target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_SMS( 5926): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5926): MmsConfig.loadMmsSettings
I/Babel_SMS( 5926): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 5926): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5926): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5926): MmsConfig.loadFromResources
E/Babel_SMS( 5926): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5926): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 5926): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5926): startup - clean
,E/DHCPCD  ( 5955): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5955): version 5.5.6 starting
,E/DHCPCD  ( 5955): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 5955): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 5955): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/Babel   ( 5926): deleted: false for 0
,V/AlarmManager(  889): done {319619a9, *walarm*:android.content.syncmanager.SYNC_ALARM} [420ms]
,W/VideoCapabilities( 5926): Unrecognized profile 2130706433 for video/avc
,D/DHCPCD  ( 5955): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 5955): wlan0: rebinding lease of 192.168.1.112
D/DHCPCD  ( 5955): wlan0: sending REQUEST (xid 0x26896753), next in 4.64 seconds
,W/AudioCapabilities( 5926): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5926): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5926): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5926): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5926): Unrecognized profile 2130706433 for video/avc
,I/DHCPCD  ( 5955): wlan0: acknowledged 192.168.1.112 from 192.168.1.1
W/VideoCapabilities( 5926): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5926): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  889): Killing 5714:com.google.android.gm/u0a63 (adj 15): empty #7
,I/DHCPCD  ( 5955): wlan0: leased 192.168.1.112 for 172800 seconds
D/DHCPCD  ( 5955): wlan0: adding IP address 192.168.1.112/24
D/DHCPCD  ( 5955): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 5955): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5955): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/TCMD    (  464): NL - Read 60 bytes from update socket.
D/TCMD    (  464): NL - ignore NL message, type = 20
D/TCMD    (  464): Listening for incoming client connection request
D/DHCPCD  ( 5955): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  889): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  889): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,W/libprocessgroup(  889): failed to open /acct/uid_10063/pid_5714/cgroup.procs: No such file or directory
,I/vclib   ( 5926): onServiceConnected
W/Babel   ( 5926): Attempted to change video mute state without an active call.
,D/CAR.SERVICE( 5829): mConnectedToCar = false, abort
,E/ActivityThread( 5829): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@38f40ea1 that was originally bound here
E/ActivityThread( 5829): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@38f40ea1 that was originally bound here
E/ActivityThread( 5829): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5829): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5829): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5829): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5829): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5829): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5829): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5829): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 5829): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 5829): 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
E/ActivityThread( 5829): 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
E/ActivityThread( 5829): 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
E/ActivityThread( 5829): 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
E/ActivityThread( 5829): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5829): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5829): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5829): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5829): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5829): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5829): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5829): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5829): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5829): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 5829): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2305b52 that was originally bound here
E/ActivityThread( 5829): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2305b52 that was originally bound here
E/ActivityThread( 5829): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5829): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5829): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5829): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5829): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5829): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 5829): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 5829): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
E/ActivityThread( 5829): 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
E/ActivityThread( 5829): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
E/ActivityThread( 5829): 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
E/ActivityThread( 5829): 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
E/ActivityThread( 5829): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5829): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5829): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5829): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5829): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5829): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5829): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5829): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5829): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5829): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
W/ActivityManager(  889): Unbind failed: could not find connection for android.os.BinderProxy@1f4d488e
,E/WifiStateMachine(  889): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  889): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  889): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  889): WifiStateMachine DHCP successful
,E/WifiStateMachine(  889): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  889): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  889): Calling ARP set with IP = 192.168.1.112
,E/WifiStateMachine(  889): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  889): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  889): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  889): Adding iface wlan0 to network 101
I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  889): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  889): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/SBar.MotoNetworkCtrlr( 1299): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  889): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  889): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  889): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/ConnectivityService(  889): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService(  889): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  889): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  889): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  889): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  889): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  889): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  889): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  889):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  889): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  889): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1299): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  889): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  889): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  889): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1299): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1959): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 14 Mar 2016 12:40:17 GMT], X-Android-Received-Millis=[1457959216644], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1457959216573]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Validated
D/ConnectivityService(  889): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  889): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  889): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  889): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1959): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1299): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1299): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1299): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1299): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/ModemStatsDSDetect( 1530): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1530): Inetcondition changed, white->blue
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  889): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  889): MasterInitialState.processMessage what=3
,D/PollingManager( 2970): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1479): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2970): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2970): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2970): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  889): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6019 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  889): MasterInitialState.processMessage what=3
,D/PollingManager( 2970): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2970): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2970): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2970): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2970): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2970): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2970): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1479): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2970): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/Central_PollingManager( 1479): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2970): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2970): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2970): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2970): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2970): [debug] > CusSM.onRadioDown
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1299): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020132=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully Activity=0x00000000=( none ) Accessibility="Wifi signal full."
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ActivityThread( 1959): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  889): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 138877, reason: UserStart
,I/MusicStore( 6019): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6019): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6019): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6019): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6019): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6019): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6019): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:37000 mC
,W/ActivityThread( 6019): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6019): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6019): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6019): GMSCore installation verified
,I/ConfigStore( 6019): Config Database version: 1
,I/MediaRouter( 6019): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6019): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6019): type=WIFI subType= reason=null isConnected=true
,I/art     (  889): Explicit concurrent mark sweep GC freed 55797(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/31MB, paused 1.651ms total 135.883ms
,I/NetworkMonitor( 6019): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  889): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6070 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6019): Using our fixed implementation of GMSCore's GoogleHttpClient
I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  889): MasterInitialState.processMessage what=3
D/PollingManager( 2970): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2970): now: 106847 ,futureTime: 9223372036854775807
D/PollingManager( 2970): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2970): now: 106847 ,futureTime: 9223372036854775807
D/PollingManager( 2970): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2970): now: 106847 ,futureTime: 9223372036854775807
,I/GoogleURLConnFactory( 6019): Using platform SSLCertificateSocketFactory
,D/Central_PollingManager( 1479): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2970): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1479): now: 106860 ,futureTime: 86478929
D/Central_PollingManager( 1479): Polling alarm set to expire at: 86478929 Current Time: 106860
,D/OtaApp  ( 2970): [debug] > PollingManagerService, now: 106863 ,futureTime: 3908611
D/OtaApp  ( 2970): [debug] > Polling alarm set to expire at: 3908611 Current Time: 106864
,D/MMApiProvisionService( 2970): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2970): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2970): createDeviceIdOrLogin update_device
D/Checkin ( 2970): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2970): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2970): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2970): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2970): createDeviceIdOrLogin update_device
D/Checkin ( 2970): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2970): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2970): set mOutstandingReq to true.
I/ Nonce  ( 2970):  Nonce getNonce 
I/ Nonce  ( 2970):  Nonce Request 
I/ Nonce  ( 2970):  Nonce execute Request 
,D/MMApiWebService( 2970): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/ActivityManager(  889): Killing 5811:com.android.providers.calendar/u0a5 (adj 15): empty #7
,D/MMApiProvisionService( 2970): isDeviceProvisioned: deviceId = 2072049230914535424
,I/NetworkMonitor( 6019): type=WIFI subType= reason=null isConnected=true
,D/CCE     ( 2970): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2970): createDeviceIdOrLogin update_device
,D/Checkin ( 2970): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2970): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2970): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2970): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2970): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
V/Mms     ( 6070): mnc/mcc: 
V/Mms     ( 6070): tag: int value: recipientLimit - 20
V/Mms     ( 6070): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6070): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6070): tag: int value: maxSubjectLength - 80
V/Mms     ( 6070): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6070): tag: bool value: enableGroupMms - false
V/Mms     ( 6070):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/OtaApp  ( 2970): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2970): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2970): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2970): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2970): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2970): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/MMApiWebService( 2970): generating token using payload instead of using session token
,D/ Nonce  ( 2970):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,W/libprocessgroup(  889): failed to open /acct/uid_10005/pid_5811/cgroup.procs: No such file or directory
,I/MMApiWSBase( 2970): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/OtaApp  ( 2970): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/Checkin ( 2970): publish the event [tag = MOT_CCE event name = LOG]
,W/ResourcesManager( 6070): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  889): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6107 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 5829:com.google.android.gms:car/u0a16 (adj 15): empty #7
,W/libprocessgroup(  889): failed to open /acct/uid_10016/pid_5829/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6107): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6107): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6107): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  889): Killing 5657:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  889): failed to open /acct/uid_10032/pid_5657/cgroup.procs: No such file or directory
,I/CheckinService( 1959): Checking schedule, now: 1457959219854 next: 1457959222121
I/CheckinService( 1959): active receiver: disabled
,I/ActivityManager(  889): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6129 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/io.jxcore.node.JXcoreExtension( 5307): isBleMultipleAdvertisementSupported: NOT_SUPPORTED
I/jxcore-log( 5307): INFO testUtils BLE multiple advertisement not supported
I/jxcore-log( 5307): 
I/jxcore-log( 5307): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5307): 
,I/chromium( 5307): [INFO:CONSOLE(86)] "logCallback Device did not have required hardware capabilities!", source: file:///android_asset/www/js/thali_main.js (86)
,E/WifiStateMachine(  889): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  889): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  889): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  889): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  889): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1299): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1959): CM callback handler got msg 524295
,I/ActivityManager(  889): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6160 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel   ( 5926): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  889): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6181 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AndroidRuntime( 6149): 
D/AndroidRuntime( 6149): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6149): CheckJNI is OFF
,I/ActivityManager(  889): Killing 5784:com.motorola.context/u0a8 (adj 15): empty #7
,I/ Nonce  ( 2970):  Nonce Reponse 
D/        ( 2970): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"ce0f5c86-e139-40ca-8e2c-74a73dd84d9a"}
D/MMApiWSBase( 2970): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2970):  Nonce Handle Reponse 
D/MMApiProvisionService( 2970): mOutstandingReq set to false
,W/libprocessgroup(  889): failed to open /acct/uid_10008/pid_5784/cgroup.procs: No such file or directory
,W/ResourcesManager( 6181): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6160): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6160): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/art     ( 1479): Explicit concurrent mark sweep GC freed 4830(213KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 742us total 30.516ms
,I/CalendarProvider2( 6181): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6160): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/MMApiProvisionService( 2970):  pTime 1457886726448 sExp 172742 cTime 1457959220753 tTime 1458059468448
D/MMApiProvisionService( 2970):  No login Required 
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6160): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6160): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6160):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6160):   adb logcat -s GAv4
,W/GAv4    ( 6160): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6160): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6160): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/AndroidRuntime( 6149): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  889): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
,I/ActivityManager(  889): Killing 5307:com.test.thalitest/u0a109 (adj 0): stop com.test.thalitest
,W/PackageSettings(  889): Skipping PackageSetting{1d9e1e0a com.example.hello/10568} due to missing metadata
,I/WindowState(  889): WIN DEATH: Window{34957ab7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  889): Client connection lost with reason: 4
,W/DataUsage( 2970): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2970): publish the event [tag = MOT_CCE event name = LOG]
,W/ActivityManager(  889): Force removing ActivityRecord{2e0c8da6 u0 com.test.thalitest/.MainActivity t9}: app died, no saved state
,W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  889): Spurious death for ProcessRecord{776e9ba 5307:com.test.thalitest/u0a109}, curProc for 5307: null
,I/ActivityManager(  889): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,I/Keyboard.Facilitator( 1423): resetDictionaries() : en_US
,D/OtaApp  ( 2970): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2970): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,I/InputReader(  889): Reconfiguring input devices.  changes=0x00000010
,D/Checkin ( 2970): publish the event [tag = MOT_OTA event name = LOG]
,W/ResourcesManager( 1556): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/OtaApp  ( 2970): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2970): publish the event [tag = MOT_OTA event name = LOG]
,I/art     ( 3416): Explicit concurrent mark sweep GC freed 9937(1651KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 7MB/12MB, paused 1.725ms total 55.262ms
,D/OtaApp  ( 2970): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2970): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2970): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator.DecoderInitializer( 1423): run()
,I/art     ( 1578): Explicit concurrent mark sweep GC freed 2249(119KB) AllocSpace objects, 3(128KB) LOS objects, 25% free, 13MB/17MB, paused 473us total 96.663ms
,I/Decoder ( 1423): createOrResetDecoder
,I/WebViewFactory( 6160): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6160): Time to load native libraries: 1 ms (timestamps 8890-8891)
I/LibraryLoader( 6160): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6160): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 6160): Expected native library version number "",actual native library version number ""
I/chromium( 6160): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6160): Initializing chromium process, singleProcess=true
W/art     ( 6160): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6160): ApplicationContext is null in ApplicationStatus
,D/BackupManagerService(  889): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  889): Receieved: android.intent.action.PACKAGE_REMOVED
,W/chromium( 6160): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6160): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6160): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6160): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6160): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6160): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6160): Local Branch: 
I/Adreno-EGL( 6160): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6160): Local Patches: NONE
I/Adreno-EGL( 6160): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/SBar.MotoNetworkCtrlr( 1299): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     (  889): Explicit concurrent mark sweep GC freed 30659(2019KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/31MB, paused 4.090ms total 287.678ms
I/art     (  889): WaitForGcToComplete blocked for 228.631ms for cause Explicit
,D/TaskPersister(  889): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  889): removeObsoleteFile: deleting file=8_task.xml
,D/AndroidRuntime( 6149): Shutting down VM
,W/AudioManagerAndroid( 6160): Requires BLUETOOTH permission
,I/NSApplication( 6160): Starting up...
,I/ActivityManager(  889): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6262 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 6019:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/art     (  889): Explicit concurrent mark sweep GC freed 5121(250KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.924ms total 165.556ms
,W/GeofencerStateMachine( 1746): Ignoring removeGeofence because network location is disabled.
,I/ConfigService( 1746): onCreate
,W/InputMethodManagerService(  889): Got RemoteException sending setActive(false) notification to pid 5307 uid 10109
,I/Keyboard.Facilitator( 1423): onFinishInput()
,W/libprocessgroup(  889): failed to open /acct/uid_10080/pid_6019/cgroup.procs: No such file or directory
,I/LaunchCheckinHandler(  889): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,21950
I/LaunchCheckinHandler(  889): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,cp,ca,19640 (total)
,I/Launcher( 1578): Deferring update until onResume
,I/CalendarProvider2( 6181): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6181): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  889): Killing 6070:com.android.mms/u0a23 (adj 15): empty #7
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1423): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1423): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Loading LM = contacts
,I/ActivityManager(  889): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6283 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,W/libprocessgroup(  889): failed to open /acct/uid_10023/pid_6070/cgroup.procs: No such file or directory
,I/ActivityManager(  889): Killing 6107:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  889): failed to open /acct/uid_10035/pid_6107/cgroup.procs: No such file or directory
,I/ActivityManager(  889): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6303 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  889): Killing 6129:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  889): failed to open /acct/uid_10088/pid_6129/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Loading LM = user
,W/ResourcesManager( 6303): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1423): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1423): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1423): run()
I/StatsUtilsManager( 1423): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1423): shouldRecordStats() = Too Soon
,I/ActivityManager(  889): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6329 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1299): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )

```
