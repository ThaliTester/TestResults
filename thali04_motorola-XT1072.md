#### Test 625090944a5472b_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/CE-UpdateModelService( 5065): ACTION_REGISTRATION_COMPLETE
--------- beginning of system
I/ActivityManager(  892): Killing 4904:com.google.android.deskclock/u0a55 (adj 15): empty #7
W/libprocessgroup(  892): failed to open /acct/uid_10055/pid_4904/cgroup.procs: No such file or directory
D/3CDM.DeviceAdminPushReceiver( 2635): Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.DeviceAdminPushReceiver( 2635): Type: null
D/3CDM.DeviceAdminPushReceiver( 2635): Data: null
D/3CDM.Service( 2635): com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.Service( 2635): Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
D/3CDM.Service( 2635): DeviceAdmin - syncWithCCC
D/3CDM.Service( 2635): blur.service.littlesister.gpsFixWaitTime = 60000
D/3CDM.Service( 2635): com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
D/3CDM.Service( 2635): blur.service.cred.locationToken = null
D/3CDM.Service( 2635): com.motorola.ccc.cce.email.marketing.optin.default = false
D/3CDM.Service( 2635): blur.service.littlesister.reportLevel2 = NONE
D/3CDM.Service( 2635): com.motorola.blur.adminfeed.device_admin_always_allowed = 1
D/3CDM.Service( 2635): com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
D/3CDM.Service( 2635): Sync to CCE settings done, instantiate Locate now.
,I/ActivityManager(  892): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5092 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BSUtils ( 2635): set .setup.DeviceAdminSetupReceiver enabled
I/Gmail   ( 4989): getAccountsCursor
V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5092): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/CalendarProvider2( 5092): Created com.android.providers.calendar.CalendarAlarmManager@a512a8f(com.android.providers.calendar.CalendarProvider2@1920e11c)
V/AlarmManager(  892): done {3b140e3, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [9371ms]
V/AlarmManager(  892): done {1cd8903f, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED} [9085ms]
E/WifiStateMachine(  892): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=26.84 rxSuccessRate=23.08 targetRoamBSSID=any RSSI=-43
E/WifiStateMachine(  892): WifiStateMachine CMD_START_SCAN with age=17202 interval=30000 maxinterval=300000
E/WifiStateMachine(  892): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  892): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  892): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
V/AlarmManager(  892): done {13951ef1, *alarm*:com.android.server.WifiManager.action.START_SCAN} [8316ms]
I/wpa_supplicant( 1448): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  892): [1,457,941,851,179 ms] noteScanstart no scan source
E/SQLiteLog( 5092): (284) automatic index on view_events(_id)
I/ActivityManager(  892): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5114 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  892): [1,457,941,851,242 ms] noteScanEnd no scan source
E/WifiStateMachine(  892): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2ed4b0e sup_state=COMPLETED debouncing=false
D/PhoneMonitor( 5114): Register our PhoneStateListener
D/Checkin ( 3203): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
V/SetupWizard( 5114): Connected to Gservices successfully
I/ActivityManager(  892): Killing 3586:com.android.defcontainer/u0a10 (adj 15): empty #7
D/AndroidRuntime( 5108): 
D/AndroidRuntime( 5108): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5108): CheckJNI is OFF
W/libprocessgroup(  892): failed to open /acct/uid_10010/pid_3586/cgroup.procs: No such file or directory
I/ActivityManager(  892): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5151 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/GCM     ( 1709): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/ResourcesManager( 5151): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/AndroidRuntime( 5108): Calling main entry com.android.commands.am.Am
I/ActivityManager(  892): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (168 us)
W/ContextImpl( 1480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5108): Shutting down VM
I/ActivityManager(  892): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5172 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/Babel_SMS( 5151): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5151): MmsConfig.loadMmsSettings
I/Babel_SMS( 5151): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5151): MmsConfig.loadFromDatabase
E/Babel_SMS( 5151): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5151): MmsConfig.loadFromResources
E/Babel_SMS( 5151): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5151): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
D/MMApiWSBase( 2635): doRequest(): v1/cs/checkin resp length: 4
D/CCE     ( 2635): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
D/CCE     ( 2635): AppWSProxy - sendAIDLWSResponse() sending reponse
I/global frequency( 2635): BcsCore.status() called with error code=ERROR_OK
D/Checkin ( 2635): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/CheckinProvider(  892): 90 events delete 0 left
,W/art     ( 5151): Suspending all threads took: 15.229ms
,I/global frequency( 2635): BcsDSCheckin.events found events 0
,D/Checkin ( 2635): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/CalendarProvider2( 5092): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/WebViewFactory( 5172): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/ContentResolver( 5092): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/BSUtils ( 2635): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2635): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2635): BcsTimer.onReceive checkin completed (865775120:ERROR_OK)
,D/Checkin ( 2635): publish the event [tag = MOT_CHECKIN event name = LOG]
,W/Settings( 5151): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5151): startup - clean
,I/LibraryLoader( 5172): Time to load native libraries: 2 ms (timestamps 157-159)
I/LibraryLoader( 5172): Expected native library version number "",actual native library version number ""
,I/Babel   ( 5151): deleted: false for 0
,V/WebViewChromiumFactoryProvider( 5172): Binding Chromium to main looper Looper (main, tid 1) {157b42fa}
,I/LibraryLoader( 5172): Expected native library version number "",actual native library version number ""
I/chromium( 5172): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5172): Initializing chromium process, singleProcess=true
,W/art     ( 5172): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5172): ApplicationContext is null in ApplicationStatus
,W/chromium( 5172): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5172): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5172): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5172): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5172): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5172): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5172): Local Branch: 
I/Adreno-EGL( 5172): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5172): Local Patches: NONE
I/Adreno-EGL( 5172): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  892): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=5219 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 4948:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.274ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 19.506ms
,D/BluetoothManagerService(  892): Message: 20
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.353ms
,W/DataUsage( 2635): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2635): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  892): failed to open /acct/uid_10080/pid_4948/cgroup.procs: No such file or directory
,I/art     (  892): Explicit concurrent mark sweep GC freed 17508(862KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 2.629ms total 181.541ms
,D/BluetoothManagerService(  892): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@143469d:true
,W/VideoCapabilities( 5151): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5151): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5151): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5151): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5151): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5151): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5151): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5151): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5151): onServiceConnected
W/Babel   ( 5151): Attempted to change video mute state without an active call.
,W/art     ( 5172): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5172): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5172): CordovaWebView is running on device made by: motorola
,W/art     ( 5172): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5172): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5172): Render dirty regions requested: true
,D/Atlas   ( 5172): Validating map...
,W/chromium( 5172): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  892): Killing 5017:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10060/pid_5017/cgroup.procs: No such file or directory
,I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (16:191 vsyncs) (18:938)
,I/OpenGLRenderer( 5172): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5172): Enabling debug mode 0
,I/SFPerfTracer(  280):      triggers: (rate: 14:520) (compose: 0:1) (post: 0:1) (render: 0:2) (0:860 frames) (1:939)
D/SFPerfTracer(  280):        layers: (3:13) (FocusedStackFrame (0xb805ab50): 0:12)* (DimLayer (0xb804e570): 0:6)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb8052008): 0:33)- (StatusBar (0xb8042880): 0:129) (NavigationBar (0xb8044598): 0:36) (com.android.systemui.ImageWallpaper (0xb80492d0): 0:5)* (Starting com.motorola.ccc.ota (0xb8075190): 0:39)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8076420): 0:56)- (Starting com.test.thalitest (0xb8051fe0): 0:28) (com.test.thalitest/com.test.thalitest.MainActivity (0xb8074230): 1:1)* 
I/ActivityManager(  892): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5252 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Keyboard.Facilitator( 1426): onFinishInput()
,I/LaunchCheckinHandler(  892): Displayed com.test.thalitest/.MainActivity,cp,ca,1266
,I/ActivityManager(  892): Displayed com.test.thalitest/.MainActivity: +1s266ms
I/ActivityManager(  892): Killing 4989:com.google.android.gm/u0a63 (adj 15): empty #7
,E/Adreno-ES20( 5172): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5172): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5172): Cannot call determinedVisibility() - never saw a connection for the pid: 5172
,W/libprocessgroup(  892): failed to open /acct/uid_10063/pid_4989/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/JsMessageQueue( 5172): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  892): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5285 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5304 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5065:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10008/pid_5065/cgroup.procs: No such file or directory
,W/ResourcesManager( 5151): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5151): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Adreno-ES20( 5172): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5172): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,V/JNIHelp ( 5151): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/jxcore_app_log( 5172): JniHelper::setJavaVM(0xb7672310), pthread_self() = -1214141024
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5172): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5172):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5172):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5172):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5172):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5172): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3253ee26 added. We now have 1 listener(s)
D/BluetoothManagerService(  892): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5172): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5172): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5172): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5172): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5172): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5172): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5172):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5172):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5172):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5172):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5172):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5172):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5172):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5172):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5172):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5172): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27cd70bd added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5172): addListener: New listener added - the number of listeners is now 1
,W/System  ( 5151): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5151): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  892): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5328 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  892): Killing 5114:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,D/WifiService(  892): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5172): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5172): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
E/io.jxcore.node.ConnectionHelper( 5172): Constructor: Bluetooth LE discovery mode is not supported
,I/ContactLocale( 5304): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  892): failed to open /acct/uid_10035/pid_5114/cgroup.procs: No such file or directory
,W/asset   ( 5328): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5328): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5328): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5328): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/chromium( 5172): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/UpdateIcingCorporaServi( 5252): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1582): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3419dc87 new=com.google.android.velvet.VelvetApplication@3419dc87
,D/PkgBroadcastIntentOp( 1945): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  892): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5355 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PkgBroadcastIntentOp( 1945): Null package name or gms related package.  Ignoreing.
,D/WearableController( 1945): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/Icing   ( 1945): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 5355): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5252): UpdateCorporaTask done [took 299 ms] updated apps [took 298 ms] 
,I/ActivityManager(  892): Killing 5219:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10088/pid_5219/cgroup.procs: No such file or directory
,I/ActivityManager(  892): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5386 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5092:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10005/pid_5092/cgroup.procs: No such file or directory
,D/Finsky  ( 5386): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5386): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5386): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5386): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 5386): Skipping gmscore version check
,D/TaskPersister(  892): removeObsoleteFile: deleting file=8_task_thumbnail.png
,D/Finsky  ( 5386): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5386): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5386): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/UpdateIcingCorporaServi( 5252): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/PkgBroadcastIntentOp( 1945): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/Finsky  ( 5386): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/WearableController( 1945): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/art     ( 1945): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,I/Icing   ( 1945): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,W/jxcore-log( 5172): Initializing JXcore engine
W/jxcore-log( 5172): JXcore engine is ready
,D/AsyncTaskServiceImpl( 1945): Submit a task: k
,D/k       ( 1945): Processing package: com.test.thalitest
,D/GassUtils( 1945): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 1945): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1945): Using Auth Proxy for data requests.
,W/BaseAppContext( 1945): Using Auth Proxy for data requests.
,W/Thread-570( 5344): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[5791]" dev="sockfs" ino=5791 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-570( 5344): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-570( 5344): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[9487]" dev="sockfs" ino=9487 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-570( 5344): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[21972]" dev="sockfs" ino=21972 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5172): Starting JXcore engine
,I/ActivityManager(  892): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5446 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 1945): Using Auth Proxy for data requests.
,W/BaseAppContext( 1945): Using Auth Proxy for data requests.
,I/Icing   ( 1945): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,W/BaseAppContext( 1945): Using Auth Proxy for data requests.
,I/UpdateIcingCorporaServi( 5252): UpdateCorporaTask done [took 560 ms] updated apps [took 559 ms] 
,I/ActivityManager(  892): Killing 5355:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/PeopleDatabaseHelper( 1945): cleanUpNonGplusAccounts done.
,W/libprocessgroup(  892): failed to open /acct/uid_10090/pid_5355/cgroup.procs: No such file or directory
,I/art     ( 4086): Explicit concurrent mark sweep GC freed 2450(90KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 400us total 29.975ms
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     (  892): Explicit concurrent mark sweep GC freed 15342(758KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.687ms total 127.929ms
,I/GAv4    ( 5446): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5446):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5446):   adb logcat -s GAv4
,W/GAv4    ( 5446): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5446): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5446): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5446): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,I/Icing   ( 1945): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
I/Icing   ( 1945): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/Icing   ( 1945): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5446): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,I/ActivityManager(  892): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5484 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5446): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5446): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  892): Killing 5304:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10007/pid_5304/cgroup.procs: No such file or directory
,V/AlarmManager(  892): send {9a40ec9, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,W/ResourcesManager( 5484): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 5446): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Icing   ( 1945): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,W/System  ( 5446): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5446): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  892): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5512 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5530 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5530): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Finsky  ( 5386): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/ActivityManager(  892): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5550 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CalendarProvider2( 5530): Created com.android.providers.calendar.CalendarAlarmManager@a512a8f(com.android.providers.calendar.CalendarProvider2@1920e11c)
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 21.461ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.060ms
,I/ContactLocale( 5512): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.811ms
,I/ActivityManager(  892): Killing 5285:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10019/pid_5285/cgroup.procs: No such file or directory
,I/ActivityManager(  892): Killing 5328:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,I/Gmail   ( 5550): getAccountsCursor
,W/libprocessgroup(  892): failed to open /acct/uid_10027/pid_5328/cgroup.procs: No such file or directory
,D/ActivityThread( 5550): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  892): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5574 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:36000 mC
,W/GAV2    ( 5550): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  892): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 5574): EasService.onCreate
,I/Gmail   ( 5550): Observing account changes for notifications
,I/Exchange( 5574): RestartPingTask
,I/Exchange( 5574): RestartPingsTask did not start any pings.
I/Exchange( 5574): PSS stopIfIdle
I/Exchange( 5574): PSS has no active accounts; stopping service.
,I/ActivityManager(  892): Killing 3294:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10049/pid_3294/cgroup.procs: No such file or directory
,I/Exchange( 5574): onDestroy
,I/ActivityManager(  892): Killing 5252:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/Gmail   ( 5550): getAccountsCursor
,W/libprocessgroup(  892): failed to open /acct/uid_10039/pid_5252/cgroup.procs: No such file or directory
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/3CDM.DeviceAdminSetupReceiver( 2635): received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,D/3CDM.DeviceAdminSetupReceiver( 2635): time to show notification
,I/ActivityManager(  892): Killing 5446:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/ResourcesManager( 1302): Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,I/ActivityManager(  892): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.WidgetDataReceiver: pid=5617 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  892): failed to open /acct/uid_10057/pid_5446/cgroup.procs: No such file or directory
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  892): Killing 5151:com.google.android.talk/u0a70 (adj 15): empty #7
,E/ActivatableNotificationView( 1302):  oops Width=0 ActualHeight=128
,E/SQLiteLog( 5550): (283) recovered 121 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 5550): notifyAccountChanged
,I/Gmail   ( 5550): getAccountsCursor
,I/Gmail   ( 5550): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5550): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5550): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5550): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/CalendarProvider2( 5530): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5530): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/libprocessgroup(  892): failed to open /acct/uid_10070/pid_5151/cgroup.procs: No such file or directory
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  892): Killing 5512:android.process.acore/u0a7 (adj 13): empty #7
,E/SQLiteLog( 5617): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,W/libprocessgroup(  892): failed to open /acct/uid_10007/pid_5512/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5550): getAccountsCursor
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  892): Killing 5484:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/AnalyticsLogBase( 5617): PlayLogger.onLoggerConnected
,W/libprocessgroup(  892): failed to open /acct/uid_10090/pid_5484/cgroup.procs: No such file or directory
,I/ActivityManager(  892): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5644 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/art     (  892): Explicit concurrent mark sweep GC freed 12239(614KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.368ms total 148.502ms
,W/ResourcesManager( 5644): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,V/AlarmManager(  892): done {9a40ec9, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [2581ms]
,E/SQLiteLog( 5530): (284) automatic index on view_events(_id)
,V/AlarmManager(  892): send {23598fd8, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
V/AlarmManager(  892): send {13951ef1, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  892): done {23598fd8, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [3ms]
,V/AlarmManager(  892): done {13951ef1, *alarm*:com.android.server.WifiManager.action.START_SCAN} [5ms]
,E/WifiStateMachine(  892): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.36 rxSuccessRate=4.63 targetRoamBSSID=any RSSI=-43
E/WifiStateMachine(  892): WifiStateMachine CMD_START_SCAN with age=26003 interval=30000 maxinterval=300000
E/WifiStateMachine(  892): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  892): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
,E/WifiStateMachine(  892): [1,457,941,859,976 ms] noteScanstart no scan source
I/wpa_supplicant( 1448): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,V/AlarmManager(  892): send {2d0812d9, *alarm*:android.intent.action.TIME_TICK}
,D/Finsky  ( 5386): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  892): done {2d0812d9, *alarm*:android.intent.action.TIME_TICK} [35ms]
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,E/WifiStateMachine(  892): [1,457,941,860,046 ms] noteScanEnd no scan source
,E/WifiStateMachine(  892): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2ed4b0e sup_state=COMPLETED debouncing=false
,V/AlarmManager(  892): send {1239c1ee, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  892): done {1239c1ee, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [1ms]
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5386): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5386): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5386): untagSocket(37) failed with errno -22
,D/Finsky  ( 5386): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  892): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5692 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5692): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5692): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5692): VM with version 2.1.0 has multidex support
I/MultiDex( 5692): install
I/MultiDex( 5692): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5692): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5692): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5692): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37309bfe: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5692): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1709): callingUid 10016, callindPid: 1709
,E/MDM     ( 1709): [165] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1945): Restart initialization of location
,D/AuthorizationBluetoothService( 1709): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ChimeraCfgMgr( 5692): Reading stored module config
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1709): No location to return for getLastLocation()
,W/FusedLocationProvider( 1709): location=null
,D/NativeLibraryUtils( 5692): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 5692): Connecting to CarCallService...
,I/art     ( 5692): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5692): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/qtaguid ( 5386): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5386): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5386): untagSocket(37) failed with errno -22
,D/CAR.SERVICE( 5692): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5692): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5692): Creating a new PhoneAdapter instance
,W/ActivityManager(  892): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5692): setListener: com.google.android.gms.car.dn@392979ba
W/ActivityManager(  892): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5692): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5692): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 5692): Package validated; name: com.android.vending
,V/Finsky  ( 5386): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:274 vsyncs) (1:1039)
,I/SFPerfTracer(  280):      triggers: (rate: 14:523) (compose: 0:1) (post: 0:1) (render: 0:2) (0:949 frames) (1:1039)
D/SFPerfTracer(  280):        layers: (3:10) (FocusedStackFrame (0xb805ab50): 0:14)* (DimLayer (0xb804e570): 0:6)* (StatusBar (0xb8042880): 1:169) (NavigationBar (0xb8044598): 0:36) (com.android.systemui.ImageWallpaper (0xb80492d0): 0:5)* (Starting com.test.thalitest (0xb8051fe0): 0:39)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8074230): 0:56) 
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/qtaguid ( 5386): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5386): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5386): untagSocket(37) failed with errno -22
,W/ActivityManager(  892): getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,W/ResourcesManager( 5386): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5386): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5386): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5386): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  892): send {2db87675, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,V/AlarmManager(  892): done {2db87675, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [24ms]
,D/DeviceConnectionService( 1709): client connected with version: 8296000
,D/Finsky  ( 5386): [610] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5386): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5386): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  892): Killing 5574:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10060/pid_5574/cgroup.procs: No such file or directory
,I/GAV2    ( 5550): Thread[GAThread,5,main]: No campaign data found.
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ContextImpl( 5617): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 5617): Thread[GAThread,5,main]: No campaign data found.
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/CAR.SERVICE( 5692): mConnectedToCar = false, abort
,E/ActivityThread( 5692): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1ad44062 that was originally bound here
E/ActivityThread( 5692): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1ad44062 that was originally bound here
E/ActivityThread( 5692): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5692): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5692): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5692): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5692): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5692): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5692): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5692): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 5692): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 5692): 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
E/ActivityThread( 5692): 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
E/ActivityThread( 5692): 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
E/ActivityThread( 5692): 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
E/ActivityThread( 5692): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5692): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5692): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5692): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5692): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5692): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5692): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5692): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5692): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5692): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 5692): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3ffc6ae5 that was originally bound here
E/ActivityThread( 5692): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3ffc6ae5 that was originally bound here
E/ActivityThread( 5692): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5692): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5692): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5692): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5692): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5692): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 5692): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 5692): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
E/ActivityThread( 5692): 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
E/ActivityThread( 5692): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
E/ActivityThread( 5692): 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
E/ActivityThread( 5692): 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
E/ActivityThread( 5692): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5692): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5692): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5692): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5692): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5692): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5692): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5692): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5692): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5692): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
W/ActivityManager(  892): Unbind failed: could not find connection for android.os.BinderProxy@39e89a4f
,V/AlarmManager(  892): send {2f27f5dc, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  892): done {2f27f5dc, *walarm*:android.content.syncmanager.SYNC_ALARM} [2ms]
,W/jxcore-log( 5172): Platform android
W/jxcore-log( 5172): 
W/jxcore-log( 5172): Process ARCH arm
W/jxcore-log( 5172): 
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/jxcore-log( 5172): JXcore Cordova bridge is ready!
I/jxcore-log( 5172): 
,W/jxcore-log( 5172): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5172): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 5172): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:36000 mC
,I/ActivityManager(  892): Killing 5530:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/ActivityManager(  892): Killing 5644:com.motorola.context/u0a8 (adj 15): empty #8
,W/libprocessgroup(  892): failed to open /acct/uid_10005/pid_5530/cgroup.procs: No such file or directory
,W/libprocessgroup(  892): failed to open /acct/uid_10008/pid_5644/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/jxcore-log( 5172): INFO testUtils Toggling radios to: true
I/jxcore-log( 5172): 
,D/BluetoothAdapter( 5172): enable(): BT is already enabled..!
I/jxcore-log( 5172): Unit Test app is loaded
I/jxcore-log( 5172): 
,D/WifiService(  892): setWifiEnabled: true pid=5172, uid=10109
E/WifiService(  892): Invoking mWifiStateMachine.setWifiEnabled
,I/chromium( 5172): [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,I/wpa_supplicant( 1448): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293):  STA Disconnected !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1448): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE,
I/wpa_supplicant( 1448): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  892): WifiStateMachine: Leaving Connected state
,D/Tethering(  892): InitialState.processMessage what=4
,W/Settings(  892): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  892): ApnList is empty for checkDunConfigured()
D/Tethering(  892):  upstream interface types: 
D/Tethering(  892):  1
D/Tethering(  892):  5
D/Tethering(  892):  7
D/Tethering(  892):  0
D/Tethering(  892): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  892): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  892): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  892): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  892): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  892): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  892): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  892): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1448): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  291): Clearing all IP addresses on wlan0
D/TCMD    (  472): NL - Read 60 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 21
D/TCMD    (  472): Listening for incoming client connection request
,E/WifiStateMachine(  892): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  892): setDetailed state send new extra info<unknown ssid>
,V/NativeCrypto( 1709): Read error: ssl=0xb7a94208: I/O error during system call, Connection timed out
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/NativeCrypto( 1709): SSL shutdown failed: ssl=0xb7a94208: I/O error during system call, Broken pipe
,I/SBar.MotoNetworkCtrlr( 1302): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  892): connected time updated 42880
,D/ConnectivityService(  892): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  892): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/GCM     ( 1709): Wifi connection closed with errorCode 20
,D/ConnectivityService(  892): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): DefaultState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/LaunchCheckinHandler(  892): cleanup(): cleared. Last call was 15078 ms ago
I/ActivityManager(  892): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=5775 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1302): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/wpa_supplicant( 1448): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  892): Start Disconnecting Watchdog 1
,D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1448): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  892): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  892): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  892): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/WifiP2pService(  892): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  892): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1448): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/CommandListener(  291): Clearing all IP addresses on wlan0
D/ConnectivityService(  892): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  892): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Nat464Xlat(  892): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1302): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  892): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  892): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Disconnected - quitting
E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  892): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 1945): CM callback handler got msg 524292
,E/WifiStateMachine(  892): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  892): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/ModemStatsDSDetect( 1528): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1528): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1528): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1302): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1528): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1528): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1528): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1302): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1302): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  892): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  892): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  892): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  892): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  892): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  892): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  892): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  892): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
W/ResourcesManager( 5775): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  892): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5803 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5550:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10063/pid_5550/cgroup.procs: No such file or directory
,W/ResourcesManager( 5803): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5803): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5803): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5803): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5803): MmsConfig.loadFromDatabase
,I/wpa_supplicant( 1448): wlan0: Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1448): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 17 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 17 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 18 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 18 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 19 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 19 
D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 20 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 20 
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 21 
D/TCMD    (  472): Listening for incoming client connection request
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 21 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 22 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 22 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 23 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 23 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  293): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  293): Event received = Trying to associate with
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiMonitor(  892): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  892): [1,457,941,876,349 ms] noteScanEnd no scan source
,E/WifiStateMachine(  892): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@21be80c5 sup_state=SCANNING debouncing=false
,E/Babel_SMS( 5803): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5803): MmsConfig.loadFromResources
E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  892): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  892): setDetailed state send new extra info0x
,E/Babel_SMS( 5803): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5803): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/TCMD    (  472): NL - Read 312 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 180 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/TCMD    (  472): NL - Read 80 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 80 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
I/wpa_supplicant( 1448): wlan0: Associated with f4:f2:6d:22:99:3e
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with f4:f2:6d
D/MDMCTBK (  293): Event received = Associated with f4:f2:6d
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  892): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/Tethering(  892): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  892): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  892): ApnList is empty for checkDunConfigured()
D/Tethering(  892):  upstream interface types: 
D/Tethering(  892):  0
D/Tethering(  892):  1
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1448): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  293): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1448): wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293):  STA Connected !!
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,E/MDMCTBK (  293): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2422, reply_len: 4, ret: 0
D/MDMCTBK (  293): get_freq !!, resp=2422
I/MDMCTBK (  293): get_freq !!, Strip data
,I/MDMCTBK (  293): get_freq !!, band = 2, freq = 2422
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
,I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  293): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
,I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  293): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  293): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
,I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1193421344
I/MDMCTBK (  293): return from set_get_from_wpa_supplicant
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
D/MDMCTBK (  293): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  892):  5
D/Tethering(  892):  7
D/Tethering(  892): sendTetherStateChangedBroadcast 1, 0, 0
,E/MDMCTBK (  293): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  293): , reply_len: 3, ret: 0
E/MDMCTBK (  293): MdmCutbackHndler, resp=OK
E/MDMCTBK (  293): 
D/MDMCTBK (  293): wifi_set_tx_pwr: Exit
,E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  892): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  892): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  892): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,W/Settings( 5803): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine(  892): Network connection established
E/WifiStateMachine(  892): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  892): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/Babel_Crash( 5803): startup - clean
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  892): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  892): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  892): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  892): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  892): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  892): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  892): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  892): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  892): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  291): Setting iface cfg
E/WifiStateMachine(  892): Start Dhcp Watchdog 2
,E/WifiStateMachine(  892): calculateWifiScore() report new score 60
,I/Babel   ( 5803): deleted: false for 0
D/ConnectivityService(  892): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  892): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  892): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  892): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  892): do suspend false
,E/wpa_supplicant( 1448): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  892): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1448): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  892): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@24f5bf97 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  892): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@24f5bf97 target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 5803): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5803): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5803): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5803): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5803): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5803): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5803): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5803): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  892): Killing 5617:com.google.android.calendar/u0a49 (adj 15): empty #7
,E/DHCPCD  ( 5853): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5853): version 5.5.6 starting
,E/DHCPCD  ( 5853): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 5853): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 5853): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  892): failed to open /acct/uid_10049/pid_5617/cgroup.procs: No such file or directory
,I/vclib   ( 5803): onServiceConnected
,W/Babel   ( 5803): Attempted to change video mute state without an active call.
V/AlarmManager(  892): send {388b291a, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  892): done {388b291a, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [15ms]
,D/DHCPCD  ( 5853): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 5853): wlan0: rebinding lease of 192.168.1.112
D/DHCPCD  ( 5853): wlan0: sending REQUEST (xid 0xbafa5bfa), next in 4.22 seconds
,I/DHCPCD  ( 5853): wlan0: acknowledged 192.168.1.112 from 192.168.1.1
,I/DHCPCD  ( 5853): wlan0: leased 192.168.1.112 for 172800 seconds
,D/DHCPCD  ( 5853): wlan0: adding IP address 192.168.1.112/24
D/TCMD    (  472): NL - Read 60 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 20
,D/TCMD    (  472): Listening for incoming client connection request
D/DHCPCD  ( 5853): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 5853): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5853): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/DHCPCD  ( 5853): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  892): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  892): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/Finsky  ( 5386): [600] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5386): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/WifiStateMachine(  892): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  892): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  892): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  892): WifiStateMachine DHCP successful
E/WifiStateMachine(  892): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  892): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  892): Calling ARP set with IP = 192.168.1.112
,E/WifiStateMachine(  892): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  892): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  892): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  892): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1302): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  892): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  892): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  892): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine(  892): ConnectedState Enter  mScreenOn=true scanperiod=20000
,D/ConnectivityService(  892): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  892): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  892): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  892): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  892): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  892): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  892): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  892):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  892): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  892): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1528): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  892): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/ModemStatsDSDetect( 1528): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1528): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1302): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  892): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  892): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1302): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1945): CM callback handler got msg 524290
,V/AlarmManager(  892): send {13951ef1, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  892): done {13951ef1, *alarm*:com.android.server.WifiManager.action.START_SCAN} [2ms]
,E/WifiStateMachine(  892): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=141.00 rxSuccessRate=130.50 targetRoamBSSID=any RSSI=-43
,E/WifiStateMachine(  892): WifiStateMachine CMD_START_SCAN with age=43463 interval=20000 maxinterval=300000
E/WifiStateMachine(  892): WifiStateMachine CMD_START_SCAN try full band scan age=43463 interval=20000 maxinterval=300000
,E/WifiStateMachine(  892): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  892): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=141.00 rx=130.50
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 14 Mar 2016 07:51:17 GMT], X-Android-Received-Millis=[1457941877536], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1457941877474]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Validated
D/ConnectivityService(  892): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  892): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  892): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  892): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1302): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1945): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1528): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1528): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1528): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1528): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1302): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1302): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1302): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  892): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:35000 mC
,D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  892): MasterInitialState.processMessage what=3
,D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1480): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2635): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  892): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5912 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  892): MasterInitialState.processMessage what=3
,D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2635): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/Central_PollingManager( 1480): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2635): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/Central_PollingManager( 1480): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2635): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2635): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2635): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2635): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2635): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2635): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2635): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2635): [debug] > CusSM.onRadioDown
,I/ActivityManager(  892): Start proc com.google.android.apps.docs.editors.sheets for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService: pid=5943 uid=10105 gids={50105, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 1945): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  892): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 179481, reason: UserStart
,I/MusicStore( 5912): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5912): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5912): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5912): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     (  892): Explicit concurrent mark sweep GC freed 62741(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/31MB, paused 1.737ms total 130.885ms
,W/ResourcesManager( 5912): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5912): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5912): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5912): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5912): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2dda93d1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5912): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5912): GMSCore installation verified
,I/ConfigStore( 5912): Config Database version: 1
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1302): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020132=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully Activity=0x00000000=( none ) Accessibility="Wifi signal full."
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/MediaRouter( 5912): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5912): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5912): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5912): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  892): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5979 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 5912): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5912): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  892): Killing 5692:com.google.android.gms:car/u0a16 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10016/pid_5692/cgroup.procs: No such file or directory
,V/Mms     ( 5979): mnc/mcc: 
,V/Mms     ( 5979): tag: int value: recipientLimit - 20
V/Mms     ( 5979): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 5979): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 5979): tag: int value: maxSubjectLength - 80
V/Mms     ( 5979): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 5979): tag: bool value: enableGroupMms - false
,V/Mms     ( 5979):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/GAv4    ( 5943): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5943):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5943):   adb logcat -s GAv4
,W/GAv4    ( 5943): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5943): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 5979): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/GAv4    ( 5943): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5943): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.312.11.30
,I/ActivityManager(  892): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6016 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5803:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10070/pid_5803/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6016): Register our PhoneStateListener
,E/SQLiteLog( 5943): (283) recovered 25 frames from WAL file /data/data/com.google.android.apps.docs.editors.sheets/databases/DocList.db-wal
,D/MobileConnectivityChangeReceiver( 6016): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6016): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  892): Killing 5386:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10032/pid_5386/cgroup.procs: No such file or directory
,I/CheckinService( 1945): Checking schedule, now: 1457941880219 next: 1457941875039
I/CheckinService( 1945): active receiver: enabled
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  892): MasterInitialState.processMessage what=3
,D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1480): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2635): now: 118224 ,futureTime: 9223372036854775807
D/Central_PollingManager( 1480): now: 118224 ,futureTime: 86480156
D/Central_PollingManager( 1480): Polling alarm set to expire at: 86480156 Current Time: 118224
D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2635): now: 118225 ,futureTime: 9223372036854775807
,I/NetworkMonitor( 5912): type=WIFI subType= reason=null isConnected=true
,D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2635): now: 118227 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2635): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2635): [debug] > PollingManagerService, now: 118230 ,futureTime: 21259069
,D/OtaApp  ( 2635): [debug] > Polling alarm set to expire at: 21259069 Current Time: 118231
,I/CheckinService( 1945): Preparing to send checkin request
I/EventLogService( 1945): Accumulating logs since 1457941836888
,D/MMApiProvisionService( 2635): isDeviceProvisioned: deviceId = 2072049230914535424
,I/ActivityManager(  892): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6049 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1945): Checkin reason type: 8 attempt count: 1
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 22.480ms
,D/CCE     ( 2635): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2635): createDeviceIdOrLogin update_device
,D/Checkin ( 2635): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2635): Not proxy app, so login/provision not allowed
,E/ActivityThread( 1945): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 346us total 19.559ms
,D/MMApiProvisionService( 2635): isDeviceProvisioned: deviceId = 2072049230914535424
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 20.610ms
,D/CCE     ( 2635): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2635): createDeviceIdOrLogin update_device
,D/Checkin ( 2635): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2635): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2635): set mOutstandingReq to true.
I/ Nonce  ( 2635):  Nonce getNonce 
I/ Nonce  ( 2635):  Nonce Request 
I/ Nonce  ( 2635):  Nonce execute Request 
,D/MMApiWebService( 2635): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2635): isDeviceProvisioned: deviceId = 2072049230914535424
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CCE     ( 2635): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2635): createDeviceIdOrLogin update_device
D/Checkin ( 2635): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2635): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2635): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2635): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2635): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2635): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2635): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2635): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2635): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2635): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2635): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2635): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/ResourcesManager( 5943): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5943): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/MMApiWebService( 2635): generating token using payload instead of using session token
,V/JNIHelp ( 5943): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 5943): Installed default security provider GmsCore_OpenSSL
,I/art     (  892): Explicit concurrent mark sweep GC freed 11944(589KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.746ms total 121.089ms
,D/ Nonce  ( 2635):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2635): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2635): publish the event [tag = MOT_CCE event name = LOG]
,V/io.jxcore.node.JXcoreExtension( 5172): isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,I/jxcore-log( 5172): INFO testUtils BLE multiple advertisement not supported
I/jxcore-log( 5172): 
,I/chromium( 5172): [INFO:CONSOLE(86)] "logCallback Device did not have required hardware capabilities!", source: file:///android_asset/www/js/thali_main.js (86)
,I/jxcore-log( 5172): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5172): 
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  892): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6076 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6093 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 5775:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10008/pid_5775/cgroup.procs: No such file or directory
,W/ResourcesManager( 6093): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6076): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6076): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6076): VM with version 2.1.0 has multidex support
I/MultiDex( 6076): install
I/MultiDex( 6076): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6076): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/WifiStateMachine(  892): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  892): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  892): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  892): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  892): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1302): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1945): CM callback handler got msg 524295
,W/ActivityThread( 6076): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6076): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37309bfe: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6076): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6076): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6076): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/AndroidRuntime( 6074): 
D/AndroidRuntime( 6074): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6074): CheckJNI is OFF
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel_SMS( 6093): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6093): MmsConfig.loadMmsSettings
I/Babel_SMS( 6093): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6093): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6093): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6093): MmsConfig.loadFromResources
E/Babel_SMS( 6093): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6093): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/NativeLibraryUtils( 6076): Install completed successfully. count=14 extracted=0
,W/Settings( 6093): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6093): startup - clean
,I/Babel   ( 6093): deleted: false for 0
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,I/ActivityManager(  892): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6135 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e25000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e25000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb545f960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb75b9e88, dataLength=8
,D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76e8030, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb76f7cf0, idLength=0xbeed62b0
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=3070116019
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb76e8030
D/DrmWidevineDash(  295): message_length=1591, signature=0xb75fcb30, signature_length=3203228308
,D/AndroidRuntime( 6074): Calling main entry com.android.commands.pm.Pm
,W/VideoCapabilities( 6093): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6093): Unsupported mime audio/amr-wb-plus
,I/ActivityManager(  892): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
I/ActivityManager(  892): Killing 5172:com.test.thalitest/u0a109 (adj 0): stop com.test.thalitest
,W/VideoCapabilities( 6093): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6093): Unsupported profile 4 for video/mp4v-es
,I/ Nonce  ( 2635):  Nonce Reponse 
D/        ( 2635): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"53fd71e4-8996-4cb3-8d6b-0cb71b9f5d96"}
D/MMApiWSBase( 2635): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2635):  Nonce Handle Reponse 
D/MMApiProvisionService( 2635): mOutstandingReq set to false
,W/VideoCapabilities( 6093): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6093): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6093): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6093): Unrecognized profile 2130706433 for video/avc
,D/WifiService(  892): Client connection lost with reason: 4
,I/WindowState(  892): WIN DEATH: Window{3e11b8d1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/art     ( 1480): Explicit concurrent mark sweep GC freed 4924(217KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 665us total 42.364ms
,E/libprocessgroup(  892): failed to kill 1 processes for processgroup 5172
,W/ActivityManager(  892): Force removing ActivityRecord{2d95a44e u0 com.test.thalitest/.MainActivity t9}: app died, no saved state
,W/PackageSettings(  892): Skipping PackageSetting{2240a27d com.example.hello/10568} due to missing metadata
,W/ContextImpl( 1480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  892): Spurious death for ProcessRecord{3bf3424 5172:com.test.thalitest/u0a109}, curProc for 5172: null
,I/ActivityManager(  892): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,I/vclib   ( 6093): onServiceConnected
W/Babel   ( 6093): Attempted to change video mute state without an active call.
,I/art     ( 3203): Explicit concurrent mark sweep GC freed 11224(1673KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/12MB, paused 1.656ms total 39.353ms
,I/InputReader(  892): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1582): Explicit concurrent mark sweep GC freed 2181(116KB) AllocSpace objects, 2(72KB) LOS objects, 24% free, 13MB/17MB, paused 497us total 74.869ms
I/Keyboard.Facilitator( 1426): resetDictionaries() : en_US
W/GeofencerStateMachine( 1709): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1426): run()
,I/art     ( 1945): Explicit concurrent mark sweep GC freed 4237(237KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 14MB/19MB, paused 3.388ms total 182.144ms
,I/dex2oat ( 6164): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/SQLiteConnectionPool( 1945): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Decoder ( 1426): createOrResetDecoder
,I/art     ( 2635): Explicit concurrent mark sweep GC freed 35104(2MB) AllocSpace objects, 5(103KB) LOS objects, 40% free, 11MB/19MB, paused 1.736ms total 143.849ms
,D/OtaApp  ( 2635): [debug] > DownloadActivity, FormattedText
,D/MMApiProvisionService( 2635):  pTime 1457886726448 sExp 172742 cTime 1457941882210 tTime 1458059468448
D/MMApiProvisionService( 2635):  No login Required 
,I/OtaApp  ( 2635): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2635): publish the event [tag = MOT_OTA event name = LOG]
,I/Babel   ( 6093): connection state changed from UNKNOWN to CONNECTED
I/OtaApp  ( 2635): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2635): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  892): Killing 5912:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/OtaApp  ( 2635): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2635): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2635): publish the event [tag = MOT_OTA event name = LOG]
,W/DataUsage( 2635): invalid counter update blocked: 'err' by 0
D/Checkin ( 2635): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6135): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6135): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6135): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6135): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  892): failed to open /acct/uid_10080/pid_5912/cgroup.procs: No such file or directory
,I/GAv4    ( 6135): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6135):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6135):   adb logcat -s GAv4
,I/ConfigService( 1709): onCreate
,D/BackupManagerService(  892): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  892): Receieved: android.intent.action.PACKAGE_REMOVED
,W/InputMethodManagerService(  892): Got RemoteException sending setActive(false) notification to pid 5172 uid 10109
W/GAv4    ( 6135): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Keyboard.Facilitator( 1426): onFinishInput()
,I/dex2oat ( 6164): dex2oat took 252.978ms (threads: 4)
D/TaskPersister(  892): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  892): removeObsoleteFile: deleting file=8_task.xml
,W/GAv4    ( 6135): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 6076): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6076): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6076): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6076): Local Branch: 
I/Adreno-EGL( 6076): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6076): Local Patches: NONE
I/Adreno-EGL( 6076): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1426): run()
,W/GAv4    ( 6135): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  892): Explicit concurrent mark sweep GC freed 24616(1682KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/31MB, paused 12.864ms total 360.921ms
,I/Launcher( 1582): Deferring update until onResume
,D/AndroidRuntime( 6074): Shutting down VM
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1426): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1426): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1426): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1426): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1426): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1426): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1426): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1426): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1426): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1426): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1426): run()
I/StatsUtilsManager( 1426): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1426): shouldRecordStats() = Too Soon
,I/Adreno-EGL( 6076): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6076): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6076): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6076): Local Branch: 
I/Adreno-EGL( 6076): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6076): Local Patches: NONE
I/Adreno-EGL( 6076): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  892): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6180 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1302): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/WebViewFactory( 6135): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6135): Time to load native libraries: 2 ms (timestamps 939-941)
I/LibraryLoader( 6135): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6135): Binding Chromium to main looper Looper (main, tid 1) {8ba00ae}
,I/LibraryLoader( 6135): Expected native library version number "",actual native library version number ""
,I/chromium( 6135): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6135): Initializing chromium process, singleProcess=true
W/art     ( 6135): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6135): ApplicationContext is null in ApplicationStatus
,W/chromium( 6135): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6135): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6135): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6135): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6135): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6135): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6135): Local Branch: 
I/Adreno-EGL( 6135): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6135): Local Patches: NONE
I/Adreno-EGL( 6135): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,I/NSApplication( 6135): Starting up...
,W/AudioManagerAndroid( 6135): Requires BLUETOOTH permission
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e25000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e25000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb555f960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb7603650, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76e9718, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb76f7d10, idLength=0xb4fb9730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=4064084191
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb75fe1c0
D/DrmWidevineDash(  295): message_length=1622, signature=0xb75fcb30, signature_length=3036387092
,I/ActivityManager(  892): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6242 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  892): Killing 6016:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
I/ActivityManager(  892): Killing 5979:com.android.mms/u0a23 (adj 15): empty #8
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  892): failed to open /acct/uid_10035/pid_6016/cgroup.procs: No such file or directory
,W/libprocessgroup(  892): failed to open /acct/uid_10023/pid_5979/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1302): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )

```
