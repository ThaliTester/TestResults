#### Test 575312438097721_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,D/ChimeraCfgMgr( 5530): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5530): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 5530): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 5530): Submit a task: k
D/ChimeraCfgMgr( 5530): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 5530): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 5530): Processing package: com.test.thalitest
I/PeopleDatabaseHelper( 5530): cleanUpNonGplusAccounts done.
I/Icing   ( 5530): Storage manager: low false usage 1.76MB avail 2.37GB capacity 4.06GB
D/GassUtils( 5530): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5530): Found info for package com.test.thalitest in db.
D/WearableService( 1730): callingUid 10006, callindPid: 1730
E/MDM     ( 1730): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/BaseAppContext( 5530): Using Auth Proxy for data requests.
I/art     ( 5530): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5530): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/BaseAppContext( 5530): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 5530): Using Auth Proxy for data requests.
D/LocationInitializer( 5530): Restart initialization of location
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/BaseAppContext( 5530): Using Auth Proxy for data requests.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
W/BaseAppContext( 5530): Using Auth Proxy for data requests.
W/BaseAppContext( 5530): Using Auth Proxy for data requests.
W/BaseAppContext( 5530): Using Auth Proxy for data requests.
--------- beginning of system
I/ActivityManager(  971): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5610 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/BaseAppContext( 5530): Using Auth Proxy for data requests.
W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
D/AndroidRuntime( 5586): 
D/AndroidRuntime( 5586): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5586): CheckJNI is OFF
W/IcingInternalCorpora( 5530): getNumBytesRead when not calculated.
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/AndroidRuntime( 5586): Calling main entry com.android.commands.am.Am
I/art     (  971): Explicit concurrent mark sweep GC freed 20580(953KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.253ms total 154.896ms
I/ActivityManager(  971): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/Icing   ( 5530): updateResources: need to parse f{com.google.android.gms}
D/ActivityManager(  971): setTaskToReturnTo : TaskRecord{317addc6 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  971): setTaskToReturnTo : TaskRecord{317addc6 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  971): AppWindowTokenEx init.. 
D/ContextHelper(  971): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  971): Focus left window: Window{cd6b9ac u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5586): Shutting down VM
D/SplitWindow(  971): check instance of lgWin Window{17f8e9d9 u0 Starting com.test.thalitest}
I/ActivityManager(  971): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5655 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1937): Closing mic
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
I/MicrophoneInputStream( 1937): mic_close com.google.android.apps.gsa.speech.audio.u@255c5319
V/AudioRecord( 1937): stop()
D/AudioRecord( 1937): AudioRecord->stop()
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
V/AudioFlinger(  280): Record stopped OK
V/AudioPolicyManager(  280): stopInput() input 16
V/AudioPolicyService(  280): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  280): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  280): ThreadBase::setParameters() routing=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
I/WindowStateAnimator(  971): Starting window displayed
,V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3846000
I/SystemUI[Framework](  971): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
W/PhoneWindowManagerEx(  971): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  971): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  971): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  971): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@c9016e5,  pkg=WindowManager.LayoutParams
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/SystemUI[Framework](  971): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1372): draw background and invalidate : color = 15000000
D/BarTransitions( 1372): draw background and invalidate : color = 11111111
V/audio_hw_primary(  280): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  280): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  280): disable_audio_route: exit
E/audio_hw_primary(  280): disable_snd_device: enter 144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  280): stop_input_stream: exit: status(0)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  280): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  280): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  280): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyService(  280): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  280): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  280): setParameters(): io 16, keyvalue hotword_active=0, calling pid 280
V/AudioFlinger(  280): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3846000
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
V/AudioPolicyManager(  280): releaseInput() 16
V/AudioPolicyManager(  280): closeInput(16)
V/AudioFlinger(  280): releasing 15 from 1937 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
V/AudioFlinger(  280): closeInput() 16
V/AudioSystem(  280): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  971): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  280): ThreadBase::exit
V/AudioSystem( 1983): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 3261): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1748): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioSystem( 2650): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  280): RecordThread 0xb3846000 exiting
D/audio_hw_primary(  280): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 16
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  280): releaseInput() exit
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioFlinger(  280): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioFlinger(  280): removeClient_l() pid 1937, calling pid 280
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioSystem( 1937): ioConfigChanged() event 4, ioHandle 16
I/HotwordRecognitionRnr( 1937): Stopping hotword detection.
I/HotwordRecognitionRnr( 1937): Hotword detection finished
I/Gmail   ( 5610): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 5530): Background sticky concurrent mark sweep GC freed 11962(908KB) AllocSpace objects, 8(128KB) LOS objects, 8% free, 13MB/14MB, paused 7.850ms total 37.405ms
D/ContextHelper( 5655): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
W/GAV2    ( 5610): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Icing   ( 5530): Internal init done: storage state 0
I/NotificationManager( 5530): com.google.android.gms: cancel(10436) by com.google.android.gms
I/Icing   ( 5530): Post-init done
I/WebViewFactory( 5655): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/ChimeraCfgMgr( 5530): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5530): Module APK com.google.android.play.games already loaded
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/LibraryLoader( 5655): Time to load native libraries: 4 ms (timestamps 4728-4732)
I/LibraryLoader( 5655): Expected native library version number "",actual native library version number ""
E/Gmail   ( 5610): Error finding the version of the Email provider.....
E/Gmail   ( 5610): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5610): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5610): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5610): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5610): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5610): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5610): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5610): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5610): We do not support migrating this version of the Email provider.
I/Gmail   ( 5610): getAccountsCursor
W/ActivityManager(  971): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/ActivityManager(  971): Killing 5294:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/Gmail   ( 5610): Observing account changes for notifications
V/WebViewChromiumFactoryProvider( 5655): Binding Chromium to main looper Looper (main, tid 1) {2e87bd61}
I/LibraryLoader( 5655): Expected native library version number "",actual native library version number ""
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/chromium( 5655): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/libprocessgroup(  971): failed to open /acct/uid_10011/pid_5294/cgroup.procs: No such file or directory
I/BrowserStartupController( 5655): Initializing chromium process, singleProcess=true
W/art     ( 5655): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5655): ApplicationContext is null in ApplicationStatus
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/chromium( 5655): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
E/libEGL  ( 5655): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5655): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5655): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5655): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5655): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5655): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5655): Remote Branch: 
I/Adreno-EGL( 5655): Local Patches: 
I/Adreno-EGL( 5655): Reconstruct Branch: 
D/InitAlarmsService( 3775): Clearing and rescheduling alarms.
,I/art     ( 5458): Explicit concurrent mark sweep GC freed 7993(401KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 950us total 67.411ms
I/ActivityManager(  971): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5721 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
V/AudioPolicyService(  280): registerClient() client 0xb57e9520, uid 10316
I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 319us total 25.001ms
,D/BluetoothManagerService(  971): Message: 20
D/BluetoothManagerService(  971): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b07345f:true
D/BluetoothAdapterService(581029533)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f7baf5b
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 24.998ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 23.645ms
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  971): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5746 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 5610): notifyAccountChanged
,I/Gmail   ( 5610): getAccountsCursor
,I/Gmail   ( 5610): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/InstanceID/Rpc( 5530): Found 10006
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5610): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/InstanceID/Rpc( 5530): Found 10006
V/DownloadManager( 3213): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@37f5f81f on behalf of 5530
I/Gmail   ( 5610): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5610): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5746): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CalendarProvider2( 5746): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@48e7adc
,W/art     ( 5655): Attempt to remove local handle scope entry from IRT, ignoring
D/CalendarProvider2( 5746): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5746): Created com.android.providers.calendar.CalendarAlarmManager@2e87bd61(com.android.providers.calendar.CalendarProvider2@48e7adc)
,D/CalendarProvider2( 5746): Scheduling check of next Alarm
W/AwContents( 5655): onDetachedFromWindow called when already detached. Ignoring
D/CalendarProvider2( 5746): SCHEDULE_ALARM_REMOVE
D/PhoneMonitor( 5721): Register our PhoneStateListener
,D/SystemWebViewEngine( 5655): CordovaWebView is running on device made by: LGE
,W/art     ( 5655): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5655): Attempt to remove local handle scope entry from IRT, ignoring
,V/DownloadManager( 3213): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@c4e476c on behalf of 5530
I/ActivityManager(  971): Killing 3775:com.android.calendar/u0a13 (adj 15): empty #11
,V/DownloadManager( 3213): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@9f8135 on behalf of 5530
,D/PhoneMonitor( 5721): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5721): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5721): [parse] Load xml
V/TelephonyAutoProfiling( 5721): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 5721): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 5721): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  971): failed to open /acct/uid_10013/pid_3775/cgroup.procs: No such file or directory
,I/Activity( 5655): Activity.onPostResume() called 
D/OpenGLRenderer( 5655): Render dirty regions requested: true
I/OpenGLRenderer( 5655): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5655): Enabling debug mode 0
I/Gmail   ( 5610): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Atlas   ( 5655): Validating map...
,D/SplitWindow(  971): check instance of lgWin Window{1f41bcc5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5655): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  971): Killing 5311:com.android.gallery3d/u0a23 (adj 15): empty #11
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/libprocessgroup(  971): failed to open /acct/uid_10023/pid_5311/cgroup.procs: No such file or directory
I/CheckinService( 5530): Checkin interval check for package: unspecified last checkin: 1454429656290 min interval config: 0 actual interval: 7654
I/CheckinService( 5530): Disabling old GoogleServicesFramework version
,D/InputDispatcher(  971): Focus entered window: Window{1f41bcc5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/CheckinService( 5530): Checking schedule, now: 1454429664025 next: 1454429686041
I/CheckinService( 5530): active receiver: disabled
,W/InputMethodManagerService(  971): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  971): Displayed com.test.thalitest/.MainActivity: +1s534ms
I/Timeline(  971): Timeline: Activity_windows_visible id: ActivityRecord{e06f187 u0 com.test.thalitest/.MainActivity t222} time:85715
I/Timeline( 5655): Timeline: Activity_idle id: android.os.BinderProxy@8aff7a4 time:85742
,W/BindingManager( 5655): Cannot call determinedVisibility() - never saw a connection for the pid: 5655
,I/Icing   ( 5530): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/ActivityManager(  971): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5792 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/Icing   ( 5530): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5530): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 5792): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5746): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5746): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  971): Process com.lge.bnr (pid 5140) has died
,D/JsMessageQueue( 5655): Set native->JS mode to OnlineEventsBridgeMode
,I/Babel_SMS( 5792): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5792): MmsConfig.loadMmsSettings
I/Babel_SMS( 5792): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5792): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5792): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5792): MmsConfig.loadFromResources
E/Babel_SMS( 5792): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5792): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5792): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5792): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5792): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5792): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5792): found sensor: LGE Gravity Sensor, handle=29
,D/SensorManager( 5792): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5792): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5792): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5792): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5792): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5792): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5792): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5792): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5792): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5792): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5792): found sensor: Motion Accel, handle=46
I/art     ( 5792): CheckpointMarkThreadRoots callback created = 0xb042d880
,W/Settings( 5792): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5792): startup - clean
D/jxcore_app_log( 5655): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618700800
I/art     ( 5792): CheckpointMarkThreadRoots callback created = 0xb042d860
,I/chromium( 5655): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Babel   ( 5792): deleted: false for 0
,W/AudioCapabilities( 5792): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5792): Unsupported mime audio/adpcm
W/AudioCapabilities( 5792): Unsupported mime audio/g726
,W/AudioCapabilities( 5792): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5792): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5792): Unsupported mime video/mjpg
W/VideoCapabilities( 5792): Unsupported mime video/theora
,I/art     ( 5655): CheckpointMarkThreadRoots callback created = 0x9b59b500
,W/AudioCapabilities( 5792): Unsupported mime audio/evrc
W/AudioCapabilities( 5792): Unsupported mime audio/qcelp
W/VideoCapabilities( 5792): Unrecognized profile 2130706433 for video/avc
,I/art     ( 5655): CheckpointMarkThreadRoots callback created = 0x9b59b4d0
W/AudioCapabilities( 5792): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5792): Unsupported mime audio/qcelp
W/AudioCapabilities( 5792): Unsupported mime audio/evrc
,W/VideoCapabilities( 5792): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5792): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 5792): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5792): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5792): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5792): Unrecognized profile 2130706433 for video/avc
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/art     (  971): Explicit concurrent mark sweep GC freed 19156(924KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.382ms total 184.903ms
,I/vclib   ( 5792): onServiceConnected
W/Babel   ( 5792): Attempted to change video mute state without an active call.
,W/ResourcesManager( 5792): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5792): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5792): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  971): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5834 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5043): getMode name:com.lge.qremote
,I/AudioManager( 5043): getMode name:com.lge.qremote
W/System  ( 5792): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5792): Installed default security provider GmsCore_OpenSSL
I/AudioManager( 5043): getMode name:com.lge.qremote
,I/ActivityManager(  971): Process com.google.android.apps.docs (pid 5391) has died
,I/AudioManager( 5043): getMode name:com.lge.qremote
,I/AudioManager( 5043): getMode name:com.lge.qremote
,I/NotificationManager( 5792): com.google.android.talk: cancel(10436) by com.google.android.talk
E/MDM     ( 1730): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5530): Restart initialization of location
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,I/AudioManager( 5043): getMode name:com.lge.qremote
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
D/UEI.SmartControl( 5834): Quickset Services start...
,I/AudioManager( 5043): getMode name:com.lge.qremote
I/UEI.SmartControl( 5834): Manufacture = LGE
D/UEI.SmartControl( 5834): File observer start...
E/UEI.SmartControl( 5834): IR Port is disabled: false
D/UEI.SmartControl( 5834): Starting file observer...
D/UEI.SmartControl( 5834): Extracting JNI libs...
D/UEI.SmartControl( 5834): --- this system supports 32-bit or 64-bit only
I/NotificationManager( 5792): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  971): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5861 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 5861): onCreate
W/AppUp4:DB( 5861):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 5861):  setFingerPrint start
I/AppUp4:DB( 5861):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5861):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5861):  SDK version = 0
I/AppUp4:DB( 5861):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5861): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5861): onReceive
I/AppUp4:CustModeStarterReceiver( 5861): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5861): Context : android.app.ReceiverRestrictedContext@3f66956b
D/AppUp4:CustFacade( 5861): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5861): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5861): begin check event
I/AppUp4:CustModeStarterReceiver( 5861): Event For Nothing, skip.
,I/ActivityManager(  971): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5880 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  971): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  971): Handling package changes for user 0
W/ResourcesManager( 5880): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5880): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5880): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5834): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5834): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5834): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ActivityManager(  971): Process com.android.vending (pid 5483) has died
E/lowmemorykiller(  241): Error writing /proc/5422/oom_score_adj; errno=22
,I/UEI.SmartControl( 5834): --- Selecting new region: 2
,I/UEI.SmartControl( 5834): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5834): Platform has CIR...
D/UEI.SmartControl( 5834): NO CIR support, need to check package...
I/UEI.SmartControl( 5834): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5834): QS Service created
I/ActivityManager(  971): Process com.google.android.apps.plus (pid 5422) has died
,I/NotificationService(  971): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  971): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  971): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  971): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
E/UEI.SmartControl( 5834): QS start get config
V/BackupManagerService(  971): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  971): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@b0e54c7
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 5834): Loading JNI Libs...
,D/UEI.SmartControl( 5834):  configuring local db...
I/ActivityManager(  971): Process com.android.contacts (pid 5330) has died
,I/AppConfig( 5880): Total System Memory = 906309632
,I/GalleryUtils( 5880): Application Heap = 96 MB
I/AppConfig( 5880): App Tier : NOT_DEF
D/SystemHelper( 5880): region [EU], country [EU], operator [OPEN], sub-operator []
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
W/ResourcesManager(  971): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  971): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5899 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
W/ResourceType(  971): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/art     ( 5655): Suspending all threads took: 17.072ms
,W/ResourcesManager( 5899): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5899): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5899): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/art     ( 5655): Background sticky concurrent mark sweep GC freed 7101(646KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 18.420ms total 52.053ms
W/ResourcesManager( 5899): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5899): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/jxcore-log( 5655): Initializing JXcore engine
W/jxcore-log( 5655): JXcore engine is ready
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/UEI.SmartControl( 5834):  ---- Has DB8: true
,D/LocationProviderProxy(  971): applying state to connected service
D/UEI.SmartControl( 5834): QS start statue = true Error code = 0
D/UEI.SmartControl( 5834): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 5834): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
I/ActivityManager(  971): Waited long enough for: ServiceRecord{10995552 u0 com.lge.qremote/.QRemoteService}
D/UEI.SmartControl( 5834): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5834): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5834): IrrcClient ++ 
D/irrcClient( 5834): getIrrcService ++ 
D/irrcClient( 5834): getIrrcService -- 
D/irrcClient( 5834): IrrcClient -- 
W/irrc_jni( 5834): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 5834): Services init done
D/UEI.SmartControl( 5834): QS Service init finished
,I/UEI.SmartControl( 5834): Device manager: loading config....
D/UEI.SmartControl( 5834): QS Service version name: 0.1.73
D/UEI.SmartControl( 5834): QS Service version code: 1073
D/UEI.SmartControl( 5834): Service requested: Control
D/UEI.SmartControl( 5834): Config is loaded...
,W/Thread-676( 5829): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6620]" dev="sockfs" ino=6620 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-676( 5829): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-676( 5829): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7396]" dev="sockfs" ino=7396 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-676( 5829): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-676( 5829): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-676( 5829): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[24004]" dev="sockfs" ino=24004 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
D/UEI.SmartControl( 5834): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 5834): Internal service binding...
D/UEI.SmartControl( 5834): -----IControl: 11
D/UEI.SmartControl( 5834): Caller: com.lge.qremote
D/UEI.SmartControl( 5834): ------------ IControl registerCallback...
,I/UEI.SmartControl( 5834): Registering callback...
D/UEI.SmartControl( 5834): -----IControl: 19
D/UEI.SmartControl( 5834): Caller: com.lge.qremote
I/UEI.SmartControl( 5834): Registering Services Ready callback...
I/UEI.SmartControl( 5834): Notify client services are ready...
D/UEI.SmartControl( 5834): -----IControl: 8
D/UEI.SmartControl( 5834): Caller: com.lge.qremote
W/jxcore-log( 5655): Starting JXcore engine
,D/UEI.SmartControl( 5834):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5834): Notify AllClients services are ready: 0
I/SystemConfig( 5899): BUILD Country: EU
I/SystemConfig( 5899): BUILD Operator: OPEN
,I/SystemConfig( 5899): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5899): existFile = false
I/SystemConfig( 5899): canReadFile = false
I/SystemConfig( 5899): systemFeature RCS result false
,D/SystemConfig( 5899): refreshRcsSupport() :false
D/LockScreenSettings( 5356): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5356): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5356): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5356): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5356): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  971): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5922 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  971): Killing 5374:com.lge.eula/1000 (adj 15): empty #11
W/jxcore-log( 5655): Platform android
W/jxcore-log( 5655): 
W/jxcore-log( 5655): Process ARCH arm
W/jxcore-log( 5655): 
,W/libprocessgroup(  971): failed to open /acct/uid_1000/pid_5374/cgroup.procs: No such file or directory
,W/ResourcesManager( 5922): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/AlarmManager(  971): RTC_WAKEUP set : Alarm{28e358ec type 0 when 1454429667797 com.google.android.googlequicksearchbox} when 1454429667797
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  971): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5962 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GAV2    ( 5610): Thread[GAThread,5,main]: No campaign data found.
I/art     ( 5530): Background sticky concurrent mark sweep GC freed 1744(101KB) AllocSpace objects, 0(0B) LOS objects, 1% free, 14MB/14MB, paused 10.551ms total 46.787ms
,I/GAv4-SVC( 5530): Google Analytics 8.4.89 is starting up.
,I/ActivityManager(  971): Killing 5610:com.google.android.gm/u0a53 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 170 ms] updated apps [took 169 ms] 
,I/jxcore-log( 5655): JXcore Cordova bridge is ready!
I/jxcore-log( 5655): 
W/jxcore-log( 5655): JXcore engine is started
,W/libprocessgroup(  971): failed to open /acct/uid_10053/pid_5610/cgroup.procs: No such file or directory
,D/Finsky  ( 5962): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/jxcore-log( 5655): Toggling radios to true
I/jxcore-log( 5655): 
,D/BluetoothAdapter( 5655): enable(): BT is already enabled..!
D/WifiServiceImplEx(  971): setWifiEnabled: true pid=5655, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  971): setWifiEnabled: true pid=5655, uid=10316
D/WifiServiceImplEx(  971): disconnect pid=5655, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  971): reconnect pid=5655, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5655): Radios toggled
I/jxcore-log( 5655): 
I/jxcore-log( 5655): My device name is: LGE-LG-D722
I/jxcore-log( 5655): 
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2769): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2769): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  971): WifiStateMachine: Leaving Connected state
,D/WfdsMonitor( 1800): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,E/WifiConfigStore(  971): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  971): InactiveState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  971): P2pEnabledState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  971): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  275): Clearing all IP addresses on wlan0
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1730): Read error: ssl=0xb044c600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1730): SSL shutdown failed: ssl=0xb044c600: I/O error during system call, Broken pipe
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  971): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  971): ignoring duplicate network state non-change
D/ConnectivityService(  971): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/WifiHS20(  971): hidePasspointNotification off =false
E/WifiStateMachine(  971): Start Disconnecting Watchdog 1
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  971): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20(  971): hidePasspointNotification off =false
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/wpa_supplicant( 2769): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/LGWifiP2pService(  971): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  971): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): ValidatedState{ when=-17ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:28.648 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): DefaultState{ when=-25ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:28.649 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): Forcing reevaluation
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/ActivityManager(  971): Process com.android.providers.calendar (pid 5746) has died
D/Finsky  ( 5962): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5962): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5962): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
V/AlarmManager(  971): ELAPSED_WAKEUP set : Alarm{dcea397 type 2 when 90377 com.android.providers.calendar} when 90377
I/NotificationManager( 5962): com.android.vending: cancel(-1050172287) by com.android.vending
,D/CommandListener(  275): Clearing all IP addresses on wlan0
D/ConnectivityService(  971): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  971): disableDataServiceNotify
,D/WifiHS20(  971): hidePasspointNotification off =false
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:28.757 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/DSQN    (  971): stop dsqn bin
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
,V/DownloadManager( 3213): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@14659ca on behalf of 5962
D/ConnectivityService(  971): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/DhcpStateMachine(  971): StoppedState
D/DhcpStateMachine(  971): StoppedState{ when=-140ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiNetworkAgent(  971): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/WifiHS20(  971): hidePasspointNotification off =false
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:28.792 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  971): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  971): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): Disconnected - quitting
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:28.801 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/CSLegacyTypeTracker(  971): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  971): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/ConnectivityService(  971): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/ActivityManager(  971): Process com.google.android.setupwizard (pid 5721) has died
,D/WifiServerServiceExt(  971): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  971): setSupplicantStateDISCONNECTED
W/QCNEJ   ( 1836): |CORE| No family connected
D/Tethering(  971): MasterInitialState.processMessage what=3
D/ConnectivityService(  971): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  971): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  971): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  971): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  971): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  971): MasterInitialState.processMessage what=3
D/ConnectivityService(  971): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  971): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/WifiServerServiceExt(  971): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  971): setSupplicantStateSCANNING
D/WIFI    (  971): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = -1
D/WIFI    (  971):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/NetworkManagementService(  971): Removing idletimer
D/TelephonyNetworkFactory-1( 1748): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/Settings(  971): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Ads     ( 5962): Skipping gmscore version check
,D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
D/Finsky  ( 5962): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5962): [1] Libraries$2.run: Finished loading 1 libraries.
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/Finsky  ( 5962): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/PackageBroadcastService( 5530): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 5962): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/PackageBroadcastService( 5530): Null package name or gms related package.  Ignoreing.
I/AudioManager( 5043): getMode name:com.lge.qremote
I/Icing   ( 5530): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  971): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6027 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6027): Register our PhoneStateListener
,V/SetupWizard( 6027): Connected to Gservices successfully
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 28716(1744KB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 13MB/22MB, paused 1.496ms total 106.247ms
D/PhoneMonitor( 6027): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6027): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6027): [parse] Load xml
V/TelephonyAutoProfiling( 6027): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6027): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  971): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PhoneMonitor( 6027): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/MDM     ( 1730): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ActivityManager(  971): Process com.android.contacts (pid 5899) has died
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 5530): Restart initialization of location
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  971): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6056 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1730): No location to return for getLastLocation()
,W/FusedLocationProvider( 1730): location=null
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2769): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/LocSvc_java(  971): onReceive
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:29.808 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  971): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  971): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:29.809 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2769): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiServerServiceExt(  971): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  971): setSupplicantStateASSOCIATED
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:29.859 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  971): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  971): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:29.861 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/wpa_supplicant( 2769): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2769): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/WifiServiceExtension(  971): setVHTCapabilityType  : false
,I/WifiServerServiceExt(  971): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  971): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  971): setSecurityType  : 2
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:29.955 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:29.958 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/ConnectivityService(  971): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  971): Got NetworkAgent Messenger
D/ConnectivityService(  971): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  971),: NetworkAgent connected
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
E/WifiConfigStore(  971): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  971): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  275): Setting iface cfg
D/DhcpStateMachine(  971): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  971): WaitBeforeStartState
E/WifiStateMachine(  971): Start Dhcp Watchdog 2
D/WifiServerServiceExt(  971): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  971): setSupplicantStateGROUP_HANDSHAKE
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ConnectivityService(  971): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/Gmail   ( 6056): getAccountsCursor
,E/WifiStateMachine(  971): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  971): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  971): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService(  971): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@31280117 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  971): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@31280117 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  971): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  275): Setting iface cfg
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  971): DHCP Start wake lock is acquired.
D/CommandListener(  275): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  971): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  971): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  971): setSupplicantStateCOMPLETED
D/ConnectivityService(  971): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/LGWifiP2pService(  971): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  971): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  971): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  971): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  971): ignoring duplicate network state non-change
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:30.156 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  971): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:30.163 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
D/ConnectivityService(  971): Adding iface wlan0 to network 101
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20(  971): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:30.173 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
E/WifiStateMachine(  971): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiHS20(  971): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:30.181 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( ,1372): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
E/ConnectivityService(  971): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  971): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  971): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  275): netlink response contains error (File exists)
D/ConnectivityService(  971): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  971): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  971): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  971): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  971): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  971): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  971): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  971): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  971):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  971):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  971):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  971):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): Connected
D/ConnectivityService(  971):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  971): currentScore = 0, newScore = 20
D/ConnectivityService(  971):    accepting network in place of null
D/ConnectivityService(  971): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  971): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  971):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1748): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  971): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{fals,e} } for legacy network type 1
D/CSLegacyTypeTracker(  971): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  971): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  971): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  971): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  971): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  971): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  971): validation of new default Network = false
D/ConnectivityService(  971): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  971): enableDataServiceNotify 
D/DSQN    (  971): start dsqn bin
D/ConnectivityService(  971): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  971): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/DSQN    ( 6085): DSQN samuel.seo ver 141203
E/DSQN    ( 6085): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6085): created command queue thread
I/DSQN    ( 6085): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6085): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/DhcpStateMachine(  971): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  971): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  971): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6088): version 5.5.6 starting
E/dhcpcd  ( 6088): get_duid: Read-only file system
,I/art     (  971): Explicit concurrent mark sweep GC freed 65162(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.802ms total 283.064ms
,W/ActivityManager(  971): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): [LWD] Start DNSResolver start to wait
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/NetworkPolicy(  971): [LG_RESTRICTED] checkMobilePolicy_type()
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): [LWD] wait 500ms before dns check
I/Gmail   ( 6056): Observing account changes for notifications
,I/Icing   ( 5530): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/dhcpcd  ( 6088): wlan0: rebinding lease of 192.168.1.134
,W/GAV2    ( 6056): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6056): Error finding the version of the Email provider.....
E/Gmail   ( 6056): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6056): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6056): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6056): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6056): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6056): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6056): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6056): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 6056): We do not support migrating this version of the Email provider.
I/dhcpcd  ( 6088): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
I/Gmail   ( 6056): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5530): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dhcpcd  ( 6088): wlan0: leased 192.168.1.134 for 86400 seconds
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  971): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6128 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 320us total 24.235ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 22.282ms
,I/Gmail   ( 6056): notifyAccountChanged
I/Gmail   ( 6056): getAccountsCursor
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.664ms
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6056): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6056): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6056): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6056): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/ResourcesManager( 6128): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): [LWD] DNSResolver start dns
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  971): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  971): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  971): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  971): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  971): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  971): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  971): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  971): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  971): RunningState
D/CalendarApplication( 6128): CalendarApplication.onCreate()
I/Gmail   ( 6056): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PreferenceKeysParser( 6128): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6128): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1f6cd2ba, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3f66956b, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3bf668c8, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2e87bd61, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@5856086, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2ad71d47, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@346d4974, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@22a1ce9d, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3646ff12, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@17de46e3, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@19cf88e0, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3651b799, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2011fa5e, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@24a46e3f, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3754530c, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@77d3455, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@24ff5e6a, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3f7baf5b, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@327993f8, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@32a9c0d1, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3dacf736, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1fbbe637, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@8aff7a4, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3d38990d, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@3cc950c2, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@305eaed3, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3bc6ea10, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2762b909, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3f5fb70e, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@85b652f, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1918973c, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@21f4dcc5, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@15e4361a, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@cc3254b, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@775eb28, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@23cb8041, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@31ff99e6, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@189ccb27, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@7d291d4, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1b0edf7d, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@251b6e72, lg_preferences_re,cent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@680f2
D/GeneralPreferenceUtils( 6128): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  971): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): [LWD] DNSResolver end dns
D/Config  ( 6128): [init]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): Checking http://clients3.google.com/generate_204 on "NG700"
I/Config  ( 6128): LGCalendar ver.4.40.17
I/Config  ( 6128): start check model
I/Config  ( 6128): start check native_ca
I/Config  ( 6128): Config Operator=OPEN, Country=EU
D/Config  ( 6128): [setDefaultValuesToPref]
D/Config  ( 6128): [parseProfiles]
D/ProfilesParser( 6128): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6128): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6128): [updateProfiletoCountryInfo]
D/GeneralPreference( 6128): [checkAndMigrateOldPreference]
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/AlertReceiver( 6128): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/DSQN    ( 6085): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6085): restart monitoring
D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6085): dsqn report finish
D/DSQN    (  971): DSQM DsqnNotification wlan0  1
D/DSQN    (  971): start to monitor internet connection
I/InitNotificationRingtoneService( 6128): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6128): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 16:14:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454429671060], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454429671033]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): Validated
D/ConnectivityService(  971): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  971): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  971):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  971):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  971):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  971): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  971): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  971): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  971): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  971): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  971): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  971):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1748): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,D/WifiDataContinuityService(  971): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  971): set CMD_CAPTIVE_CHECK_COMPLETED
I/AlertUtils( 6128): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/ActivityManager(  971): Killing 5792:com.google.android.talk/u0a61 (adj 15): empty #11
I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 6128): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6128): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
W/libprocessgroup(  971): failed to open /acct/uid_10061/pid_5792/cgroup.procs: No such file or directory
,D/ConnectivityService(  971): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
I/AlertUtils( 6128): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6128): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6128): onHandleIntent
,D/HolidayDataLoader( 6128): readJsonAsset : holiday.json
D/AlertService( 6128): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6128): [updateWidgets] 
,D/MonthWidgetProvider( 6128): [onReceive]
D/CalendarWidgetProvider( 6128): [onReceive]
D/CalendarWidgetProvider( 6128): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6128): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6128): [onReceive]
D/CalendarWidgetProvider( 6128): [onReceive]
D/CalendarWidgetProvider( 6128): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 6128): [onCreate] mContext.getPackageName() = com.android.calendar
I/ActivityManager(  971): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6160 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/HolidayIntentService( 6128): onHandleIntent:holiday data empty
,W/ResourcesManager( 6160): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/AlarmManager(  971): RTC_WAKEUP set : Alarm{3807c5e3 type 0 when 1454429671562 com.android.vending} when 1454429671562
D/Finsky  ( 5962): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel_SMS( 6160): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6160): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6160): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6160): MmsConfig.loadFromDatabase
I/NotificationManager(  971): android: cancelAsUser(2) by android
,E/Babel_SMS( 6160): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6160): MmsConfig.loadFromResources
E/Babel_SMS( 6160): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6160): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6160): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6160): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6160): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6160): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6160): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6160): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6160): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6160): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6160): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6160): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6160): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6160): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6160): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6160): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6160): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6160): found sensor: Motion Accel, handle=46
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/ConnectivityService(  971): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  971): identical MTU - not setting
D/Nat464Xlat(  971): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  971): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  971): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  971): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  971): enableDataServiceNotify 
D/DSQN    (  971): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524295
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:31.74 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/DSQN    (  971): dsqn is running restart
,I/DSQN    ( 6187): DSQN samuel.seo ver 141203
E/DSQN    ( 6187): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6187): created command queue thread
I/DSQN    ( 6187): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6187): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,W/Settings( 6160): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 5962): propertyValue:false
D/libc-netbsd( 5962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Babel_Crash( 6160): startup - clean
I/Babel   ( 6160): deleted: false for 0
,I/DSQN    ( 6187): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6187): restart monitoring
I/DSQN    ( 6187): dsqn report finish
D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  971): DSQM DsqnNotification wlan0  1
D/DSQN    (  971): start to monitor internet connection
W/art     ( 6160): Suspending all threads took: 7.640ms
,I/art     ( 6160): CheckpointMarkThreadRoots callback created = 0xb042d910
,I/AppUp4:CustModeStarterReceiver( 5861): onReceive
I/AppUp4:CustModeStarterReceiver( 5861): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5861): Context : android.app.ReceiverRestrictedContext@3f66956b
D/AppUp4:CustFacade( 5861): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5861): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5861): begin check event
I/AppUp4:CustModeStarterReceiver( 5861): Event For Nothing, skip.
I/art     ( 6160): CheckpointMarkThreadRoots callback created = 0xb042d8f0
D/ConnectivityService(  971): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  971): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  971): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
W/AudioCapabilities( 6160): Unsupported mime audio/x-lg-flac
,D/LocSvc_java(  971): onReceive
D/LocSvc_java(  971): got connectivity action
W/AudioCapabilities( 6160): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6160): Unsupported mime audio/g726
D/LocSvc_java(  971): broadcast - no network connections
D/LocSvc_java(  971): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  971): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  971): onReceive
D/GpsLocationProvider(  971): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  971): got connectivity action
D/LocSvc_java(  971): broadcast - no network connections
D/LocSvc_java(  971): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  971): Sending msg: 4 arg1:0 arg2:1
D/GpsLocationProvider(  971): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java(  971): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  971): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  971): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  971): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  971): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  971): ignore wifi update if we are not in OPENING or CLOSING
W/AudioCapabilities( 6160): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6160): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6160): Unsupported mime video/mjpg
W/VideoCapabilities( 6160): Unsupported mime video/theora
,I/ActivityManager(  971): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6193 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/GpsLocationProvider(  971): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,W/AudioCapabilities( 6160): Unsupported mime audio/evrc
W/AudioCapabilities( 6160): Unsupported mime audio/qcelp
W/VideoCapabilities( 6160): Unrecognized profile 2130706433 for video/avc
W/ResourcesManager( 6193): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6193): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6193): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6193): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6193): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/AudioCapabilities( 6160): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6160): Unsupported mime audio/qcelp
W/AudioCapabilities( 6160): Unsupported mime audio/evrc
,D/libc-netbsd( 5962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/VideoCapabilities( 6160): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6160): Unsupported profile 4 for video/mp4v-es
I/SystemConfig( 6193): BUILD Country: EU
I/SystemConfig( 6193): BUILD Operator: OPEN
,W/VideoCapabilities( 6160): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6160): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6160): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6160): Unrecognized profile 2130706433 for video/avc
D/LockScreenSettings( 5356): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5356): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5356): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5356): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5356): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/SystemConfig( 6193): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6193): existFile = false
I/SystemConfig( 6193): canReadFile = false
I/SystemConfig( 6193): systemFeature RCS result false
D/SystemConfig( 6193): refreshRcsSupport() :false
I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 5530): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 5530): Null package name or gms related package.  Ignoreing.
I/AudioManager( 5043): getMode name:com.lge.qremote
,I/Icing   ( 5530): updateResources: need to parse f{com.google.android.gms}
,D/UEI.SmartControl( 5834): Internal timer expired: 1
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 82 ms] updated apps [took 82 ms] 
I/ActivityManager(  971): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6222 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/vclib   ( 6160): onServiceConnected
W/Babel   ( 6160): Attempted to change video mute state without an active call.
,I/NotificationManager( 6160): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6160): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6160): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  971): android: cancelAsUser(2) by android
,V/JNIHelp ( 6160): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 5962): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5962): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5962): untagSocket(41) failed with errno -22
D/Finsky  ( 5962): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
W/System  ( 6160): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6160): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6160): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  971): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6246 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/ResourcesManager( 6222): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6222): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6222): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6222): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6222): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  971): Process com.google.android.gm (pid 6056) has died
,I/NotificationManager(  971): android: cancelAsUser(2) by android
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:33.032 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/IndexDatabaseHelper( 6222): Using schema version: 115
,I/IndexDatabaseHelper( 6222): Index is fine
I/art     (  971): Explicit concurrent mark sweep GC freed 36512(1804KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.502ms total 192.114ms
,W/ResourcesManager( 6246): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6246): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/WifiInternetCheck(  971): Single check msg out of sync, ignoring.
I/ActivityManager(  971): Process com.google.process.gapps (pid 5458) has died
,I/art     ( 5962): WaitForGcToComplete blocked for 6.138ms for cause DisableMovingGc
,D/ConnectivityService(  971): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  971): onReceive
D/LocSvc_java(  971): got connectivity action
D/LocSvc_java(  971): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  971): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  971): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  971): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  971): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  971): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  971): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/MultiDex( 6246): VM with version 2.1.0 has multidex support
,I/MultiDex( 6246): install
I/MultiDex( 6246): VM has multidex support, MultiDex support library is disabled.
I/NotificationManager( 1937): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ActivityManager(  971): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6268 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/GservicesProvider( 6268): Gservices pushing to system: true; secure/global: true
,D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
,I/qtaguid ( 5962): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5962): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5962): untagSocket(41) failed with errno -22
I/ActivityManager(  971): Process com.google.android.setupwizard (pid 6027) has died
I/Icing   ( 5530): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/GoogleHttpClient( 6268): GMS http client unavailable, use old client
,I/ActivityManager(  971): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6287 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/GoogleHttpClient( 6268): GMS http client unavailable, use old client
,I/Icing   ( 5530): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,V/JNIHelp ( 6246): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PCSuite ( 6287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6287): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ActivityThread( 6246): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6246): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@368bf73b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6246): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6246): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6246): com.google.android.gms: cancel(39789) by com.google.android.gms
V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
I/PCSuite ( 6287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6287): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/ChimeraCfgMgr( 6246): Reading stored module config
,I/ActivityManager(  971): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6315 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  971): Process com.android.contacts (pid 6193) has died
,D/ChimeraCfgMgr( 6246): Loading module com.google.android.gms.car from APK com.google.android.gms
W/ResourcesManager( 6315): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     ( 5962): CheckpointMarkThreadRoots callback created = 0xb042d870
,I/art     ( 5962): CheckpointMarkThreadRoots callback created = 0xaaffa820
,D/CalendarProvider2( 6315): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@48e7adc
D/NativeLibraryUtils( 6246): Install completed successfully. count=14 extracted=0
,D/CalendarProvider2( 6315): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6315): Created com.android.providers.calendar.CalendarAlarmManager@2e87bd61(com.android.providers.calendar.CalendarProvider2@48e7adc)
D/CalendarProviderBroadcastReceiver( 6315): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 6315): [IntentService] WakeLock acquire, start IntentSerivce
D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 95822322051; DSPS: 3239798; Offset : -3053347589
V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/CalendarProvider2( 6315): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6315): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
,I/PCSuite ( 6287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6287): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/CalendarProvider2( 6315): [getOrCreateCalendarAlarmManager]
V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
I/PCSuite ( 6287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6287): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
I/AudioManager( 5043): getMode name:com.lge.qremote
,D/CAR.SERVICE( 6246): Connecting to CarCallService...
I/AudioManager( 5043): getMode name:com.lge.qremote
,V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6222): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/art     ( 6246): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6246): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/CalendarProvider2( 6315): [IntentService] Release Lock
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/CalendarProvider2( 6315): CalendarProviderIntentService.onDestroy()
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/CAR.SERVICE( 6246): com.google.android.projection.gearhead isn't installed.
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out(  971): propertyValue:false
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  971): propertyValue:false
I/ActivityManager(  971): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6343 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/WifiInternetCheck(  971): isHttpConnectionAvailable - We got a valid response : 204
,D/CAR.TEL.Service( 6246): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6246): Creating a new PhoneAdapter instance
W/ActivityManager(  971): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6246): setListener: com.google.android.gms.car.dn@17520346
W/ActivityManager(  971): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6246): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6246): Starting CarCallService with initial phone null
V/AlarmManager(  971): ELAPSED_WAKEUP set : Alarm{344b9d85 type 2 when 96174 com.google.android.gms} when 96174
,I/NotificationManager( 6246): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ActivityManager(  971): Killing 5861:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/CAR.SERVICE( 6246): Package validated; name: com.android.vending
,W/libprocessgroup(  971): failed to open /acct/uid_10011/pid_5861/cgroup.procs: No such file or directory
,I/NotificationManager( 5962): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5962): [1] GearheadStateMonitor.access$100: mIsProjecting:false
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6343): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6343): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  971): Process com.android.gallery3d (pid 5880) has died
,W/ActivityManager(  971): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6343): Observing account changes for notifications
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Gmail   ( 6343): Error finding the version of the Email provider.....
E/Gmail   ( 6343): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6343): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6343): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6343): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6343): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6343): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6343): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6343): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6343): We do not support migrating this version of the Email provider.
V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/NotificationManager(  971): android: cancelAsUser(2) by android
D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
I/Gmail   ( 6343): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
I/PCSuite ( 6287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6222): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6222): MCCMNC not supported: null
I/PCSuite ( 6287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,E/lowmemorykiller(  241): Error writing /proc/5922/oom_score_adj; errno=22
,I/ActivityManager(  971): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6386 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/lowmemorykiller(  241): Error writing /proc/5922/oom_score_adj; errno=22
I/qtaguid ( 5962): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5962): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5962): untagSocket(41) failed with errno -22
,I/Gmail   ( 6343): notifyAccountChanged
,I/Gmail   ( 6343): getAccountsCursor
I/Gmail   ( 6343): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6343): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6343): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6343): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  971): Process com.google.android.apps.plus (pid 5922) has died
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5962): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5962): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Gmail   ( 6343): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5962): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/MusicStore( 6386): Database version: 120
,D/Finsky  ( 5962): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  971): RTC_WAKEUP set : Alarm{1015f792 type 0 when 1454429675748 com.android.vending} when 1454429675748
,D/DeviceConnectionService( 1730): client connected with version: 8296000
,D/WearableService( 1730): callingUid 10006, callindPid: 1730
D/Finsky  ( 5962): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5962): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6386): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  971): Process com.google.android.gms (pid 5530) has died
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6386): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6386): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6386): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6386): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6386): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6386): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6386): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@141e8f82: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6386): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6386): GMSCore installation verified
I/ConfigStore( 6386): Config Database version: 1
,D/AlertService( 6128): Beginning updateAlertNotification
,D/AlertService( 6128): No fired or scheduled alerts
,I/NotificationManager( 6128): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(14) by com.android.calendar
,I/NotificationManager( 6128): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6128): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6128): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 6128): No events found starting within 1 week.
,I/MediaRouter( 6386): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6386): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6386): type=WIFI subType= reason=null isConnected=true
,I/art     (  971): Explicit concurrent mark sweep GC freed 25047(1219KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.481ms total 148.154ms
,I/ActivityManager(  971): Killing 6128:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10013/pid_6128/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6386): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  971): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6421 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a,
,I/GHttpClientFactory( 6386): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/ActivityManager(  971): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=6439 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GoogleURLConnFactory( 6386): Using platform SSLCertificateSocketFactory
I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 23.991ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.496ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.872ms
,I/ActivityManager(  971): Killing 5356:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/ResourcesManager( 6439): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6439): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6421): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6421): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6421): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/MultiDex( 6439): VM with version 2.1.0 has multidex support
I/MultiDex( 6439): install
I/MultiDex( 6439): VM has multidex support, MultiDex support library is disabled.
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
W/libprocessgroup(  971): failed to open /acct/uid_10069/pid_5356/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/LGEmail ( 6421): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6421): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,V/JNIHelp ( 6439): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6439): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6439): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19d52559: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6439): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  971): Process com.android.settings (pid 6222) has died
,I/NotificationManager( 6439): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6439): com.google.android.gms: cancel(39789) by com.google.android.gms
I/NotificationManager( 6386): com.google.android.music: cancel(1061) by com.google.android.music
,D/NativeLibraryUtils( 6439): Install completed successfully. count=14 extracted=0
,D/eas_req ( 6421): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  971): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6474 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  971): Killing 6315:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/HubEmail( 6421): JNI_OnLoad()
I/HubEmail( 6421): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6421): registerNatives()
I/HubEmail( 6421): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6421): registerNativeMethods()
I/HubEmail( 6421): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6421): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/libprocessgroup(  971): failed to open /acct/uid_10014/pid_6315/cgroup.procs: No such file or directory
,W/Settings( 6421): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  971): Killing 6160:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10061/pid_6160/cgroup.procs: No such file or directory
,D/LGDMClient( 6474): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6474): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6474): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6474): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6474): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6474): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6474): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6474): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  971): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6501 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6474): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6474): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6474): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6474): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6474): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6474): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  971): Killing 6287:com.lge.sync/1000 (adj 15): empty #11
,I/jxcore-log( 5655): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5655): 
,W/libprocessgroup(  971): failed to open /acct/uid_1000/pid_6287/cgroup.procs: No such file or directory
V/AlarmManager(  971): RTC_WAKEUP set : Alarm{1ade2877 type 0 when 1454429678267 com.google.android.googlequicksearchbox} when 1454429678267
I/AppUp4:AppBoxCP( 6501): onCreate
,W/AppUp4:DB( 6501):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6501):  setFingerPrint start
,I/AppUp4:DB( 6501):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6501):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6501):  SDK version = 0
I/AppUp4:DB( 6501):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6501): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6501): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6501): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6501): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6501): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6501): onReceive
I/AppUp4:CustModeStarterReceiver( 6501): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6501): Context : android.app.ReceiverRestrictedContext@5856086
D/AppUp4:CustFacade( 6501): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6501): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6501): begin check event
I/AppUp4:CustModeStarterReceiver( 6501): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6501): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6501): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6501): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6501): handleAsyncCustNotification do not startCustService
I/ActivityManager(  971): Killing 5834:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5043): android.os.DeadObjectException
,W/System.err( 5043): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5043): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5043): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5043): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5043): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5043): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5043): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5043): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5043): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5043): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5043): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5043): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5043): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5043): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5043): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5043): android.os.DeadObjectException
W/System.err( 5043): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5043): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5043): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5043): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5043): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5043): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5043): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5043): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5043): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5043): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5043): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5043): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5043): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5043): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5043): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  971): failed to open /acct/uid_10089/pid_5834/cgroup.procs: No such file or directory
W/ActivityManager(  971): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/LgeMiscReceiver( 3261): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3261): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3261): networkInfo.isConnected() = false
,I/ActivityManager(  971): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6527 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  971): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6537 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/UEI.SmartControl( 6527): Quickset Services start...
,I/UEI.SmartControl( 6527): Manufacture = LGE
D/UEI.SmartControl( 6527): File observer start...
E/UEI.SmartControl( 6527): IR Port is disabled: false
D/UEI.SmartControl( 6527): Starting file observer...
D/UEI.SmartControl( 6527): Extracting JNI libs...
D/UEI.SmartControl( 6527): --- this system supports 32-bit or 64-bit only
,D/PhoneMonitor( 6537): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6537): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6537): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  971): Killing 6343:com.google.android.gm/u0a53 (adj 15): empty #11
D/UEI.SmartControl( 6527): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6527): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6527): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6527): --- Selecting new region: 2
I/UEI.SmartControl( 6527): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6527): Platform has CIR...
D/UEI.SmartControl( 6527): NO CIR support, need to check package...
I/UEI.SmartControl( 6527): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6527): QS Service created
W/libprocessgroup(  971): failed to open /acct/uid_10053/pid_6343/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-68 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:39.078 DNS addrs= 192.168.1.1, 0.0.0.0, 
,V/DownloadManager( 3213): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/PhoneMonitor( 6537): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6537): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6537): [parse] Load xml
V/TelephonyAutoProfiling( 6537): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6537): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3213): DownloadService onCreate
E/UEI.SmartControl( 6527): QS start get config
,I/ActivityManager(  971): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6578 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/NotificationManager( 3213): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3213): in removeSpuriousFiles
V/DownloadManager( 3213): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@368bf73b on behalf of 3213
D/PhoneMonitor( 6537): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/UEI.SmartControl( 6527): Loading JNI Libs...
D/UEI.SmartControl( 6527):  configuring local db...
,I/DownloadManager( 3213): in trimDatabase
,V/DownloadManager( 3213): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3213): DownloadService onStartCommand
V/DownloadManager( 3213): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@39584896 on behalf of 3213
I/CheckinService( 6439): Checkin interval check for package: unspecified last checkin: 1454429656290 min interval config: 0 actual interval: 22952
V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@ab8cc17 on behalf of 3213
I/CheckinService( 6439): Disabling old GoogleServicesFramework version
,D/WeatherAncestor( 2626): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:14:39
,D/UpdateThreadPoolManager( 2626): 2 : This is isUpdating : false
D/WeatherAncestor( 2626): connectivity changed - connection : true
D/Weather_cast( 2626): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2626): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:14:39
D/WeatherService( 2626): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  971): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6600 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  971): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2626): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3213): DownloadService onDestroy
,D/WeatherService( 2626): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2626): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/CheckinService( 6439): Checking schedule, now: 1454429679495 next: 1454429686041
I/CheckinService( 6439): active receiver: disabled
,W/ResourcesManager( 6600): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/jxcore-log( 5655): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5655): 
,D/UEI.SmartControl( 6527):  ---- Has DB8: true
,D/UEI.SmartControl( 6527): QS start statue = true Error code = 0
D/UEI.SmartControl( 6527): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6527): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6527): IRRCDataComm has AudioManager!!!!.
I/ActivityManager(  971): Killing 5043:com.lge.qremote/u0a106 (adj 15): empty #11
W/irrc_jni( 6527): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6527): IrrcClient ++ 
D/irrcClient( 6527): getIrrcService ++ 
D/irrcClient( 6527): getIrrcService -- 
D/irrcClient( 6527): IrrcClient -- 
W/irrc_jni( 6527): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6527): Services init done
I/UEI.SmartControl( 6527): Device manager: loading config....
D/UEI.SmartControl( 6527): Config is loaded...
,D/UEI.SmartControl( 6527):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6527): Notify AllClients services are ready: 0
,I/jxcore-log( 5655): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5655): 
,W/libprocessgroup(  971): failed to open /acct/uid_10106/pid_5043/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6527): QS Service init finished
I/jxcore-log( 5655): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 5655): 
D/UEI.SmartControl( 6527): QS Service version name: 0.1.73
D/UEI.SmartControl( 6527): QS Service version code: 1073
D/UEI.SmartControl( 6527): Service requested: Control
D/UEI.SmartControl( 6527): Service.onUnbind: IControl
D/UEI.SmartControl( 6527): Service.onDestroy
D/UEI.SmartControl( 6527): Shutdown IRRCPlayer... 
I/jxcore-log( 5655): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5655): 
,W/irrc_jni( 6527): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6527): ~IrrcClient ++ 
D/irrcClient( 6527): ~IrrcClient -- 
W/irrc_jni( 6527): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6527): Blaster closed
D/UEI.SmartControl( 6527): Blaster closed
D/UEI.SmartControl( 6527): Shut down QS...
D/UEI.SmartControl( 6527): Stopped file observer...
I/UEI.SmartControl( 6527): QS lib stop result = true
,D/UEI.SmartControl( 6527): QS shutdown complete
D/UEI.SmartControl( 6527): QS Service created
E/UEI.SmartControl( 6527): QS start get config
D/UEI.SmartControl( 6527):  configuring local db...
,D/CAR.SERVICE( 6246): mConnectedToCar = false, abort
,E/ActivityThread( 6246): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@c37d46e that was originally bound here
E/ActivityThread( 6246): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@c37d46e that was originally bound here
E/ActivityThread( 6246): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6246): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6246): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6246): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6246): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6246): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6246): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6246): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6246): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6246): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6246): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6246): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6246): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6246): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6246): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6246): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6246): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6246): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6246): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6246): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6246): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6246): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6246): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 6246): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2a6a3321 that was originally bound here
E/ActivityThread( 6246): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2a6a3321 that was originally bound here
E/ActivityThread( 6246): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6246): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6246): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6246): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6246): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6246): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6246): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6246): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6246): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6246): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6246): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6246): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6246): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6246): 	at android.app.ActivityThread.access,$1900(ActivityThread.java:155)
E/ActivityThread( 6246): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6246): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6246): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6246): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6246): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6246): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6246): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6246): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  971): Unbind failed: could not find connection for android.os.BinderProxy@2511b6b9
,I/Babel_SMS( 6600): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6600): MmsConfig.loadMmsSettings
I/Babel_SMS( 6600): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6600): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6600): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6600): MmsConfig.loadFromResources
E/Babel_SMS( 6600): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6600): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/UEI.SmartControl( 6527):  ---- Has DB8: true
,D/UEI.SmartControl( 6527): QS start statue = true Error code = 0
D/UEI.SmartControl( 6527): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6527): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6527): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6527): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6527): IrrcClient ++ 
D/irrcClient( 6527): getIrrcService ++ 
D/SensorManager( 6600): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6600): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6600): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6600): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6600): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6600): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6600): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6600): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6600): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6600): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6600): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6600): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6600): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6600): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6600): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6600): found sensor: Motion Accel, handle=46
D/irrcClient( 6527): getIrrcService -- 
D/irrcClient( 6527): IrrcClient -- 
W/irrc_jni( 6527): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6527): Services init done
D/UEI.SmartControl( 6527): QS Service init finished
D/UEI.SmartControl( 6527): QS Service version name: 0.1.73
D/UEI.SmartControl( 6527): QS Service version code: 1073
D/UEI.SmartControl( 6527): Service requested: Control
E/ActivityThread( 6527): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@22a1ce9d that was originally bound here
E/ActivityThread( 6527): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@22a1ce9d that was originally bound here
E/ActivityThread( 6527): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6527): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6527): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6527): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6527): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6527): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6527): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6527): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6527): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6527): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6527): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6527): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6527): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6527): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6527): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6527): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6527): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6527): Internal service binding...
,I/UEI.SmartControl( 6527): Device manager: loading config....
D/UEI.SmartControl( 6527): Config is loaded...
I/art     ( 6600): CheckpointMarkThreadRoots callback created = 0xb042d580
,W/Settings( 6600): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6600): startup - clean
D/UEI.SmartControl( 6527):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6527): Notify AllClients services are ready: 0
I/art     ( 6600): CheckpointMarkThreadRoots callback created = 0xb042d560
,I/Babel   ( 6600): deleted: false for 0
,I/ActivityManager(  971): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6634 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  971): Killing 6246:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  971): failed to open /acct/uid_10006/pid_6246/cgroup.procs: No such file or directory
,W/AudioCapabilities( 6600): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6600): Unsupported mime audio/adpcm
W/AudioCapabilities( 6600): Unsupported mime audio/g726
W/AudioCapabilities( 6600): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6600): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6600): Unsupported mime video/mjpg
W/VideoCapabilities( 6600): Unsupported mime video/theora
,W/AudioCapabilities( 6600): Unsupported mime audio/evrc
,W/AudioCapabilities( 6600): Unsupported mime audio/qcelp
W/VideoCapabilities( 6600): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6600): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6600): Unsupported mime audio/qcelp
W/AudioCapabilities( 6600): Unsupported mime audio/evrc
,W/VideoCapabilities( 6600): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6600): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6600): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6600): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6600): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6600): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6600): onServiceConnected
W/Babel   ( 6600): Attempted to change video mute state without an active call.
,I/NotificationManager( 6600): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6600): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6600): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6600): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6600): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 6600): propertyValue:false
I/Babel   ( 6600): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  971): Killing 5962:com.android.vending/u0a36 (adj 15): empty #11
D/charger_monitor(  486): init target 500000
,W/libprocessgroup(  971): failed to open /acct/uid_10036/pid_5962/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
,D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6634): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6634): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6634): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6634):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6634):   adb logcat -s GAv4
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6634): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6634): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6634): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6634): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6634): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6634): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6634): Time to load native libraries: 3 ms (timestamps 2793-2796)
I/LibraryLoader( 6634): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6634): Binding Chromium to main looper Looper (main, tid 1) {3de5252b}
I/LibraryLoader( 6634): Expected native library version number "",actual native library version number ""
,I/chromium( 6634): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6634): Initializing chromium process, singleProcess=true
,W/art     ( 6634): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6634): ApplicationContext is null in ApplicationStatus
W/chromium( 6634): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6634): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6634): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6634): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6634): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6634): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6634): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6634): Remote Branch: 
I/Adreno-EGL( 6634): Local Patches: 
I/Adreno-EGL( 6634): Reconstruct Branch: 
,V/AudioPolicyService(  280): registerClient() client 0xb40dec40, uid 10079
,W/AudioManagerAndroid( 6634): Requires BLUETOOTH permission
I/NSApplication( 6634): Starting up...
,I/ActivityManager(  971): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6697 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  971): Killing 6386:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10081/pid_6386/cgroup.procs: No such file or directory
,I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  270): wakelock acquired: 1, error no: 42
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  270): 
I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,I/ActivityManager(  971): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6716 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  971): Killing 6421:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10021/pid_6421/cgroup.procs: No such file or directory
,W/ResourcesManager( 6716): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:42.089 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/iu.SyncManager( 6439): SYNC; picasa accounts
,D/NetworkLogImpl( 6439): Loaded NetworkSpeedPredictor
I/iu.Environment( 6439): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  971): Killing 6474:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/iu.UploadsManager( 6439): num queued entries: 0
,I/iu.UploadsManager( 6439): num updated entries: 0
I/iu.SyncManager( 6439): NEXT; no task
W/libprocessgroup(  971): failed to open /acct/uid_1000/pid_6474/cgroup.procs: No such file or directory
,I/ActivityManager(  971): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6746 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  971): Explicit concurrent mark sweep GC freed 21551(1086KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.852ms total 140.332ms
,I/MusicStore( 6746): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6746): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6746): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6746): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6746): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6746): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6746): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6746): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6746): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@141e8f82: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6746): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6746): GMSCore installation verified
I/ConfigStore( 6746): Config Database version: 1
,I/MediaRouter( 6746): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6746): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
E/UEI.SmartControl( 6527): file observer is disposed!
I/NetworkMonitor( 6746): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6746): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  971): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6783 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 24.424ms
,I/GHttpClientFactory( 6746): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6746): Using platform SSLCertificateSocketFactory
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 22.057ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.288ms
I/ActivityManager(  971): Killing 6501:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6783): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6783): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6783): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  971): failed to open /acct/uid_10011/pid_6501/cgroup.procs: No such file or directory
,I/NotificationManager( 6746): com.google.android.music: cancel(1061) by com.google.android.music
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/LGEmail ( 6783): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6783): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6783): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  971): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6815 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6783): JNI_OnLoad()
I/HubEmail( 6783): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6783): registerNatives()
I/HubEmail( 6783): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6783): registerNativeMethods()
I/HubEmail( 6783): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6783): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  971): Killing 6537:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10038/pid_6537/cgroup.procs: No such file or directory
,W/Settings( 6783): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6815): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6815): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6815): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6815): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6815): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6815): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6815): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6815): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  971): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6839 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6815): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6815): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6815): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6815): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6815): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6815): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  971): Killing 6578:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/UEI.SmartControl( 6527): Internal timer expired: 2
,W/libprocessgroup(  971): failed to open /acct/uid_10051/pid_6578/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6527): Service.onUnbind: IControl
D/UEI.SmartControl( 6527): Service.onDestroy
D/UEI.SmartControl( 6527): Shutdown IRRCPlayer... 
W/irrc_jni( 6527): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6527): ~IrrcClient ++ 
D/irrcClient( 6527): ~IrrcClient -- 
W/irrc_jni( 6527): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6527): Blaster closed
D/UEI.SmartControl( 6527): Blaster closed
D/UEI.SmartControl( 6527): Shut down QS...
I/UEI.SmartControl( 6527): QS lib stop result = true
D/UEI.SmartControl( 6527): QS shutdown complete
I/AppUp4:AppBoxCP( 6839): onCreate
,W/AppUp4:DB( 6839):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6839):  setFingerPrint start
I/AppUp4:DB( 6839):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6839):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6839):  SDK version = 0
I/AppUp4:DB( 6839):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6839): AppBoxApplication onCreate()
I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-67 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:45.106 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/NetworkStateForAutoUpdateMonitor( 6839): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6839): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/NetworkStateForAutoUpdateMonitor( 6839): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6839): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6839): onReceive
I/AppUp4:CustModeStarterReceiver( 6839): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6839): Context : android.app.ReceiverRestrictedContext@5856086
D/AppUp4:CustFacade( 6839): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6839): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6839): begin check event
I/AppUp4:CustModeStarterReceiver( 6839): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6839): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6839): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6839): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6839): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  971): Killing 6527:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  971): failed to open /acct/uid_10089/pid_6527/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3261): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3261): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3261): networkInfo.isConnected() = false
I/ActivityManager(  971): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6858 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6858): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6858): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6858): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  971): Killing 6600:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10061/pid_6600/cgroup.procs: No such file or directory
V/DownloadManager( 3213): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3213): DownloadService onCreate
I/DownloadManager( 3213): in removeSpuriousFiles
V/DownloadManager( 3213): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/NotificationManager( 3213): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@38fba1ed on behalf of 3213
I/DownloadManager( 3213): in trimDatabase
V/DownloadManager( 3213): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@18c85822 on behalf of 3213
D/PhoneMonitor( 6858): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6858): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6858): [parse] Load xml
V/TelephonyAutoProfiling( 6858): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 6858): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/ActivityManager(  971): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6881 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3213): DownloadService onStartCommand
V/DownloadManager( 3213): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@15fd6fe9 on behalf of 3213
D/PhoneMonitor( 6858): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 6439): Checkin interval check for package: unspecified last checkin: 1454429656290 min interval config: 0 actual interval: 29401
I/CheckinService( 6439): Checking schedule, now: 1454429685703 next: 1454429686041
I/CheckinService( 6439): active receiver: disabled
,V/DownloadManager( 3213): DownloadService onDestroy
,I/ActivityManager(  971): Killing 6634:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,E/libprocessgroup(  971): failed to kill 1 processes for processgroup 6634
,D/WeatherAncestor( 2626): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:14:45
,D/UpdateThreadPoolManager( 2626): 2 : This is isUpdating : false
D/WeatherAncestor( 2626): connectivity changed - connection : true
D/Weather_cast( 2626): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2626): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:14:46
D/WeatherService( 2626): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  971): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6902 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  971): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2626): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2626): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2626): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ResourcesManager( 6902): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6902): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6902): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6902): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6902): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6902): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6902): MmsConfig.loadFromResources
E/Babel_SMS( 6902): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6902): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6902): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6902): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6902): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6902): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6902): found sensor: LGE Gravity Sensor, handle=29
,D/SensorManager( 6902): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6902): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6902): found sensor: LGE Step Detector Sensor, handle=43
,D/SensorManager( 6902): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6902): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6902): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6902): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6902): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6902): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6902): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6902): found sensor: Motion Accel, handle=46
W/Settings( 6902): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6902): startup - clean
,I/Babel   ( 6902): deleted: false for 0
I/art     ( 6902): CheckpointMarkThreadRoots callback created = 0xaaf24640
,I/art     ( 6902): CheckpointMarkThreadRoots callback created = 0xaaf24610
,I/ActivityManager(  971): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6938 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6902): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6902): Unsupported mime audio/adpcm
W/AudioCapabilities( 6902): Unsupported mime audio/g726
W/AudioCapabilities( 6902): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6902): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6902): Unsupported mime video/mjpg
W/VideoCapabilities( 6902): Unsupported mime video/theora
,W/AudioCapabilities( 6902): Unsupported mime audio/evrc
,W/AudioCapabilities( 6902): Unsupported mime audio/qcelp
W/VideoCapabilities( 6902): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6902): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6902): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6902): Unsupported mime audio/evrc
W/VideoCapabilities( 6902): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6902): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6902): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6902): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6902): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6902): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6902): onServiceConnected
W/Babel   ( 6902): Attempted to change video mute state without an active call.
,D/libc-netbsd( 6902): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6902): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6902): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6902): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 6902): propertyValue:false
I/NotificationManager( 6902): com.google.android.talk: cancel(10436) by com.google.android.talk
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6938): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6938): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6938): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6938):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6938):   adb logcat -s GAv4
I/Babel   ( 6902): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  971): Killing 6697:com.android.chrome/u0a48 (adj 15): empty #11
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6938): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6938): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/libprocessgroup(  971): failed to open /acct/uid_10048/pid_6697/cgroup.procs: No such file or directory
,W/GAv4    ( 6938): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6938): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6938): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6938): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6938): Time to load native libraries: 3 ms (timestamps 9192-9195)
I/LibraryLoader( 6938): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6938): Binding Chromium to main looper Looper (main, tid 1) {3de5252b}
I/LibraryLoader( 6938): Expected native library version number "",actual native library version number ""
I/chromium( 6938): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6938): Initializing chromium process, singleProcess=true
W/art     ( 6938): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6938): ApplicationContext is null in ApplicationStatus
W/chromium( 6938): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6938): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6938): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6938): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6938): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6938): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6938): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6938): Remote Branch: 
I/Adreno-EGL( 6938): Local Patches: 
I/Adreno-EGL( 6938): Reconstruct Branch: 
V/AudioPolicyService(  280): registerClient() client 0xb57e9640, uid 10079
,W/AudioManagerAndroid( 6938): Requires BLUETOOTH permission
I/NSApplication( 6938): Starting up...
,I/ActivityManager(  971): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6999 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  971): Killing 6716:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10086/pid_6716/cgroup.procs: No such file or directory
,I/ActivityManager(  971): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7021 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  971): Killing 6746:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10081/pid_6746/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-63 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 17:14:48.194 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/ResourcesManager( 7021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  971): Killing 6783:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10021/pid_6783/cgroup.procs: No such file or directory
,I/ActivityManager(  971): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7053 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7053): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  971): Message: 20
D/BluetoothManagerService(  971): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@89a79c1:true
,D/BluetoothAdapterService(581029533)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f7baf5b
D/BluetoothAdapterService(581029533)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f7baf5b
,I/art     (  971): Explicit concurrent mark sweep GC freed 19246(929KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.585ms total 146.278ms
,I/AudioManager( 7053): getMode name:com.lge.qremote
I/AudioManager( 7053): getMode name:com.lge.qremote
,I/ActivityManager(  971): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7074 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/jxcore-log( 5655): Test app app.js loaded
I/jxcore-log( 5655): 
,I/MusicStore( 7074): Database version: 120
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5655): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5655): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5655): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5655): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5655): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5655): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5655): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5655): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5655): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5655): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e4e6e0 added. We now have 1 listener(s)
D/BluetoothAdapterService(581029533)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3f7baf5b
,I/jxcore-log( 5655): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5655): 
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7074): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/chromium( 5655): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7074): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7074): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7074): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7074): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7074): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7074): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7074): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@141e8f82: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7074): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7074): GMSCore installation verified
I/ConfigStore( 7074): Config Database version: 1
,V/AlarmManager(  971): RTC_WAKEUP set : Alarm{3c2f54bb type 0 when 1454429686041 com.google.android.gms} when 1454429686041
,I/ActivityManager(  971): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7103 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  971): RTC_WAKEUP set : Alarm{f9a3dd8 type 0 when 1454429689780 com.android.vending} when 1454429689780
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.847ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.964ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 21.695ms
I/MediaRouter( 7074): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7074): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7074): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7074): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  971): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7125 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7074): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7074): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7125): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7125): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7125): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationManager( 7074): com.google.android.music: cancel(1061) by com.google.android.music
,D/Finsky  ( 7103): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/LGEmail ( 7125): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7125): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/Finsky  ( 7103): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/eas_req ( 7125): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,W/Settings( 7103): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7103): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7103): com.android.vending: cancel(-1050172287) by com.android.vending
D/LGDMClient( 6815): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6815): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6815): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6815): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/HubEmail( 7125): JNI_OnLoad()
I/HubEmail( 7125): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7125): registerNatives()
I/HubEmail( 7125): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7125): registerNativeMethods()
I/HubEmail( 7125): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7125): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,D/LGDMClient( 6815): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/NetworkStateForAutoUpdateMonitor( 6839): [onReceive] BroadcastReceiver onReceive
W/Settings( 7125): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NetworkStateForAutoUpdateMonitor( 6839): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6839): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 6839): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6839): onReceive
I/AppUp4:CustModeStarterReceiver( 6839): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6839): Context : android.app.ReceiverRestrictedContext@5856086
D/AppUp4:CustFacade( 6839): isCustomizationCompleted : false
D/LGDMClient( 6815): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6815): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/AppUp4:CustFacade( 6839): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6839): begin check event
I/LGDMClient( 6815): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/AppUp4:CustModeStarterReceiver( 6839): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/LgeMiscReceiver( 3261): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3261): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3261): networkInfo.isConnected() = true
D/PhoneState( 3261): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 6858): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6858): onReceive CONNECTIVITY_CHANGE networkType=1
,W/ContextImpl( 6815): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3213): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
E/LGDMClient( 6815): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6815): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6815): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6815): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
V/DownloadManager( 3213): DownloadService onCreate
D/LGDMClient( 6815): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/NotificationManager( 3213): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3213): in removeSpuriousFiles
V/DownloadManager( 3213): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/WeatherAncestor( 2626): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:14:50
V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@3193270f on behalf of 3213
I/DownloadManager( 3213): in trimDatabase
V/DownloadManager( 3213): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@3628639c on behalf of 3213
D/UpdateThreadPoolManager( 2626): 2 : This is isUpdating : false
D/WeatherAncestor( 2626): connectivity changed - connection : true
D/Weather_cast( 2626): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2626): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:14:50
I/ActivityManager(  971): Killing 6902:com.google.android.talk/u0a61 (adj 15): empty #11
D/WeatherService( 2626): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,D/Ads     ( 7103): Skipping gmscore version check
W/BroadcastQueue(  971): Exception when sending broadcast to ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver}
W/BroadcastQueue(  971): android.os.DeadObjectException
W/BroadcastQueue(  971): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  971): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue(  971): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
W/BroadcastQueue(  971): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:270)
W/BroadcastQueue(  971): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1002)
W/BroadcastQueue(  971): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16810)
W/BroadcastQueue(  971): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
W/BroadcastQueue(  971): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/BroadcastQueue(  971): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/BroadcastQueue(  971): 	at android.os.Binder.execTransact(Binder.java:446)
W/libprocessgroup(  971): failed to open /acct/uid_10061/pid_6902/cgroup.procs: No such file or directory
,I/ActivityManager(  971): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7183 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  971): Spurious death for ProcessRecord{331318f5 7183:com.google.android.talk/u0a61}, curProc for 6902: null
V/DownloadManager( 3213): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
W/ActivityManager(  971): getTasks: caller 10074 does not hold GET_TASKS; limiting output
V/DownloadManager( 3213): DownloadService onStartCommand
V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@3de5252b on behalf of 7103
D/Weather.Utils( 2626): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2626): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2626): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/Finsky  ( 7103): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7103): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3213): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/Finsky  ( 7103): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@16261d88 on behalf of 3213
,D/Finsky  ( 7103): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  971): Killing 6938:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/ResourcesManager( 7183): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Finsky  ( 7103): [900] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7103): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
W/libprocessgroup(  971): failed to open /acct/uid_10079/pid_6938/cgroup.procs: No such file or directory
,I/ActivityManager(  971): Killing 6999:com.android.chrome/u0a48 (adj 15): empty #11
,V/DownloadManager( 3213): DownloadService onDestroy
W/libprocessgroup(  971): failed to open /acct/uid_10048/pid_6999/cgroup.procs: No such file or directory
I/Babel_SMS( 7183): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7183): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7183): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7183): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7183): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7183): MmsConfig.loadFromResources
E/Babel_SMS( 7183): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7183): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7183): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7183): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7183): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7183): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7183): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7183): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7183): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 7183): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7183): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7183): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7183): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7183): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7183): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7183): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7183): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7183): found sensor: Motion Accel, handle=46
W/Settings( 7183): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7183): startup - clean
,I/Babel   ( 7183): deleted: false for 0
,I/art     ( 7183): CheckpointMarkThreadRoots callback created = 0xb042d510
,I/art     ( 7183): CheckpointMarkThreadRoots callback created = 0xb042d4f0
,I/ActivityManager(  971): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7215 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7183): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7183): Unsupported mime audio/adpcm
W/AudioCapabilities( 7183): Unsupported mime audio/g726
,W/AudioCapabilities( 7183): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7183): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7183): Unsupported mime video/mjpg
,W/VideoCapabilities( 7183): Unsupported mime video/theora
W/AudioCapabilities( 7183): Unsupported mime audio/evrc
,W/AudioCapabilities( 7183): Unsupported mime audio/qcelp
W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7183): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7183): Unsupported mime audio/qcelp
,W/AudioCapabilities( 7183): Unsupported mime audio/evrc
W/VideoCapabilities( 7183): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7183): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7183): onServiceConnected
W/Babel   ( 7183): Attempted to change video mute state without an active call.
,I/GAv4    ( 7215): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7215):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7215):   adb logcat -s GAv4
I/NotificationManager( 7183): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7183): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7183): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7183): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7183): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7215): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 7183): propertyValue:false
,W/GAv4    ( 7215): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7215): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7215): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7215): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7215): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7215): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 7183): connection state changed from UNKNOWN to CONNECTED
,I/WebViewFactory( 7215): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7215): Time to load native libraries: 2 ms (timestamps 3496-3498)
I/LibraryLoader( 7215): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7215): Binding Chromium to main looper Looper (main, tid 1) {3de5252b}
I/LibraryLoader( 7215): Expected native library version number "",actual native library version number ""
I/chromium( 7215): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7215): Initializing chromium process, singleProcess=true
,W/art     ( 7215): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7215): ApplicationContext is null in ApplicationStatus
W/chromium( 7215): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7215): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7215): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7215): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7215): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7215): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7215): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7215): Remote Branch: 
I/Adreno-EGL( 7215): Local Patches: 
I/Adreno-EGL( 7215): Reconstruct Branch: 
V/AudioPolicyService(  280): registerClient() client 0xb40decc0, uid 10079
,W/AudioManagerAndroid( 7215): Requires BLUETOOTH permission
I/NSApplication( 7215): Starting up...
I/ActivityManager(  971): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7286 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  971): Killing 7074:com.google.android.music:main/u0a81 (adj 15): empty #11
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  971): Killing 7021:com.google.android.apps.plus/u0a86 (adj 15): empty #12
W/libprocessgroup(  971): failed to open /acct/uid_10081/pid_7074/cgroup.procs: No such file or directory
,W/libprocessgroup(  971): failed to open /acct/uid_10086/pid_7021/cgroup.procs: No such file or directory
I/ActivityManager(  971): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7305 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  971): Killing 7125:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10021/pid_7125/cgroup.procs: No such file or directory
,W/ResourcesManager( 7305): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  971): Killing 6839:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10011/pid_6839/cgroup.procs: No such file or directory
,D/WearableService( 1730): callingUid 10006, callindPid: 1730
,E/MDM     ( 1730): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6439): Restart initialization of location
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,I/art     (  971): Explicit concurrent mark sweep GC freed 25573(1177KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.111ms total 161.491ms
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  971): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7338 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
,I/art     ( 6439): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6439): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,W/IcingInternalCorpora( 6439): getNumBytesRead when not calculated.
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Gmail   ( 7338): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7338): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  971): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 7338): Observing account changes for notifications
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 7338): Error finding the version of the Email provider.....
E/Gmail   ( 7338): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7338): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7338): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7338): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7338): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7338): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7338): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7338): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7338): We do not support migrating this version of the Email provider.
I/Gmail   ( 7338): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7103): [905] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,E/MDM     ( 1730): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 6439): Restart initialization of location
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  971): android: cancelAsUser(2) by android
W/GCoreFlp( 1730): No location to return for getLastLocation()
,W/FusedLocationProvider( 1730): location=null
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 7103): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7103): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7103): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7103): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  971): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=7401 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 7338): notifyAccountChanged
,I/Gmail   ( 7338): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7338): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7338): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     ( 6268): Explicit concurrent mark sweep GC freed 2583(113KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 456us total 37.734ms
I/Gmail   ( 7338): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7338): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out( 7103): propertyValue:false
I/MusicStore( 7401): Database version: 120
,I/Gmail   ( 7338): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7401): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7401): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7401): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7401): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7401): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7401): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7401): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7401): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@141e8f82: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7401): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7401): GMSCore installation verified
I/ConfigStore( 7401): Config Database version: 1
,I/MusicWidget( 2585): mDelayedStopHandler : unbind
D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  971): tsOffsetIs: Apps: 115823267773; DSPS: 3895189; Offset : -3053347860
I/MusicBrowser( 2650): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2650): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2650): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2650): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2650): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2650): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2650): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2650): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaRouter( 7401): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/MediaFocusControl(  971):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@8aff7a4com.lge.music.MediaPlaybackService$6@3d38990d
D/MusicBrowser( 2650): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2650): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2650): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2650): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/NetworkMonitor( 7401): type=WIFI subType= reason=null isConnected=true
I/MusicBrowser( 2650): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@3646ff12
I/MusicBrowser( 2650): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2650): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2650): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2650): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2650): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2650): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2650): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2650): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2650): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2650): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2650): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2650): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2650): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2650): reset
V/MediaPlayer[Native]( 2650): setListener
V/MediaPlayer[Native]( 2650): disconnect
V/MediaPlayer[Native]( 2650): destructor
,V/AudioFlinger(  280): releasing 18 from 2650 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
V/MediaPlayer[Native]( 2650): disconnect
D/MusicBrowser( 2650): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2650): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2650): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2650): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2650): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2650): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2650): [SmartShareManagerClient] unregisterListener: 1019826370
W/SmartShareClient( 2650): [SmartShareManagerClient] unregisterListener invalid listener: 1019826370
I/SmartShareClient( 2650): [SmartShareManagerClient] terminate service: 2650/MediaPlaybackService/1006004424
E/HomeCloudIF( 2650): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2650): [SmartShareManagerClient] unbindService context:android.app.Application@305eaed3
,V/CloudHub( 2650): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2650): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2650): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2650): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2650): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/art     ( 7401): CheckpointMarkThreadRoots callback created = 0xb042d3f0
,I/CloudHub( 2650): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29990
I/art     ( 7401): CheckpointMarkThreadRoots callback created = 0xb042d3d0
,I/art     (  971): Explicit concurrent mark sweep GC freed 10628(504KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.254ms total 153.451ms
,I/NetworkMonitor( 7401): type=WIFI subType= reason=null isConnected=true
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MusicLeanback( 7401): Stop autocaching.
I/MusicLeanback( 7401): Stop autocaching.
I/MusicLeanback( 7401): Stop autocaching.
,I/GHttpClientFactory( 7401): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/MusicLeanback( 7401): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 7401): Stop autocaching.
I/GoogleURLConnFactory( 7401): Using platform SSLCertificateSocketFactory
I/ActivityManager(  971): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7450 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7053): Create singleton instance
,I/ActivityManager(  971): Killing 6815:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/AudioManager( 7053): getMode name:com.lge.qremote
,W/libprocessgroup(  971): failed to open /acct/uid_1000/pid_6815/cgroup.procs: No such file or directory
I/NotificationManager( 7401): com.google.android.music: cancel(1061) by com.google.android.music
I/CheckinService( 6439): Checkin interval check for package: unspecified last checkin: 1454429656290 min interval config: 0 actual interval: 38518
,I/CheckinService( 6439): Checking schedule, now: 1454429694821 next: 1454429686041
I/CheckinService( 6439): active receiver: enabled
,E/GmsUtils( 7401): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 7401): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
W/ContextImpl( 3587): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/CheckinService( 6439): Preparing to send checkin request
D/UEI.SmartControl( 7450): Quickset Services start...
,I/UEI.SmartControl( 7450): Manufacture = LGE
D/UEI.SmartControl( 7450): File observer start...
E/UEI.SmartControl( 7450): IR Port is disabled: false
D/UEI.SmartControl( 7450): Starting file observer...
D/UEI.SmartControl( 7450): Extracting JNI libs...
,D/UEI.SmartControl( 7450): --- this system supports 32-bit or 64-bit only
I/EventLogService( 6439): Accumulating logs since 1454429648381
I/NotificationManager( 6439): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ActivityManager(  971): Killing 6881:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/UEI.SmartControl( 7450): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7450): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7450): --- Extracting JNI libs: libqs_armeabi-v7a.zip
W/libprocessgroup(  971): failed to open /acct/uid_10051/pid_6881/cgroup.procs: No such file or directory
I/UEI.SmartControl( 7450): --- Selecting new region: 2
,I/UEI.SmartControl( 7450): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7450): Platform has CIR...
D/UEI.SmartControl( 7450): NO CIR support, need to check package...
I/UEI.SmartControl( 7450): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7450): QS Service created
,E/UEI.SmartControl( 7450): QS start get config
,I/CheckinRequestBuilder( 6439): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6439): Failed to find provider info for com.google.android.wearable.settings
D/UEI.SmartControl( 7450): Loading JNI Libs...
,D/UEI.SmartControl( 7450):  configuring local db...
,I/ActivityManager(  971): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7494 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/UEI.SmartControl( 7450):  ---- Has DB8: true
,D/UEI.SmartControl( 7450): QS start statue = true Error code = 0
D/UEI.SmartControl( 7450): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7450): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7450): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7450): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7450): IrrcClient ++ 
D/irrcClient( 7450): getIrrcService ++ 
,D/irrcClient( 7450): getIrrcService -- 
D/irrcClient( 7450): IrrcClient -- 
W/irrc_jni( 7450): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7450): Services init done
I/UEI.SmartControl( 7450): Device manager: loading config....
D/UEI.SmartControl( 7450): QS Service init finished
,D/UEI.SmartControl( 7450): Config is loaded...
,D/UEI.SmartControl( 7450): QS Service version name: 0.1.73
W/ResourcesManager( 7494): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7494): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 7450): QS Service version code: 1073
D/UEI.SmartControl( 7450): Service requested: Control
,I/MultiDex( 7494): VM with version 2.1.0 has multidex support
I/MultiDex( 7494): install
I/MultiDex( 7494): VM has multidex support, MultiDex support library is disabled.
,D/UEI.SmartControl( 7450):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7450): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7450): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7450): Internal service binding...
V/JNIHelp ( 7494): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/UEI.SmartControl( 7450): -----IControl: 11
D/UEI.SmartControl( 7450): Caller: com.lge.qremote
,D/UEI.SmartControl( 7450): ------------ IControl registerCallback...
I/UEI.SmartControl( 7450): Registering callback...
D/UEI.SmartControl( 7450): -----IControl: 19
D/UEI.SmartControl( 7450): Caller: com.lge.qremote
I/UEI.SmartControl( 7450): Registering Services Ready callback...
I/UEI.SmartControl( 7450): Notify client services are ready...
D/UEI.SmartControl( 7450): -----IControl: 8
D/UEI.SmartControl( 7450): Caller: com.lge.qremote
,I/AudioManager( 7053): getMode name:com.lge.qremote
I/ActivityManager(  971): Killing 7215:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/ActivityThread( 7494): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7494): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@368bf73b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7494): Installed default security provider GmsCore_OpenSSL
E/libprocessgroup(  971): failed to kill 1 processes for processgroup 7215
,I/NotificationManager( 7494): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7494): com.google.android.gms: cancel(39789) by com.google.android.gms
I/AudioManager( 7053): getMode name:com.lge.qremote
E/MDM     ( 1730): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6439): Restart initialization of location
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 7494): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7494): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,I/AudioManager( 7053): getMode name:com.lge.qremote
I/ActivityManager(  971): Killing 7286:com.android.chrome/u0a48 (adj 15): empty #11
,D/NativeLibraryUtils( 7494): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  971): failed to open /acct/uid_10048/pid_7286/cgroup.procs: No such file or directory
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): CdmEngine::OpenSession
I/WVCdm   (  280): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  280): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  280): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  280): L1 library not specified. Falling Back to L3
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  280): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  280): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
D/WVCdm   (  280): PrepareKeyRequest: nonce=2922859266
I/art     ( 7494): CheckpointMarkThreadRoots callback created = 0xb04d4eb0
,I/art     ( 7494): CheckpointMarkThreadRoots callback created = 0xb04d4ea0
,I/dex2oat ( 7532): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7532): dex2oat took 125.311ms (threads: 4)
,I/Adreno-EGL( 7494): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7494): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7494): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7494): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7494): Remote Branch: 
I/Adreno-EGL( 7494): Local Patches: 
I/Adreno-EGL( 7494): Reconstruct Branch: 
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/WVCdm   (  280): CdmEngine::OpenSession
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WVCdm   (  280): CdmEngine::CloseSession
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  280): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  280): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
D/WVCdm   (  280): PrepareKeyRequest: nonce=978030940
I/GAv4-SVC( 6439): Google Analytics 8.4.89 is starting up.
,I/GAV2    ( 7338): Thread[GAThread,5,main]: No campaign data found.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/MusicLeanback( 7401): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 7401): Stop autocaching.
,E/GmsUtils( 7401): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 7401): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/CheckinService( 6439): Done disabling old GoogleServicesFramework version
,D/PowerManagerServiceEx(  971): acquireWakeLockInternal: lock=1024270344, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=971
,D/WeatherService( 2626): 2 : TimeTick Intent has been received, Time(hour:min:sec) 17:15:0
,D/WeatherService( 2626): 2 : TimeTick Intent And Screen On
D/WeatherService( 2626): 2 : SDK version : 21
W/ActivityManager(  971): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2626): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2626): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2626): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2626): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2626): 2 : This is isUpdating : false
D/WeatherService( 2626): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2626): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2626): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2626): 2 : Fixed theme : optimus
D/WeatherReflect( 2626): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
,D/lim     ( 2626): 2 : time = 17:15
I/WeatherReflect( 2626): Model Name : LG-D722
,D/WeatherTheme( 2626): 2 : Different view - status_min_formatted : 14 != 15
D/WeatherTheme( 2626): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2626): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2626): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2626): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2626): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2626): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]Clock( 1372): called onTimeUpdated()
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
,I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/Weather4x2_optimus( 2626): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2626): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2626): forecast size is 0
D/Theme   ( 2626): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2626): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2626): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2626): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2626): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2626): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2626): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2626): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2626): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2626): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2626): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2626): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2626): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2626): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2626): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2626): url is : null
,D/Theme   ( 2626): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2626): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2626): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2626): 2 : update view, appWidgetId: 2
D/WeatherService( 2626): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 17:15:0
D/PowerManagerServiceEx(  971): releaseWakeLockInternal: lock=1024270344 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/WVCdm   (  280): CdmEngine::CloseSession
,I/WVCdm   (  280): L3 Terminate.
D/UEI.SmartControl( 7450): Internal timer expired: 1
,I/Adreno-EGL( 7494): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7494): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7494): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7494): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7494): Remote Branch: 
I/Adreno-EGL( 7494): Local Patches: 
I/Adreno-EGL( 7494): Reconstruct Branch: 
,I/Adreno-EGL( 7494): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7494): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7494): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7494): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7494): Remote Branch: 
I/Adreno-EGL( 7494): Local Patches: 
I/Adreno-EGL( 7494): Reconstruct Branch: 
,I/CheckinRequestBuilder( 6439): Classify the device as Phone.
,D/libc-netbsd( 6439): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6439): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6439): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6439): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 6439): propertyValue:false
I/ActivityManager(  971): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7576 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/libc-netbsd( 6439): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6439): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6439): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6439): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6439): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6439): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinTask( 6439): Sending checkin request (9693 bytes)
,I/DigitalAppWidgetProvider( 7576): onReceive: com.android.deskclock.ON_QUARTER_HOUR
V/DigitalAppWidgetProvider( 7576): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3f66956b
,I/ActivityManager(  971): Killing 7305:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10086/pid_7305/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 6439): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6439): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 6268): Explicit concurrent mark sweep GC freed 2899(117KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 385us total 28.425ms
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/CheckinRequestBuilder( 6439): Classify the device as Phone.
,I/CheckinTask( 6439): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6439): Checking schedule, now: 1454429702135 next: 1454956951128
I/CheckinService( 6439): active receiver: disabled
,D/CheckinService( 6439): Recording last checkin time for package unspecified as 1454429702165
I/ActivityManager(  971): Killing 7103:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10036/pid_7103/cgroup.procs: No such file or directory
,V/SetupWizard( 6858): Connected to Gservices successfully
I/ActivityManager(  971): Killing 2650:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  280): 2650 died, releasing its sessions
V/AudioFlinger(  280):  pid 1748 @ 0
V/AudioFlinger(  280):  pid 3261 @ 1
V/AudioFlinger(  280):  pid 3261 @ 2
,W/libprocessgroup(  971): failed to open /acct/uid_10028/pid_2650/cgroup.procs: No such file or directory
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  971): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  971): Handling package changes for user 0
I/ActivityManager(  971): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7618 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 323us total 22.354ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 23.010ms
,I/NotificationManager( 7183): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7183): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7183): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 22.202ms
I/AppUp4:AppBoxCP( 7618): onCreate
,W/AppUp4:DB( 7618):  [AppBoxDatabaseHelper] construct
V/JNIHelp ( 7183): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AppUp4:DB( 7618):  setFingerPrint start
I/AppUp4:DB( 7618):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7618):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7618):  SDK version = 0
I/AppUp4:DB( 7618):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7618): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7618): onReceive
I/AppUp4:CustModeStarterReceiver( 7618): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7618): Context : android.app.ReceiverRestrictedContext@3f66956b
D/AppUp4:CustFacade( 7618): isCustomizationCompleted : false
,W/System  ( 7183): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7183): Installed default security provider GmsCore_OpenSSL
I/NotificationService(  971): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  971): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  971): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/AppUp4:CustFacade( 7618): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7618): begin check event
I/AppUp4:CustModeStarterReceiver( 7618): Event For Nothing, skip.
I/BackupManagerService(  971): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  971): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7641 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/charger_monitor(  486): init target 500000
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
W/ResourcesManager(  971): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  971): Process com.google.android.music:main (pid 7401) has died
,I/art     (  971): Explicit concurrent mark sweep GC freed 21384(1095KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 3.220ms total 194.929ms
,V/BackupManagerService(  971): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  971): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@25cb58c5
W/ResourcesManager( 7641): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7641): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7641): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType(  971): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  971): applying state to connected service
,I/AppConfig( 7641): Total System Memory = 906309632
,I/GalleryUtils( 7641): Application Heap = 96 MB
I/AppConfig( 7641): App Tier : NOT_DEF
D/SystemHelper( 7641): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  971): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7662 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  971): Process com.google.android.gm (pid 7338) has died
,W/ResourcesManager( 7662): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7662): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7662): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7662): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7662): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7662): BUILD Country: EU
I/SystemConfig( 7662): BUILD Operator: OPEN
,I/ActivityManager(  971): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7690 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/SystemConfig( 7662): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7662): existFile = false
I/SystemConfig( 7662): canReadFile = false
I/SystemConfig( 7662): systemFeature RCS result false
D/SystemConfig( 7662): refreshRcsSupport() :false
,I/LockScreenSettings( 7690): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7690): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7690): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7690): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7690): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,D/LockScreenSettings( 7690): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  971): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7707 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  971): Killing 7450:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 7053): android.os.DeadObjectException
,W/System.err( 7053): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7053): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7053): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7053): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7053): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7053): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7053): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7053): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7053): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7053): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7053): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7053): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7053): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7053): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/UEI.SmartControl( 7053): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7053): android.os.DeadObjectException
W/System.err( 7053): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7053): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7053): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7053): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7053): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7053): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7053): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7053): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7053): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7053): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7053): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7053): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7053): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7053): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7053): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  971): failed to open /acct/uid_10089/pid_7450/cgroup.procs: No such file or directory
,W/ActivityManager(  971): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
W/ResourcesManager( 7707): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  971): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7731 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7731): Quickset Services start...
I/UEI.SmartControl( 7731): Manufacture = LGE
D/UEI.SmartControl( 7731): File observer start...
E/UEI.SmartControl( 7731): IR Port is disabled: false
D/UEI.SmartControl( 7731): Starting file observer...
D/UEI.SmartControl( 7731): Extracting JNI libs...
,D/UEI.SmartControl( 7731): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7731): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7731): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7731): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7731): --- Selecting new region: 2
I/UEI.SmartControl( 7731): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7731): Platform has CIR...
D/UEI.SmartControl( 7731): NO CIR support, need to check package...
I/UEI.SmartControl( 7731): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7731): QS Service created
E/UEI.SmartControl( 7731): QS start get config
,D/UEI.SmartControl( 7731): Loading JNI Libs...
,D/UEI.SmartControl( 7731):  configuring local db...
I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  971): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7768 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 77 ms] updated apps [took 77 ms] 
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
I/ActivityManager(  971): Killing 7053:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10106/pid_7053/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7731):  ---- Has DB8: true
D/UEI.SmartControl( 7731): QS start statue = true Error code = 0
D/UEI.SmartControl( 7731): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 7731): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7731): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7731): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7731): IrrcClient ++ 
D/irrcClient( 7731): getIrrcService ++ 
,D/irrcClient( 7731): getIrrcService -- 
D/irrcClient( 7731): IrrcClient -- 
W/irrc_jni( 7731): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7731): Services init done
,I/UEI.SmartControl( 7731): Device manager: loading config....
D/UEI.SmartControl( 7731): QS Service init finished
,D/UEI.SmartControl( 7731): QS Service version name: 0.1.73
D/UEI.SmartControl( 7731): QS Service version code: 1073
D/UEI.SmartControl( 7731): Config is loaded...
D/UEI.SmartControl( 7731): Service requested: Control
D/UEI.SmartControl( 7731):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7731): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7731): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7731): Service.onUnbind: IControl
D/UEI.SmartControl( 7731): Service.onDestroy
D/UEI.SmartControl( 7731): Shutdown IRRCPlayer... 
W/irrc_jni( 7731): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7731): ~IrrcClient ++ 
D/irrcClient( 7731): ~IrrcClient -- 
W/irrc_jni( 7731): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7731): Blaster closed
D/UEI.SmartControl( 7731): Blaster closed
D/UEI.SmartControl( 7731): Shut down QS...
D/UEI.SmartControl( 7731): Stopped file observer...
,I/UEI.SmartControl( 7731): QS lib stop result = true
D/UEI.SmartControl( 7731): QS shutdown complete
D/UEI.SmartControl( 7731): QS Service created
E/UEI.SmartControl( 7731): QS start get config
,D/UEI.SmartControl( 7731):  configuring local db...
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/Finsky  ( 7768): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 7731):  ---- Has DB8: true
,D/Finsky  ( 7768): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
D/UEI.SmartControl( 7731): QS start statue = true Error code = 0
D/UEI.SmartControl( 7731): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7731): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7731): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7731): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7731): IrrcClient ++ 
D/irrcClient( 7731): getIrrcService ++ 
D/irrcClient( 7731): getIrrcService -- 
D/irrcClient( 7731): IrrcClient -- 
W/irrc_jni( 7731): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7731): Services init done
I/UEI.SmartControl( 7731): Device manager: loading config....
D/UEI.SmartControl( 7731): QS Service init finished
D/UEI.SmartControl( 7731): QS Service version name: 0.1.73
D/UEI.SmartControl( 7731): QS Service version code: 1073
D/UEI.SmartControl( 7731): Service requested: Control
,D/UEI.SmartControl( 7731): Config is loaded...
W/Settings( 7768): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7768): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7768): com.android.vending: cancel(-1050172287) by com.android.vending
D/UEI.SmartControl( 7731):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7731): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7731): Request IControl service: devices are loaded...
E/ActivityThread( 7731): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@22a1ce9d that was originally bound here
E/ActivityThread( 7731): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@22a1ce9d that was originally bound here
E/ActivityThread( 7731): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 7731): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 7731): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 7731): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 7731): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7731): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 7731): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 7731): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 7731): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 7731): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 7731): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 7731): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7731): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7731): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 7731): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7731): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7731): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 7731): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 7731): Internal service binding...
V/DownloadManager( 3213): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@17520346 on behalf of 7768
D/Finsky  ( 7768): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Ads     ( 7768): Skipping gmscore version check
D/Finsky  ( 7768): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  971): Killing 7576:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10010/pid_7576/cgroup.procs: No such file or directory
,D/Finsky  ( 7768): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7768): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 6439): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6439): Null package name or gms related package.  Ignoreing.
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 30859(2MB) AllocSpace objects, 29(464KB) LOS objects, 39% free, 13MB/22MB, paused 1.501ms total 114.604ms
,I/Icing   ( 6439): Storage manager: low false usage 1.76MB avail 2.37GB capacity 4.06GB
,I/Icing   ( 6439): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 6439): Internal init done: storage state 0
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/Icing   ( 6439): Post-init done
I/Icing   ( 6439): updateResources: need to parse f{com.google.android.gms}
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Icing   ( 6439): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 6439): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6439): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  971): Killing 6858:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10038/pid_6858/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  971): Killing 7494:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10006/pid_7494/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 7731): file observer is disposed!
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/UEI.SmartControl( 7731): Internal timer expired: 2
,D/UEI.SmartControl( 7731): Service.onUnbind: IControl
D/UEI.SmartControl( 7731): Service.onDestroy
W/System.err( 7731): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@2011fa5e
W/System.err( 7731): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7731): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7731): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7731): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7731): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7731): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7731): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7731): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7731): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7731): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7731): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7731): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7731): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7731): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7731): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7731): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@2011fa5e
D/UEI.SmartControl( 7731): Shutdown IRRCPlayer... 
W/irrc_jni( 7731): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7731): ~IrrcClient ++ 
D/irrcClient( 7731): ~IrrcClient -- 
W/irrc_jni( 7731): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7731): Blaster closed
D/UEI.SmartControl( 7731): Blaster closed
D/UEI.SmartControl( 7731): Shut down QS...
I/UEI.SmartControl( 7731): QS lib stop result = true
D/UEI.SmartControl( 7731): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 135824100004; DSPS: 4550576; Offset : -3053339681
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  971): ELAPSED_WAKEUP set : Alarm{3b0c6291 type 2 when 145662 com.google.android.gms} when 145662
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1730): Vacuum at: now=1454429724233 tag=VacuumService
W/InstanceID/Rpc( 6439): Found 10006
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PhenotypeConfigurator( 1730): Scheduling Phenotype for one-off execution 2043 seconds from now (1454429724682)
,D/GetConfigurationSnapshotOperation( 1730): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1730): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1730): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  971): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LocationManagerService(  971): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  971): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  971): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  971): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/PowerManagerService(  971): ALS enabled for SRE
D/PowerManagerServiceEx(  971): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29376 ms ago)
,D/qdlights(  971): set_light_backlight: 254
,D/qdlights(  971): set_light_backlight: 251
D/qdlights(  971): set_light_backlight: 247
,D/qdlights(  971): set_light_backlight: 244
,D/qdlights(  971): set_light_backlight: 241
,D/qdlights(  971): set_light_backlight: 237
,D/qdlights(  971): set_light_backlight: 234
,D/qdlights(  971): set_light_backlight: 231
,D/qdlights(  971): set_light_backlight: 227
,D/qdlights(  971): set_light_backlight: 224
,D/qdlights(  971): set_light_backlight: 221
,D/qdlights(  971): set_light_backlight: 217
,D/qdlights(  971): set_light_backlight: 214
,D/qdlights(  971): set_light_backlight: 211
,D/qdlights(  971): set_light_backlight: 207
,D/qdlights(  971): set_light_backlight: 204
,D/qdlights(  971): set_light_backlight: 201
,D/qdlights(  971): set_light_backlight: 197
,D/qdlights(  971): set_light_backlight: 194
,D/qdlights(  971): set_light_backlight: 191
,D/qdlights(  971): set_light_backlight: 187
,D/qdlights(  971): set_light_backlight: 184
,D/qdlights(  971): set_light_backlight: 181
,D/qdlights(  971): set_light_backlight: 177
,D/qdlights(  971): set_light_backlight: 174
,D/qdlights(  971): set_light_backlight: 171
,D/qdlights(  971): set_light_backlight: 167
,D/qdlights(  971): set_light_backlight: 164
,D/qdlights(  971): set_light_backlight: 161
,D/qdlights(  971): set_light_backlight: 157
,D/qdlights(  971): set_light_backlight: 154
,D/qdlights(  971): set_light_backlight: 151
,D/qdlights(  971): set_light_backlight: 147
,D/qdlights(  971): set_light_backlight: 144
,D/qdlights(  971): set_light_backlight: 141
,D/qdlights(  971): set_light_backlight: 137
,D/qdlights(  971): set_light_backlight: 134
,D/qdlights(  971): set_light_backlight: 131
,D/qdlights(  971): set_light_backlight: 127
,D/qdlights(  971): set_light_backlight: 124
,D/qdlights(  971): set_light_backlight: 121
,D/qdlights(  971): set_light_backlight: 117
,D/qdlights(  971): set_light_backlight: 114
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  971): set_light_backlight: 111
,D/qdlights(  971): set_light_backlight: 107
,D/qdlights(  971): set_light_backlight: 104
,D/qdlights(  971): set_light_backlight: 101
,D/qdlights(  971): set_light_backlight: 97
,D/qdlights(  971): set_light_backlight: 94
,D/qdlights(  971): set_light_backlight: 91
,D/qdlights(  971): set_light_backlight: 87
,D/qdlights(  971): set_light_backlight: 84
,D/qdlights(  971): set_light_backlight: 81
,D/qdlights(  971): set_light_backlight: 77
,D/qdlights(  971): set_light_backlight: 74
,D/qdlights(  971): set_light_backlight: 71
,D/qdlights(  971): set_light_backlight: 67
,D/qdlights(  971): set_light_backlight: 64
,D/qdlights(  971): set_light_backlight: 61
,D/qdlights(  971): set_light_backlight: 57
,D/qdlights(  971): set_light_backlight: 54
,D/qdlights(  971): set_light_backlight: 51
,D/qdlights(  971): set_light_backlight: 47
,D/qdlights(  971): set_light_backlight: 44
,D/qdlights(  971): set_light_backlight: 41
,D/qdlights(  971): set_light_backlight: 37
,D/qdlights(  971): set_light_backlight: 34
,D/qdlights(  971): set_light_backlight: 31
,D/qdlights(  971): set_light_backlight: 27
,D/qdlights(  971): set_light_backlight: 24
,D/qdlights(  971): set_light_backlight: 21
,D/qdlights(  971): set_light_backlight: 17
,D/qdlights(  971): set_light_backlight: 14
,D/qdlights(  971): set_light_backlight: 11
,D/qdlights(  971): set_light_backlight: 10
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 155824996767; DSPS: 5205966; Offset : -3053358238
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  971): ALS enabled for SRE
D/PowerManagerServiceEx(  971): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36369 ms ago)
,I/PowerManagerService(  971): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  971): ALS enabled for SRE
D/PowerManagerServiceEx(  971): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36385 ms ago)
,W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  971): Sleeping (uid 1000)...
,D/LPWGController(  971): [updateScreenState] screen on = false
D/LPWGController(  971): disable proximity sensor
,D/LPWGController(  971): enable proximity sensor
I/SensorManager(  971): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@21e60039] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  971): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  971): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  971): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  971): activate: handle is 48, enable
,V/sensors_hal_Ctx(  971): activate sensors is 1400000000000
D/sensors_hal_Thresh(  971): enable: handle=48
I/sensors_hal_SAM(  971): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  971): waitForResponse: timeout=1000
V/sensors_hal_SAM(  971): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  971): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  971): enable: Received response: 0
D/PowerManagerServiceEx(  971): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36455 ms ago)
I/Adreno-EGL(  971): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  971): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  971): Build Date: 03/02/15 Mon
I/Adreno-EGL(  971): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  971): Remote Branch: 
I/Adreno-EGL(  971): Local Patches: 
I/Adreno-EGL(  971): Reconstruct Branch: 
,D/PermissionCache(  244): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1056 us)
,I/Sensors (  423): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  971): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  971): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  971): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  971): processInd: handle 48, count=1
V/sensors_hal_Thresh(  971): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  971): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  971): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  971): poll: count: 256
I/sensors_hal_Ctx(  971): poll: released wakelock sensor_ind
D/sensors_hal_Util(  971): waitForResponse: timeout=0
D/LPWGController(  971): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  971): current mode = 1  value = 1 1
I/LPWGController(  971): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  971): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  971): set_light_backlight: 0
,I/SensorManager(  971): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  971): activate: handle is 46, disable
V/sensors_hal_Ctx(  971): activate sensors is 1000000000000
D/sensors_hal_LP2(  971): enable: handle=46
D/sensors_hal_LP2(  971): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  971): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  244): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  244): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  971): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  971): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/DisplayManagerService(  971): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  971): Display changed displayId=0
,D/DSDPConnection( 1748): Display #0 changed.
,I/ActivityManager(  971): Process com.google.android.talk (pid 7183) has died
,D/qdhwcomposer(  244): hwc_blank: Done blanking display: 0
D/SurfaceControl(  971): Excessive delay in setPowerMode(): 231ms
,I/qdhwcomposer(  244): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  971): Got set_interactive hint
D/KeyguardViewMediator( 1372): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1372): notifyScreenOffLocked
D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1372): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1372): handleNotifyScreenOff
D/WifiServerServiceExt(  971): sendKtScanInterval  mRtspPlay : false
,I/WifiServerServiceExt(  971): set CMD_KT_SCAN_INTERVAL
D/ScreenTurnOffBySensor( 1372): unregisterProximitySensor
V/AudioFlinger(  280): setParameters(): io 0, keyvalue screen_state=on, calling pid 971
,D/audio_hw_primary(  280): adev_set_parameters: enter: screen_state=on
V/voice   (  280): voice_set_parameters: enter: screen_state=on
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: exit
V/voice   (  280): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  280): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  280): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  280): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  280): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  280): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  280): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  280): adev_set_parameters: exit with code(0)
D/StatusBarWindowView( 1372): onScreenTurnedOff why = 3
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
,D/GpsLocationProvider(  971): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:true
D/LNfcService( 1783): action : android.intent.action.SCREEN_ON
I/LEDService( 1800): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1800): stopPatternFlashing()
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/NfcServiceNXP( 1783): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1783): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1783): isRequireNfcCRouting() return true
D/LNfcService( 1783): isHCERoutingtoHost() return : true
D/NfcService( 1783): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): newParams.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): screenState= 3
D/NfcService( 1783): Discovery configuration equal, not updating.
I/Cliptray Service( 1800): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1800): lockStatus = 0
I/LEDService( 1800): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): updateLightsLocked : turn off led
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1800): RESTART MSG
,D/Ulp_jni (  971): JNI:system_update. Event-0
D/SplitWindow(  971): check instance of lgWin Window{22a12c2c u0 SearchPanel}
,D/InputDispatcher(  971): Window went away: Window{2eea025a u0 SearchPanel}
,I/[SystemUI]Clock( 1372): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1372): time changed, timezoneChanged : false
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2626): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:15:36
,D/WeatherService( 2626): 2 : ACTION screen on
D/WeatherService( 2626): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2626): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2626): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:15:36
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): ACTION_SCREEN_ON
,D/AppCleanupService( 4036): android.intent.action.SCREEN_ON
,V/AudioFlinger(  280): setParameters(): io 0, keyvalue screen_state=off, calling pid 971
D/audio_hw_primary(  280): adev_set_parameters: enter: screen_state=off
V/voice   (  280): voice_set_parameters: enter: screen_state=off
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: exit
V/voice   (  280): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  280): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  280): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  280): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  280): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  280): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  280): adev_set_parameters: exit with code(0)
D/WifiController(  971): CMD_SCREEN_OFF 
D/WifiController(  971): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  971): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:false
,I/LEDService( 1800): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1800): stopPatternFlashing()
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1800): clear
I/LEDService( 1800): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1783): action : android.intent.action.SCREEN_OFF
I/Cliptray Service( 1800): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1800): updateLightsLocked : turn on led
E/LEDService( 1800): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1800): Can't handle this request of patternId:0
D/LEDHandler( 1800): RESTART MSG
D/NfcServiceNXP( 1783): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1875): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,E/NxpNfcJni( 1783): getReconnectState = 0x0
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
D/LNfcService( 1783): isRequireNfcCRouting() return true
D/LNfcService( 1783): isHCERoutingtoHost() return : true
,D/NfcService( 1783): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): newParams.techmask= mTechMask: 0
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): screenState= 1
E/NxpNfcJni( 1783): getReconnectState = 0x0
,I/Sensors (  423): sns_pwr.c(301):releasing wakelock
,I/art     (  971): Explicit concurrent mark sweep GC freed 48404(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 1.941ms total 148.650ms
,D/WeatherService( 2626): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:15:36
,D/WeatherService( 2626): 2 : ACTION screen off
,D/WeatherService( 2626): 2 : TimeTick Receiver Unregister
D/WeatherService( 2626): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:15:36
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): ACTION_SCREEN_OFF
D/AppCleanupService( 4036): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4036): AppUsageStatsSaveTask
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1372): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  971): ELAPSED_WAKEUP set : Alarm{301d66f5 type 2 when 162393 com.android.systemui} when 162393
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1748): getCallState : 0
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1372): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1372): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 175825675094; DSPS: 5861348; Offset : -3053351244
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/PowerManagerServiceEx(  971): acquireWakeLockInternal: lock=1024270344, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=971
,V/AlarmManager(  971): ELAPSED_WAKEUP set : Alarm{861ac8a type 2 when 183635 android} when 183635
D/PowerManagerServiceEx(  971): releaseWakeLockInternal: lock=1024270344 [*alarm*], flags=0x0
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1730): disconnect managed GoogleApiClient
,D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
V/AlarmManager(  971): ELAPSED_WAKEUP set : Alarm{10e4b2fb type 2 when 188254 com.google.android.gms} when 188254
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 195826383523; DSPS: 6516731; Offset : -3053344928
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 215827125754; DSPS: 7172115; Offset : -3053335067
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  971): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 235827809550; DSPS: 7827498; Offset : -3053353202
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
,I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 255828526677; DSPS: 8482881; Offset : -3053337718
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 275829286722; DSPS: 9138266; Offset : -3053340978
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 295829971505; DSPS: 9793649; Offset : -3053358125
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 315830750561; DSPS: 10449034; Offset : -3053342138
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 335831433366; DSPS: 11104417; Offset : -3053360925
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  971): remove 3b4bf225
,D/LocationManagerService(  971): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  971): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  971): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  971): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  971): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 355832099348; DSPS: 11759799; Offset : -3053366460
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  971): acquireWakeLockInternal: lock=1024270344, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=971
,V/AlarmManager(  971): RTC_WAKEUP set : Alarm{90adf18 type 0 when 1454429945441 com.google.android.gms} when 1454429945441
D/PowerManagerServiceEx(  971): releaseWakeLockInternal: lock=1024270344 [*alarm*], flags=0x0
,I/EventLogService( 6439): Aggregate from 1454429695138 (log), 1454428145353 (data)
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/WifiController(  971): battery changed pluggedType: 2
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 375832836267; DSPS: 12415183; Offset : -3053363213
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 395833586833; DSPS: 13070567; Offset : -3053343871
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 415834218335; DSPS: 13725948; Offset : -3053353004
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  971): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 435834969213; DSPS: 14381333; Offset : -3053365066
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 455835718684; DSPS: 15036717; Offset : -3053348616
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 475836385396; DSPS: 15692099; Offset : -3053353055
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 495837136430; DSPS: 16347484; Offset : -3053364597
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 515837788401; DSPS: 17002865; Offset : -3053353260
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 535838555581; DSPS: 17658250; Offset : -3053349306
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 555839320521; DSPS: 18313635; Offset : -3053347254
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 575839987024; DSPS: 18969017; Offset : -3053351980
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 595840796653; DSPS: 19624403; Offset : -3053335808
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 615841516228; DSPS: 20279787; Offset : -3053349020
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 635842164345; DSPS: 20935168; Offset : -3053341825
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 655842985328; DSPS: 21590555; Offset : -3053344452
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 675843659695; DSPS: 22245937; Offset : -3053341472
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 695844316197; DSPS: 22901319; Offset : -3053356408
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 715845134523; DSPS: 23556706; Offset : -3053362030
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 735845893213; DSPS: 24212091; Offset : -3053366306
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 755846548986; DSPS: 24867472; Offset : -3053351689
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 775847359396; DSPS: 25522859; Offset : -3053365071
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 795848104909; DSPS: 26178243; Offset : -3053351641
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 815848756047; DSPS: 26833624; Offset : -3053341737
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 835849573435; DSPS: 27489011; Offset : -3053348324
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 855850357803; DSPS: 28144397; Offset : -3053357465
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 875851010869; DSPS: 28799778; Offset : -3053344981
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 895851824611; DSPS: 29455165; Offset : -3053355371
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 915852506998; DSPS: 30110547; Offset : -3053344317
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 935853150637; DSPS: 30765928; Offset : -3053341861
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  971): acquireWakeLockInternal: lock=1024270344, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=971
,V/AlarmManager(  971): ELAPSED_WAKEUP set : Alarm{1a187fad type 2 when 951964 com.android.bluetooth} when 951964
D/PowerManagerServiceEx(  971): releaseWakeLockInternal: lock=1024270344 [*alarm*], flags=0x0
,W/bt-smp  ( 1983): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1983): Plain text(LSB ~ MSB) = 6c 8c 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 1983): Encrypted text(LSB ~ MSB) = 8e e5 94 43 4a fa 45 24 bc 09 e4 a5 a1 58 e2 86 
W/bt-btm  ( 1983): Stopping oneshot timer
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 955853977973; DSPS: 31421315; Offset : -3053338421
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 975854737341; DSPS: 32076700; Offset : -3053341654
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 995855449052; DSPS: 32732084; Offset : -3053362392
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  971): acquireWakeLockInternal: lock=1024270344, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=971
,V/AlarmManager(  971): ELAPSED_WAKEUP set : Alarm{2342e2 type 2 when 1015515 com.google.android.gms} when 1015515
D/PowerManagerServiceEx(  971): releaseWakeLockInternal: lock=1024270344 [*alarm*], flags=0x0
,I/ActivityManager(  971): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=8069 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1015856385502; DSPS: 33387474; Offset : -3053343109
,W/ResourcesManager( 8069): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8069): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8069): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 8069): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8069): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  971): Process com.android.gallery3d (pid 7641) has died
,W/ResourcesManager( 8069): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8069): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 8069): CheckpointMarkThreadRoots callback created = 0xb042da30
I/art     ( 8069): CheckpointMarkThreadRoots callback created = 0xb042da20
,E/YouTube MDX( 8069): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd( 8069): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8069): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8069): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/dex2oat ( 8135): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1134998930.jar --oat-fd=22 --oat-location=/data/data/com.google.android.youtube/cache/ads-1134998930.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8135): dex2oat took 139.890ms (threads: 4)
,I/NotificationManager( 8069): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8069): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8069): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8069): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 8069): Found 10006
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8069): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/NotificationManager( 8069): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,D/libc-netbsd( 8069): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8069): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 8069): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 8069): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  275): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out( 8069): propertyValue:false
D/libc-netbsd( 8069): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8069): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 8069): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8069): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  971): Process com.lge.appbox.client (pid 7618) has died
,D/libc-netbsd( 8069): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8069): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 8069): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 8069): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  275): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 8069): propertyValue:false
D/libc-netbsd( 8069): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8069): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 8069): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 8069): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1035857268984; DSPS: 34042863; Offset : -3053342841
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1055858034862; DSPS: 34698248; Offset : -3053339979
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1075858709489; DSPS: 35353631; Offset : -3053368844
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1095859554951; DSPS: 36009018; Offset : -3053346004
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1115860504423; DSPS: 36664409; Offset : -3053342576
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1135861180352; DSPS: 37319791; Offset : -3053337826
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1155861919980; DSPS: 37975176; Offset : -3053361137
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1175862640337; DSPS: 38630559; Offset : -3053342606
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1195863293403; DSPS: 39285941; Offset : -3053362907
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1215864061259; DSPS: 39941326; Offset : -3053355933
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  971): User[0] Flushing usage stats to disk
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1235864724845; DSPS: 40596708; Offset : -3053363994
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1255865393223; DSPS: 41252090; Offset : -3053367262
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1275866070351; DSPS: 41907472; Offset : -3053360818
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 1295869019040; DSPS: 42562928; Offset : -3053342416
D/AndroidRuntime( 8237): 
D/AndroidRuntime( 8237): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8237): CheckJNI is OFF
D/AndroidRuntime( 8237): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  971): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  971): Killing 5655:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  971): WIN DEATH: Window{1f41bcc5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  971): Focus left window: Window{1f41bcc5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  971): Window went away: Window{1f41bcc5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  971): Skipping PackageSetting{1395f3cb com.example.hello/10317} due to missing metadata
I/ActivityManager(  971):   Force finishing activity ActivityRecord{e06f187 u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  971): Display changed displayId=0
D/DSDPConnection( 1748): Display #0 changed.
W/ActivityManager(  971): Spurious death for ProcessRecord{19b86f9a 5655:com.test.thalitest/u0a316}, curProc for 5655: null
I/[LGHome]EVENT( 1875): [Launcher.java:5203:onStart()]onStart
I/ActivityManager(  971): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/[LGHome]EVENT( 1875): [Launcher.java:776:onResume()]onResume
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/art     ( 1937): Explicit concurrent mark sweep GC freed 22624(1394KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 1.273ms total 102.102ms
I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3587): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/GeofencerStateMachine( 1730): Ignoring removeGeofence because network location is disabled.
I/InputReader(  971): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3587): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3587): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3587): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3587): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3587): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3587): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3587): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3587): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3587): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3587): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3587): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  971): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8270 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1875): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/art     (  971): Explicit concurrent mark sweep GC freed 37583(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/34MB, paused 2.256ms total 211.386ms
I/art     (  971): WaitForGcToComplete blocked for 71.327ms for cause Explicit
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1875): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1875): [Launcher.java:929:onResume()]onResume end
I/Activity( 1875): Activity.onPostResume() called 
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/[LGHome]LGWallpaperInfo( 1875): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1875): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/administrator(  971): Handling package changes for user 0
I/SystemUI[Framework](  971): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
W/PhoneWindowManagerEx(  971): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  971): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  971): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  971): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@c9016e5,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  971): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  971): Focus entered window: Window{cd6b9ac u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/SystemUI[Framework](  971): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  971): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  971): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  971): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  971): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@c9016e5,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  971): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1372): handleShortcutListChanged...
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourcesManager( 8270): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/ResourcesManager( 8270): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/ResourcesManager( 8270): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1372): handleShortcutListChanged...
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1875): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  971): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  971): Got RemoteException sending setActive(false) notification to pid 5655 uid 10316
I/art     (  971): Explicit concurrent mark sweep GC freed 3734(212KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 17.773ms total 243.295ms
I/LGEmail ( 8270): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 8270): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/Timeline(  971): Timeline: Activity_windows_visible id: ActivityRecord{2c224600 u0 com.lge.launcher2/.Launcher t221} time:1297270
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 1875): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1556): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1875): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 8237): Shutting down VM
I/NotificationService(  971): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  971): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  971): Receieved: android.intent.action.PACKAGE_REMOVED
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  971): removeObsoleteFile: deleting file=222_task.xml
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
I/PackageChangeReceiver( 8270): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/ActivityManager(  971): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8297 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/AppUp4:AppBoxCP( 8297): onCreate
W/AppUp4:DB( 8297):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 8297):  setFingerPrint start
I/AppUp4:DB( 8297):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8297):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8297):  SDK version = 0
I/AppUp4:DB( 8297):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8297): AppBoxApplication onCreate()
E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/AppUp4:PreloadHelper( 8297): added Exclude : com.test.thalitest
I/ActivityManager(  971): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8316 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null

```
