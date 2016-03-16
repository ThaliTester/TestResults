#### Test 62509094c147163_thali04_motorola-XT1072 Logs


```
--------- beginning of main
03-16 08:34:49.825  4785  4785 I Exchange: onDestroy
--------- beginning of system
03-16 08:34:49.826   880   896 I ActivityManager: Killing 4593:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
03-16 08:34:49.832  4758  4817 I Gmail   : getAccountsCursor
03-16 08:34:49.916   880  1505 W libprocessgroup: failed to open /acct/uid_10096/pid_4593/cgroup.procs: No such file or directory
03-16 08:34:49.918  1738  1738 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 08:34:49.974   880  1560 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.ccc.UpdateModelReceiver: pid=4828 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
03-16 08:34:49.985   880  1298 I ActivityManager: Killing 3496:com.android.defcontainer/u0a10 (adj 15): empty #7
03-16 08:34:50.154   880  1475 W libprocessgroup: failed to open /acct/uid_10010/pid_3496/cgroup.procs: No such file or directory
03-16 08:34:50.156  1738  1738 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 08:34:50.171  4828  4828 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
03-16 08:34:50.212  2538  2538 D 3CDM.DeviceAdminPushReceiver: Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-16 08:34:50.212  2538  2538 D 3CDM.DeviceAdminPushReceiver: Type: null
03-16 08:34:50.212  2538  2538 D 3CDM.DeviceAdminPushReceiver: Data: null
03-16 08:34:50.214  2538  2592 D 3CDM.Service: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-16 08:34:50.214  2538  2592 D 3CDM.Service: Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
03-16 08:34:50.214  2538  2592 D 3CDM.Service: DeviceAdmin - syncWithCCC
03-16 08:34:50.214  2538  2592 D 3CDM.Service: blur.service.littlesister.gpsFixWaitTime = 60000
03-16 08:34:50.214  2538  2592 D 3CDM.Service: com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
03-16 08:34:50.214  2538  2592 D 3CDM.Service: blur.service.cred.locationToken = null
03-16 08:34:50.214  2538  2592 D 3CDM.Service: com.motorola.ccc.cce.email.marketing.optin.default = false
03-16 08:34:50.214  2538  2592 D 3CDM.Service: blur.service.littlesister.reportLevel2 = NONE
03-16 08:34:50.214  2538  2592 D 3CDM.Service: com.motorola.blur.adminfeed.device_admin_always_allowed = 1
03-16 08:34:50.214  2538  2592 D 3CDM.Service: com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
03-16 08:34:50.218  4828  4849 I CE-UpdateModelService: ACTION_REGISTRATION_COMPLETE
03-16 08:34:50.223  2538  2592 D 3CDM.Service: Sync to CCE settings done, instantiate Locate now.
03-16 08:34:50.234   880   880 V AlarmManager: done {500bd87, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [9744ms]
03-16 08:34:50.240  4671  4850 E SQLiteLog: (284) automatic index on view_events(_id)
03-16 08:34:50.250   880   880 V AlarmManager: done {3aff684e, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [9047ms]
03-16 08:34:50.296   880   880 V AlarmManager: done {173765b3, *alarm*:com.android.server.WifiManager.action.START_SCAN} [8405ms]
03-16 08:34:50.296   880  1232 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=15.33 rxSuccessRate=13.38 targetRoamBSSID=any RSSI=-49
03-16 08:34:50.296   880  1232 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=1458113690296 interval=20000 maxinterval=300000
03-16 08:34:50.296   880  1232 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=1458113690296 interval=20000 maxinterval=300000
03-16 08:34:50.297   880  1232 E WifiStateMachine: WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
03-16 08:34:50.297   880  1232 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-16 08:34:50.297   880  1232 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-16 08:34:50.297  1439  1439 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-16 08:34:50.298   290  1645 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-16 08:34:50.298   290  1645 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
03-16 08:34:50.300   880  1232 E WifiStateMachine: [1,458,113,690,300 ms] noteScanstart no scan source
03-16 08:34:50.304  2538  2592 D BSUtils : set .setup.DeviceAdminSetupReceiver enabled
03-16 08:34:50.315  4837  4837 D AndroidRuntime: 
03-16 08:34:50.315  4837  4837 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 08:34:50.319  4837  4837 D AndroidRuntime: CheckJNI is OFF
03-16 08:34:50.348   880  1505 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=4858 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
03-16 08:34:50.353   290  1645 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 19 
03-16 08:34:50.353   290  1645 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 19 
03-16 08:34:50.353   290  1645 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-16 08:34:50.353   290  1645 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
03-16 08:34:50.353   511   531 D TCMD    : NL - Read 56 bytes from update socket.
03-16 08:34:50.353   511   531 D TCMD    : NL - message type is RTM_NEWLINK
03-16 08:34:50.353   511   531 D TCMD    : Listening for incoming client connection request
03-16 08:34:50.355   880  1232 E WifiStateMachine: [1,458,113,690,355 ms] noteScanEnd no scan source
03-16 08:34:50.358   880  1232 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@32c15d82 sup_state=COMPLETED debouncing=false
03-16 08:34:50.433  2990  3010 D Checkin : publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
03-16 08:34:50.437   880  1577 I ActivityManager: Killing 4651:com.google.android.deskclock/u0a55 (adj 15): empty #7
03-16 08:34:50.512   880  4211 W libprocessgroup: failed to open /acct/uid_10055/pid_4651/cgroup.procs: No such file or directory
03-16 08:34:50.541  4858  4858 D PhoneMonitor: Register our PhoneStateListener
03-16 08:34:50.562  4858  4858 V SetupWizard: Connected to Gservices successfully
03-16 08:34:50.564   880  1539 I ActivityManager: Killing 4712:com.google.android.music:main/u0a80 (adj 15): empty #7
03-16 08:34:50.603   880  1577 W libprocessgroup: failed to open /acct/uid_10080/pid_4712/cgroup.procs: No such file or directory
03-16 08:34:50.636  4758  4847 E SQLiteLog: (283) recovered 48 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
03-16 08:34:50.643   880  1572 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4891 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-16 08:34:50.671  4837  4837 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 08:34:50.672  1738  2345 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
03-16 08:34:50.677   880   895 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-16 08:34:50.709   277   418 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (169 us)
03-16 08:34:50.727  1477  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-16 08:34:50.749  4837  4837 D AndroidRuntime: Shutting down VM
03-16 08:34:50.754  4758  4848 I Gmail   : notifyAccountChanged
03-16 08:34:50.757  4758  4818 I Gmail   : getAccountsCursor
03-16 08:34:50.761  4758  4848 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-16 08:34:50.779  4758  4848 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-16 08:34:50.787  4758  4848 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-16 08:34:50.788  4758  4848 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-16 08:34:50.800   880  1560 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4914 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 08:34:50.810  2538  2538 E ActivityThread: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
03-16 08:34:50.810  2538  2538 E ActivityThread: java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
03-16 08:34:50.810  2538  2538 E ActivityThread: 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3396)
03-16 08:34:50.810  2538  2538 E ActivityThread: 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3477)
03-16 08:34:50.810  2538  2538 E ActivityThread: 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
03-16 08:34:50.810  2538  2538 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1321)
03-16 08:34:50.810  2538  2538 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 08:34:50.810  2538  2538 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-16 08:34:50.810  2538  2538 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-16 08:34:50.810  2538  2538 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 08:34:50.810  2538  2538 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 08:34:50.810  2538  2538 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-16 08:34:50.810  2538  2538 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
03-16 08:34:50.813  1738  1738 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 08:34:50.846  2538  4746 D MMApiWSBase: doRequest(): v1/cs/checkin resp length: 4
03-16 08:34:50.852  2538  4746 D CCE     : AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
03-16 08:34:50.853  2538  4746 D CCE     : AppWSProxy - sendAIDLWSResponse() sending reponse
03-16 08:34:50.862  4891  4891 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 08:34:50.871  2538  4746 I global frequency: BcsCore.status() called with error code=ERROR_OK
03-16 08:34:50.872  2538  4746 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-16 08:34:50.917   880  1475 D CheckinProvider: 35 events delete 0 left
03-16 08:34:50.944  2538  4746 I global frequency: BcsDSCheckin.events found events 0
03-16 08:34:50.946  2538  4746 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-16 08:34:50.952  2538  4746 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
03-16 08:34:50.955  2538  4746 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-16 08:34:50.987   880  1595 I art     : Explicit concurrent mark sweep GC freed 15141(727KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.507ms total 146.071ms
,03-16 08:34:50.991  1477  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 08:34:51.016   880   896 I ActivityManager: Activity reported stop, but no longer stopping: ActivityRecord{ced0520 u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
,03-16 08:34:51.039  2538  2538 I global frequency: BcsTimer.onReceive checkin completed (615319702:ERROR_OK)
,03-16 08:34:51.040  2538  2538 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-16 08:34:51.155  4758  4782 I Gmail   : getAccountsCursor
,03-16 08:34:51.161  1738  1738 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 08:34:51.223  4914  4914 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-16 08:34:51.245  4891  4944 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,03-16 08:34:51.247  4891  4944 I Babel_SMS: MmsConfig.loadMmsSettings
,03-16 08:34:51.252  4891  4944 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-16 08:34:51.252  4891  4944 I Babel_SMS: MmsConfig.loadFromDatabase
,03-16 08:34:51.255  4914  4914 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8500-8503)
,03-16 08:34:51.256  4914  4914 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 08:34:51.281  4914  4914 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2b8ce729}
,03-16 08:34:51.282  4914  4914 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 08:34:51.282  4914  4914 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 08:34:51.284  4891  4944 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-16 08:34:51.284  4891  4944 I Babel_SMS: MmsConfig.loadFromResources
03-16 08:34:51.287  4891  4944 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-16 08:34:51.287  4891  4944 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 08:34:51.300  4914  4914 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-16 08:34:51.301  4914  4914 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 08:34:51.302  4914  4914 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 08:34:51.324  4914  4914 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-16 08:34:51.331  4914  4914 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 08:34:51.331  4914  4914 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 08:34:51.332  4914  4914 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 08:34:51.332  4914  4914 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 08:34:51.332  4914  4914 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 08:34:51.332  4914  4914 I Adreno-EGL: Local Branch: 
03-16 08:34:51.332  4914  4914 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 08:34:51.332  4914  4914 I Adreno-EGL: Local Patches: NONE
03-16 08:34:51.332  4914  4914 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 08:34:51.359  2538  2557 W DataUsage: invalid counter update blocked: 'err' by 0
03-16 08:34:51.359  2538  2557 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-16 08:34:51.392  4891  4891 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 08:34:51.397  4891  4891 I Babel_Crash: startup - clean
,03-16 08:34:51.417   880  1136 D BluetoothManagerService: Message: 20
,03-16 08:34:51.417   880  1136 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b3a9516:true
,03-16 08:34:51.435  4891  4964 I Babel   : deleted: false for 0
,03-16 08:34:51.506  4891  4910 W art     : Suspending all threads took: 17.203ms
,03-16 08:34:51.561   880  1522 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=4973 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 08:34:51.577  4914  4914 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 08:34:51.594  4914  4914 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 08:34:51.617  4914  4914 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-16 08:34:51.624  4914  4914 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 08:34:51.624  4914  4914 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 08:34:51.656  4891  4891 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 08:34:51.673  4891  4891 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-16 08:34:51.684  4891  4891 W VideoCapabilities: Unsupported mime video/mpeg2
,03-16 08:34:51.712  4914  4995 D OpenGLRenderer: Render dirty regions requested: true
,03-16 08:34:51.724  4914  4914 D Atlas   : Validating map...
,03-16 08:34:51.731  4891  4891 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-16 08:34:51.740  4891  4891 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 08:34:51.741  4891  4891 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 08:34:51.745  4891  4891 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 08:34:51.748  4914  4961 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-16 08:34:51.751  4891  4891 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 08:34:51.758   880  1560 I ActivityManager: Killing 4785:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-16 08:34:51.762   277   277 I SFPerfTracer:      triggers: (rate: 12:477) (compose: 0:1) (post: 0:1) (render: 0:2) (4:904 frames) (5:984)
03-16 08:34:51.762   277   277 D SFPerfTracer:        layers: (3:12) (FocusedStackFrame (0xb76aa578): 0:12)* (DimLayer (0xb7614d38): 0:4)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7617128): 0:37)- (StatusBar (0xb761a650): 0:139) (NavigationBar (0xb7696408): 0:39) (com.android.systemui.ImageWallpaper (0xb7699470): 0:8)* (Starting com.motorola.ccc.ota (0xb76b7120): 0:31)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb76b8e38): 0:53)* (Starting com.test.thalitest (0xb76b7120): 5:28) 
,03-16 08:34:51.798  4914  4995 I OpenGLRenderer: Initialized EGL, version 1.4
,03-16 08:34:51.808  4914  4995 D OpenGLRenderer: Enabling debug mode 0
,03-16 08:34:51.879  1418  1418 I Keyboard.Facilitator: onFinishInput()
,03-16 08:34:51.903   880  1539 W libprocessgroup: failed to open /acct/uid_10060/pid_4785/cgroup.procs: No such file or directory
,03-16 08:34:51.906   880  1137 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,1153
03-16 08:34:51.906   880  1137 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s153ms
,03-16 08:34:51.912  4891  4891 I vclib   : onServiceConnected
,03-16 08:34:51.915  4891  4891 W Babel   : Attempted to change video mute state without an active call.
,03-16 08:34:51.979  4914  5000 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-16 08:34:51.980  4914  5000 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-16 08:34:52.018  4914  4914 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4914
,03-16 08:34:52.076   880  1560 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5005 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-16 08:34:52.150   880  4211 I ActivityManager: Killing 4758:com.google.android.gm/u0a63 (adj 15): empty #7
,03-16 08:34:52.229  4914  4914 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 08:34:52.242   880  1560 W libprocessgroup: failed to open /acct/uid_10063/pid_4758/cgroup.procs: No such file or directory
,03-16 08:34:52.461  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 08:34:52.577   880  1298 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5037 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-16 08:34:52.624  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 08:34:52.624  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 08:34:52.649   880  1577 I ActivityManager: Killing 4671:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 08:34:52.658  4914  4995 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-16 08:34:52.659  4914  4995 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-16 08:34:52.754   880   895 W libprocessgroup: failed to open /acct/uid_10005/pid_4671/cgroup.procs: No such file or directory
,03-16 08:34:52.797  4914  4998 D jxcore_app_log: JniHelper::setJavaVM(0xb7262310), pthread_self() = -1218418104
,03-16 08:34:52.805  4914  4998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 08:34:52.805  4914  4998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 08:34:52.805  4914  4998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 08:34:52.805  4914  4998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 08:34:52.805  4914  4998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-16 08:34:52.805  4914  4998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@349da1c5 added. We now have 1 listener(s)
,03-16 08:34:52.850   880  4211 I ActivityManager: Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5064 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-16 08:34:52.853   880  1241 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-16 08:34:52.874   305   305 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 22.443ms
,03-16 08:34:52.895   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 20.358ms
,03-16 08:34:52.909  4914  4998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
,03-16 08:34:52.914  4914  4998 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,03-16 08:34:52.916  4914  4998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-16 08:34:52.916  4914  4998 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
,03-16 08:34:52.916  4914  4998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-16 08:34:52.919   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 337us total 24.015ms
,03-16 08:34:52.922  4914  4998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 08:34:52.922  4914  4998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 08:34:52.922  4914  4998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 08:34:52.922  4914  4998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-16 08:34:52.922  4914  4998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 08:34:52.922  4914  4998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 08:34:52.922  4914  4998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 08:34:52.922  4914  4998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 08:34:52.922  4914  4998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 08:34:52.922  4914  4998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-16 08:34:52.922  4914  4998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a753428 added. We now have 1 listener(s)
03-16 08:34:52.923  4914  4998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 08:34:52.935   880  1235 D WifiService: New client listening to asynchronous messages
,03-16 08:34:52.938  4914  4998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-16 08:34:52.942  4914  4998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-16 08:34:52.942  4914  4998 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-16 08:34:52.946  4914  4998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-16 08:34:52.947   880  1298 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-16 08:34:52.949  4914  4998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-16 08:34:52.958  4914  4998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 08:34:52.958  4914  4998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 08:34:52.958  4914  4998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-16 08:34:52.958  4914  4998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 08:34:52.958  4914  4998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 08:34:52.958  4914  4998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 08:34:52.958  4914  4998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 08:34:52.958  4914  4998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-16 08:34:52.959  4914  4998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 08:34:52.959  4914  4998 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-16 08:34:52.963  4914  4914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 08:34:52.966  4914  4914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 08:34:52.974  4891  4891 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 08:34:52.974  4891  4891 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 08:34:52.992   277   731 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:264 vsyncs) (2:1036)
,03-16 08:34:53.001  4914  4914 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 08:34:53.093  4891  4891 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 08:34:53.137   880  1475 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5086 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
03-16 08:34:53.138   880  1475 I ActivityManager: Killing 4828:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 08:34:53.149  4914  4928 I art     : Background sticky concurrent mark sweep GC freed 19581(1594KB) AllocSpace objects, 6(92KB) LOS objects, 10% free, 10MB/11MB, paused 9.824ms total 64.605ms
,03-16 08:34:53.171  5064  5085 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-16 08:34:53.230  4891  4891 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 08:34:53.231  4891  4891 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 08:34:53.312   880  1577 W libprocessgroup: failed to open /acct/uid_10008/pid_4828/cgroup.procs: No such file or directory
,03-16 08:34:53.351  5086  5086 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-16 08:34:53.351  5086  5086 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-16 08:34:53.352  5086  5086 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 08:34:53.352  5086  5086 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-16 08:34:53.460  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 08:34:53.504  1569  1569 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@130a33ba new=com.google.android.velvet.VelvetApplication@130a33ba
,03-16 08:34:53.504  5005  5107 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-16 08:34:53.564   880  1577 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5111 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 08:34:53.568  1952  5117 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-16 08:34:53.570  1952  5117 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-16 08:34:53.622  1952  5117 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-16 08:34:53.643  1952  2024 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-16 08:34:53.658  5111  5111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 08:34:53.776  5005  5107 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 271 ms] updated apps [took 271 ms] 
,03-16 08:34:53.782   880  1465 I ActivityManager: Killing 4858:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-16 08:34:53.906   880  1560 W libprocessgroup: failed to open /acct/uid_10035/pid_4858/cgroup.procs: No such file or directory
,03-16 08:34:54.018  1738  2000 I art     : Explicit concurrent mark sweep GC freed 42931(2MB) AllocSpace objects, 34(544KB) LOS objects, 39% free, 13MB/22MB, paused 1.094ms total 108.222ms
,03-16 08:34:54.145   880  1572 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5141 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 08:34:54.299   880  1298 I ActivityManager: Killing 4973:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-16 08:34:54.461  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 08:34:54.462   880  3965 W libprocessgroup: failed to open /acct/uid_10088/pid_4973/cgroup.procs: No such file or directory
,03-16 08:34:54.464   880  1252 D TaskPersister: removeObsoleteFile: deleting file=8_task_thumbnail.png
,03-16 08:34:54.616  4914  5083 W jxcore-log: Initializing JXcore engine
03-16 08:34:54.616  4914  5083 W jxcore-log: JXcore engine is ready
,03-16 08:34:54.622  5141  5141 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 08:34:54.681  5083  5083 W Thread-555: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[9331]" dev="sockfs" ino=9331 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-16 08:34:54.681  5083  5083 W Thread-555: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-16 08:34:54.681  5083  5083 W Thread-555: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[6743]" dev="sockfs" ino=6743 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-16 08:34:54.681  5083  5083 W Thread-555: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[23041]" dev="sockfs" ino=23041 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-16 08:34:54.714  4914  5083 W jxcore-log: Starting JXcore engine
,03-16 08:34:54.794  5141  5141 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-16 08:34:54.814  5141  5141 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 08:34:54.816  5141  5141 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 08:34:54.885  4914  5083 W jxcore-log: Platform android
03-16 08:34:54.885  4914  5083 W jxcore-log: 
03-16 08:34:54.886  4914  5083 W jxcore-log: Process ARCH arm
03-16 08:34:54.886  4914  5083 W jxcore-log: 
,03-16 08:34:54.975   880  1241 I art     : Explicit concurrent mark sweep GC freed 12417(639KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.701ms total 120.510ms
,03-16 08:34:55.004  5141  5184 D Ads     : Skipping gmscore version check
,03-16 08:34:55.006  5141  5141 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-16 08:34:55.006  5141  5141 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-16 08:34:55.019  5141  5141 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-16 08:34:55.064  5141  5141 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-16 08:34:55.067  1952  2024 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-16 08:34:55.081   880  1539 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5186 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-16 08:34:55.112   880  1475 I ActivityManager: Killing 5037:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 08:34:55.150  1952  2024 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,03-16 08:34:55.192  1952  2024 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-16 08:34:55.276   880  1560 W libprocessgroup: failed to open /acct/uid_10019/pid_5037/cgroup.procs: No such file or directory
,03-16 08:34:55.291  5186  5186 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-16 08:34:55.342   880  4211 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5208 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 08:34:55.422   880  1298 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5226 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-16 08:34:55.466   880  1560 I ActivityManager: Killing 5086:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-16 08:34:55.476  5208  5208 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 08:34:55.595  4914  5083 I jxcore-log: JXcore Cordova bridge is ready!
03-16 08:34:55.595  4914  5083 I jxcore-log: 
03-16 08:34:55.595  4914  5083 W jxcore-log: JXcore engine is started
,03-16 08:34:55.602  4914  4998 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-16 08:34:55.604  4914  4914 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-16 08:34:55.613  4914  5083 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-16 08:34:55.613  4914  5083 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-16 08:34:55.619  4914  4914 I chromium: [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,03-16 08:34:55.619  4914  4914 I chromium: [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,03-16 08:34:55.622   880  1539 W libprocessgroup: failed to open /acct/uid_10027/pid_5086/cgroup.procs: No such file or directory
03-16 08:34:55.633  5208  5208 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1dffba62(com.android.providers.calendar.CalendarProvider2@3a7867f3)
,03-16 08:34:55.646  4914  4998 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,03-16 08:34:55.652  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 08:34:55.652  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 08:34:55.657  1477  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 08:34:55.667  1477  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 08:34:55.678  2538  2538 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-16 08:34:55.681  2538  2538 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
03-16 08:34:55.683  2538  2538 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-16 08:34:55.685  2538  2538 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-16 08:34:55.686  2538  2538 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 08:34:55.690  2538  2538 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-16 08:34:55.691  2538  2538 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-16 08:34:55.693  2538  2538 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 08:34:55.739   880  1465 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5255 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 08:34:55.770   880  1298 I ActivityManager: Killing 5005:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-16 08:34:55.806  4914  4914 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-16 08:34:55.807  1418  1418 I Keyboard.Facilitator: onFinishInput()
,03-16 08:34:55.948   880  1221 V AlarmManager: send {1f318e55, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
03-16 08:34:55.948   880  1137 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,7853
03-16 08:34:55.948   880  1137 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,cp,ca,5195 (total)
,03-16 08:34:55.949   880  1241 W libprocessgroup: failed to open /acct/uid_10039/pid_5005/cgroup.procs: No such file or directory
,03-16 08:34:55.966  5255  5255 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-16 08:34:55.967  5255  5255 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,03-16 08:34:55.968  5255  5255 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 08:34:55.968  5255  5255 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-16 08:34:55.988  5251  5251 D AndroidRuntime: 
03-16 08:34:55.988  5251  5251 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-16 08:34:56.002  5251  5251 D AndroidRuntime: CheckJNI is OFF
,03-16 08:34:56.085   880  1522 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5281 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-16 08:34:56.100   880   895 I ActivityManager: Killing 5111:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-16 08:34:56.138   880   896 W libprocessgroup: failed to open /acct/uid_10090/pid_5111/cgroup.procs: No such file or directory
,03-16 08:34:56.256  5251  5251 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-16 08:34:56.280   880  1123 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
,03-16 08:34:56.282   880  1123 I ActivityManager: Killing 4914:com.test.thalitest/u0a109 (adj 1): stop com.test.thalitest
,03-16 08:34:56.328   880  1235 D WifiService: Client connection lost with reason: 4
,03-16 08:34:56.343   880  1560 I WindowState: WIN DEATH: Window{c3696dd u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-16 08:34:56.360   880  1146 W PackageSettings: Skipping PackageSetting{360f48e8 com.example.hello/10568} due to missing metadata
,03-16 08:34:56.395   277   277 I SFPerfTracer:      triggers: (rate: 12:480) (compose: 0:1) (post: 0:1) (render: 0:2) (9:990 frames) (10:1087)
03-16 08:34:56.395   277   277 D SFPerfTracer:        layers: (5:12) (FocusedStackFrame (0xb76aa578): 0:17)* (DimLayer (0xb7614d38): 0:7) (StatusBar (0xb761a650): 0:158) (NavigationBar (0xb7696408): 0:52) (com.android.systemui.ImageWallpaper (0xb7699470): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb76b8e38): 0:54)- (Starting com.test.thalitest (0xb76b7120): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7617f90): 10:84) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7608f38): 7:12) 
,03-16 08:34:56.532   880   896 W ActivityManager: Spurious death for ProcessRecord{2a98995b 4914:com.test.thalitest/u0a109}, curProc for 4914: null
03-16 08:34:56.532   880  1146 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,03-16 08:34:56.675  5208  5208 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 08:34:56.675  5208  5208 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 08:34:56.759  2990  2990 I art     : Explicit concurrent mark sweep GC freed 10764(1655KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 7MB/12MB, paused 868us total 58.167ms
,03-16 08:34:56.822  1418  1418 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-16 08:34:56.833  1738  2023 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-16 08:34:56.839   880  1223 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-16 08:34:56.845   880  1577 I ActivityManager: Killing 4619:com.google.process.gapps/u0a16 (adj 15): empty #7
,03-16 08:34:56.850  1418  5333 I Keyboard.Facilitator.DecoderInitializer: run()
,03-16 08:34:56.855  1569  1569 I art     : Explicit concurrent mark sweep GC freed 2224(119KB) AllocSpace objects, 2(72KB) LOS objects, 25% free, 13MB/17MB, paused 494us total 124.824ms
,03-16 08:34:56.865  1418  5333 I Decoder : createOrResetDecoder
,03-16 08:34:56.894   880   896 W libprocessgroup: failed to open /acct/uid_10016/pid_4619/cgroup.procs: No such file or directory
,03-16 08:34:56.913  1738  1738 I ConfigService: onCreate
,03-16 08:34:56.954   880  1298 I ActivityManager: Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5338 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-16 08:34:56.975   880   880 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-16 08:34:56.975   880   880 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-16 08:34:57.019  1952  1952 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,03-16 08:34:57.036  1418  5333 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-16 08:34:57.082  5338  5338 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,03-16 08:34:57.089  1418  5333 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-16 08:34:57.092   880  1252 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
03-16 08:34:57.093   880  1252 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
03-16 08:34:57.093   880  1252 D TaskPersister: removeObsoleteFile: deleting file=9_task_thumbnail.png
,03-16 08:34:57.105  1418  5333 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-16 08:34:57.105  1418  5333 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
03-16 08:34:57.110  1418  5333 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-16 08:34:57.110  1418  5333 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-16 08:34:57.112  1418  5333 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-16 08:34:57.112  1418  5333 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-16 08:34:57.115  1418  5333 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,03-16 08:34:57.117  1418  5333 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,03-16 08:34:57.119  1418  5333 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-16 08:34:57.119  1418  5333 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-16 08:34:57.119  1418  5333 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,03-16 08:34:57.120  1418  5333 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-16 08:34:57.121   880  1146 I art     : Explicit concurrent mark sweep GC freed 21620(1583KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/32MB, paused 2.148ms total 262.774ms
,03-16 08:34:57.197  5251  5251 D AndroidRuntime: Shutting down VM
,03-16 08:34:57.209  5338  5338 I GoogleHttpClient: GMS http client unavailable, use old client
,03-16 08:34:57.227  1952  1952 D AsyncTaskServiceImpl: Submit a task: k
,03-16 08:34:57.238  5338  5338 I GoogleHttpClient: GMS http client unavailable, use old client
03-16 08:34:57.241  1952  5367 D k       : Processing package: com.test.thalitest
,03-16 08:34:57.243  1952  5367 W k       : Failed to find package com.test.thalitest
,03-16 08:34:57.247  1569  1569 I Launcher: Deferring update until onResume
,03-16 08:34:57.260  1952  5117 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-16 08:34:57.261  1952  1952 E Vision  : Failed to find package com.test.thalitest
,03-16 08:34:57.267   880  4211 I ActivityManager: Killing 5141:com.android.vending/u0a32 (adj 15): empty #7
,03-16 08:34:57.299  5281  5332 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-16 08:34:57.302   880  1539 W libprocessgroup: failed to open /acct/uid_10032/pid_5141/cgroup.procs: No such file or directory
,03-16 08:34:57.351   880  1572 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5376 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,03-16 08:34:57.354  1952  5117 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-16 08:34:57.368  1952  2024 E Icing   : Package com.test.thalitest not found
,03-16 08:34:57.382  1952  5360 W BaseAppContext: Using Auth Proxy for data requests.
03-16 08:34:57.382  1952  5360 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 08:34:57.386  5281  5332 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 85 ms] updated apps [took 85 ms] 
,03-16 08:34:57.395  1952  5360 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 08:34:57.407   880  1465 I ActivityManager: Killing 5186:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 08:34:57.415  1952  5360 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 08:34:57.484   880  1146 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5398 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-16 08:34:57.484   880   896 W libprocessgroup: failed to open /acct/uid_10008/pid_5186/cgroup.procs: No such file or directory
,03-16 08:34:57.506   305   305 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 22.682ms
,03-16 08:34:57.514  1952  5360 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 08:34:57.528   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 21.453ms
,03-16 08:34:57.550   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 21.100ms
,03-16 08:34:57.563   880   896 I ActivityManager: Killing 5064:android.process.acore/u0a7 (adj 15): empty #7
,03-16 08:34:57.749   880  1505 W libprocessgroup: failed to open /acct/uid_10007/pid_5064/cgroup.procs: No such file or directory
,03-16 08:34:57.953  1952  5375 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-16 08:34:57.962  1952  5375 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-16 08:34:57.962  1952  5375 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM2KRjU36UR
03-16 08:34:57.962  1952  5375 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-16 08:34:57.962  1952  5375 I GCore-Chimera-Crash: ==
03-16 08:34:57.962  1952  5375 I GCore-Chimera-Crash: GCore-Chimera-Crash
,--------- beginning of crash
03-16 08:34:57.972  1952  5375 E AndroidRuntime: FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
03-16 08:34:57.972  1952  5375 E AndroidRuntime: Process: com.google.android.gms, PID: 1952
03-16 08:34:57.972  1952  5375 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-16 08:34:57.972  1952  5375 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-16 08:34:57.972  1952  5375 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-16 08:34:57.972  1952  5375 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-16 08:34:57.972  1952  5375 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-16 08:34:57.972  1952  5375 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-16 08:34:57.972  1952  5375 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-16 08:34:57.972  1952  5375 E AndroidRuntime: 	at com.google.android.gms.people.c.e.a(:com.google.android.gms:110)
03-16 08:34:57.972  1952  5375 E AndroidRuntime: 	at com.google.android.gms.people.sync.a.b.d(:com.google.android.gms:3166)
03-16 08:34:57.972  1952  5375 E AndroidRuntime: 	at com.google.android.gms.people.service.bg.b.a(:com.google.android.gms:245)
03-16 08:34:57.972  1952  5375 E AndroidRuntime: 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(:com.google.android.gms:77)
03-16 08:34:57.972  1952  5375 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 08:34:57.972  1952  5375 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 08:34:57.972  1952  5375 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-16 08:34:57.972  1952  5375 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 08:34:58.009   880  5425 E DropBoxManagerService: Can't write: system_app_crash
03-16 08:34:58.009   880  5425 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
03-16 08:34:58.009   880  5425 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-16 08:34:58.009   880  5425 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-16 08:34:58.009   880  5425 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-16 08:34:58.009   880  5425 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-16 08:34:58.009   880  5425 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-16 08:34:58.009   880  5425 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
03-16 08:34:58.009   880  5425 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-16 08:34:58.009   880  5425 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-16 08:34:58.009   880  5425 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-16 08:34:58.009   880  5425 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-16 08:34:58.009   880  5425 E DropBoxManagerService: 	... 5 more
,03-16 08:34:58.055   880  5431 D OpenGLRenderer: Render dirty regions requested: true
,03-16 08:34:58.056   880  1123 D Atlas   : Validating map...
,03-16 08:34:58.116   880  5431 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 08:34:58.116   880  5431 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 08:34:58.116   880  5431 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 08:34:58.116   880  5431 I Adreno-EGL: Local Branch: 
03-16 08:34:58.116   880  5431 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 08:34:58.116   880  5431 I Adreno-EGL: Local Patches: NONE
03-16 08:34:58.116   880  5431 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
03-16 08:34:58.116  1418  5333 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-16 08:34:58.116  1418  5333 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-16 08:34:58.116   880  5431 I OpenGLRenderer: Initialized EGL, version 1.4
,03-16 08:34:58.125   880  5431 D OpenGLRenderer: Enabling debug mode 0
,03-16 08:34:58.164   880  1298 I ActivityManager: Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5435 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-16 08:34:58.479   277   692 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-16 08:34:58.491  2163  2175 E MP-Decision: Error(-22) changing core 2 status to offline
03-16 08:34:58.492  2163  2175 E MP-Decision: Error(-22) changing core 1 status to offline

```
