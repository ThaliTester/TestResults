#### Test 625481247756efd_thali04_motorola-XT1072 Logs


```
--------- beginning of system
I/ActivityManager(  879): Killing 5194:android.process.acore/u0a7 (adj 15): empty #7
W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_5194/cgroup.procs: No such file or directory
--------- beginning of main
D/Central_PollingManager( 1459): wake lock released
D/OtaApp  ( 2591): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
D/OtaApp  ( 2591): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2591): [debug] > In cancelAnyPendingIntentSetPreviously
I/ActivityManager(  879): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
D/OtaApp  ( 2591): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2591): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 2591): [info] > Exceed max defer attempts for optional update, suppresing later btn
V/AlarmManager(  879): done {3994c413, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [15387ms]
D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2591): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2591): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
D/ChimeraCfgMgr( 5305): Reading stored module config
,E/global frequency( 2591): no tags to log
D/Checkin ( 2591): publish the event [tag = MOT_CHECKIN event name = LOG]
D/WearableService( 1721): callingUid 10016, callindPid: 1721
D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
E/MDM     ( 1721): [224] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5305): Restart initialization of location
D/AuthorizationBluetoothService( 1721): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/art     ( 1459): Explicit concurrent mark sweep GC freed 4500(195KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 706us total 33.072ms
V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 5305): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5305): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/ActivityManager(  879): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5392 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  319): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 31.801ms
I/art     (  319): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 19.152ms
I/BSUtils ( 2591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 21.077ms
D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 5376): 
D/AndroidRuntime( 5376): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5376): CheckJNI is OFF
I/ActivityManager(  879): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5417 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
W/GCoreFlp( 1721): No location to return for getLastLocation()
W/FusedLocationProvider( 1721): location=null
I/art     (  879): Explicit concurrent mark sweep GC freed 11371(526KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.691ms total 139.736ms
I/art     ( 1459): Explicit concurrent mark sweep GC freed 3612(142KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 639us total 26.504ms
D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/Gmail   ( 5392): getAccountsCursor
D/ActivityThread( 5392): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 5376): Calling main entry com.android.commands.am.Am
I/ContactLocale( 5417): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
V/AlarmManager(  879): send {237e90ca, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/art     ( 2591): Explicit concurrent mark sweep GC freed 23040(1371KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 11MB/18MB, paused 1.056ms total 65.832ms
I/BSUtils ( 2591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (384 us)
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5376): Shutting down VM
I/ActivityManager(  879): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5453 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/BSUtils ( 2591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 2591): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2591): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2591): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2591): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2591): publish the event [tag = DEV_ATTRIBS event name = SW]
D/Checkin ( 2591): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
I/global frequency( 2591): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
I/ActivityManager(  879): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5470 uid=10570 gids={50570, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/Checkin ( 2591): publish the event [tag = MOT_CHECKIN event name = LOG]
W/IcingInternalCorpora( 5305): getNumBytesRead when not calculated.
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ActivityManager(  879): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 5392): Observing account changes for notifications
,W/GAV2    ( 5392): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Exchange( 5453): EasService.onCreate
,I/Exchange( 5453): RestartPingTask
,I/Exchange( 5453): RestartPingsTask did not start any pings.
I/Exchange( 5453): PSS stopIfIdle
I/Exchange( 5453): PSS has no active accounts; stopping service.
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/WebViewFactory( 5470): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5470): Time to load native libraries: 6 ms (timestamps 5719-5725)
I/Exchange( 5453): onDestroy
,I/ActivityManager(  879): Killing 5260:com.android.providers.calendar/u0a5 (adj 15): empty #7
I/LibraryLoader( 5470): Expected native library version number "",actual native library version number ""
,I/Gmail   ( 5392): getAccountsCursor
,V/WebViewChromiumFactoryProvider( 5470): Binding Chromium to main looper Looper (main, tid 1) {179993cb}
,I/LibraryLoader( 5470): Expected native library version number "",actual native library version number ""
,I/chromium( 5470): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5470): Initializing chromium process, singleProcess=true
,W/art     ( 5470): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5470): ApplicationContext is null in ApplicationStatus
,W/chromium( 5470): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5470): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5470): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5470): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5470): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5470): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5470): Local Branch: 
I/Adreno-EGL( 5470): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5470): Local Patches: NONE
I/Adreno-EGL( 5470): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  879): failed to open /acct/uid_10005/pid_5260/cgroup.procs: No such file or directory
,I/SundryService( 2591): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 2591): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 2591): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 2591): ServiceHandler.handleMessage: mWaitCount=0
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetNotificationsWS( 2591): unbindWebServices(): un-registering our AIDL callback...
,E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=40.50 rxSuccessRate=33.25 targetRoamBSSID=any RSSI=-41
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN with age=18778 interval=30000 maxinterval=300000
,E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=40.50 rx=33.25
,V/AlarmManager(  879): done {3d33ff03, *alarm*:com.android.server.WifiManager.action.START_SCAN} [46459ms]
,I/CE-UpdateModelService( 5218): ACTION_REGISTRATION_COMPLETE
,D/BluetoothManagerService(  879): Message: 20
D/BluetoothManagerService(  879): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1618400b:true
,I/ActivityManager(  879): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5526 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 5286:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10096/pid_5286/cgroup.procs: No such file or directory
,W/ResourcesManager( 5526): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 5392): (283) recovered 28 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/CalendarProvider2( 5526): Created com.android.providers.calendar.CalendarAlarmManager@2690dbbc(com.android.providers.calendar.CalendarProvider2@3e090745)
,V/AlarmManager(  879): done {3ad22d00, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [12680ms]
,D/3CDM.DeviceAdminPushReceiver( 2591): Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.DeviceAdminPushReceiver( 2591): Type: null
D/3CDM.DeviceAdminPushReceiver( 2591): Data: null
,D/3CDM.Service( 2591): com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.Service( 2591): Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
D/3CDM.Service( 2591): DeviceAdmin - syncWithCCC
D/3CDM.Service( 2591): blur.service.littlesister.gpsFixWaitTime = 60000
D/3CDM.Service( 2591): com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
D/3CDM.Service( 2591): blur.service.cred.locationToken = null
D/3CDM.Service( 2591): com.motorola.ccc.cce.email.marketing.optin.default = false
D/3CDM.Service( 2591): blur.service.littlesister.reportLevel2 = NONE
D/3CDM.Service( 2591): com.motorola.blur.adminfeed.device_admin_always_allowed = 1
D/3CDM.Service( 2591): com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
E/SQLiteLog( 5526): (284) automatic index on view_events(_id)
,W/art     ( 5470): Attempt to remove local handle scope entry from IRT, ignoring
,D/3CDM.Service( 2591): Sync to CCE settings done, instantiate Locate now.
,W/AwContents( 5470): onDetachedFromWindow called when already detached. Ignoring
,I/SFPerfTracer(  278):      triggers: (rate: 13:529) (compose: 0:1) (post: 0:1) (render: 0:2) (10:897 frames) (11:975)
D/SFPerfTracer(  278):        layers: (4:12) (FocusedStackFrame (0xb7aea308): 0:12)* (DimLayer (0xb7acf860): 0:5) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7ad1768): 0:48)- (StatusBar (0xb7ad5f88): 0:154) (NavigationBar (0xb7a43c38): 0:49) (com.android.systemui.ImageWallpaper (0xb7a46028): 0:8)* (Starting com.motorola.ccc.ota (0xb7af4800): 0:28)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7af5a90): 1:56)* (Starting com.test.thalitest (0xb7ad1768): 11:22) 
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=5551 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/SystemWebViewEngine( 5470): CordovaWebView is running on device made by: motorola
,W/art     ( 5470): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5470): Attempt to remove local handle scope entry from IRT, ignoring
,D/BSUtils ( 2591): set .setup.DeviceAdminSetupReceiver enabled
,I/Gmail   ( 5392): notifyAccountChanged
,I/Gmail   ( 5392): getAccountsCursor
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5392): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5392): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/OpenGLRenderer( 5470): Render dirty regions requested: true
,I/Gmail   ( 5392): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5392): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/Atlas   ( 5470): Validating map...
,I/ActivityManager(  879): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=5582 uid=10054 gids={50054, 9997, 3003} abi=armeabi-v7a
,W/chromium( 5470): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,E/UpdateRequestReceiver( 5582): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/art     (  879): Explicit concurrent mark sweep GC freed 9170(470KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.672ms total 119.935ms
,I/Gmail   ( 5392): getAccountsCursor
,E/UpdateRequestReceiver( 5582): Received malformed URL while handling Gservices.CHANGED_ACTION
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/UpdateRequestReceiver( 5582): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/OpenGLRenderer( 5470): Initialized EGL, version 1.4
E/UpdateRequestReceiver( 5582): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/OpenGLRenderer( 5470): Enabling debug mode 0
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:39000 mC
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=5612 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/LaunchCheckinHandler(  879): Displayed com.test.thalitest/.MainActivity,cp,ca,1204
I/ActivityManager(  879): Displayed com.test.thalitest/.MainActivity: +1s204ms
,I/Keyboard.Facilitator( 1408): onFinishInput()
,E/Adreno-ES20( 5470): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 5470): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5470): Cannot call determinedVisibility() - never saw a connection for the pid: 5470
,E/Adreno-ES20( 5470): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 5470): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
I/CalendarProvider2( 5526): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5526): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  879): Killing 5341:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10055/pid_5341/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 5417:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_5417/cgroup.procs: No such file or directory
,I/GservicesUpdateTask( 5612): Updating Gservices keys
,I/ActivityManager(  879): Killing 5453:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10060/pid_5453/cgroup.procs: No such file or directory
,D/GmsModuleFndr( 5305): Beginning GMS chimera module scan
,D/GmsModuleFndr( 5305): Module pkg com.google.android.apps.kids.familylink not installed, skipping
,D/GmsModuleFndr( 5305): Module pkg com.google.android.gms.ads.dynamite not installed, skipping
,D/GmsModuleFndr( 5305): Module pkg com.google.android.projection.gearhead not installed, skipping
,D/ChimeraCfgMgr( 5305): Beginning module configuration check
,I/CheckinService( 5305): Disabling old GoogleServicesFramework version
,D/ChimeraCfgMgr( 5305): Module APKs unchanged, check complete
,I/SystemUpdateService( 5305): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 5305): onCreate
,D/JsMessageQueue( 5470): Set native->JS mode to OnlineEventsBridgeMode
,I/CheckinService( 5305): Checking schedule, now: 1457708830890 next: 1457708848454
I/CheckinService( 5305): active receiver: disabled
,D/SystemUpdateService( 5305): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/art     ( 4037): Explicit concurrent mark sweep GC freed 3762(163KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 482us total 26.033ms
,I/SystemUpdateService( 5305): cancelUpdate (empty URL)
I/SystemUpdateService( 5305): active receiver: disabled
,W/InstanceID/Rpc( 5305): Found 10016
,D/jxcore_app_log( 5470): JniHelper::setJavaVM(0xb89d8310), pthread_self() = -1193878400
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@244aff87 added. We now have 1 listener(s)
,D/BluetoothManagerService(  879): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@289cf652 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5470): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  879): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5470): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 5470): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 5470): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 5470): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5470): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
,W/System.err( 5470): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5470): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
,W/System.err( 5470): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5470): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5470): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5470): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5470): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5470): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5470): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5470): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 5470): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@334e0d23 added. We now have 2 listener(s)
D/BluetoothManagerService(  879): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c4e7220 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5470): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 5470): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 5470): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 5470): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5470): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5470): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5470): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5470): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5470): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5470): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5470): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
,W/System.err( 5470): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5470): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5470): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5470): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/art     ( 4037): Explicit concurrent mark sweep GC freed 2653(102KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 536us total 34.286ms
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     ( 5305): Explicit concurrent mark sweep GC freed 17839(1197KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 10MB/17MB, paused 948us total 68.287ms
,I/ActivityManager(  879): Killing 5392:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10063/pid_5392/cgroup.procs: No such file or directory
,D/SystemUpdateService( 5305): onDestroy
,W/ContextImpl( 5240): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 5240): Thread[GAThread,5,main]: No campaign data found.
,W/DynamiteLoaderImpl( 5305): Failed to load module version: module com.google.android.gms.flags not found
I/DynamiteModule( 5305): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 5305): Selected local version of com.google.android.gms.flags
,I/GAv4-SVC( 5305): Google Analytics 8.7.03 is starting up.
,D/SystemEventReceiver( 5305): Received GSERVICES_CHANGED broadcast
,I/Icing   ( 5305): Storage manager: low false usage 1.77MB avail 3.08GB capacity 4.85GB
,I/OcrUtils( 5305): Updating ocr activity enabled=false
,I/ActivityManager(  879): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=5689 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  879): send {33953fc0, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
V/AlarmManager(  879): send {3d33ff03, *alarm*:com.android.server.WifiManager.action.START_SCAN}
V/AlarmManager(  879): done {33953fc0, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [46ms]
,V/AlarmManager(  879): send {3e78d4f9, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,I/ActivityManager(  879): Killing 5240:com.google.android.calendar/u0a49 (adj 15): empty #7
,E/Icing   ( 5305): Array storage bad crc 3797865835 vs 3263762921
,E/Icing   ( 5305): Array storage bad crc 3006036120 vs 4044529038
,E/Icing   ( 5305): Array storage bad crc 3974537029 vs 3643544
E/Icing   ( 5305): Trie mmap suffix failed
,W/Icing   ( 5305): Docstore bad crc 0x79e1e417 vs 0x6d18c56c
,W/libprocessgroup(  879): failed to open /acct/uid_10049/pid_5240/cgroup.procs: No such file or directory
,E/Icing   ( 5305): Array storage bad crc 2108579274 vs 0
E/Icing   ( 5305): Trie mmap node failed
,I/art     ( 1721): Explicit concurrent mark sweep GC freed 29208(2001KB) AllocSpace objects, 34(544KB) LOS objects, 40% free, 13MB/22MB, paused 1.082ms total 104.430ms
,D/Finsky  ( 5689): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  879): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 5305): Updating downloaded model state (gservices changed)
,D/Finsky  ( 5689): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/art     ( 4037): Explicit concurrent mark sweep GC freed 2582(101KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 670us total 25.593ms
,W/Settings( 5689): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5689): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 5689): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/Finsky  ( 5689): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5689): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5689): Skipping gmscore version check
,D/Finsky  ( 5689): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/GCM     ( 1721): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/Finsky  ( 5689): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5305): updateResources: need to parse f{com.google.android.gms}
,D/TaskPersister(  879): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/GCoreUlr( 1721): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1721): DispatchingService.onCreate()
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver: pid=5751 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 4037): Explicit concurrent mark sweep GC freed 2926(116KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 490us total 33.428ms
,I/Icing   ( 5305): Internal init done: storage state 0
,I/Icing   ( 5305): 24 corpora need re-polling
,I/Icing   ( 5305): Post-init done
,I/GCoreUlr( 1721): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GeofencerStateMachine( 1721): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1721): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/art     (  879): Explicit concurrent mark sweep GC freed 16951(810KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/31MB, paused 1.633ms total 117.815ms
,I/Icing   ( 5305): Indexing 4872BCF0222204F7BD264D301612C97BCD2D2DDC from com.google.android.googlequicksearchbox
,E/SQLiteLog( 5612): (284) automatic index on phones(data_id)
,I/Icing   ( 5305): Indexing done 4872BCF0222204F7BD264D301612C97BCD2D2DDC
,I/Icing   ( 5305): Indexing 66B77DC231A28AED1F70AB8F1470C430B255E161 from com.google.android.googlequicksearchbox
,I/art     ( 1721): Explicit concurrent mark sweep GC freed 16964(975KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 13MB/23MB, paused 1.500ms total 79.043ms
,I/Icing   ( 5305): Indexing done 66B77DC231A28AED1F70AB8F1470C430B255E161
,I/Icing   ( 5305): Indexing FAC5D5C372F1FE03E0CF6D19726C451BC6ABAC12 from com.google.android.googlequicksearchbox
,E/SQLiteLog( 5612): (284) automatic index on emails(data_id)
,I/Icing   ( 5305): Indexing done FAC5D5C372F1FE03E0CF6D19726C451BC6ABAC12
,I/Icing   ( 5305): Not indexing corpus from package com.android.chrome as it has never connected
,E/Icing   ( 5305): Aborting indexing of corpus omnibox
,I/Icing   ( 5305): Not indexing corpus from package com.google.android.apps.messaging as it has never connected
E/Icing   ( 5305): Aborting indexing of corpus messagesCorpus
,I/Icing   ( 5305): Indexing 37CAF1DD096EBA1346D0004D1B70177E33DE9430 from com.google.android.gms
,W/ctxmgr  ( 1721): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10016, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1721): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/Icing   ( 5305): Indexing done 37CAF1DD096EBA1346D0004D1B70177E33DE9430
I/Icing   ( 5305): Not indexing corpus from package com.google.android.apps.messaging as it has never connected
,E/Icing   ( 5305): Aborting indexing of corpus participantsCorpus
I/Icing   ( 5305): Indexing 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A from com.google.android.gm
,I/ActivityManager(  879): Start proc com.google.android.gm for content provider com.google.android.gm/.provider.SearchQuery$Provider: pid=5775 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GCoreUlr( 1721): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  879): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=5794 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 5218:com.motorola.context/u0a8 (adj 15): empty #7
,I/art     (  319): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.130ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 19.575ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 19.772ms
,W/libprocessgroup(  879): failed to open /acct/uid_10008/pid_5218/cgroup.procs: No such file or directory
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1721): Unbound from all location providers
I/GCoreUlr( 1721): Place inference reporting - stopped
,I/GCoreUlr( 1721): DispatchingService.onDestroy()
I/GCoreUlr( 1721): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1721): Unbound from all location providers
I/GCoreUlr( 1721): Place inference reporting - stopped
,E/SQLiteLog( 5794): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/Gmail   ( 5775): getAccountsCursor
D/ActivityThread( 5775): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5820 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/qtaguid ( 5689): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5689): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5689): untagSocket(37) failed with errno -22
,I/ActivityManager(  879): Killing 5582:com.google.android.configupdater/u0a54 (adj 15): empty #7
,D/Finsky  ( 5689): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (15:273 vsyncs) (17:1037)
,I/ActivityManager(  879): Start proc com.motorola.context for broadcast com.motorola.context/.ccc.UpdateModelReceiver: pid=5840 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ActivityManager(  879): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/libprocessgroup(  879): failed to open /acct/uid_10054/pid_5582/cgroup.procs: No such file or directory
,I/Gmail   ( 5775): Observing account changes for notifications
W/ResourcesManager( 5840): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/AnalyticsLogBase( 5794): PlayLogger.onLoggerConnected
,I/Exchange( 5820): EasService.onCreate
,D/Checkin ( 3034): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/Exchange( 5820): RestartPingTask
,W/GAV2    ( 5775): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  879): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5868 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 5820): RestartPingsTask did not start any pings.
I/Exchange( 5820): PSS stopIfIdle
I/Exchange( 5820): PSS has no active accounts; stopping service.
,E/SQLiteLog( 5775): (283) recovered 29 frames from WAL file /data/user/0/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5888 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 5551:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/ResourcesManager( 5868): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5868): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Gmail   ( 5775): notifyAccountChanged
I/Gmail   ( 5775): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5775): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5775): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5775): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/MultiDex( 5868): VM with version 2.1.0 has multidex support
,I/MultiDex( 5868): install
I/MultiDex( 5868): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  879): failed to open /acct/uid_10019/pid_5551/cgroup.procs: No such file or directory
,I/Gmail   ( 5775): getAccountsCursor
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 5820): onDestroy
,V/JNIHelp ( 5868): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Icing   ( 5305): Indexing done 2AECF53D399C59B39116834B1BCDDAF8EA2DCC5A
,I/ActivityManager(  879): Killing 5751:com.google.android.apps.photos/u0a88 (adj 15): empty #7
I/Icing   ( 5305): Indexing 346450671AD4EC90E40EFFA60B87477CADDF794C from com.google.android.videos
,D/PhoneMonitor( 5888): Register our PhoneStateListener
,W/ActivityThread( 5868): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5868): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@fea587f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5868): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  879): Start proc com.google.android.videos for content provider com.google.android.videos/.search.IcingContentProvider: pid=5912 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002} abi=armeabi
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_5751/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 5868): Reading stored module config
,V/SetupWizard( 5888): Connected to Gservices successfully
,I/ActivityManager(  879): Killing 5612:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_5612/cgroup.procs: No such file or directory
,W/ResourcesManager( 5912): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/qtaguid ( 5689): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5689): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5689): untagSocket(37) failed with errno -22
,D/NativeLibraryUtils( 5868): Install completed successfully. count=14 extracted=0
,I/Gmail   ( 5775): getAccountsCursor
,D/GCM     ( 1721): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5775): getAccountsCursor
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     ( 5305): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,D/CAR.SERVICE( 5868): Connecting to CarCallService...
,I/art     ( 5868): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5868): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 5868): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5868): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5868): Creating a new PhoneAdapter instance
,W/ActivityManager(  879): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5868): setListener: com.google.android.gms.car.dn@6d838b
W/ActivityManager(  879): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5868): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5868): Starting CarCallService with initial phone null
,I/art     (  879): Explicit concurrent mark sweep GC freed 10957(540KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 4.822ms total 127.271ms
,W/PlaySystemBroadcastReceiver( 5305): Processed handlePeopleChanged at 100879
,D/GCM     ( 1721): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/CAR.SERVICE( 5868): Package validated; name: com.android.vending
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5972 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/Finsky  ( 5689): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,W/BaseAppContext( 5305): Using Auth Proxy for data requests.
,W/ResourcesManager( 5972): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 4037): Explicit concurrent mark sweep GC freed 2720(108KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 423us total 24.916ms
,E/BaseAppContext( 5305): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5305): Using Auth Proxy for data requests.
,I/art     ( 5305): Explicit concurrent mark sweep GC freed 38349(2MB) AllocSpace objects, 38(608KB) LOS objects, 24% free, 12MB/16MB, paused 814us total 91.896ms
,W/BaseAppContext( 5305): Using Auth Proxy for data requests.
,W/BaseAppContext( 5305): Using Auth Proxy for data requests.
,W/PlayMovies( 5912): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 5912): 
,W/BaseAppContext( 5305): Using Auth Proxy for data requests.
,E/SQLiteLog( 5912): (284) automatic index on sqlite_sq_B8C124F0(video_id)
,I/Icing   ( 5305): Indexing done 346450671AD4EC90E40EFFA60B87477CADDF794C
,I/Icing   ( 5305): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,W/PlayMovies( 5912): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 5912): 
,I/Babel_SMS( 5972): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5972): MmsConfig.loadMmsSettings
I/Babel_SMS( 5972): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5972): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5972): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5972): MmsConfig.loadFromResources
,E/Babel_SMS( 5972): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5972): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/PlayMovies( 5912): PersistentCache.cleanup:94 Cache is below limit, no need to shrink: [size=0, limit=5242880]
D/PlayMovies( 5912): 
,D/Finsky  ( 5689): [644] SignatureUtils.faultInOtherSignatures: Will not allow first-party apps signed by test keys
D/Finsky  ( 5689): [644] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.videos
,D/PlayMovies( 5912): TransferService.onCreate:60 creating transfer service
D/PlayMovies( 5912): 
,W/VideoCapabilities( 5912): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5912): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5912): Unsupported mime video/mpeg2
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5912): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.videos/files/Movies
,W/Settings( 5972): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/VideoCapabilities( 5912): Unsupported profile 4 for video/mp4v-es
,W/MediaCodecUtil( 5912): MediaCodecList API didn't list secure decoder for: video/avc. Assuming: OMX.qcom.video.decoder.avc.secure
,I/Babel_Crash( 5972): startup - clean
,D/WVCdm   (  302): Instantiating CDM.
,I/WVCdm   (  302): CdmEngine::QueryStatus
I/WVCdm   (  302): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  302): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  302): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  302): Service_Initialize: starts!
D/QSEECOMAPI: (  302): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  302): App is not loaded in QSEE
E/QSEECOMAPI: (  302): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  302): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  302): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  302): App is not loaded in QSEE
E/QSEECOMAPI: (  302): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  302): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  302): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  302): App is not loaded in QSEE
,I/Babel   ( 5972): deleted: false for 0
,D/QSEECOMAPI: (  302): Loaded image: APP id = 3
D/DrmWidevineDash(  302): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  302): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ce5000
E/DrmWidevineDash(  302): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ce5000
,D/DrmWidevineDash(  302): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  302): hlos api version =  9
D/DrmWidevineDash(  302): tz api version =  8
,D/DrmWidevineDash(  302): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  302): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  302): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  302): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  302): OEMCrypto_GetDeviceID: starts! deviceID=0xb73ce6e8, idLength=0xb5476998
,D/DrmWidevineDash(  302): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_GetKeyData: starts! keyData=0xb5476964, keyDataLength=0xb547695c
,D/DrmWidevineDash(  302): OEMCrypto_GetKeyData: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_GetKeyData: starts! keyData=0xb5476964, keyDataLength=0xb547695c
,D/DrmWidevineDash(  302): OEMCrypto_GetKeyData: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  302): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: ends! returns 0x0
I/WVCdm   (  302): L3 Terminate.
D/DrmWidevineDash(  302): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  302): Service_Uninitialize: starts!
D/QSEECOMAPI: (  302): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  302): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  302): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  302): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6021 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 5526:com.android.providers.calendar/u0a5 (adj 15): empty #7
,D/Icing   ( 5305): Loaded CLD2 Version V2.0 - 20141016
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=353, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2362000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311727, SEQNUM=4361, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/libprocessgroup(  879): failed to open /acct/uid_10005/pid_5526/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,W/VideoCapabilities( 5972): Unrecognized profile 2130706433 for video/avc
,I/Icing   ( 5305): Indexing CAB1456BE3B211EBC307C171B72F719E92FCECCC from com.google.android.gms
W/AudioCapabilities( 5972): Unsupported mime audio/amr-wb-plus
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/DataBroker( 5305): No player ID found when refreshing
,W/VideoCapabilities( 5972): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5972): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5972): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5972): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5972): Unrecognized profile 2130706433 for video/avc
,I/Icing   ( 5305): Indexing done CAB1456BE3B211EBC307C171B72F719E92FCECCC
,I/chromium( 5470): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
I/chromium( 5470): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,W/VideoCapabilities( 5972): Unrecognized profile 2130706433 for video/avc
,I/Icing   ( 5305): Indexing F89A5A554A34155FDE8136238C97721890582172 from com.google.android.music
,I/ActivityManager(  879): Killing 5775:com.google.android.gm/u0a63 (adj 15): empty #7
,I/vclib   ( 5972): onServiceConnected
,W/Babel   ( 5972): Attempted to change video mute state without an active call.
,I/ActivityManager(  879): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=6045 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  879): failed to open /acct/uid_10063/pid_5775/cgroup.procs: No such file or directory
,V/AlarmManager(  879): done {1b937b80, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED} [13037ms]
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6067 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/qtaguid ( 5689): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5689): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5689): untagSocket(37) failed with errno -22
,I/ActivityManager(  879): Killing 5820:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,I/MusicStore( 6045): Database version: 120
,W/libprocessgroup(  879): failed to open /acct/uid_10060/pid_5820/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6045): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/SQLiteLog( 5305): (284) automatic index on invitations(external_inviter_id)
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6045): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6045): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6102 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,W/ResourcesManager( 6045): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6045): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6121 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/ActivityManager(  879): getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,I/art     (  319): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 22.064ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 19.787ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 21.087ms
,V/JNIHelp ( 6045): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ResourcesManager( 5972): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5972): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5972): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ResourcesManager( 5689): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5689): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Icing   ( 5305): Indexing done F89A5A554A34155FDE8136238C97721890582172
I/Icing   ( 5305): Indexing C4E2C5CC550D05661E7AD615FD9F7900AE32897E from com.google.android.googlequicksearchbox
,W/ActivityThread( 6045): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6045): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@372a5d44: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6045): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6045): GMSCore installation verified
,I/ConfigStore( 6045): Config Database version: 1
E/SQLiteLog( 6067): (284) automatic index on contacts(contact_id)
,W/System  ( 5972): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5972): Installed default security provider GmsCore_OpenSSL
,I/Icing   ( 5305): Indexing done C4E2C5CC550D05661E7AD615FD9F7900AE32897E
,I/Icing   ( 5305): Indexing B38ECE6979252B6258324BDB4A6CBA7FE716FBF6 from com.google.android.music
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6150 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 5888:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 6121): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_5888/cgroup.procs: No such file or directory
,I/Icing   ( 5305): Indexing done B38ECE6979252B6258324BDB4A6CBA7FE716FBF6
,I/Icing   ( 5305): Indexing D2B9966BFA31E94C2E19CD89CAAF0DABB369A465 from com.google.android.gms
,W/asset   ( 6150): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6150): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 6150): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6150): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Icing   ( 5305): Indexing done D2B9966BFA31E94C2E19CD89CAAF0DABB369A465
I/Icing   ( 5305): Indexing 3FCCFCF7A9CBB53DD847A445F260A1713A23D74F from com.google.android.gms
,I/Icing   ( 5305): Indexing done 3FCCFCF7A9CBB53DD847A445F260A1713A23D74F
,I/Icing   ( 5305): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,I/MediaRouter( 6045): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 6045): type=WIFI subType= reason=null isConnected=true
,W/ResourcesManager( 5689): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     (  879): Explicit concurrent mark sweep GC freed 13880(712KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/31MB, paused 1.631ms total 132.711ms
,D/Finsky  ( 5689): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  879): send {3509db24, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,I/UpdateIcingCorporaServi( 6067): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2a7ee654 new=com.google.android.velvet.VelvetApplication@2a7ee654
,I/NetworkMonitor( 6045): type=WIFI subType= reason=null isConnected=true
,D/DeviceConnectionService( 1721): client connected with version: 8296000
,D/WearableService( 1721): callingUid 10016, callindPid: 1721
D/PkgBroadcastIntentOp( 5305): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PkgBroadcastIntentOp( 5305): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6184 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 5912:com.google.android.videos/u0a98 (adj 15): empty #7
,I/Icing   ( 5305): Indexing 35EEF8AB756C109C4A9E0B05D40C0D1BC827283E from com.google.android.googlequicksearchbox
,I/UpdateIcingCorporaServi( 6067): UpdateCorporaTask done [took 116 ms] updated apps [took 115 ms] 
,W/libprocessgroup(  879): failed to open /acct/uid_10098/pid_5912/cgroup.procs: No such file or directory
,D/WearableController( 5305): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/GHttpClientFactory( 6045): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/Finsky  ( 5689): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/GoogleURLConnFactory( 6045): Using platform SSLCertificateSocketFactory
,E/SQLiteLog( 6067): (284) automatic index on postals(data_id)
D/Finsky  ( 5689): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,W/ResourcesManager( 6184): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Killing 6021:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ActivityManager(  879): Killing 5840:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_6021/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10008/pid_5840/cgroup.procs: No such file or directory
,I/Icing   ( 5305): Indexing done 35EEF8AB756C109C4A9E0B05D40C0D1BC827283E
,I/Icing   ( 5305): Indexing EEE3E0FF4DADAE4CB4C7878F0618998FF68C443F from com.google.android.gms
,I/Icing   ( 5305): Indexing done EEE3E0FF4DADAE4CB4C7878F0618998FF68C443F
I/Icing   ( 5305): Indexing F31C33A9C165C418DC665D5D5CCC2C59547B796D from com.google.android.apps.books
,W/ActivityManager(  879): Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{c6e97ec 5305:com.google.android.gms/u0a16} (pid=5305, uid=10016) that is not exported from uid 10046
,E/Icing   ( 5305): Cursor call threw an exception: Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{c6e97ec 5305:com.google.android.gms/u0a16} (pid=5305, uid=10016) that is not exported from uid 10046
,I/Icing   ( 5305): Indexing done F31C33A9C165C418DC665D5D5CCC2C59547B796D
E/Icing   ( 5305): Aborting indexing of corpus volumes__id
,I/Icing   ( 5305): Indexing AD155643591D3539F6A352C4DB59513CA6893D4B from com.google.android.music
,I/ActivityManager(  879): Killing 6121:android.process.acore/u0a7 (adj 15): empty #7
,I/ActivityManager(  879): Killing 6102:com.google.android.partnersetup/u0a19 (adj 15): empty #8
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_6121/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10019/pid_6102/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6222 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/Icing   ( 5305): Indexing done AD155643591D3539F6A352C4DB59513CA6893D4B
,I/Icing   ( 5305): Indexing 4EDDE6AB8EB8EAD44D177EBA476C0D4D5DBE54AF from com.google.android.music
,I/Icing   ( 5305): Indexing done 4EDDE6AB8EB8EAD44D177EBA476C0D4D5DBE54AF
I/Icing   ( 5305): Indexing E4D473B56BA677AE6825C925C78E1DD1A496197B from com.google.android.videos
,I/ActivityManager(  879): Start proc com.google.android.videos for content provider com.google.android.videos/.search.IcingContentProvider: pid=6243 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002} abi=armeabi
,I/ContactLocale( 6222): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  879): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6262 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6243): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=6279 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6150:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/ResourcesManager( 6262): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/libprocessgroup(  879): failed to open /acct/uid_10027/pid_6150/cgroup.procs: No such file or directory
,I/CalendarProvider2( 6262): Created com.android.providers.calendar.CalendarAlarmManager@2690dbbc(com.android.providers.calendar.CalendarProvider2@3e090745)
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6313 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/ContextImpl( 5794): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/ActivityManager(  879): Killing 6067:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_6067/cgroup.procs: No such file or directory
,I/GAV2    ( 5794): Thread[GAThread,5,main]: No campaign data found.
,W/asset   ( 6313): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6313): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6313): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6313): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/art     ( 4037): Explicit concurrent mark sweep GC freed 3018(118KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 401us total 29.794ms
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6341 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6045:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10080/pid_6045/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 4037:com.google.process.gapps/u0a16 (adj 15): empty #7
,E/SQLiteLog( 6243): (284) automatic index on sqlite_sq_B8C0A858(show_id)
,W/libprocessgroup(  879): failed to open /acct/uid_10016/pid_4037/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 5868:com.google.android.gms:car/u0a16 (adj 15): empty #7
,I/Icing   ( 5305): Indexing done E4D473B56BA677AE6825C925C78E1DD1A496197B
I/Icing   ( 5305): Not indexing corpus from package com.google.android.apps.messaging as it has never connected
,E/Icing   ( 5305): Aborting indexing of corpus partsCorpus
,I/ActivityManager(  879): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6360 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/libprocessgroup(  879): failed to open /acct/uid_10016/pid_5868/cgroup.procs: No such file or directory
,I/Icing   ( 5305): updateResources: need to parse f{com.google.android.gms}
,W/ActivityManager(  879): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,D/PkgBroadcastIntentOp( 5305): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/ActivityManager(  879): Killing 6184:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_6184/cgroup.procs: No such file or directory
,D/WearableController( 5305): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/AsyncTaskServiceImpl( 5305): Submit a task: k
,I/GservicesProvider( 6360): Gservices pushing to system: true; secure/global: true
,D/k       ( 5305): Processing package: com.test.thalitest
,I/CalendarProvider2( 6262): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6262): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/GassUtils( 5305): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5305): Found info for package com.test.thalitest in db.
,I/ActivityManager(  879): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6394 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/Icing   ( 5305): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,I/UpdateIcingCorporaServi( 6341): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/GoogleHttpClient( 6360): GMS http client unavailable, use old client
,I/GoogleHttpClient( 6360): GMS http client unavailable, use old client
,I/Icing   ( 5305): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  879): Killing 5689:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10032/pid_5689/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 6341): UpdateCorporaTask done [took 243 ms] updated apps [took 243 ms] 
,I/ActivityManager(  879): Killing 6222:android.process.acore/u0a7 (adj 15): empty #7
,I/PeopleDatabaseHelper( 5305): cleanUpNonGplusAccounts done.
,I/art     (  879): Explicit concurrent mark sweep GC freed 13948(765KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.722ms total 117.897ms
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_6222/cgroup.procs: No such file or directory
,W/PlayMovies( 6243): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 6243): 
,W/PackageSettings(  879): Skipping PackageSetting{31e714e3 com.example.hello/10568} due to missing metadata
,I/GAv4    ( 6394): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6394):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6394):   adb logcat -s GAv4
,I/ActivityManager(  879): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6433 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/PlayMovies( 6243): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 6243): 
,I/art     (  319): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 21.426ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 18.820ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.457ms
,W/GAv4    ( 6394): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/PlayMovies( 6243): PersistentCache.cleanup:94 Cache is below limit, no need to shrink: [size=0, limit=5242880]
D/PlayMovies( 6243): 
,W/GAv4    ( 6394): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/PlayMovies( 6243): TransferService.onCreate:60 creating transfer service
D/PlayMovies( 6243): 
,W/GAv4    ( 6394): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ThermalEngine(  315): Sensor:xo_therm_pu2:39000 mC
,W/AnalyticsTrackerProxyImpl( 6394): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,W/VideoCapabilities( 6243): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6243): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6243): Unsupported mime video/mpeg2
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6243): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.videos/files/Movies
,E/SQLiteLog( 6394): (283) recovered 2 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
,I/VideoCapabilities( 6243): Unsupported profile 4 for video/mp4v-es
,W/MediaCodecUtil( 6243): MediaCodecList API didn't list secure decoder for: video/avc. Assuming: OMX.qcom.video.decoder.avc.secure
,D/Finsky  ( 6433): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/WVCdm   (  302): Instantiating CDM.
,I/WVCdm   (  302): CdmEngine::QueryStatus
I/WVCdm   (  302): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  302): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/DrmWidevineDash(  302): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  302): Service_Initialize: starts!
D/QSEECOMAPI: (  302): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  302): App is not loaded in QSEE
E/QSEECOMAPI: (  302): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  302): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  302): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  302): App is not loaded in QSEE
E/QSEECOMAPI: (  302): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  302): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  302): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  302): App is not loaded in QSEE
,D/QSEECOMAPI: (  302): Loaded image: APP id = 3
,D/DrmWidevineDash(  302): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ce4000
E/DrmWidevineDash(  302): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ce4000
,D/DrmWidevineDash(  302): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  302): hlos api version =  9
D/DrmWidevineDash(  302): tz api version =  8
D/DrmWidevineDash(  302): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  302): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  302): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  302): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  302): OEMCrypto_GetDeviceID: starts! deviceID=0xb73ce6e8, idLength=0xb4fd0998
,D/DrmWidevineDash(  302): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_GetKeyData: starts! keyData=0xb4fd0964, keyDataLength=0xb4fd095c
,D/DrmWidevineDash(  302): OEMCrypto_GetKeyData: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_GetKeyData: starts! keyData=0xb4fd0964, keyDataLength=0xb4fd095c
,D/DrmWidevineDash(  302): OEMCrypto_GetKeyData: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  302): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: ends! returns 0x0
I/WVCdm   (  302): L3 Terminate.
D/DrmWidevineDash(  302): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  302): Service_Uninitialize: starts!
D/QSEECOMAPI: (  302): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  302): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  302): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  302): OEMCrypto_Terminate: ends! returns 0
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6394): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 6394): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6394): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 6433): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6481 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 6433): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6433): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 6481): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 6394): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  879): Killing 6313:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
D/Finsky  ( 6433): [769] SignatureUtils.faultInOtherSignatures: Will not allow first-party apps signed by test keys
D/Finsky  ( 6433): [769] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.videos
,I/Icing   ( 5305): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,W/System  ( 6394): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6394): Installed default security provider GmsCore_OpenSSL
,I/Icing   ( 5305): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  879): Killing 6262:com.android.providers.calendar/u0a5 (adj 15): empty #8
,W/libprocessgroup(  879): failed to open /acct/uid_10027/pid_6313/cgroup.procs: No such file or directory
,D/Ads     ( 6433): Skipping gmscore version check
,W/libprocessgroup(  879): failed to open /acct/uid_10005/pid_6262/cgroup.procs: No such file or directory
,D/Finsky  ( 6433): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6433): [1] Libraries$2.run: Finished loading 1 libraries.
I/Icing   ( 5305): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5305): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,D/Finsky  ( 6433): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6433): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 5305): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,I/Icing   ( 5305): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,I/ActivityManager(  879): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6512 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Finsky  ( 6433): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/WearableService( 1721): callingUid 10016, callindPid: 1721
,D/AuthorizationBluetoothService( 1721): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1721): [200] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5305): Restart initialization of location
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6538 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ContactLocale( 6512): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/GCoreFlp( 1721): No location to return for getLastLocation()
,W/FusedLocationProvider( 1721): location=null
,I/ActivityManager(  879): Killing 6279:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  879): failed to open /acct/uid_10019/pid_6279/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 6341:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/ResourcesManager( 6538): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_6341/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6556 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6394:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10057/pid_6394/cgroup.procs: No such file or directory
,W/ResourcesManager( 6556): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6556): Created com.android.providers.calendar.CalendarAlarmManager@2690dbbc(com.android.providers.calendar.CalendarProvider2@3e090745)
,V/AlarmManager(  879): done {237e90ca, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [24456ms]
,E/SQLiteLog( 6556): (284) automatic index on view_events(_id)
,I/ActivityManager(  879): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6575 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 6575): getAccountsCursor
,D/ActivityThread( 6575): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=6603 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  879): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 6603): EasService.onCreate
,I/Gmail   ( 6575): Observing account changes for notifications
W/GAV2    ( 6575): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Exchange( 6603): RestartPingTask
,I/Exchange( 6603): RestartPingsTask did not start any pings.
I/Exchange( 6603): PSS stopIfIdle
I/Exchange( 6603): PSS has no active accounts; stopping service.
,I/Exchange( 6603): onDestroy
,I/ActivityManager(  879): Killing 6243:com.google.android.videos/u0a98 (adj 15): empty #7
,I/Gmail   ( 6575): getAccountsCursor
,W/libprocessgroup(  879): failed to open /acct/uid_10098/pid_6243/cgroup.procs: No such file or directory
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/3CDM.DeviceAdminSetupReceiver( 2591): received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,D/3CDM.DeviceAdminSetupReceiver( 2591): time to show notification
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Killing 6481:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_6481/cgroup.procs: No such file or directory
,W/ResourcesManager( 1287): Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,E/SQLiteLog( 6575): (283) recovered 30 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6646 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/Gmail   ( 6575): notifyAccountChanged
,I/Gmail   ( 6575): getAccountsCursor
,I/Gmail   ( 6575): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6575): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/AlarmManager(  879): send {1c6a6522, *walarm*:android.content.syncmanager.SYNC_ALARM}
,I/Gmail   ( 6575): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/ActivatableNotificationView( 1287):  oops Width=0 ActualHeight=128
,I/Gmail   ( 6575): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/PhoneMonitor( 6646): Register our PhoneStateListener
,I/ActivityManager(  879): Killing 6512:android.process.acore/u0a7 (adj 15): empty #7
,I/art     (  879): Explicit concurrent mark sweep GC freed 17375(1096KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/31MB, paused 1.602ms total 150.304ms
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_6512/cgroup.procs: No such file or directory
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Killing 5972:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_5972/cgroup.procs: No such file or directory
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1721): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 5305): Checking schedule, now: 1457708842129 next: 1457708848454
I/CheckinService( 5305): active receiver: disabled
,V/AlarmManager(  879): done {3d33ff03, *alarm*:com.android.server.WifiManager.action.START_SCAN} [10566ms]
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=16.91 rxSuccessRate=19.20 targetRoamBSSID=any RSSI=-41
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN with age=31684 interval=30000 maxinterval=300000
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN try full band scan age=31684 interval=30000 maxinterval=300000
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN full=false
,E/WifiStateMachine(  879): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1419): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  879): [1,457,708,842,163 ms] noteScanstart no scan source
V/AlarmManager(  879): done {3e78d4f9, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [10492ms]
,I/Gmail   ( 6575): getAccountsCursor
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TCMD    (  471): NL - Read 56 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-RESULTS 
,E/WifiStateMachine(  879): [1,457,708,842,234 ms] noteScanEnd no scan source
,E/WifiStateMachine(  879): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@ebd35dc sup_state=COMPLETED debouncing=false
,D/LocationInitializer( 5305): Restart initialization of location
,E/MDM     ( 1721): [153] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1721): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1721): No location to return for getLastLocation()
,W/FusedLocationProvider( 1721): location=null
,V/AlarmManager(  879): done {3509db24, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [5029ms]
,D/Finsky  ( 6433): [795] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  879): done {1c6a6522, *walarm*:android.content.syncmanager.SYNC_ALARM} [442ms]
,I/CalendarProvider2( 6556): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6556): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/GCM     ( 1721): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  879): Killing 6603:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10060/pid_6603/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SFPerfTracer(  278):      triggers: (rate: 13:532) (compose: 0:1) (post: 0:1) (render: 0:2) (38:986 frames) (39:1080)
,D/SFPerfTracer(  278):        layers: (3:11) (FocusedStackFrame (0xb7aea308): 0:15)* (DimLayer (0xb7acf860): 0:7)* (StatusBar (0xb7ad5f88): 39:195) (NavigationBar (0xb7a43c38): 0:49) (com.android.systemui.ImageWallpaper (0xb7a46028): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7af5a90): 0:57)- (Starting com.test.thalitest (0xb7ad1768): 0:38)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7af7a60): 0:49) 
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/GAV2    ( 6575): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  879): Waited long enough for: ServiceRecord{7bce90e u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/OtaApp  ( 2591): [info] > Device got rebooted and poll interval expired
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.cUsPollingService.pollingManagerIntent
,I/OtaApp  ( 2591): [info] > CusPollingService interval expired, doing check for upgrade
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/OtaApp  ( 2591): [debug] > CusSM.onPollingExpiryNotification
,E/CdsService( 2591): [e] > Failed to parse int value from string null exception :java.lang.NumberFormatException: Invalid int: "null"
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2591): [d] > Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/CdsService( 2591): [d] > Check Request getUrl(): url is https://moto-cds.appspot.com/cds/upgrade/1/check/ctx/ota/key/XT1072
,I/CdsService( 2591): [i] > Starting webservice android service
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,I/CdsService( 2591): [i] > Received web service call for request :https://moto-cds.appspot.com/cds/upgrade/1/check/ctx/ota/key/XT1072
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2591): [d] > appending web service request to serviceHandler
,W/ActivityThread( 2591): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:38000 mC
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/CheckinService( 5305): Done disabling old GoogleServicesFramework version
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/CdsService( 2591): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/SbBHNyN0rXQjmOJQCpmfFXb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mTuJGx46U6EpyfxKrlh5tcSdFokPHBzDzREij%2BvdKIRzO5FL7iE20PB33LGaO09sGDEvIpKFSH4%2BzIHQSDghJUYRNKKQ9SRc%2FBVfWhZi2lZUInPgXaTrkRdTqC3Nschp0T58OPhFUKWddXFmREvjTh8YbSey29%2BC%2BRfN7PDtajWIaRxSfU2XZ7wcK85lgBeq64dbfuti2QAHLpKSv5%2F5rV6kbhp%2BF3pIy43susTnHSCK2ihDMJRgyBc%2FI8X84VLXD35m6iyx%2BGv2BvyTRULsTPEA7M7LEu98BFmb5okGxwLJ4%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/diM9nJFHceVNvrcVnPlsRnb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7
,D/CdsService( 2591): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/SbBHNyN0rXQjmOJQCpmfFXb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mTuJGx46U6EpyfxKrlh5tcSdFokPHBzDzREij%2BvdKIRzO5FL7iE20PB33LGaO09sGDEvIpKFSH4%2BzIHQSDghJUYRNKKQ9SRc%2FBVfWhZi2lZUInPgXaTrkRdTqC3Nschp0T58OPhFUKWddXFmREvjTh8YbSey29%2BC%2BRfN7PDtajWIaRxSfU2XZ7wcK85lgBeq64dbfuti2QAHLpKSv5%2F5rV6kbhp%2BF3pIy43susTnHSCK2ihDMJRgyBc%2FI8X84VLXD35m6iyx%2BGv2BvyTRULsTPEA7M7LEu98BFmb5okGxwLJ4%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/diM9nJFHceVNvrcVnP
,I/OtaApp  ( 2591): [info] > OTAUpgradeSource.handleCheckWSResponse: check_for_update : 200 : {"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/SbBHNyN0rXQjmOJQCpmfFXb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mTuJGx46U6EpyfxKrlh5tcSdFokPHBzDzREij%2BvdKIRzO5FL7iE20PB33LGaO09sGDEvIpKFSH4%2BzIHQSDghJUYRNKKQ9SRc%2FBVfWhZi2lZUInPgXaTrkRdTqC3Nschp0T58OPhFUKWddXFmREvjTh8YbSey29%2BC%2BRfN7PDtajWIaRxSfU2XZ7wcK85lgBeq64dbfuti2QAHLpKSv5%2F5rV6kbhp%2BF3pIy43susTnHSCK2ihDMJRgyBc%2FI8X84VLXD35m6iyx%2BGv2BvyTRULsTPEA7M7LEu98BFmb5okGxwLJ4%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/diM9nJFHceVNvrcVnPlsRnb98SYvcz3La8G7Q%2FzZfF%2Fx2%
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > AndroidPollingManager.handleIntent: com.motorola.blur.service.blur.upgrade_poll
I/OtaApp  ( 2591): [info] > Next Polling is scheduled at 1439 mins from now
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > PollingManagerService, registerApp(): cUsPollingService
,I/OtaApp  ( 2591): [info] > CusSM.handleNewVersion: was notified of a new version : src Blur_Version.22.21.28.thea_reteu.reteuall.en.EU: dest Blur_Version.22.46.12.thea_reteu.reteuall.en.EU: current Blur_Version.22.21.28.thea_reteu.reteuall.en.EU: size 263329787: contentTimeStamp 1445419042000
,D/OtaApp  ( 2591): [debug] > PollingManagerService, registerApp(): shortest interval is 86399000
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2591): [info] > Device is NOT rooted. persist.qe=qe 0/0
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > Polling alarm set to expire at: 86517785 Current Time: 118798
,E/OtaApp  ( 2591): [error] > UpgradeSource.isUpgradeAcceptable succeeded 
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > prevDestVersion = Blur_Version.22.46.12.thea_reteu.reteuall.en.EU
,W/OtaApp  ( 2591): [warn] > CusSM.handleNewVersion: already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,E/OtaApp  ( 2591): [error] > CusSM.failNotify: notification failed from repository upgrade for reason already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK; additional information: polling initiated upgrade
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1457708852221, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/OtaApp  ( 2591): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1457708852235, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/OtaApp  ( 2591): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
D/OtaApp  ( 2591): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  NotifiedBlur_Version.22.21.28.thea_reteu.reteuall.en.EUBlur_Version.22.46.12.thea_reteu.reteuall.en.EURepository: upgrade; Location: null; AddOnInfo: polling initiated upgradehttps://motorola-global-en-uk.custhelp.com/app/answers/prod_answer_detail/a_id/1073741457708852245true
,D/OtaApp  ( 2591): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; src: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; dest: Blur_Version.22.46.12.thea_reteu.reteuall.en.EU; upgradeSource:upgrade; Repository: upgrade; Location: null; AddOnInfo: polling initiated upgrade; reportingTag: ; trackingId: 1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E; metaDataVersion: null; ro.carrier: reteu. time: 1457708852
,E/CdsService( 2591): [e] > Failed to parse int value from string null exception :java.lang.NumberFormatException: Invalid int: "null"
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2591): [d] > Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/CdsService( 2591): [d] > State Request getUrl(): url is https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072
,I/CdsService( 2591): [i] > Received web service call for request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072
,I/OtaApp  ( 2591): [info] > OTAUpgradeSource.handleCheckWSResponse: check_for_update handle new version returned false
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
D/CdsService( 2591): [d] > appending web service request to serviceHandler
,D/OtaApp  ( 2591): [debug] > BotaFotaResolver.parse got the following check order (bota); assuming only bota is enabled
D/OtaApp  ( 2591): [debug] > OTAUpgradeSource.handleCheckWSResponse: authoritative response from BOTA ERR_NOTFOUND
,D/OtaApp  ( 2591): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2591): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: server told to :wait
D/CdsService( 2591): [d] > appending web service response to serviceHandler
D/CdsService( 2591): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/check/ctx/ota/key/XT1072 from queue
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/art     ( 3034): Background sticky concurrent mark sweep GC freed 13436(1956KB) AllocSpace objects, 6(96KB) LOS objects, 21% free, 7MB/9MB, paused 5.962ms total 29.972ms
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=338, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2362000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311474, SEQNUM=4385, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-7, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,V/AlarmManager(  879): send {2006f900, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  879): send {3a82377e, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  879): send {3d33ff03, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  879): done {3a82377e, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [14ms]
,V/AlarmManager(  879): done {2006f900, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [42ms]
V/AlarmManager(  879): done {3d33ff03, *alarm*:com.android.server.WifiManager.action.START_SCAN} [42ms]
,E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.15 rxSuccessRate=4.19 targetRoamBSSID=any RSSI=-41
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN with age=45304 interval=30000 maxinterval=300000
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN try full band scan age=45304 interval=30000 maxinterval=300000
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN bump interval =45000
I/wpa_supplicant( 1419): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  879): [1,457,708,855,784 ms] noteScanstart no scan source
,I/CheckinService( 5305): Checking schedule, now: 1457708855820 next: 1457708848454
I/CheckinService( 5305): active receiver: enabled
,I/CheckinService( 5305): Preparing to send checkin request
,I/EventLogService( 5305): Accumulating logs since 1457708812016
,I/CheckinRequestBuilder( 5305): Checkin reason type: 8 attempt count: 1
,D/WifiService(  879): New client listening to asynchronous messages
,E/ActivityThread( 5305): Failed to find provider info for com.google.android.wearable.settings
,D/Finsky  ( 6433): [790] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6433): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LaunchCheckinHandler(  879): cleanup(): cleared. Last call was 14276 ms ago
I/ActivityManager(  879): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6780 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6780): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6780): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6780): VM with version 2.1.0 has multidex support
I/MultiDex( 6780): install
,I/MultiDex( 6780): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6780): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 25 
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-ADDED 25 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 26 
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-ADDED 26 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 1
,D/TCMD    (  471): NL - Read 56 bytes from update socket.
,D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
,D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-RESULTS 
,E/WifiStateMachine(  879): [1,457,708,856,248 ms] noteScanEnd no scan source
,E/WifiStateMachine(  879): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@ebd35dc sup_state=COMPLETED debouncing=false
,W/ActivityThread( 6780): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6780): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@fea587f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6780): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1721): callingUid 10016, callindPid: 1721
,E/MDM     ( 1721): [180] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5305): Restart initialization of location
,D/AuthorizationBluetoothService( 1721): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1721): No location to return for getLastLocation()
W/FusedLocationProvider( 1721): location=null
,D/Volley  ( 2591): [255] BasicNetwork.logSlowRequests: HTTP response for request=<[ ] https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072 0xbbf0b9ca NORMAL 1> [lifetime=3993], [size=331], [rc=200], [retryCount=0]
,D/CdsService( 2591): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}
,D/Volley  ( 2591): [1] Request.finish: 4015 ms: [ ] https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072 0xbbf0b9ca NORMAL 1
,D/CdsService( 2591): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}}
D/OtaApp  ( 2591): [debug] > Inside handleStateResponse
D/OtaApp  ( 2591): [debug] > exec delete from status where _id=1
,D/OtaApp  ( 2591): [debug] > stopTimer, cancel()
,D/OtaApp  ( 2591): [debug] > handleStateResponse server told to : continue
,D/OtaApp  ( 2591): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
,D/OtaApp  ( 2591): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  ResultBlur_Version.22.21.28.thea_reteu.reteuall.en.EUBlur_Version.22.46.12.thea_reteu.reteuall.en.EUalready working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OKhttps://motorola-global-en-uk.custhelp.com/app/answers/prod_answer_detail/a_id/1073741457708856369true
,D/OtaApp  ( 2591): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; src: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; dest: Blur_Version.22.46.12.thea_reteu.reteuall.en.EU; upgradeSource:upgrade; already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK; reportingTag: ; trackingId: 1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E; metaDataVersion: null; ro.carrier: reteu. time: 1457708852
,I/art     ( 6780): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6780): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/CdsService( 2591): [e] > Failed to parse int value from string null exception :java.lang.NumberFormatException: Invalid int: "null"
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2591): [d] > Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/CdsService( 2591): [d] > State Request getUrl(): url is https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072
,I/CdsService( 2591): [i] > Received web service call for request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/CdsService( 2591): [d] > appending web service request to serviceHandler
,I/OtaApp  ( 2591): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2591): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/OtaApp  ( 2591): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/CdsService( 2591): [d] > appending web service response to serviceHandler
,D/OtaApp  ( 2591): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/CdsService( 2591): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072 from queue
,D/OtaApp  ( 2591): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2591): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  879): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/NativeLibraryUtils( 6780): Install completed successfully. count=14 extracted=0
,D/OtaApp  ( 2591): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2591): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/JX-Cordova( 5470): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28ec87d9 added. We now have 3 listener(s)
,D/BluetoothManagerService(  879): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/OtaApp  ( 2591): [info] > Exceed max defer attempts for optional update, suppresing later btn
D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > cancelling the previous pending intent set for download later
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5470): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5470): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): load: Already loaded
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28f0259e added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5470): addListener: New listener added - the number of listeners is now 1
,I/OtaApp  ( 2591): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5470): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
W/System.err( 5470): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 5470): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 5470): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5470): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5470): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5470): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5470): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5470): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
,W/System.err( 5470): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5470): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5470): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5470): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5470): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5470): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/OtaApp  ( 2591): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2591): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2591): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2591): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1408): onFinishInput()
,W/IInputConnectionWrapper( 5470): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  879): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,130
,D/WVCdm   (  302): Instantiating CDM.
I/WVCdm   (  302): CdmEngine::OpenSession
,I/WVCdm   (  302): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  302): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  302): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  302): Service_Initialize: starts!
D/QSEECOMAPI: (  302): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  302): App is not loaded in QSEE
E/QSEECOMAPI: (  302): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  302): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  302): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  302): App is not loaded in QSEE
E/QSEECOMAPI: (  302): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  302): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  302): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  302): App is not loaded in QSEE
,D/QSEECOMAPI: (  302): Loaded image: APP id = 3
,D/DrmWidevineDash(  302): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ce2000
E/DrmWidevineDash(  302): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ce2000
,D/DrmWidevineDash(  302): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  302): hlos api version =  9
D/DrmWidevineDash(  302): tz api version =  8
D/DrmWidevineDash(  302): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  302): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  302): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  302): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  302): OEMCrypto_OpenSession: starts! SID=0xb5476960
D/DrmWidevineDash(  302): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  302): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_GetRandom: starts! randomData=0xb729bfb8, dataLength=8
D/DrmWidevineDash(  302): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  302): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb72a17c0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  302): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  302): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  302): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  302): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  302): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  302): OEMCrypto_GetDeviceID: starts! deviceID=0xb73ce7e8, idLength=0xb4fd0730
,D/DrmWidevineDash(  302): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  302): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  302): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  302): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  302): hlos api version =  9
D/DrmWidevineDash(  302): tz api version =  8
,D/DrmWidevineDash(  302): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  302): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  302): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  302): PrepareKeyRequest: nonce=1116393464
D/DrmWidevineDash(  302): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7382f78
D/DrmWidevineDash(  302): message_length=1591, signature=0xb72d4610, signature_length=3036481300
,I/art     ( 6780): Background partial concurrent mark sweep GC freed 16171(992KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/16MB, paused 6.270ms total 49.314ms
,D/DrmWidevineDash(  302): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  302): CdmEngine::CloseSession
D/DrmWidevineDash(  302): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  302): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  302): L3 Terminate.
D/DrmWidevineDash(  302): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  302): Service_Uninitialize: starts!
D/QSEECOMAPI: (  302): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  302): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  302): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  302): OEMCrypto_Terminate: ends! returns 0
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/WVCdm   (  302): CdmEngine::OpenSession
I/WVCdm   (  302): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  302): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  302): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  302): Service_Initialize: starts!
D/QSEECOMAPI: (  302): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  302): App is not loaded in QSEE
E/QSEECOMAPI: (  302): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  302): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  302): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  302): App is not loaded in QSEE
E/QSEECOMAPI: (  302): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  302): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  302): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  302): App is not loaded in QSEE
,D/QSEECOMAPI: (  302): Loaded image: APP id = 3
,D/DrmWidevineDash(  302): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  302): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ce2000
E/DrmWidevineDash(  302): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ce2000
,D/DrmWidevineDash(  302): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  302): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  302): hlos api version =  9
D/DrmWidevineDash(  302): tz api version =  8
,D/DrmWidevineDash(  302): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  302): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  302): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  302): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  302): OEMCrypto_OpenSession: starts! SID=0xb5476960
D/DrmWidevineDash(  302): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  302): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_GetRandom: starts! randomData=0xb729bfb8, dataLength=8
D/DrmWidevineDash(  302): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  302): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb72d0ff0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  302): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  302): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  302): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  302): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  302): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  302): OEMCrypto_GetDeviceID: starts! deviceID=0xb73ce808, idLength=0xb5576730
,D/DrmWidevineDash(  302): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  302): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  302): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  302): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  302): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  302): hlos api version =  9
D/DrmWidevineDash(  302): tz api version =  8
D/DrmWidevineDash(  302): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  302): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  302): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  302): PrepareKeyRequest: nonce=3114210288
D/DrmWidevineDash(  302): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb72add10
D/DrmWidevineDash(  302): message_length=1622, signature=0xb72b17d0, signature_length=3042404116
,D/DrmWidevineDash(  302): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  302): CdmEngine::CloseSession
,D/DrmWidevineDash(  302): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  302): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  302): L3 Terminate.
D/DrmWidevineDash(  302): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  302): Service_Uninitialize: starts!
D/QSEECOMAPI: (  302): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  302): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  302): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  302): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 6839): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6839): dex2oat took 79.978ms (threads: 4)
,I/Adreno-EGL( 6780): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6780): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6780): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6780): Local Branch: 
I/Adreno-EGL( 6780): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6780): Local Patches: NONE
I/Adreno-EGL( 6780): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Adreno-EGL( 6780): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6780): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6780): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6780): Local Branch: 
I/Adreno-EGL( 6780): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6780): Local Patches: NONE
I/Adreno-EGL( 6780): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6780): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6780): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6780): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6780): Local Branch: 
I/Adreno-EGL( 6780): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6780): Local Patches: NONE
I/Adreno-EGL( 6780): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6780): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6780): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6780): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6780): Local Branch: 
I/Adreno-EGL( 6780): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6780): Local Patches: NONE
I/Adreno-EGL( 6780): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 5305): Classify the device as Phone.
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/CheckinTask( 5305): Sending checkin request (9649 bytes)
,I/CheckinRequestBuilder( 5305): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5305): Failed to find provider info for com.google.android.wearable.settings
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/CheckinRequestBuilder( 5305): Classify the device as Phone.
,I/CheckinTask( 5305): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5305): Checking schedule, now: 1457708859166 next: 1458309996154
I/CheckinService( 5305): active receiver: disabled
,D/CheckinService( 5305): Recording last checkin time for package unspecified as 1457708859178
,I/art     (  879): Explicit concurrent mark sweep GC freed 29547(1470KB) AllocSpace objects, 4(162KB) LOS objects, 33% free, 21MB/32MB, paused 1.476ms total 119.792ms
,V/SetupWizard( 6646): Connected to Gservices successfully
,D/GCM     ( 1721): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:37000 mC
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TaskPersister(  879): removeObsoleteFile: deleting file=8_task.xml
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Volley  ( 2591): [262] BasicNetwork.logSlowRequests: HTTP response for request=<[ ] https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072 0xbbf0b9ca NORMAL 1> [lifetime=5047], [size=331], [rc=200], [retryCount=0]
,D/CdsService( 2591): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}
D/Volley  ( 2591): [1] Request.finish: 5053 ms: [ ] https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072 0xbbf0b9ca NORMAL 1
,D/CdsService( 2591): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}}
D/OtaApp  ( 2591): [debug] > Inside handleStateResponse
D/OtaApp  ( 2591): [debug] > exec delete from status where _id=2
,D/OtaApp  ( 2591): [debug] > stopTimer, have stoped, do nothing
D/OtaApp  ( 2591): [debug] > handleStateResponse server told to : continue
D/OtaApp  ( 2591): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2591): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2591): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2591): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2591): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2591): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  879): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,D/OtaApp  ( 2591): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 2591): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2591): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2591): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2591): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/CdsService( 2591): [d] > appending web service response to serviceHandler
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2591): [debug] > cancelling the previous pending intent set for download later
,D/CdsService( 2591): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072 from queue
D/CdsService( 2591): [d] > No pending web request. shutdown webservice
,I/OtaApp  ( 2591): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,I/CdsService( 2591): [i] > Stopping webservice android service
,D/Checkin ( 2591): publish the event [tag = MOT_OTA event name = LOG]
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  879): Killing 6575:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10063/pid_6575/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  879): Killing 6538:com.motorola.context/u0a8 (adj 15): empty #7
,I/ActivityManager(  879): Killing 6556:com.android.providers.calendar/u0a5 (adj 15): empty #8
,W/libprocessgroup(  879): failed to open /acct/uid_10008/pid_6538/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10005/pid_6556/cgroup.procs: No such file or directory
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6872 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  879): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  879): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  879): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  879): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1b8ac349
,I/GCoreNlp( 1721): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1567): Deferring update until onResume
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6904 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6921 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 5794:com.google.android.calendar/u0a49 (adj 15): empty #7
,I/art     (  319): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.042ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 21.395ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 20.663ms
,I/ActivityManager(  879): Killing 6433:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10049/pid_5794/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10032/pid_6433/cgroup.procs: No such file or directory
,W/ResourcesManager( 6921): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6921): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6921): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6921): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6921): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6921): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6921): MmsConfig.loadFromResources
,E/Babel_SMS( 6921): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6921): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6921): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6921): startup - clean
,I/Babel   ( 6921): deleted: false for 0
,I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6950 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 6921): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6921): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6921): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6921): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6921): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6921): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6921): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6921): Unrecognized profile 2130706433 for video/avc
,I/ContactLocale( 6950): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6975 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 6646:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_6646/cgroup.procs: No such file or directory
,I/vclib   ( 6921): onServiceConnected
,W/Babel   ( 6921): Attempted to change video mute state without an active call.
,W/asset   ( 6975): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 6975): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 6975): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6975): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 6921): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6921): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2a7ee654 new=com.google.android.velvet.VelvetApplication@2a7ee654
I/UpdateIcingCorporaServi( 6872): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,V/JNIHelp ( 6921): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PkgBroadcastIntentOp( 5305): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PkgBroadcastIntentOp( 5305): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7002 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/System  ( 6921): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6921): Installed default security provider GmsCore_OpenSSL
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WearableController( 5305): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/Icing   ( 5305): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7002): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 6872): UpdateCorporaTask done [took 140 ms] updated apps [took 140 ms] 
,I/art     ( 1721): Explicit concurrent mark sweep GC freed 30247(1877KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 14MB/23MB, paused 1.432ms total 76.121ms
,I/ActivityManager(  879): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7032 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6780:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10016/pid_6780/cgroup.procs: No such file or directory
,D/Finsky  ( 7032): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7032): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7032): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7032): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7032): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7032): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7032): Skipping gmscore version check
,D/Finsky  ( 7032): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7032): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  879): Killing 6904:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10019/pid_6904/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Icing   ( 5305): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 5305): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:36000 mC
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  879): send {1c6a6522, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  879): done {1c6a6522, *walarm*:android.content.syncmanager.SYNC_ALARM} [3ms]
,I/ActivityManager(  879): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7085 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6921:com.google.android.talk/u0a70 (adj 15): empty #7
,E/ActivityThread( 5305): Failed to find provider info for com.android.contacts.metadata
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_6921/cgroup.procs: No such file or directory
,D/SyncManager(  879): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 200105, reason: UserStart
,I/ActivityManager(  879): Start proc com.google.android.apps.docs.editors.sheets for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService: pid=7119 uid=10105 gids={50105, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  879): send {13c75ac3, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
V/AlarmManager(  879): send {3d33ff03, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  879): done {13c75ac3, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [10ms]
V/AlarmManager(  879): done {3d33ff03, *alarm*:com.android.server.WifiManager.action.START_SCAN} [11ms]
,E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.82 rxSuccessRate=1.38 targetRoamBSSID=any RSSI=-41
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN with age=16914 interval=45000 maxinterval=300000
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  879): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
,I/wpa_supplicant( 1419): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  879): [1,457,708,872,696 ms] noteScanstart no scan source
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 27 
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-ADDED 27 
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  471): NL - Read 56 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
E/WifiStateMachine(  879): [1,457,708,872,763 ms] noteScanEnd no scan source
E/WifiStateMachine(  879): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@ebd35dc sup_state=COMPLETED debouncing=false
,I/art     (  879): Explicit concurrent mark sweep GC freed 28934(1480KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/32MB, paused 1.807ms total 131.158ms
,I/GAv4    ( 7085): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7085):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7085):   adb logcat -s GAv4
,W/GAv4    ( 7085): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7085): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7085): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7085): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7085): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 7085): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7085): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7085): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7085): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7085): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  879): Killing 6975:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10027/pid_6975/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1721): Vacuum at: now=1457708873444 tag=VacuumService
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 5305): 0 accounts found with uca feature
I/GamesSyncAdapter( 5305): Starting sync for 3a3529a
I/GamesSyncAdapter( 5305): Sync duration for 3a3529a: 4
,I/GAv4    ( 7119): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7119):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7119):   adb logcat -s GAv4
,W/GAv4    ( 7119): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7119): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7119): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7119): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.312.11.30
,E/SQLiteLog( 7119): (283) recovered 25 frames from WAL file /data/data/com.google.android.apps.docs.editors.sheets/databases/DocList.db-wal
,I/ActivityManager(  879): Killing 6872:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_6872/cgroup.procs: No such file or directory
,W/ResourcesManager( 7119): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7119): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Killing 6950:android.process.acore/u0a7 (adj 15): empty #7
,V/JNIHelp ( 7119): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 7119): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_6950/cgroup.procs: No such file or directory
,I/PhenotypeConfigurator( 1721): Scheduling Phenotype for one-off execution 11528 seconds from now (1457708874672)
,I/PhenotypeFlagCommitter( 1721): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1721): Using platform SSLCertificateSocketFactory
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=328, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311768, SEQNUM=4414, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1010, POWER_SUPPLY_CHARGE_COUNTER=3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:358 vsyncs) (1:1138)
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1721): Background sticky concurrent mark sweep GC freed 111455(6MB) AllocSpace objects, 20(343KB) LOS objects, 27% free, 16MB/23MB, paused 1.920ms total 100.767ms
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:36000 mC
,V/AlarmManager(  879): send {3f2b2b23, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): done {3f2b2b23, *alarm*:android.intent.action.TIME_TICK} [39ms]
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/BackupManagerService(  879): Timeout restoring application @pm@
,W/BackupManagerService(  879): Tried to clear data for @pm@ but not found
,W/GmsBackupTransport( 1721): Restore processing aborted, no more packages
,E/BackupManagerService(  879): Failure getting next package name
E/BackupManagerService(  879): Duplicate finish
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:35000 mC
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=320, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312355, SEQNUM=4419, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1616, POWER_SUPPLY_CHARGE_COUNTER=15, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,V/AlarmManager(  879): send {3b277e01, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
V/AlarmManager(  879): send {3d33ff03, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  879): done {3b277e01, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [13ms]
V/AlarmManager(  879): done {3d33ff03, *alarm*:com.android.server.WifiManager.action.START_SCAN} [13ms]
,E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.58 rxSuccessRate=0.34 targetRoamBSSID=any RSSI=-40
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN with age=41058 interval=45000 maxinterval=300000
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  879): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1419): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  879): [1,457,708,896,843 ms] noteScanstart no scan source
,I/EventLogService( 5305): Aggregate from 1457708855901 (log), 1457707096610 (data)
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  471): NL - Read 56 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
,E/WifiStateMachine(  879): [1,457,708,896,917 ms] noteScanEnd no scan source
,E/WifiStateMachine(  879): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@ebd35dc sup_state=COMPLETED debouncing=false
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/PowerManagerService(  879): Nap time (uid 1000)...
,I/PowerManagerService(  879): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  879): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  879): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  879): Build Date: 10/28/14 Tue
I/Adreno-EGL(  879): Local Branch: 
I/Adreno-EGL(  879): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  879): Local Patches: NONE
I/Adreno-EGL(  879): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  879): activate, handle: 1598182242, enabled: 0, index 2
,D/        (  879): BstSensorExt: id=1598182242, en=0
D/        (  879): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 230
,D/        (  879): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  879): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  879): Display changed displayId=0
,D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb79ba550
,D/qdhwcomposer(  278): hwc_blank: Blanking display: 0
,I/rmt_storage(  294): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8e2f820
I/rmt_storage(  294): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  294): wakelock acquired: 1, error no: 42
I/rmt_storage(  294): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1193085640)
,I/rmt_storage(  294): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  294): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  294): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1193085640) wakelock released: 1, error no: 0
I/rmt_storage(  294): 
,I/rmt_storage(  294): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8e2f820
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  278): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  278): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  879): Excessive delay in setPowerMode(): 355ms
,I/SFPerfTracer(  278):       trigger: frame rate (-29.189%)	(42.487 fps)	(23.537 ms) 	(3 drops)	(16 frames)
,I/SFPerfTracer(  278):      triggers: (rate: 14:538) (compose: 0:2) (post: 0:1) (render: 0:3) (16:1044 frames) (17:1164)
D/SFPerfTracer(  278):        layers: (4:11) (FocusedStackFrame (0xb7aea308): 0:17)* (DimLayer (0xb7acf860): 0:10)* (StatusBar (0xb7ad5f88): 0:221) (NavigationBar (0xb7a43c38): 0:62) (com.android.systemui.ImageWallpaper (0xb7a46028): 0:8)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb7af7a60): 0:78)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7ad1768): 0:31) (ColorFade (0xb7ad2b70): 17:19) 
I/WindowManager(  879): AOD feature not enabled!
I/PowerManagerService(  879): Sleeping (uid 1000)...
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/LaunchCheckinHandler(  879): cleanup(): cleared. Last call was 26298 ms ago
,D/audio_hw_primary(  302): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  302): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  302): platform_set_parameters: exit with code(0)
E/msm8974_platform(  302): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  302): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  302): adev_set_parameters: ERROR: set param called even when stream out is null
D/WifiStateMachine(  879): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  879): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  879): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  879): do suspend false
,I/Keyboard.Facilitator( 1408): onFinishInput()
,D/        (  879): activate, handle: 1598182229, enabled: 0, index 0
E/        (  879): <BST> disable accel, orig state: 1
I/        (  879): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  302): adev_set_parameters: enter: screen_state=off
,V/msm8974_platform(  302): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  302): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  302): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  302): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiStateMachine(  879): backgroundScan enabled=true startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  879): handleScreenStateChanged Exit: false
E/WifiStateMachine(  879): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  879): do suspend true
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:35000 mC
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  879): send {1c6a6522, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  879): done {1c6a6522, *walarm*:android.content.syncmanager.SYNC_ALARM} [5ms]
,V/AlarmManager(  879): send {2fde082c, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  879): done {2fde082c, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [6ms]
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:34000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=311, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312186, SEQNUM=4429, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=504, POWER_SUPPLY_CHARGE_COUNTER=14, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:34000 mC
,V/AlarmManager(  879): send {60f12f5, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  879): done {60f12f5, *walarm*:com.google.android.intent.action.SEND_IDLE} [71ms]
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:33000 mC
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=303, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311806, SEQNUM=4431, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-7, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,E/global frequency( 2591): no tags to log
,D/Checkin ( 2591): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     (  879): Explicit concurrent mark sweep GC freed 45725(2MB) AllocSpace objects, 2(234KB) LOS objects, 33% free, 21MB/32MB, paused 1.928ms total 134.962ms
,I/BSUtils ( 2591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 7575(335KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 7MB/12MB, paused 585us total 36.208ms
,I/BSUtils ( 2591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2591): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2591): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2591): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2591): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2591): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2591): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2591): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2591): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ClearcutLoggerApiImpl( 1721): disconnect managed GoogleApiClient
,V/AlarmManager(  879): send {3f2b2b23, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {2f8ae971, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  879): done {2f8ae971, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [10ms]
,V/AlarmManager(  879): done {3f2b2b23, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/Keyboard.Facilitator.LanguageModelFlusher( 1408): run()
,I/Keyboard.Facilitator( 1408): flushDynamicLanguageModels()
,I/ConfigService( 1721): onCreate
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:33000 mC
,I/ConfigService( 1721): onDestroy
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=297, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312291, SEQNUM=4434, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-57, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 2
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311880, SEQNUM=4436, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-31, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,D/AndroidRuntime( 7284): 
D/AndroidRuntime( 7284): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7284): CheckJNI is OFF
,D/AndroidRuntime( 7284): Calling main entry com.android.commands.pm.Pm
,D/AndroidRuntime( 7284): Shutting down VM
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1721): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  879): send {3f2b2b23, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): done {3f2b2b23, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311539, SEQNUM=4440, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-49, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  879): send {3f2b2b23, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  879): send {1556dceb, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  879): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7308 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  879): done {3f2b2b23, *alarm*:android.intent.action.TIME_TICK} [109ms]
,I/GAv4    ( 7308): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7308):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7308):   adb logcat -s GAv4
,W/GAv4    ( 7308): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7308): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7308): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  879): done {1556dceb, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [351ms]
I/ActivityManager(  879): Killing 7002:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_7002/cgroup.procs: No such file or directory
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=282, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312101, SEQNUM=4443, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-46, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs.editors.sheets/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7119): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs.editors.sheets/files
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311760, SEQNUM=4444, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-44, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  879): send {3f2b2b23, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  879): send {3e78d4f9, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  879): done {3e78d4f9, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [3ms]
,V/AlarmManager(  879): done {3f2b2b23, *alarm*:android.intent.action.TIME_TICK} [43ms]
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311755, SEQNUM=4446, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-70, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/UsageStatsService(  879): User[0] Flushing usage stats to disk
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312006, SEQNUM=4447, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1615, POWER_SUPPLY_CHARGE_COUNTER=12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2450): Disconnected process message: 10, size: 0
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  879): send {3f2b2b23, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  879): send {160dda48, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  879): done {160dda48, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [20ms]
,V/AlarmManager(  879): done {3f2b2b23, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  315): Sensor:xo_therm_pu2:30000 mC
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 7358): 
D/AndroidRuntime( 7358): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7358): CheckJNI is OFF
D/AndroidRuntime( 7358): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10570 user=-1: uninstall pkg
I/ActivityManager(  879): Killing 5470:com.test.thalitest/u0a570 (adj 7): stop com.test.thalitest
I/WindowState(  879): WIN DEATH: Window{aea5619 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  879): Client connection lost with reason: 4
W/PackageSettings(  879): Skipping PackageSetting{31e714e3 com.example.hello/10568} due to missing metadata
I/ActivityManager(  879):   Force finishing activity ActivityRecord{333d623b u0 com.test.thalitest/.MainActivity t9}
W/ActivityManager(  879): Spurious death for ProcessRecord{381810e1 5470:com.test.thalitest/u0a570}, curProc for 5470: null
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10570 user=0: pkg removed
I/ActivityManager(  879):   Force finishing activity ActivityRecord{333d623b u0 com.test.thalitest/.MainActivity t9 f}
W/ActivityManager(  879): Duplicate finish request for ActivityRecord{333d623b u0 com.test.thalitest/.MainActivity t9 f}
I/art     ( 3034): Explicit concurrent mark sweep GC freed 12071(3MB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 7MB/12MB, paused 1.072ms total 37.696ms
I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1721): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1408): resetDictionaries() : en_US
I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7387 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1408): run()
I/art     ( 5305): Explicit concurrent mark sweep GC freed 36958(2MB) AllocSpace objects, 14(224KB) LOS objects, 24% free, 14MB/19MB, paused 870us total 144.567ms
I/art     ( 1567): Explicit concurrent mark sweep GC freed 6274(426KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 492us total 115.088ms
I/Decoder ( 1408): createOrResetDecoder
I/ConfigService( 1721): onCreate
I/art     (  879): Explicit concurrent mark sweep GC freed 17173(1222KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 21MB/32MB, paused 2.368ms total 179.136ms
I/art     (  879): WaitForGcToComplete blocked for 76.424ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1408): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1408): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1408): run()
I/StatsUtilsManager( 1408): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1408): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 7387): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7411 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 7387): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  879): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  879): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  879): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/ActivityManager(  879): Killing 7032:com.android.vending/u0a32 (adj 15): empty #7
I/Launcher( 1567): Deferring update until onResume
I/art     (  879): Explicit concurrent mark sweep GC freed 5044(266KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 2.699ms total 186.728ms
W/libprocessgroup(  879): failed to open /acct/uid_10032/pid_7032/cgroup.procs: No such file or directory
W/asset   ( 7411): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7411): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7411): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7411): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
D/AndroidRuntime( 7358): Shutting down VM
I/ActivityManager(  879): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7432 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
W/ContextImpl( 7432): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7453 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/ActivityManager(  879): Killing 7085:com.google.android.apps.docs/u0a57 (adj 15): empty #7
I/art     (  319): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 34.977ms
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.634ms
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 400us total 21.716ms
I/ActivityManager(  879): Killing 7119:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
W/libprocessgroup(  879): failed to open /acct/uid_10057/pid_7085/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10105/pid_7119/cgroup.procs: No such file or directory
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
