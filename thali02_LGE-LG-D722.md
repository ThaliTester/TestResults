#### Test 58135655a1ee273_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
W/BaseAppContext( 5549): Using Auth Proxy for data requests.
--------- beginning of system
W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5609): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5609): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  854): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5609): Observing account changes for notifications
E/Gmail   ( 5609): Error finding the version of the Email provider.....
E/Gmail   ( 5609): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5609): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5609): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5609): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5609): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5609): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5609): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5609): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5609): We do not support migrating this version of the Email provider.
I/Icing   ( 5549): updateResources: need to parse f{com.google.android.gms}
I/Gmail   ( 5609): getAccountsCursor
I/ActivityManager(  854): Killing 5324:com.android.gallery3d/u0a23 (adj 15): empty #11
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/libprocessgroup(  854): failed to open /acct/uid_10023/pid_5324/cgroup.procs: No such file or directory
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
D/AndroidRuntime( 5658): 
D/AndroidRuntime( 5658): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5658): CheckJNI is OFF
I/art     ( 5399): Explicit concurrent mark sweep GC freed 7999(401KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.171ms total 64.114ms
I/ActivityManager(  854): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5681 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
W/InstanceID/Rpc( 5549): Found 10006
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@25a50083 on behalf of 5549
I/Gmail   ( 5609): notifyAccountChanged
I/Gmail   ( 5609): getAccountsCursor
I/art     ( 5549): Background sticky concurrent mark sweep GC freed 14598(1034KB) AllocSpace objects, 9(144KB) LOS objects, 8% free, 13MB/14MB, paused 11.154ms total 79.677ms
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5609): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5609): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/ChimeraCfgMgr( 5549): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5549): Module APK com.google.android.play.games already loaded
I/Gmail   ( 5609): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5609): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@35bb5200 on behalf of 5549
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@1fbe1a39 on behalf of 5549
D/PhoneMonitor( 5681): Register our PhoneStateListener
D/AndroidRuntime( 5658): Calling main entry com.android.commands.am.Am
I/Icing   ( 5549): Internal init done: storage state 0
I/ActivityManager(  854): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PhoneMonitor( 5681): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5681): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5681): [parse] Load xml
V/TelephonyAutoProfiling( 5681): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5681): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 5681): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/ActivityManager(  854): setTaskToReturnTo : TaskRecord{1a6b38c3 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  854): setTaskToReturnTo : TaskRecord{1a6b38c3 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  854): AppWindowTokenEx init.. 
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
D/ContextHelper(  854): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  854): Focus left window: Window{2a5ecce5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5658): Shutting down VM
I/NotificationManager( 5549): com.google.android.gms: cancel(10436) by com.google.android.gms
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
I/Icing   ( 5549): Post-init done
I/Gmail   ( 5609): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SplitWindow(  854): check instance of lgWin Window{256771b1 u0 Starting com.test.thalitest}
I/ActivityManager(  854): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5720 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/ActivityManager(  854): Killing 5346:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10018/pid_5346/cgroup.procs: No such file or directory
I/HotwordDetector( 1937): Closing mic
I/MicrophoneInputStream( 1937): mic_close com.google.android.apps.gsa.speech.audio.u@3124a952
V/AudioRecord( 1937): stop()
D/AudioRecord( 1937): AudioRecord->stop()
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioFlinger(  279): Record stopped OK
V/AudioPolicyManager(  279): stopInput() input 16
V/AudioPolicyService(  279): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  279): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  279): ThreadBase::setParameters() routing=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb3840000
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
I/WindowStateAnimator(  854): Starting window displayed
I/SystemUI[Framework](  854): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1363): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  854): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  854): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  854): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  854): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2aed8ae6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  854): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1363): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1363):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1363): , Keyguard show=false, IME shown=false, Panel expanded=false
,D/BarTransitions( 1363): draw background and invalidate : color = 10000000
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/BarTransitions( 1363): draw background and invalidate : color = e0d0d0d
I/CheckinService( 5549): Checkin interval check for package: unspecified last checkin: 1454597191319 min interval config: 0 actual interval: 4711
V/audio_hw_primary(  279): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  279): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  279): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  279): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  279): disable_audio_route: exit
E/audio_hw_primary(  279): disable_snd_device: enter 144
D/hardware_info(  279): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  279): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  279): stop_input_stream: exit: status(0)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  279): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  279): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  279): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyService(  279): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  279): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  279): setParameters(): io 16, keyvalue hotword_active=0, calling pid 279
V/AudioFlinger(  279): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  279): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  279): in_set_parameters: exit: status(0)
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb3840000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 16
V/AudioPolicyManager(  279): closeInput(16)
V/AudioFlinger(  279): closeInput() 16
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1363): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  854): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1751): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1937): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  279): ThreadBase::exit
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioSystem( 3211): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  279): RecordThread 0xb3840000 exiting
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  279): releaseInput() exit
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioFlinger(  279): removeClient_l() pid 1937, calling pid 279
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
I/CheckinService( 5549): Disabling old GoogleServicesFramework version
V/AudioSystem( 1974): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2673): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  279): releasing 15 from 1937 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
I/HotwordRecognitionRnr( 1937): Stopping hotword detection.
I/HotwordRecognitionRnr( 1937): Hotword detection finished
D/ContextHelper( 5720): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/art     ( 5549): Background partial concurrent mark sweep GC freed 20948(1397KB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 13MB/21MB, paused 3.834ms total 142.983ms
I/CheckinService( 5549): Checking schedule, now: 1454597196284 next: 1454597221284
I/CheckinService( 5549): active receiver: disabled
I/WebViewFactory( 5720): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/ActivityManager(  854): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5744 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/LibraryLoader( 5720): Time to load native libraries: 2 ms (timestamps 4257-4259)
I/LibraryLoader( 5720): Expected native library version number "",actual native library version number ""
W/ResourcesManager( 5744): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/WebViewChromiumFactoryProvider( 5720): Binding Chromium to main looper Looper (main, tid 1) {123e477a}
I/LibraryLoader( 5720): Expected native library version number "",actual native library version number ""
I/chromium( 5720): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5720): Initializing chromium process, singleProcess=true
W/art     ( 5720): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5720): ApplicationContext is null in ApplicationStatus
W/chromium( 5720): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5720): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5720): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5720): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5720): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5720): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5720): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5720): Remote Branch: 
I/Adreno-EGL( 5720): Local Patches: 
I/Adreno-EGL( 5720): Reconstruct Branch: 
,V/AudioPolicyService(  279): registerClient() client 0xb551ce60, uid 10316
,D/BluetoothManagerService(  854): Message: 20
,D/BluetoothManagerService(  854): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28ac54a3:true
D/BluetoothAdapterService(182018374)( 1974): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e8f39cc
I/Babel_SMS( 5744): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5744): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5744): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5744): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5744): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5744): MmsConfig.loadFromResources
E/Babel_SMS( 5744): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5744): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/art     ( 5720): Attempt to remove local handle scope entry from IRT, ignoring
,D/SensorManager( 5744): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5744): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5744): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5744): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5744): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5744): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5744): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5744): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5744): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5744): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5744): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5744): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5744): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5744): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5744): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5744): found sensor: Motion Accel, handle=46
,W/AwContents( 5720): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 5744): CheckpointMarkThreadRoots callback created = 0xb002d820
,D/SystemWebViewEngine( 5720): CordovaWebView is running on device made by: LGE
W/art     ( 5720): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5720): Attempt to remove local handle scope entry from IRT, ignoring
,W/Settings( 5744): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5744): startup - clean
I/Babel   ( 5744): deleted: false for 0
,I/art     ( 5744): CheckpointMarkThreadRoots callback created = 0xb002d800
I/Activity( 5720): Activity.onPostResume() called 
,D/OpenGLRenderer( 5720): Render dirty regions requested: true
I/OpenGLRenderer( 5720): Initialized EGL, version 1.4
D/OpenGLRenderer( 5720): Enabling debug mode 0
,D/Atlas   ( 5720): Validating map...
,D/SplitWindow(  854): check instance of lgWin Window{15bd0de8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5720): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  854): Focus entered window: Window{15bd0de8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  854): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  854): Displayed com.test.thalitest/.MainActivity: +1s236ms
I/Timeline(  854): Timeline: Activity_windows_visible id: ActivityRecord{14c4c540 u0 com.test.thalitest/.MainActivity t222} time:84921
,D/InitAlarmsService( 3799): Clearing and rescheduling alarms.
,D/CalendarProvider2( 5476): Scheduling check of next Alarm
I/Timeline( 5720): Timeline: Activity_idle id: android.os.BinderProxy@1b58bc91 time:84951
D/CalendarProvider2( 5476): SCHEDULE_ALARM_REMOVE
,W/AudioCapabilities( 5744): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5744): Unsupported mime audio/adpcm
W/AudioCapabilities( 5744): Unsupported mime audio/g726
,W/AudioCapabilities( 5744): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5744): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5744): Unsupported mime video/mjpg
W/VideoCapabilities( 5744): Unsupported mime video/theora
,W/AudioCapabilities( 5744): Unsupported mime audio/evrc
,W/AudioCapabilities( 5744): Unsupported mime audio/qcelp
W/VideoCapabilities( 5744): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5744): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5744): Unsupported mime audio/qcelp
W/AudioCapabilities( 5744): Unsupported mime audio/evrc
W/VideoCapabilities( 5744): Unsupported mime video/mp4v-esdp
,W/BindingManager( 5720): Cannot call determinedVisibility() - never saw a connection for the pid: 5720
I/Icing   ( 5549): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/VideoCapabilities( 5744): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 5744): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5744): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5744): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5744): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5744): onServiceConnected
W/Babel   ( 5744): Attempted to change video mute state without an active call.
,D/Icing   ( 5549): Loaded CLD2 Version V2.0 - 20141016
,W/art     ( 5744): Suspending all threads took: 7.964ms
D/JsMessageQueue( 5720): Set native->JS mode to OnlineEventsBridgeMode
,I/NotificationManager( 5744): com.google.android.talk: cancel(10436) by com.google.android.talk
I/Icing   ( 5549): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/ResourcesManager( 5744): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5744): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 5744): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  854): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5810 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5131): getMode name:com.lge.qremote
,I/AudioManager( 5131): getMode name:com.lge.qremote
,I/AudioManager( 5131): getMode name:com.lge.qremote
,W/System  ( 5744): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5744): Installed default security provider GmsCore_OpenSSL
,I/AudioManager( 5131): getMode name:com.lge.qremote
,I/AudioManager( 5131): getMode name:com.lge.qremote
E/MDM     ( 1733): [83] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5549): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/UEI.SmartControl( 5810): Quickset Services start...
,I/UEI.SmartControl( 5810): Manufacture = LGE
D/UEI.SmartControl( 5810): File observer start...
E/UEI.SmartControl( 5810): IR Port is disabled: false
D/UEI.SmartControl( 5810): Starting file observer...
D/UEI.SmartControl( 5810): Extracting JNI libs...
D/UEI.SmartControl( 5810): --- this system supports 32-bit or 64-bit only
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
I/AudioManager( 5131): getMode name:com.lge.qremote
I/NotificationManager( 5744): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  854): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5836 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-67 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:37.886 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/AppUp4:AppBoxCP( 5836): onCreate
,W/AppUp4:DB( 5836):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5836):  setFingerPrint start
I/AppUp4:DB( 5836):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5836):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5836):  SDK version = 0
I/AppUp4:DB( 5836):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5836): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5836): onReceive
I/AppUp4:CustModeStarterReceiver( 5836): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5836): Context : android.app.ReceiverRestrictedContext@20e319c
D/AppUp4:CustFacade( 5836): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5836): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5836): begin check event
I/AppUp4:CustModeStarterReceiver( 5836): Event For Nothing, skip.
I/ActivityManager(  854): Killing 3799:com.android.calendar/u0a13 (adj 15): empty #11
D/jxcore_app_log( 5720): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426127360
,W/libprocessgroup(  854): failed to open /acct/uid_10013/pid_3799/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5476): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5476): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/UEI.SmartControl( 5810): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5810): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5810): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/chromium( 5720): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  854): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5857 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/UEI.SmartControl( 5810): --- Selecting new region: 2
I/UEI.SmartControl( 5810): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5810): Platform has CIR...
I/ActivityManager(  854): Killing 5365:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,D/UEI.SmartControl( 5810): NO CIR support, need to check package...
I/UEI.SmartControl( 5810): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5810): QS Service created
,I/art     ( 5720): CheckpointMarkThreadRoots callback created = 0x9c5b6450
,W/libprocessgroup(  854): failed to open /acct/uid_10069/pid_5365/cgroup.procs: No such file or directory
,I/art     ( 5720): CheckpointMarkThreadRoots callback created = 0x9c5b6420
,E/UEI.SmartControl( 5810): QS start get config
W/ResourcesManager( 5857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5857): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5857): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5810): Loading JNI Libs...
,D/UEI.SmartControl( 5810):  configuring local db...
I/ActivityManager(  854): Process com.google.android.apps.docs (pid 5416) has died
,I/AppConfig( 5857): Total System Memory = 906309632
I/GalleryUtils( 5857): Application Heap = 96 MB
I/AppConfig( 5857): App Tier : NOT_DEF
,D/SystemHelper( 5857): region [EU], country [EU], operator [OPEN], sub-operator []
D/UEI.SmartControl( 5810):  ---- Has DB8: true
,D/UEI.SmartControl( 5810): QS start statue = true Error code = 0
D/UEI.SmartControl( 5810): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5810): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5810): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5810): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 5810): IrrcClient ++ 
D/irrcClient( 5810): getIrrcService ++ 
D/irrcClient( 5810): getIrrcService -- 
D/irrcClient( 5810): IrrcClient -- 
W/irrc_jni( 5810): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5810): Services init done
I/UEI.SmartControl( 5810): Device manager: loading config....
D/UEI.SmartControl( 5810): Config is loaded...
,I/ActivityManager(  854): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5879 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/UEI.SmartControl( 5810): QS Service init finished
D/UEI.SmartControl( 5810): QS Service version name: 0.1.73
,D/UEI.SmartControl( 5810): QS Service version code: 1073
D/UEI.SmartControl( 5810): Service requested: Control
D/UEI.SmartControl( 5810): Internal service binding...
D/UEI.SmartControl( 5810): -----IControl: 11
,D/UEI.SmartControl( 5810): Caller: com.lge.qremote
D/UEI.SmartControl( 5810):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 5810): ------------ IControl registerCallback...
I/UEI.SmartControl( 5810): Notify AllClients services are ready: 0
I/UEI.SmartControl( 5810): Registering callback...
D/UEI.SmartControl( 5810): -----IControl: 19
D/UEI.SmartControl( 5810): Caller: com.lge.qremote
,I/UEI.SmartControl( 5810): Registering Services Ready callback...
I/UEI.SmartControl( 5810): Notify client services are ready...
D/UEI.SmartControl( 5810): -----IControl: 8
,D/UEI.SmartControl( 5810): Caller: com.lge.qremote
I/ActivityManager(  854): Killing 5157:com.lge.bnr/1000 (adj 15): empty #11
W/ResourcesManager( 5879): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5879): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5879): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 5879): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5879): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  854): Killing 5382:com.lge.eula/1000 (adj 15): empty #12
,I/art     (  854): Explicit concurrent mark sweep GC freed 23806(1138KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.683ms total 254.731ms
,W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_5157/cgroup.procs: No such file or directory
,W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_5382/cgroup.procs: No such file or directory
I/SystemConfig( 5879): BUILD Country: EU
I/SystemConfig( 5879): BUILD Operator: OPEN
,I/ActivityManager(  854): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5898 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 5453:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10086/pid_5453/cgroup.procs: No such file or directory
,I/SystemConfig( 5879): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5879): existFile = false
I/SystemConfig( 5879): canReadFile = false
I/SystemConfig( 5879): systemFeature RCS result false
D/SystemConfig( 5879): refreshRcsSupport() :false
I/LockScreenSettings( 5898): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5898): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 5898): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 5898): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5898): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5898): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  854): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5915 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  854): Killing 5506:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10036/pid_5506/cgroup.procs: No such file or directory
,W/ResourcesManager( 5915): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  854): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5940 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 5609:com.google.android.gm/u0a53 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 110 ms] updated apps [took 110 ms] 
,W/libprocessgroup(  854): failed to open /acct/uid_10053/pid_5609/cgroup.procs: No such file or directory
W/jxcore-log( 5720): Initializing JXcore engine
,W/jxcore-log( 5720): JXcore engine is ready
W/Thread-692( 5856): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5589]" dev="sockfs" ino=5589 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-692( 5856): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-692( 5856): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6390]" dev="sockfs" ino=6390 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-692( 5856): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-692( 5856): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-692( 5856): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26510]" dev="sockfs" ino=26510 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5720): Starting JXcore engine
,D/Finsky  ( 5940): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/jxcore-log( 5720): Platform android
W/jxcore-log( 5720): 
,W/jxcore-log( 5720): Process ARCH arm
W/jxcore-log( 5720): 
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/Finsky  ( 5940): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 5940): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5940): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 5940): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  854): Process com.lge.qremote (pid 5131) has died
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@3104b87e on behalf of 5940
D/Ads     ( 5940): Skipping gmscore version check
D/Finsky  ( 5940): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5940): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5940): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5549): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 5940): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  854): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5991 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 5549): Null package name or gms related package.  Ignoreing.
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 24.012ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.790ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 313us total 22.069ms
,I/Icing   ( 5549): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 5991): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/BluetoothManagerService(  854): Message: 20
D/BluetoothManagerService(  854): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22560724:true
D/BluetoothAdapterService(182018374)( 1974): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e8f39cc
,D/BluetoothAdapterService(182018374)( 1974): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e8f39cc
V/LGMDMManager( 5991): Create singleton instance
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:40.896 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/AudioManager( 5991): getMode name:com.lge.qremote
,I/jxcore-log( 5720): JXcore Cordova bridge is ready!
I/jxcore-log( 5720): 
W/jxcore-log( 5720): JXcore engine is started
D/UEI.SmartControl( 5810): -----IControl: 11
,D/UEI.SmartControl( 5810): Caller: com.lge.qremote
D/UEI.SmartControl( 5810): ------------ IControl registerCallback...
I/UEI.SmartControl( 5810): Registering callback...
D/UEI.SmartControl( 5810): -----IControl: 19
D/UEI.SmartControl( 5810): Caller: com.lge.qremote
I/UEI.SmartControl( 5810): Registering Services Ready callback...
I/UEI.SmartControl( 5810): Notify client services are ready...
I/AudioManager( 5991): getMode name:com.lge.qremote
D/UEI.SmartControl( 5810): -----IControl: 8
,D/UEI.SmartControl( 5810): Caller: com.lge.qremote
V/SetupWizard( 5681): Connected to Gservices successfully
,I/ActivityManager(  854): Killing 5476:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10014/pid_5476/cgroup.procs: No such file or directory
,V/AlarmManager(  854): RTC_WAKEUP set : Alarm{d4c2645 type 0 when 1454597201126 com.google.android.googlequicksearchbox} when 1454597201126
I/jxcore-log( 5720): Toggling radios to true
I/jxcore-log( 5720): 
,D/BluetoothAdapter( 5720): enable(): BT is already enabled..!
D/WifiServiceImplEx(  854): setWifiEnabled: true pid=5720, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  854): setWifiEnabled: true pid=5720, uid=10316
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiServiceImplEx(  854): disconnect pid=5720, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  854): reconnect pid=5720, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5720): Radios toggled
I/jxcore-log( 5720): 
I/jxcore-log( 5720): My device name is: LGE-LG-D722
I/jxcore-log( 5720): 
D/LocationInitializer( 5549): Restart initialization of location
,E/MDM     ( 1733): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/wpa_supplicant( 2803): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2803): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  854): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1803): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  854): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  854): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  854): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  275): Clearing all IP addresses on wlan0
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
I/ActivityManager(  854): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6028 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/NativeCrypto( 1733): Read error: ssl=0xaaee1600: I/O error during system call, Connection timed out
,D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/WifiStateMachine(  854): Start Disconnecting Watchdog 1
,D/WifiHS20(  854): hidePasspointNotification off =false
I/wpa_supplicant( 2803): wlan0: CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService(  854): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  275): Clearing all IP addresses on wlan0
D/ConnectivityService(  854): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  854): ignoring duplicate network state non-change
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  854): hidePasspointNotification off =false
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  854): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20(  854): hidePasspointNotification off =false
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:41.345 DNS addrs= 0.0.0.0, 0.0.0.0, 
V/NativeCrypto( 1733): SSL shutdown failed: ssl=0xaaee1600: I/O error during system call, Broken pipe
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:41.346 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:41.347 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/InputReader(  854): Reconfiguring input devices.  changes=0x00000010
,D/ConnectivityService(  854): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,D/WifiNetworkAgent(  854): NetworkAgent: NetworkAgent channel lost
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:41.409 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:41.419 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  854): Default network via Wi-Fi disconnect. stop DSQN
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): ValidatedState{ when=-15ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): DefaultState{ when=-21ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): Forcing reevaluation
D/DSQN    (  854): disableDataServiceNotify
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/DSQN    (  854): stop dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
I/[SystemUI]QPairHandler( 1363): onReceive = android.intent.action.PACKAGE_CHANGED
D/administrator(  854): Handling package changes for user 0
D/ConnectivityService(  854): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]QSlideListController( 1363): onReceive = android.intent.action.PACKAGE_CHANGED
,D/ConnectivityService(  854): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/Nat464Xlat(  854): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1363): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): Disconnected - quitting
,D/DhcpStateMachine(  854): StoppedState
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/DhcpStateMachine(  854): StoppedState{ when=-164ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
W/[SystemUI]QSlideLoader( 1363): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
D/CSLegacyTypeTracker(  854): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
D/CSLegacyTypeTracker(  854): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1363): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  854): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  854): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,V/NetworkPolicy(  854): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  854): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  854): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  854):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1751): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
V/NetworkPolicy(  854): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1839): |CORE| No family connected
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/QCNEJ   ( 1839): |CORE| No family connected
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = false, mWifiLevel = 0
D/NetworkManagementService(  854): Removing idletimer
,W/Settings(  854): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = -1
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
D/TelephonyIcons( 1363): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1363): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1363): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1363): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/NotificationService(  854): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  854): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  854): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  854): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/WifiHS20(  854): hidePasspointNotification off =false
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateSCANNING
D/Tethering(  854): MasterInitialState.processMessage what=3
D/Tethering(  854): MasterInitialState.processMessage what=3
V/BackupManagerService(  854): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  854): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@30342005
,W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Icing   ( 5549): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5549): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/Gmail   ( 6028): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager(  854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,W/GAV2    ( 6028): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  854): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6028): Observing account changes for notifications
W/ResourceType(  854): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/Gmail   ( 6028): getAccountsCursor
E/Gmail   ( 6028): Error finding the version of the Email provider.....
E/Gmail   ( 6028): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6028): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6028): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6028): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6028): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6028): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6028): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6028): We do not support migrating this version of the Email provider.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  854): Killing 5836:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10011/pid_5836/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{39bfb247 type 2 when 89945 com.android.providers.calendar} when 89945
I/art     ( 1733): Explicit concurrent mark sweep GC freed 30910(1890KB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 13MB/22MB, paused 1.365ms total 100.502ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2803): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/ActivityManager(  854): Process com.android.contacts (pid 5879) has died
,D/LocationProviderProxy(  854): applying state to connected service
I/Gmail   ( 6028): notifyAccountChanged
I/Gmail   ( 6028): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6028): getAccountsCursor
,I/Gmail   ( 6028): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/LocSvc_java(  854): onReceive
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:42.5 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = false, mWifiLevel = 0
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:42.507 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2803): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateASSOCIATED
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
I/Gmail   ( 6028): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6028): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/wpa_supplicant( 2803): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2803): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:42.564 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:42.565 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = false, mWifiLevel = 0
I/WifiServiceExtension(  854): setVHTCapabilityType  : false
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
,I/WifiServerServiceExt(  854): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  854): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  854): setSecurityType  : 2
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:42.592 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:42.593 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
,D/ConnectivityService(  854): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  854): Got NetworkAgent Messenger
D/ConnectivityService(  854): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  854): NetworkAgent connected
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
E/WifiConfigStore(  854): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  854): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  275): Setting iface cfg
,E/WifiStateMachine(  854): Start Dhcp Watchdog 2
D/DhcpStateMachine(  854): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  854): WaitBeforeStartState
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  854): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  854): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  854): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  854): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@38b70148 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@38b70148 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  854): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  854): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  854): DHCP Start wake lock is acquired.
D/CommandListener(  275): Setting iface cfg
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     (  854): Explicit concurrent mark sweep GC freed 54217(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.230ms total 204.911ms
D/CommandListener(  275): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  854): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateCOMPLETED
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WifiServerServiceExt(  854): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  854): setSupplicantStateCOMPLETED
D/ConnectivityService(  854): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  854): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  854): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  854): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  854): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  854): ignoring duplicate network state non-change
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:42.775 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
D/ConnectivityService(  854): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  854): Adding iface wlan0 to network 101
E/WifiStateMachine(  854): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = false, mWifiLevel = 0
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20(  854): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,E/ConnectivityService(  854): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  854): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  854): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  275): netlink response contains error (File exists)
D/ConnectivityService(  854): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  854): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  854): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  854): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  854): [PASSPOINT] passpointNotification: hs20AP list is checked
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:42.842 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/Nat464Xlat(  854): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  854): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/ConnectivityService(  854): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService(  854): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  854):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  854):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  854):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  854): currentScore = 0, newScore = 20
D/ConnectivityService(  854):    accepting network in place of null,
D/ConnectivityService(  854): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:42.852 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WIFI    (  854): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  854):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1751): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  854): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  854): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  854): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  854): [e] list.add(nai) empty : false size: 1
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:42.856 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  854): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  854): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  854): validation of new default Network = false
D/ConnectivityService(  854): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  854): enableDataServiceNotify 
D/DSQN    (  854): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only w,ifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): [LWD] wait 500ms before dns check
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  854): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1363): CM callback handler got msg 524290
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
I/[SystemUI]StatusBar.NetworkController( 1363): mWifiConnected = true, mWifiLevel = 2
,I/DSQN    ( 6079): DSQN samuel.seo ver 141203
E/DSQN    ( 6079): DSQN sock connect success to lgdatalistenerd
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/DSQN    ( 6079): created command queue thread
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/DSQN    ( 6079): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6079): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1363): Remote
I/ActivityManager(  854): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6082 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/NetworkPolicy(  854): [LG_RESTRICTED] checkMobilePolicy_type()
D/DhcpStateMachine(  854): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  854): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  854): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6092): version 5.5.6 starting
E/dhcpcd  ( 6092): get_duid: Read-only file system
,D/TelephonyIcons( 1363): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1363): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/dhcpcd  ( 6092): wlan0: rebinding lease of 192.168.1.134
,I/ActivityManager(  854): Process com.google.android.talk (pid 5744) has died
,W/ResourcesManager( 6082): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6082): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6082): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6082): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@35576d0f, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@20e319c, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2dd0d7a5, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@123e477a, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@a7cb2b, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@359acb88, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@301c4921, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@ad96146, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1c55ef07, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@25d51834, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3553565d, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1ba4bd2, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@35d874a3, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@39c583a0, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@34f3fb59, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@224d531e, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1173b7ff, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3e8f39cc, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@65ff415, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1077832a, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@955d51b, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@e5c26b8, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1b58bc91, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1762a7f6, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2272a7f7, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3a08f664, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@263b90cd, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@39094d82, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@131fcc93, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@219114d0, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@27fd6cc9, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2a82bfce, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@17709eef, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@273aadfc, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@21e70c85, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@90f0ada, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2f523b0b, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2982ade8, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2710ec01, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@13e2faa6, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@22677ce7, lg_preferences_rece,nt_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2fc8c09
D/GeneralPreferenceUtils( 6082): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,D/Config  ( 6082): [init]
I/Config  ( 6082): LGCalendar ver.4.40.17
I/Config  ( 6082): start check model
I/Config  ( 6082): start check native_ca
I/Config  ( 6082): Config Operator=OPEN, Country=EU
D/Config  ( 6082): [setDefaultValuesToPref]
D/Config  ( 6082): [parseProfiles]
D/ProfilesParser( 6082): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6082): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6082): [updateProfiletoCountryInfo]
D/GeneralPreference( 6082): [checkAndMigrateOldPreference]
,D/AlertReceiver( 6082): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/Gmail   ( 6028): getAccountsCursor
,I/InitNotificationRingtoneService( 6082): Start InitializeAlertRingtoneService.onHandleIntent
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AlertUtils( 6082): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 6082): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): [LWD] DNSResolver start dns
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  854): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): [LWD] DNSResolver end dns
I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): Checking http://clients3.google.com/generate_204 on "NG700"
I/AlertUtils( 6082): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6082): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6082): set default noti to content://media/internal/audio/media/38
,D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/InitNotificationRingtoneService( 6082): End InitializeAlertRingtoneService.onHandleIntent
I/DSQN    ( 6079): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6079): restart monitoring
,D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6079): dsqn report finish
D/DSQN    (  854): DSQM DsqnNotification wlan0  1
D/DSQN    (  854): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 14:46:43 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454597203463], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454597203441]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  854): Validated
D/ConnectivityService(  854): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  854): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  854):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  854):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/WifiDataContinuityService(  854): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  854): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  854): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1363): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1751): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/WifiServerServiceExt(  854): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  854): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  854):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1363): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1363): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/HolidayIntentService( 6082): onHandleIntent
,D/HolidayDataLoader( 6082): readJsonAsset : holiday.json
E/AgendaWidgetManager( 6082): [updateWidgets] 
D/AlertService( 6082): 0 Action = android.intent.action.PROVIDER_CHANGED
D/MonthWidgetProvider( 6082): [onReceive]
D/CalendarWidgetProvider( 6082): [onReceive]
D/CalendarWidgetProvider( 6082): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,D/CalendarTypeController( 6082): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6082): [onReceive]
D/CalendarWidgetProvider( 6082): [onReceive]
D/CalendarWidgetProvider( 6082): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
I/AudioManager( 5991): getMode name:com.lge.qremote
D/CalendarTypeController( 6082): [onCreate] mContext.getPackageName() = com.android.calendar
,I/AudioManager( 5991): getMode name:com.lge.qremote
I/AudioManager( 5991): getMode name:com.lge.qremote
,I/ActivityManager(  854): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6125 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/HolidayIntentService( 6082): onHandleIntent:holiday data empty
,D/UEI.SmartControl( 5810): Internal timer expired: 1
,W/ResourcesManager( 6125): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6125): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6125): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6125): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6125): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  854): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/IndexDatabaseHelper( 6125): Using schema version: 115
I/IndexDatabaseHelper( 6125): Index is fine
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{3c491ce9 type 2 when 91879 com.google.android.gms} when 91879
,V/WiFiOffLoadBroadcast( 6125): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6125): MCCMNC not supported: null
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  854): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  854): identical MTU - not setting
D/Nat464Xlat(  854): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  854): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  854): enableDataServiceNotify 
D/DSQN    (  854): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1363): CM callback handler got msg 524295
D/DSQN    (  854): dsqn is running restart
,I/ActivityManager(  854): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6152 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/DSQN    ( 6159): DSQN samuel.seo ver 141203
,E/DSQN    ( 6159): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6159): created command queue thread
I/DSQN    ( 6159): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6159): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:44.208 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/PCSuite ( 6152): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6152): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6152): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/dhcpcd  ( 6092): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,V/WiFiOffLoadBroadcast( 6125): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6125): MCCMNC not supported: null
I/PCSuite ( 6152): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6152): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6152): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6125): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/dhcpcd  ( 6092): wlan0: leased 192.168.1.134 for 86400 seconds
D/WiFiOffLoadBroadcast( 6125): MCCMNC not supported: null
I/PCSuite ( 6152): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6152): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6152): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  854): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6185 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  854): Killing 5857:com.android.gallery3d/u0a23 (adj 15): empty #11
D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  854): failed to open /acct/uid_10023/pid_5857/cgroup.procs: No such file or directory
,D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  854): onReceive
D/LocSvc_java(  854): got connectivity action
D/LocSvc_java(  854): broadcast - no network connections
D/LocSvc_java(  854): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  854): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java(  854): onReceive
D/LocSvc_java(  854): got connectivity action
D/LocSvc_java(  854): broadcast - no network connections
D/LocSvc_java(  854): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  854): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  854): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  854): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  854): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  854): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  854): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  854): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  854): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  854): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  854): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  854): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 6185): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  854): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  854): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  854): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  854): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  854): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  854): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  854): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  854): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  854): RunningState
,I/Babel_SMS( 6185): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6185): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6185): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6185): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6185): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6185): MmsConfig.loadFromResources
E/Babel_SMS( 6185): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6185): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6185): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6185): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6185): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6185): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6185): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6185): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6185): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6185): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6185): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6185): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6185): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6185): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6185): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6185): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6185): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6185): found sensor: Motion Accel, handle=46
,W/Settings( 6185): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6185): startup - clean
,I/art     ( 6185): CheckpointMarkThreadRoots callback created = 0xaaf41630
,I/Babel   ( 6185): deleted: false for 0
,I/art     ( 6185): CheckpointMarkThreadRoots callback created = 0xaaf41610
,W/AudioCapabilities( 6185): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6185): Unsupported mime audio/adpcm
W/AudioCapabilities( 6185): Unsupported mime audio/g726
W/AudioCapabilities( 6185): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6185): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6185): Unsupported mime video/mjpg
I/ActivityManager(  854): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6233 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/VideoCapabilities( 6185): Unsupported mime video/theora
,W/AudioCapabilities( 6185): Unsupported mime audio/evrc
,W/AudioCapabilities( 6185): Unsupported mime audio/qcelp
W/VideoCapabilities( 6185): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6185): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6185): Unsupported mime audio/qcelp
W/AudioCapabilities( 6185): Unsupported mime audio/evrc
I/ActivityManager(  854): Process com.google.android.gm (pid 6028) has died
,V/AlarmManager(  854): RTC_WAKEUP set : Alarm{3e6596a0 type 0 when 1454597205411 com.android.vending} when 1454597205411
D/Finsky  ( 5940): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/VideoCapabilities( 6185): Unsupported mime video/mp4v-esdp
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VideoCapabilities( 6185): Unsupported profile 4 for video/mp4v-es
,I/AppUp4:AppBoxCP( 6233): onCreate
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/AppUp4:DB( 6233):  [AppBoxDatabaseHelper] construct
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AppUp4:DB( 6233):  setFingerPrint start
I/AppUp4:DB( 6233):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
W/VideoCapabilities( 6185): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6185): Unrecognized profile 2130706433 for video/avc
I/NotificationManager(  854): android: cancelAsUser(2) by android
W/VideoCapabilities( 6185): Unrecognized profile 2130706433 for video/avc
I/AppUp4:DB( 6233):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6233):  SDK version = 0
I/AppUp4:DB( 6233):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6233): AppBoxApplication onCreate()
,W/VideoCapabilities( 6185): Unrecognized profile 2130706433 for video/avc
I/AppUp4:CustModeStarterReceiver( 6233): onReceive
I/AppUp4:CustModeStarterReceiver( 6233): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6233): Context : android.app.ReceiverRestrictedContext@20e319c
D/AppUp4:CustFacade( 6233): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6233): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6233): begin check event
I/AppUp4:CustModeStarterReceiver( 6233): Event For Nothing, skip.
I/ActivityManager(  854): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6256 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 15:46:45.669 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/art     ( 6185): Suspending all threads took: 6.837ms
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/vclib   ( 6185): onServiceConnected
W/Babel   ( 6185): Attempted to change video mute state without an active call.
I/NotificationManager( 6185): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 6256): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6256): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6256): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6185): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6185): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/WifiInternetCheck(  854): Single check msg out of sync, ignoring.
,D/libc-netbsd( 5940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
V/JNIHelp ( 6185): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1363): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  854): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 5940): propertyValue:false
D/libc-netbsd( 5940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocSvc_java(  854): onReceive
D/LocSvc_java(  854): got connectivity action
D/LocSvc_java(  854): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  854): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  854): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  854): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  854): ignore wifi update if we are not in OPENING or CLOSING
I/DSQN    ( 6159): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 6159): restart monitoring
I/DSQN    ( 6159): dsqn report finish
D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  854): DSQM DsqnNotification wlan0  1
D/DSQN    (  854): start to monitor internet connection
D/GpsLocationProvider(  854): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppConfig( 6256): Total System Memory = 906309632
I/GalleryUtils( 6256): Application Heap = 96 MB
,I/AppConfig( 6256): App Tier : NOT_DEF
D/SystemHelper( 6256): region [EU], country [EU], operator [OPEN], sub-operator []
,W/System  ( 6185): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6185): Installed default security provider GmsCore_OpenSSL
D/libc-netbsd( 5940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  854): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6280 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/NotificationManager( 6185): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 6280): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6280): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6280): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6280): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6280): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  854): android: cancelAsUser(2) by android
I/ActivityManager(  854): Killing 5898:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/SystemConfig( 6280): BUILD Country: EU
I/SystemConfig( 6280): BUILD Operator: OPEN
,I/qtaguid ( 5940): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5940): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5940): untagSocket(41) failed with errno -22
D/Finsky  ( 5940): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,W/libprocessgroup(  854): failed to open /acct/uid_10069/pid_5898/cgroup.procs: No such file or directory
,I/SystemConfig( 6280): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 6280): existFile = false
I/SystemConfig( 6280): canReadFile = false
I/SystemConfig( 6280): systemFeature RCS result false
,D/SystemConfig( 6280): refreshRcsSupport() :false
I/NotificationManager( 1937): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ActivityManager(  854): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6302 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  854): Killing 5915:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10086/pid_5915/cgroup.procs: No such file or directory
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  854): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6320 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/NotificationManager(  854): android: cancelAsUser(2) by android
,I/LockScreenSettings( 6302): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,W/ResourcesManager( 6320): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6320): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LockScreenSettings( 6302): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6302): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6302): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6302): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6302): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  854): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6338 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  854): Killing 5681:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 333us total 24.209ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 20.955ms
,I/qtaguid ( 5940): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5940): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5940): untagSocket(41) failed with errno -22
I/MultiDex( 6320): VM with version 2.1.0 has multidex support
I/MultiDex( 6320): install
I/MultiDex( 6320): VM has multidex support, MultiDex support library is disabled.
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 26.937ms
I/ActivityManager(  854): Process com.android.settings (pid 6125) has died
,W/libprocessgroup(  854): failed to open /acct/uid_10038/pid_5681/cgroup.procs: No such file or directory
W/ResourcesManager( 6338): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/JNIHelp ( 6320): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6320): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6320): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1838e2c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6320): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6320): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6320): com.google.android.gms: cancel(39789) by com.google.android.gms
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 94895836948; DSPS: 3208054; Offset : -3015788837
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/ChimeraCfgMgr( 6320): Reading stored module config
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out(  854): propertyValue:false
,D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  854): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  854): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  854): propertyValue:false
,V/WifiInternetCheck(  854): isHttpConnectionAvailable - We got a valid response : 204
,I/art     ( 5940): CheckpointMarkThreadRoots callback created = 0xaafe30b0
,I/ActivityManager(  854): Process com.lge.sync (pid 6152) has died
I/art     ( 5940): CheckpointMarkThreadRoots callback created = 0xaafe3080
,D/NativeLibraryUtils( 6320): Install completed successfully. count=14 extracted=0
I/art     (  854): Explicit concurrent mark sweep GC freed 52423(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.788ms total 235.549ms
,D/ChimeraCfgMgr( 6320): Loading module com.google.android.gms.car from APK com.google.android.gms
D/CAR.SERVICE( 6320): Connecting to CarCallService...
,I/art     ( 6320): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6320): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/CAR.SERVICE( 6320): com.google.android.projection.gearhead isn't installed.
,D/PackageBroadcastService( 5549): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 73 ms] updated apps [took 73 ms] 
,I/ActivityManager(  854): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6376 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/PackageBroadcastService( 5549): Null package name or gms related package.  Ignoreing.
,D/CAR.TEL.Service( 6320): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6320): Creating a new PhoneAdapter instance
,W/ActivityManager(  854): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6320): setListener: com.google.android.gms.car.dn@3e321aeb
W/ActivityManager(  854): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6320): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6320): Starting CarCallService with initial phone null
,I/NotificationManager( 6320): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Icing   ( 5549): updateResources: need to parse f{com.google.android.gms}
D/CAR.SERVICE( 6320): Package validated; name: com.android.vending
,I/NotificationManager( 5940): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5940): [1] GearheadStateMonitor.access$100: mIsProjecting:false
W/ResourcesManager( 6376): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6376): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6376): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6376): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6376): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ActivityManager(  854): Process com.lge.qremote (pid 5991) has died
D/UEI.SmartControl( 5810): Service.onUnbind: IControl
,D/UEI.SmartControl( 5810): Service.onDestroy
D/UEI.SmartControl( 5810): Shutdown IRRCPlayer... 
W/irrc_jni( 5810): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5810): ~IrrcClient ++ 
D/irrcClient( 5810): ~IrrcClient -- 
,W/irrc_jni( 5810): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5810): Blaster closed
D/UEI.SmartControl( 5810): Blaster closed
D/UEI.SmartControl( 5810): Shut down QS...
D/UEI.SmartControl( 5810): Stopped file observer...
I/UEI.SmartControl( 5810): QS lib stop result = true
D/UEI.SmartControl( 5810): QS shutdown complete
I/IndexDatabaseHelper( 6376): Using schema version: 115
,I/IndexDatabaseHelper( 6376): Index is fine
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  854): android: cancelAsUser(2) by android
V/WiFiOffLoadBroadcast( 6376): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6376): MCCMNC not supported: null
,I/qtaguid ( 5940): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5940): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5940): untagSocket(41) failed with errno -22
,I/ActivityManager(  854): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6405 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6405): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6405): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6405): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  854): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6425 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/AlertService( 6082): Beginning updateAlertNotification
,W/ResourcesManager( 5940): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5940): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6425): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5940): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  854): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6442 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  854): Process com.android.gallery3d (pid 6256) has died
,D/Finsky  ( 5940): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  854): RTC_WAKEUP set : Alarm{108a8d45 type 0 when 1454597208770 com.android.vending} when 1454597208770
,W/ResourcesManager( 6442): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  854): Message: 20
,D/BluetoothManagerService(  854): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25cea866:true
D/WearableService( 1733): callingUid 10006, callindPid: 1733
D/DeviceConnectionService( 1733): client connected with version: 8296000
D/BluetoothAdapterService(182018374)( 1974): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e8f39cc
,D/BluetoothAdapterService(182018374)( 1974): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e8f39cc
D/Finsky  ( 5940): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5940): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/WiFiOffLoadBroadcast( 6376): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6376): MCCMNC not supported: null
D/CalendarProvider2( 6442): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@c1ac5e9
I/Icing   ( 5549): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  854): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6463 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/CalendarProvider2( 6442): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6442): Created com.android.providers.calendar.CalendarAlarmManager@123e477a(com.android.providers.calendar.CalendarProvider2@c1ac5e9)
D/AlertService( 6082): No fired or scheduled alerts
I/NotificationManager( 6082): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(1) by com.android.calendar
,I/NotificationManager( 6082): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(13) by com.android.calendar
,I/NotificationManager( 6082): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(16) by com.android.calendar
,I/NotificationManager( 6082): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6082): com.android.calendar: cancel(20) by com.android.calendar
I/Icing   ( 5549): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
D/AlertService( 6082): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  854): Killing 5810:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10089/pid_5810/cgroup.procs: No such file or directory
W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/AlarmScheduler( 6082): No events found starting within 1 week.
I/ActivityManager(  854): Killing 6082:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10013/pid_6082/cgroup.procs: No such file or directory
,I/Gmail   ( 6463): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6463): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  854): Killing 6233:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10011/pid_6233/cgroup.procs: No such file or directory
,W/ActivityManager(  854): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6463): Observing account changes for notifications
,I/Gmail   ( 6463): getAccountsCursor
E/Gmail   ( 6463): Error finding the version of the Email provider.....
E/Gmail   ( 6463): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6463): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6463): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6463): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6463): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6463): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6463): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6463): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6463): We do not support migrating this version of the Email provider.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CalendarProviderBroadcastReceiver( 6442): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 6442): [IntentService] WakeLock acquire, start IntentSerivce
V/WiFiOffLoadBroadcast( 6376): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/CalendarProvider2( 6442): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6442): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6442): [getOrCreateCalendarAlarmManager]
D/WiFiOffLoadBroadcast( 6376): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6376): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6376): MCCMNC not supported: null
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WiFiOffLoadBroadcast( 6376): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6376): MCCMNC not supported: null
D/CalendarProvider2( 6442): [IntentService] Release Lock
D/CalendarProvider2( 6442): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  854): Killing 6280:com.android.contacts/u0a18 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  854): failed to open /acct/uid_10018/pid_6280/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6376): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6376): MCCMNC not supported: null
I/Gmail   ( 6463): notifyAccountChanged
,I/Gmail   ( 6463): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WiFiOffLoadBroadcast( 6376): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/Gmail   ( 6463): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/WiFiOffLoadBroadcast( 6376): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6376): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/Gmail   ( 6463): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/WiFiOffLoadBroadcast( 6376): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6376): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/Gmail   ( 6463): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6463): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/WiFiOffLoadBroadcast( 6376): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6376): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6376): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6376): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6376): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6376): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6376): MCCMNC not supported: null
I/PCSuite ( 6405): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6405): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6376): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6376): MCCMNC not supported: null
I/PCSuite ( 6405): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6405): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/AudioManager( 6425): getMode name:com.lge.qremote
I/jxcore-log( 5720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5720): 
,I/AudioManager( 6425): getMode name:com.lge.qremote
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  854): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6517 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
,I/Gmail   ( 6463): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     (  854): Explicit concurrent mark sweep GC freed 16958(775KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.339ms total 149.273ms
,I/MusicStore( 6517): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6517): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6517): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6517): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 6517): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6517): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/AlarmManager(  854): RTC_WAKEUP set : Alarm{3addbb13 type 0 when 1454597210863 com.google.android.googlequicksearchbox} when 1454597210863
,V/JNIHelp ( 6517): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6517): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6517): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c8ca3b7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6517): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6517): GMSCore installation verified
,I/ConfigStore( 6517): Config Database version: 1
,I/MediaRouter( 6517): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6517): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6517): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  854): Killing 6302:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/jxcore-log( 5720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5720): 
,W/libprocessgroup(  854): failed to open /acct/uid_10069/pid_6302/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6517): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  854): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6554 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/jxcore-log( 5720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5720): 
I/jxcore-log( 5720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5720): 
,I/GHttpClientFactory( 6517): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6517): Using platform SSLCertificateSocketFactory
I/jxcore-log( 5720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5720): 
,I/ActivityManager(  854): Killing 6338:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/ResourcesManager( 6554): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6554): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6554): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/jxcore-log( 5720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5720): 
I/jxcore-log( 5720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5720): 
,I/jxcore-log( 5720): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5720): 
W/libprocessgroup(  854): failed to open /acct/uid_10086/pid_6338/cgroup.procs: No such file or directory
,I/NotificationManager( 6517): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6554): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6554): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/eas_req ( 6554): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  854): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6586 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6554): JNI_OnLoad()
I/HubEmail( 6554): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6554): registerNatives()
I/HubEmail( 6554): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6554): registerNativeMethods()
I/HubEmail( 6554): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6554): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  854): Killing 6320:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10006/pid_6320/cgroup.procs: No such file or directory
W/ActivityManager(  854): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
W/Settings( 6554): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6586): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6586): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6586): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6586): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6586): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6586): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 6586): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/ActivityManager(  854): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6609 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/LGDMClient( 6586): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6586): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6586): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6586): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6586): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6586): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6586): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  854): Killing 5940:com.android.vending/u0a36 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6609): onCreate
,W/AppUp4:DB( 6609):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6609):  setFingerPrint start
I/AppUp4:DB( 6609):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6609):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6609):  SDK version = 0
I/AppUp4:DB( 6609):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  854): failed to open /acct/uid_10036/pid_5940/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6609): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6609): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6609): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6609): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6609): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6609): onReceive
I/AppUp4:CustModeStarterReceiver( 6609): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6609): Context : android.app.ReceiverRestrictedContext@a7cb2b
D/AppUp4:CustFacade( 6609): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6609): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6609): begin check event
I/AppUp4:CustModeStarterReceiver( 6609): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6609): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6609): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6609): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6609): handleAsyncCustNotification do not startCustService
I/ActivityManager(  854): Killing 6185:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10061/pid_6185/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3211): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3211): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3211): networkInfo.isConnected() = false
,I/ActivityManager(  854): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6641 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PhoneMonitor( 6641): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6641): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6641): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  854): Killing 6463:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10053/pid_6463/cgroup.procs: No such file or directory
,I/CheckinService( 5549): Checkin interval check for package: unspecified last checkin: 1454597191319 min interval config: 0 actual interval: 21773
V/DownloadManager( 3231): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3231): DownloadService onCreate
,I/DownloadManager( 3231): in removeSpuriousFiles
I/NotificationManager( 3231): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@3ead21df on behalf of 3231
I/DownloadManager( 3231): in trimDatabase
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@1838e2c on behalf of 3231
D/PhoneMonitor( 6641): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6641): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6641): [parse] Load xml
V/TelephonyAutoProfiling( 6641): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6641): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6641): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  854): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6671 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3231): DownloadService onStartCommand
I/CheckinService( 5549): Checking schedule, now: 1454597213148 next: 1454597221284
I/CheckinService( 5549): active receiver: disabled
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 345us total 20.960ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.649ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.107ms
,V/DownloadManager( 3231): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@ebfcfb on behalf of 3231
,V/DownloadManager( 3231): DownloadService onDestroy
,I/ActivityManager(  854): Killing 6442:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10014/pid_6442/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2643): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:46:53
D/UpdateThreadPoolManager( 2643): 2 : This is isUpdating : false
D/WeatherAncestor( 2643): connectivity changed - connection : true
D/Weather_cast( 2643): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2643): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:46:53
D/WeatherService( 2643): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  854): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6688 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  854): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2643): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2643): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2643): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6688): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Babel_SMS( 6688): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6688): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6688): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6688): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6688): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6688): MmsConfig.loadFromResources
E/Babel_SMS( 6688): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6688): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6688): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6688): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6688): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6688): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 6688): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6688): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6688): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6688): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6688): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6688): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6688): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6688): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6688): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6688): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6688): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6688): found sensor: Motion Accel, handle=46
W/art     ( 6688): Suspending all threads took: 7.707ms
,W/Settings( 6688): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     ( 6688): CheckpointMarkThreadRoots callback created = 0xb002d820
,I/Babel_Crash( 6688): startup - clean
,I/art     ( 6688): CheckpointMarkThreadRoots callback created = 0xb002d800
,I/Babel   ( 6688): deleted: false for 0
I/ActivityManager(  854): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6721 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6688): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6688): Unsupported mime audio/adpcm
W/AudioCapabilities( 6688): Unsupported mime audio/g726
W/AudioCapabilities( 6688): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6688): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6688): Unsupported mime video/mjpg
W/VideoCapabilities( 6688): Unsupported mime video/theora
,W/AudioCapabilities( 6688): Unsupported mime audio/evrc
,W/AudioCapabilities( 6688): Unsupported mime audio/qcelp
W/VideoCapabilities( 6688): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6688): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6688): Unsupported mime audio/qcelp
W/AudioCapabilities( 6688): Unsupported mime audio/evrc
W/VideoCapabilities( 6688): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6688): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6688): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6688): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6688): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6688): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6688): onServiceConnected
W/Babel   ( 6688): Attempted to change video mute state without an active call.
,I/NotificationManager( 6688): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6688): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6688): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6688): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6688): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 6688): propertyValue:false
I/Babel   ( 6688): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  854): Killing 6376:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_6376/cgroup.procs: No such file or directory
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6721): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6721): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6721): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6721): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6721): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6721):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6721):   adb logcat -s GAv4
,W/GAv4    ( 6721): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6721): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6721): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/WebViewFactory( 6721): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6721): Time to load native libraries: 2 ms (timestamps 2925-2927)
I/LibraryLoader( 6721): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6721): Binding Chromium to main looper Looper (main, tid 1) {159cda5c}
I/LibraryLoader( 6721): Expected native library version number "",actual native library version number ""
I/chromium( 6721): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6721): Initializing chromium process, singleProcess=true
,W/art     ( 6721): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6721): ApplicationContext is null in ApplicationStatus
W/chromium( 6721): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6721): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6721): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6721): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6721): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6721): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6721): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6721): Remote Branch: 
I/Adreno-EGL( 6721): Local Patches: 
I/Adreno-EGL( 6721): Reconstruct Branch: 
,I/NSApplication( 6721): Starting up...
,V/AudioPolicyService(  279): registerClient() client 0xb551c6e0, uid 10079
,I/ActivityManager(  854): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6784 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  854): Killing 6405:com.lge.sync/1000 (adj 15): empty #11
W/AudioManagerAndroid( 6721): Requires BLUETOOTH permission
,W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_6405/cgroup.procs: No such file or directory
,I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  270): wakelock acquired: 1, error no: 42
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/ActivityManager(  854): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6815 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 6517:com.google.android.music:main/u0a81 (adj 15): empty #11
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  270): 
W/libprocessgroup(  854): failed to open /acct/uid_10081/pid_6517/cgroup.procs: No such file or directory
I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,W/ResourcesManager( 6815): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/CheckinService( 5549): Done disabling old GoogleServicesFramework version
,I/iu.SyncManager( 5549): SYNC; picasa accounts
,D/NetworkLogImpl( 5549): Loaded NetworkSpeedPredictor
,I/iu.Environment( 5549): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ActivityManager(  854): Killing 6554:com.lge.email/u0a21 (adj 15): empty #11
I/iu.UploadsManager( 5549): num queued entries: 0
I/iu.UploadsManager( 5549): num updated entries: 0
,I/iu.SyncManager( 5549): NEXT; no task
W/libprocessgroup(  854): failed to open /acct/uid_10021/pid_6554/cgroup.procs: No such file or directory
,I/ActivityManager(  854): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6876 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6876): Database version: 120
,I/art     (  854): Explicit concurrent mark sweep GC freed 19378(926KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.455ms total 157.521ms
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6876): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6876): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6876): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6876): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6876): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6876): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6876): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6876): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c8ca3b7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6876): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6876): GMSCore installation verified
,I/ConfigStore( 6876): Config Database version: 1
,I/MediaRouter( 6876): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6876): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6876): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6876): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  854): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6919 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6876): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6876): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 6919): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6919): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6919): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  854): Killing 6586:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_6586/cgroup.procs: No such file or directory
,I/NotificationManager( 6876): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6919): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6919): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/eas_req ( 6919): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/ActivityManager(  854): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6942 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6919): JNI_OnLoad()
I/HubEmail( 6919): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6919): registerNatives()
I/HubEmail( 6919): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6919): registerNativeMethods()
I/HubEmail( 6919): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6919): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  854): Killing 6609:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10011/pid_6609/cgroup.procs: No such file or directory
W/Settings( 6919): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6942): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6942): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6942): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6942): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6942): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6942): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  854): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6966 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6942): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6942): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6942): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6942): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6942): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  854): Killing 6641:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10038/pid_6641/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6966): onCreate
,W/AppUp4:DB( 6966):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6966):  setFingerPrint start
I/AppUp4:DB( 6966):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6966):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6966):  SDK version = 0
I/AppUp4:DB( 6966):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6966): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6966): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6966): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6966): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6966): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6966): onReceive
I/AppUp4:CustModeStarterReceiver( 6966): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6966): Context : android.app.ReceiverRestrictedContext@a7cb2b
,D/AppUp4:CustFacade( 6966): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6966): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6966): begin check event
I/AppUp4:CustModeStarterReceiver( 6966): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6966): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6966): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6966): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6966): handleAsyncCustNotification do not startCustService
I/ActivityManager(  854): Killing 6671:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10051/pid_6671/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3211): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3211): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3211): networkInfo.isConnected() = false
I/ActivityManager(  854): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6985 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6985): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6985): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6985): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  854): Killing 6688:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 6985): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6985): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6985): [parse] Load xml
V/TelephonyAutoProfiling( 6985): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6985): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6985): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  854): failed to open /acct/uid_10061/pid_6688/cgroup.procs: No such file or directory
V/DownloadManager( 3231): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3231): DownloadService onCreate
,I/NotificationManager( 3231): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3231): in removeSpuriousFiles
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@37abd771 on behalf of 3231
I/DownloadManager( 3231): in trimDatabase
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@736dd7 on behalf of 3231
I/ActivityManager(  854): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7007 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3231): DownloadService onStartCommand
V/DownloadManager( 3231): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 5549): Checkin interval check for package: unspecified last checkin: 1454597191319 min interval config: 0 actual interval: 27662
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@235579ad on behalf of 3231
I/CheckinService( 5549): Checking schedule, now: 1454597219009 next: 1454597221284
I/CheckinService( 5549): active receiver: disabled
,I/ActivityManager(  854): Killing 6721:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,E/libprocessgroup(  854): failed to kill 1 processes for processgroup 6721
,D/WeatherAncestor( 2643): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:46:59
V/DownloadManager( 3231): DownloadService onDestroy
D/UpdateThreadPoolManager( 2643): 2 : This is isUpdating : false
D/WeatherAncestor( 2643): connectivity changed - connection : true
D/Weather_cast( 2643): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2643): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:46:59
D/WeatherService( 2643): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  854): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7029 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  854): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,I/art     (  305): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 290us total 23.650ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.338ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 26.754ms
,D/Weather.Utils( 2643): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2643): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2643): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
W/ResourcesManager( 7029): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7029): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7029): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7029): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7029): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7029): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7029): MmsConfig.loadFromResources
E/Babel_SMS( 7029): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7029): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7029): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7029): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7029): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7029): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7029): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7029): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7029): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7029): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7029): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7029): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7029): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
,D/SensorManager( 7029): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7029): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7029): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7029): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7029): found sensor: Motion Accel, handle=46
W/Settings( 7029): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7029): startup - clean
I/Babel   ( 7029): deleted: false for 0
,I/art     ( 7029): CheckpointMarkThreadRoots callback created = 0xaaf39970
,I/art     ( 7029): CheckpointMarkThreadRoots callback created = 0xaaf39940
,I/ActivityManager(  854): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7066 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/AudioCapabilities( 7029): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7029): Unsupported mime audio/adpcm
W/AudioCapabilities( 7029): Unsupported mime audio/g726
,W/AudioCapabilities( 7029): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7029): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 7029): Unsupported mime video/mjpg
W/VideoCapabilities( 7029): Unsupported mime video/theora
W/AudioCapabilities( 7029): Unsupported mime audio/evrc
,W/AudioCapabilities( 7029): Unsupported mime audio/qcelp
W/VideoCapabilities( 7029): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7029): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7029): Unsupported mime audio/qcelp
W/AudioCapabilities( 7029): Unsupported mime audio/evrc
D/WeatherService( 2643): 2 : TimeTick Intent has been received, Time(hour:min:sec) 15:47:0
,D/WeatherService( 2643): 2 : TimeTick Intent And Screen On
D/WeatherService( 2643): 2 : SDK version : 21
W/ActivityManager(  854): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2643): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2643): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2643): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2643): 2 : requestRefreshAppWidget, isUpdateStart : false
W/VideoCapabilities( 7029): Unsupported mime video/mp4v-esdp
D/UpdateThreadPoolManager( 2643): 2 : This is isUpdating : false
D/WeatherService( 2643): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2643): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2643): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2643): 2 : Fixed theme : optimus
D/WeatherReflect( 2643): 2 : Map key string is -2
,I/VideoCapabilities( 7029): Unsupported profile 4 for video/mp4v-es
I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
W/VideoCapabilities( 7029): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7029): Unrecognized profile 2130706433 for video/avc
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
W/VideoCapabilities( 7029): Unrecognized profile 2130706433 for video/avc
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,D/lim     ( 2643): 2 : time = 15:47
W/ContextImpl( 7066): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/VideoCapabilities( 7029): Unrecognized profile 2130706433 for video/avc
I/WeatherReflect( 2643): Model Name : LG-D722
D/WeatherTheme( 2643): 2 : Different view - status_min_formatted : 46 != 47
D/WeatherTheme( 2643): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2643): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,I/vclib   ( 7029): onServiceConnected
W/Babel   ( 7029): Attempted to change video mute state without an active call.
I/GAv4    ( 7066): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7066):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7066):   adb logcat -s GAv4
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7066): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/[SystemUI]Clock( 1363): called onTimeUpdated()
D/libc-netbsd( 7029): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7029): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7029): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7029): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out( 7029): propertyValue:false
I/NotificationManager( 7029): com.google.android.talk: cancel(10436) by com.google.android.talk
I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7066): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7066): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7066): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/Theme   ( 2643): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(home): com.lge.launcher2.theme.optimus
,D/Theme   ( 2643): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2643): currentPackage=com.lge.sizechangable.weather.theme.optimus
W/GAv4    ( 7066): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7029): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  854): Killing 6784:com.android.chrome/u0a48 (adj 15): empty #11
,D/Weather4x2_optimus( 2643): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2643): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2643): forecast size is 0
D/Theme   ( 2643): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2643): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2643): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2643): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2643): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2643): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2643): setTouchIntent, appWidgetId: 2
,W/GAv4    ( 7066): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup(  854): failed to open /acct/uid_10048/pid_6784/cgroup.procs: No such file or directory
,D/Theme_WeatherAncestor_optimus( 2643): url is : null
D/Theme   ( 2643): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2643): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2643): 2 : update view, appWidgetId: 2
D/WeatherService( 2643): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 15:47:0
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/WebViewFactory( 7066): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7066): Time to load native libraries: 2 ms (timestamps 8364-8366)
I/LibraryLoader( 7066): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7066): Binding Chromium to main looper Looper (main, tid 1) {159cda5c}
I/LibraryLoader( 7066): Expected native library version number "",actual native library version number ""
I/chromium( 7066): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/BrowserStartupController( 7066): Initializing chromium process, singleProcess=true
W/art     ( 7066): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7066): ApplicationContext is null in ApplicationStatus
W/chromium( 7066): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7066): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7066): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7066): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7066): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7066): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7066): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7066): Remote Branch: 
I/Adreno-EGL( 7066): Local Patches: 
I/Adreno-EGL( 7066): Reconstruct Branch: 
V/AudioPolicyService(  279): registerClient() client 0xb57e95e0, uid 10079
,I/NSApplication( 7066): Starting up...
W/AudioManagerAndroid( 7066): Requires BLUETOOTH permission
I/ActivityManager(  854): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7126 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 6815:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,W/libprocessgroup(  854): failed to open /acct/uid_10086/pid_6815/cgroup.procs: No such file or directory
,I/jxcore-log( 5720): Test app app.js loaded
I/jxcore-log( 5720): 
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5720): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5720): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5720): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5720): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5720): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5720): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5720): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5720): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5720): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5720): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cc1212b added. We now have 1 listener(s)
D/BluetoothAdapterService(182018374)( 1974): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e8f39cc
I/jxcore-log( 5720): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5720): 
I/chromium( 5720): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  854): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7150 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  854): Killing 6876:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10081/pid_6876/cgroup.procs: No such file or directory
,W/ResourcesManager( 7150): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  854): Killing 6919:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10021/pid_6919/cgroup.procs: No such file or directory
,I/ActivityManager(  854): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7177 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7177): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7177): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7177): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7177): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7177): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7177): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7177): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7177): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7177): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c8ca3b7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7177): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7177): GMSCore installation verified
,I/ConfigStore( 7177): Config Database version: 1
,I/art     (  854): Explicit concurrent mark sweep GC freed 22158(1128KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.839ms total 156.205ms
,I/MediaRouter( 7177): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7177): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7177): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7177): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  854): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7205 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7177): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7177): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  854): Killing 6942:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 7205): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7205): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7205): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_6942/cgroup.procs: No such file or directory
,I/LGEmail ( 7205): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/NotificationManager( 7177): com.google.android.music: cancel(1061) by com.google.android.music
D/LGEmail ( 7205): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7205): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  854): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7236 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7205): JNI_OnLoad()
I/HubEmail( 7205): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7205): registerNatives()
I/HubEmail( 7205): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7205): registerNativeMethods()
I/HubEmail( 7205): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7205): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 7205): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  854): Killing 6966:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10011/pid_6966/cgroup.procs: No such file or directory
D/LGDMClient( 7236): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7236): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7236): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7236): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7236): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7236): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7236): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7236): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  854): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7260 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7236): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7236): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7236): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 7236): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7236): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 7236): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  854): Killing 6985:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/AppUp4:AppBoxCP( 7260): onCreate
,W/AppUp4:DB( 7260):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7260):  setFingerPrint start
I/AppUp4:DB( 7260):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7260):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 7260):  SDK version = 0
,I/AppUp4:DB( 7260):  beforefinger == newfinger no write in DB
W/libprocessgroup(  854): failed to open /acct/uid_10038/pid_6985/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 7260): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7260): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7260): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7260): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7260): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7260): onReceive
,I/AppUp4:CustModeStarterReceiver( 7260): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7260): Context : android.app.ReceiverRestrictedContext@a7cb2b
D/AppUp4:CustFacade( 7260): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7260): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7260): begin check event
I/AppUp4:CustModeStarterReceiver( 7260): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 7260): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7260): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7260): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7260): handleAsyncCustNotification do not startCustService
I/ActivityManager(  854): Killing 7007:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10051/pid_7007/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3211): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3211): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3211): networkInfo.isConnected() = true
D/PhoneState( 3211): setPdpRejectCasuse : false
I/ActivityManager(  854): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7279 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/AlarmManager(  854): RTC_WAKEUP set : Alarm{1c02ea4 type 0 when 1454597221284 com.google.android.gms} when 1454597221284
,I/ActivityManager(  854): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7296 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  854): RTC_WAKEUP set : Alarm{3e2040d type 0 when 1454597222885 com.android.vending} when 1454597222885
,D/PhoneMonitor( 7279): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7279): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7279): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  854): Killing 7029:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7279): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7279): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7279): [parse] Load xml
V/TelephonyAutoProfiling( 7279): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7279): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7279): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  854): failed to open /acct/uid_10061/pid_7029/cgroup.procs: No such file or directory
V/DownloadManager( 3231): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3231): DownloadService onCreate
I/NotificationManager( 3231): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3231): in removeSpuriousFiles
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@16971073 on behalf of 3231
,I/DownloadManager( 3231): in trimDatabase
V/DownloadManager( 3231): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@11473b30 on behalf of 3231
I/ActivityManager(  854): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7322 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3231): DownloadService onStartCommand
,V/DownloadManager( 3231): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 5549): Checkin interval check for package: unspecified last checkin: 1454597191319 min interval config: 0 actual interval: 31898
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@144840cf on behalf of 3231
I/CheckinService( 5549): Checking schedule, now: 1454597223224 next: 1454597221284
I/CheckinService( 5549): active receiver: enabled
,V/DownloadManager( 3231): DownloadService onDestroy
,I/CheckinService( 5549): Preparing to send checkin request
,I/EventLogService( 5549): Accumulating logs since 1454597181817
,D/WeatherAncestor( 2643): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:47:3
D/UpdateThreadPoolManager( 2643): 2 : This is isUpdating : false
D/WeatherAncestor( 2643): connectivity changed - connection : true
D/Weather_cast( 2643): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2643): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:47:3
D/WeatherService( 2643): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/art     ( 5399): Explicit concurrent mark sweep GC freed 2712(105KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 391us total 27.390ms
,I/ActivityManager(  854): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7351 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  854): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2643): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 359us total 21.872ms
,D/WeatherService( 2643): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2643): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/Finsky  ( 7296): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.001ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.200ms
,W/ResourcesManager( 7351): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 5549): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5549): Failed to find provider info for com.google.android.wearable.settings
,D/Finsky  ( 7296): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7296): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7296): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7296): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Finsky  ( 7296): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7296): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7296): Skipping gmscore version check
I/Babel_SMS( 7351): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7351): MmsConfig.loadMmsSettings
I/Babel_SMS( 7351): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7351): MmsConfig.loadFromDatabase
,V/DownloadManager( 3231): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@3d793165 on behalf of 7296
D/Finsky  ( 7296): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/Babel_SMS( 7351): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7351): MmsConfig.loadFromResources
E/Babel_SMS( 7351): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7351): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/ActivityManager(  854): Waited long enough for: ServiceRecord{2905758e u0 com.lge.qremote/.QRemoteService}
D/Finsky  ( 7296): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/SensorManager( 7351): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7351): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7351): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7351): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7351): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7351): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7351): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7351): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7351): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7351): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7351): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7351): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7351): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7351): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7351): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7351): found sensor: Motion Accel, handle=46
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Settings( 7351): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7351): startup - clean
I/art     ( 7351): CheckpointMarkThreadRoots callback created = 0xb002d540
,I/Babel   ( 7351): deleted: false for 0
,I/art     ( 7351): CheckpointMarkThreadRoots callback created = 0xb002d520
,W/AudioCapabilities( 7351): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7351): Unsupported mime audio/adpcm
W/AudioCapabilities( 7351): Unsupported mime audio/g726
W/AudioCapabilities( 7351): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7351): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7351): Unsupported mime video/mjpg
W/VideoCapabilities( 7351): Unsupported mime video/theora
,I/ActivityManager(  854): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7402 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/AudioCapabilities( 7351): Unsupported mime audio/evrc
,W/AudioCapabilities( 7351): Unsupported mime audio/qcelp
W/VideoCapabilities( 7351): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7351): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7351): Unsupported mime audio/qcelp
W/AudioCapabilities( 7351): Unsupported mime audio/evrc
I/art     ( 7150): CheckpointMarkThreadRoots callback created = 0xaaf06f60
,W/ResourcesManager( 7402): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7402): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/VideoCapabilities( 7351): Unsupported mime video/mp4v-esdp
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
E/MDM     ( 1733): [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/art     ( 7150): CheckpointMarkThreadRoots callback created = 0xaaf06f30
D/LocationInitializer( 5549): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/VideoCapabilities( 7351): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7351): Unrecognized profile 2130706433 for video/avc
I/MultiDex( 7402): VM with version 2.1.0 has multidex support
,I/MultiDex( 7402): install
W/VideoCapabilities( 7351): Unrecognized profile 2130706433 for video/avc
I/MultiDex( 7402): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 7296): [945] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
W/VideoCapabilities( 7351): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7351): Unrecognized profile 2130706433 for video/avc
,I/art     (  854): Explicit concurrent mark sweep GC freed 22110(989KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.164ms total 149.934ms
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
D/Finsky  ( 7296): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Finsky  ( 7296): [950] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/vclib   ( 7351): onServiceConnected
W/Babel   ( 7351): Attempted to change video mute state without an active call.
D/libc-netbsd( 7351): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7351): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7351): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7351): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 7351): propertyValue:false
V/JNIHelp ( 7402): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NotificationManager( 7351): com.google.android.talk: cancel(10436) by com.google.android.talk
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  854): android: cancelAsUser(2) by android
,W/ActivityThread( 7402): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7402): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1838e2c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7402): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7402): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7402): com.google.android.gms: cancel(39789) by com.google.android.gms
D/libc-netbsd( 7296): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7296): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7296): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7296): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
,I/ActivityManager(  854): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7434 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Babel   ( 7351): connection state changed from UNKNOWN to CONNECTED
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 7296): propertyValue:false
V/LGMDMManager( 6425): Create singleton instance
,I/art     ( 7402): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7402): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  854): Process com.google.android.music:main (pid 7177) has died
,I/AudioManager( 6425): getMode name:com.lge.qremote
,I/ActivityManager(  854): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7452 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7434): Quickset Services start...
,I/UEI.SmartControl( 7434): Manufacture = LGE
D/NativeLibraryUtils( 7402): Install completed successfully. count=14 extracted=0
,D/UEI.SmartControl( 7434): File observer start...
E/UEI.SmartControl( 7434): IR Port is disabled: false
D/UEI.SmartControl( 7434): Starting file observer...
D/UEI.SmartControl( 7434): Extracting JNI libs...
D/UEI.SmartControl( 7434): --- this system supports 32-bit or 64-bit only
D/WVCdm   (  279): Instantiating CDM.
I/WVCdm   (  279): CdmEngine::OpenSession
I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
,I/art     ( 7402): Background sticky concurrent mark sweep GC freed 24475(1441KB) AllocSpace objects, 2(32KB) LOS objects, 5% free, 10MB/11MB, paused 9.544ms total 86.692ms
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=3769716451
I/ActivityManager(  854): Killing 7205:com.lge.email/u0a21 (adj 15): empty #11
,I/art     ( 7402): CheckpointMarkThreadRoots callback created = 0xb002d530
,I/art     ( 7402): CheckpointMarkThreadRoots callback created = 0xb002d520
,W/libprocessgroup(  854): failed to open /acct/uid_10021/pid_7205/cgroup.procs: No such file or directory
,W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/UEI.SmartControl( 7434): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7434): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7434): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/Gmail   ( 7452): getAccountsCursor
,I/UEI.SmartControl( 7434): --- Selecting new region: 2
I/UEI.SmartControl( 7434): -- Running on KitKat(19) and above! JNI will be used.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 7434): Platform has CIR...
D/UEI.SmartControl( 7434): NO CIR support, need to check package...
I/UEI.SmartControl( 7434): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7434): QS Service created
W/GAV2    ( 7452): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/UEI.SmartControl( 7434): QS start get config
E/Gmail   ( 7452): Error finding the version of the Email provider.....
E/Gmail   ( 7452): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7452): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7452): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7452): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7452): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7452): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7452): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7452): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7452): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7452): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7434): Loading JNI Libs...
,D/UEI.SmartControl( 7434):  configuring local db...
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  854): Killing 7236:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_7236/cgroup.procs: No such file or directory
,W/ActivityManager(  854): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 5549): Checkin interval check for package: unspecified last checkin: 1454597191319 min interval config: 0 actual interval: 34267
E/MDM     ( 1733): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager(  854): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 7452): Observing account changes for notifications
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 5549): Restart initialization of location
I/Gmail   ( 7452): notifyAccountChanged
I/Gmail   ( 7452): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7452): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
W/ContextImpl( 3598): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/Gmail   ( 7452): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/UEI.SmartControl( 7434):  ---- Has DB8: true
I/dex2oat ( 7504): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/UEI.SmartControl( 7434): QS start statue = true Error code = 0
D/UEI.SmartControl( 7434): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 7434): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7434): IRRCDataComm has AudioManager!!!!.
,I/Gmail   ( 7452): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7452): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/irrc_jni( 7434): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7434): IrrcClient ++ 
D/irrcClient( 7434): getIrrcService ++ 
D/irrcClient( 7434): getIrrcService -- 
D/irrcClient( 7434): IrrcClient -- 
,W/irrc_jni( 7434): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7434): Services init done
,I/UEI.SmartControl( 7434): Device manager: loading config....
D/UEI.SmartControl( 7434): QS Service init finished
D/UEI.SmartControl( 7434): QS Service version name: 0.1.73
D/UEI.SmartControl( 7434): QS Service version code: 1073
D/UEI.SmartControl( 7434): Service requested: Control
D/UEI.SmartControl( 7434): Config is loaded...
,I/ActivityManager(  854): Process com.google.android.apps.magazines (pid 7066) has died
,I/Gmail   ( 7452): getAccountsCursor
I/dex2oat ( 7504): dex2oat took 167.213ms (threads: 4)
D/UEI.SmartControl( 7434): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7434): Internal service binding...
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7434): -----IControl: 11
D/UEI.SmartControl( 7434): Caller: com.lge.qremote
,D/UEI.SmartControl( 7434): ------------ IControl registerCallback...
I/UEI.SmartControl( 7434): Registering callback...
D/UEI.SmartControl( 7434): -----IControl: 19
D/UEI.SmartControl( 7434): Caller: com.lge.qremote
I/UEI.SmartControl( 7434): Registering Services Ready callback...
I/UEI.SmartControl( 7434): Notify client services are ready...
D/UEI.SmartControl( 7434):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7434): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7434): -----IControl: 8
D/UEI.SmartControl( 7434): Caller: com.lge.qremote
I/Adreno-EGL( 7402): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7402): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7402): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7402): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7402): Remote Branch: 
I/Adreno-EGL( 7402): Local Patches: 
I/Adreno-EGL( 7402): Reconstruct Branch: 
I/AudioManager( 6425): getMode name:com.lge.qremote
,I/ActivityManager(  854): Killing 7260:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10011/pid_7260/cgroup.procs: No such file or directory
,I/Adreno-EGL( 7402): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7402): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7402): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7402): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7402): Remote Branch: 
I/Adreno-EGL( 7402): Local Patches: 
I/Adreno-EGL( 7402): Reconstruct Branch: 
I/AudioManager( 6425): getMode name:com.lge.qremote
I/AudioManager( 6425): getMode name:com.lge.qremote
,I/WVCdm   (  279): CdmEngine::OpenSession
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 114896633710; DSPS: 3863440; Offset : -3015786132
,I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=3348489413
I/MusicWidget( 2576): mDelayedStopHandler : unbind
,I/MusicBrowser( 2673): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2673): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2673): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2673): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2673): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2673): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2673): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2673): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  854):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1b58bc91com.lge.music.MediaPlaybackService$6@1762a7f6
,D/MusicBrowser( 2673): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1c55ef07
,I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2673): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2673): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2673): reset
V/MediaPlayer[Native]( 2673): setListener
V/MediaPlayer[Native]( 2673): disconnect
V/MediaPlayer[Native]( 2673): destructor
,V/AudioFlinger(  279): releasing 18 from 2673 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/MediaPlayer[Native]( 2673): disconnect
D/MusicBrowser( 2673): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2673): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2673): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2673): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
,I/MusicBrowser( 2673): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2673): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2673): [SmartShareManagerClient] unregisterListener: 577939447
W/SmartShareClient( 2673): [SmartShareManagerClient] unregisterListener invalid listener: 577939447
I/SmartShareClient( 2673): [SmartShareManagerClient] terminate service: 2673/MediaPlaybackService/768661413
E/HomeCloudIF( 2673): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2673): [SmartShareManagerClient] unbindService context:android.app.Application@3a08f664
V/CloudHub( 2673): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2673): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2673): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2673): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2673): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  854): Killing 7322:com.lge.drmservice/u0a51 (adj 15): empty #11
I/CloudHub( 2673): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29982
,W/libprocessgroup(  854): failed to open /acct/uid_10051/pid_7322/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): L3 Terminate.
I/Adreno-EGL( 7402): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7402): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7402): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7402): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7402): Remote Branch: 
I/Adreno-EGL( 7402): Local Patches: 
I/Adreno-EGL( 7402): Reconstruct Branch: 
,I/CheckinRequestBuilder( 5549): Classify the device as Phone.
,D/libc-netbsd( 5549): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5549): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5549): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5549): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 5549): propertyValue:false
D/libc-netbsd( 5549): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5549): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5549): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5549): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5549): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5549): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 5549): Sending checkin request (9703 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 5549): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5549): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 5549): Classify the device as Phone.
,I/CheckinTask( 5549): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5549): Checking schedule, now: 1454597230213 next: 1455124479206
I/CheckinService( 5549): active receiver: disabled
,I/GAV2    ( 7452): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 5549): Google Analytics 8.4.89 is starting up.
,I/CheckinService( 5549): Checking schedule, now: 1454597230306 next: 1455124479206
I/CheckinService( 5549): active receiver: disabled
,D/CheckinService( 5549): Recording last checkin time for package unspecified as 1454597230315
V/SetupWizard( 7279): Connected to Gservices successfully
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  854): Killing 7150:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/ActivityManager(  854): Killing 7126:com.android.chrome/u0a48 (adj 15): empty #12
,W/libprocessgroup(  854): failed to open /acct/uid_10086/pid_7150/cgroup.procs: No such file or directory
,W/libprocessgroup(  854): failed to open /acct/uid_10048/pid_7126/cgroup.procs: No such file or directory
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/UEI.SmartControl( 7434): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1363): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  854): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1363): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1363): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1363): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1363): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  854): Handling package changes for user 0
I/ActivityManager(  854): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7585 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 7351): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7351): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NotificationManager( 7351): com.google.android.talk: cancel(8) by com.google.android.talk
,I/AppUp4:AppBoxCP( 7585): onCreate
,W/AppUp4:DB( 7585):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7585):  setFingerPrint start
I/AppUp4:DB( 7585):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7585):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7585):  SDK version = 0
I/AppUp4:DB( 7585):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7585): AppBoxApplication onCreate()
V/JNIHelp ( 7351): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:CustModeStarterReceiver( 7585): onReceive
I/AppUp4:CustModeStarterReceiver( 7585): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7585): Context : android.app.ReceiverRestrictedContext@20e319c
D/AppUp4:CustFacade( 7585): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7585): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7585): begin check event
I/AppUp4:CustModeStarterReceiver( 7585): Event For Nothing, skip.
I/NotificationService(  854): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  854): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  854): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/System  ( 7351): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7351): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  854): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7608 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/BackupManagerService(  854): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourcesManager(  854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  854): Explicit concurrent mark sweep GC freed 21501(1085KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.821ms total 176.166ms
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/BackupManagerService(  854): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  854): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3814b64e
W/ResourcesManager( 7608): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7608): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7608): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType(  854): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 },
,I/AppConfig( 7608): Total System Memory = 906309632
,I/GalleryUtils( 7608): Application Heap = 96 MB,
I/AppConfig( 7608): App Tier : NOT_DEF
I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/SystemHelper( 7608): region [EU], country [EU], operator [OPEN], sub-operator []
D/LocationProviderProxy(  854): applying state to connected service
,I/ActivityManager(  854): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7629 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 7296:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10036/pid_7296/cgroup.procs: No such file or directory
,W/ResourcesManager( 7629): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7629): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7629): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7629): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7629): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  854): Process com.google.android.gm (pid 7452) has died
,I/SystemConfig( 7629): BUILD Country: EU
I/SystemConfig( 7629): BUILD Operator: OPEN
,I/ActivityManager(  854): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7654 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7629): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7629): existFile = false
I/SystemConfig( 7629): canReadFile = false
I/SystemConfig( 7629): systemFeature RCS result false
D/SystemConfig( 7629): refreshRcsSupport() :false
,I/LockScreenSettings( 7654): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7654): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7654): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7654): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7654): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7654): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  854): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7676 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  854): Killing 2673:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  279): 2673 died, releasing its sessions
V/AudioFlinger(  279):  pid 1751 @ 0
,V/AudioFlinger(  279):  pid 3211 @ 1
V/AudioFlinger(  279):  pid 3211 @ 2
W/libprocessgroup(  854): failed to open /acct/uid_10028/pid_2673/cgroup.procs: No such file or directory
,W/ResourcesManager( 7676): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  854): Killing 7434:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6425): android.os.DeadObjectException
,W/System.err( 6425): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 6425): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6425): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6425): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6425): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6425): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6425): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6425): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6425): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6425): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6425): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6425): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6425): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6425): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6425): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6425): android.os.DeadObjectException
W/System.err( 6425): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6425): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6425): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6425): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6425): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6425): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6425): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6425): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6425): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6425): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6425): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6425): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6425): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6425): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6425): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 68 ms] updated apps [took 68 ms] 
,I/ActivityManager(  854): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7702 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/lowmemorykiller(  241): Error opening /proc/7434/oom_score_adj; errno=2
W/ActivityManager(  854): Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  854): android.os.DeadObjectException
W/ActivityManager(  854): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  854): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  854): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager(  854): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
W/ActivityManager(  854): 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:907)
W/ActivityManager(  854): 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15651)
W/ActivityManager(  854): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
W/ActivityManager(  854): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/ActivityManager(  854): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/ActivityManager(  854): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ActivityManager(  854): Exception when destroying service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  854): android.os.DeadObjectException
W/ActivityManager(  854): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  854): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  854): 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
W/ActivityManager(  854): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1693)
W/ActivityManager(  854): 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1605)
W/ActivityManager(  854): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1805)
W/ActivityManager(  854): 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:907)
W/ActivityManager(  854): 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15651)
W/ActivityManager(  854): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
W/ActivityManager(  854): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/ActivityManager(  854): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/ActivityManager(  854): 	at android.os.Binder.execTransact(Binder.java:446)
W/libprocessgroup(  854): failed to open /acct/uid_10089/pid_7434/cgroup.procs: No such file or directory
I/ActivityManager(  854): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7719 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7719): Quickset Services start...
,I/UEI.SmartControl( 7719): Manufacture = LGE
D/UEI.SmartControl( 7719): File observer start...
E/UEI.SmartControl( 7719): IR Port is disabled: false
D/UEI.SmartControl( 7719): Starting file observer...
,D/UEI.SmartControl( 7719): Extracting JNI libs...
D/UEI.SmartControl( 7719): --- this system supports 32-bit or 64-bit only
,I/art     ( 5399): Explicit concurrent mark sweep GC freed 3344(137KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 356us total 25.769ms
,D/Finsky  ( 7702): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 7719): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7719): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7719): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7719): --- Selecting new region: 2
I/UEI.SmartControl( 7719): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7719): Platform has CIR...
D/UEI.SmartControl( 7719): NO CIR support, need to check package...
I/UEI.SmartControl( 7719): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7719): QS Service created
,E/UEI.SmartControl( 7719): QS start get config
,D/UEI.SmartControl( 7719): Loading JNI Libs...
,D/UEI.SmartControl( 7719):  configuring local db...
,D/Finsky  ( 7702): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7702): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7702): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7702): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3231): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3231): created cursor android.database.sqlite.SQLiteCursor@32c4fe3a on behalf of 7702
,D/Finsky  ( 7702): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7702): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7702): Skipping gmscore version check
D/Finsky  ( 7702): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 5549): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5549): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5549): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 7702): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/UEI.SmartControl( 7719):  ---- Has DB8: true
,D/UEI.SmartControl( 7719): QS start statue = true Error code = 0
D/UEI.SmartControl( 7719): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 7719): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7719): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7719): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7719): IrrcClient ++ 
D/irrcClient( 7719): getIrrcService ++ 
,D/irrcClient( 7719): getIrrcService -- 
D/irrcClient( 7719): IrrcClient -- 
W/irrc_jni( 7719): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7719): Services init done
,D/UEI.SmartControl( 7719): QS Service init finished
I/UEI.SmartControl( 7719): Device manager: loading config....
D/UEI.SmartControl( 7719): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7719): QS Service version code: 1073
D/UEI.SmartControl( 7719): Service requested: Control
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
D/UEI.SmartControl( 7719): Config is loaded...
,D/UEI.SmartControl( 7719):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7719): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7719): Request IControl service: devices are loaded...
,I/ActivityManager(  854): Killing 6425:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10106/pid_6425/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7719): Internal service binding...
,I/ActivityManager(  854): Killing 7279:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  854): failed to open /acct/uid_10038/pid_7279/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/Icing   ( 5549): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5549): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  854): Killing 7402:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  854): failed to open /acct/uid_10006/pid_7402/cgroup.procs: No such file or directory
,D/charger_monitor(  479): init target 500000
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
D/WifiController(  854): battery changed pluggedType: 2
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/charger_monitor(  479): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1974): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/UEI.SmartControl( 7719): Internal timer expired: 1
,D/UEI.SmartControl( 7719): Service.onUnbind: IControl
D/UEI.SmartControl( 7719): Service.onDestroy
W/System.err( 7719): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@ad96146
W/System.err( 7719): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7719): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7719): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7719): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7719): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7719): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7719): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7719): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7719): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7719): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7719): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7719): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7719): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7719): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7719): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7719): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@ad96146
D/UEI.SmartControl( 7719): Shutdown IRRCPlayer... 
,W/irrc_jni( 7719): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7719): ~IrrcClient ++ 
D/irrcClient( 7719): ~IrrcClient -- 
W/irrc_jni( 7719): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7719): Blaster closed
D/UEI.SmartControl( 7719): Blaster closed
D/UEI.SmartControl( 7719): Shut down QS...
,D/UEI.SmartControl( 7719): Stopped file observer...
I/UEI.SmartControl( 7719): QS lib stop result = true
D/UEI.SmartControl( 7719): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 134897410266; DSPS: 4518826; Offset : -3015803006
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{ccb8d0c type 2 when 144034 com.google.android.gms} when 144034
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 34447(2MB) AllocSpace objects, 28(448KB) LOS objects, 39% free, 13MB/22MB, paused 1.079ms total 87.707ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1733): Vacuum at: now=1454597256503 tag=VacuumService
I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 9208 seconds from now (1454597256947)
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/GetConfigurationSnapshotOperation( 1733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  854): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  854): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  854): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/LocationManagerService(  854): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  854): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  854): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  854): android: cancelAsUser(2) by android
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/PowerManagerService(  854): ALS enabled for SRE
D/PowerManagerServiceEx(  854): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (31069 ms ago)
,D/qdlights(  854): set_light_backlight: 253
,D/qdlights(  854): set_light_backlight: 250
D/qdlights(  854): set_light_backlight: 247
,D/qdlights(  854): set_light_backlight: 243
,D/qdlights(  854): set_light_backlight: 240
,D/qdlights(  854): set_light_backlight: 237
,D/qdlights(  854): set_light_backlight: 233
,D/qdlights(  854): set_light_backlight: 230
,D/qdlights(  854): set_light_backlight: 227
,D/qdlights(  854): set_light_backlight: 223
,D/qdlights(  854): set_light_backlight: 220
,D/qdlights(  854): set_light_backlight: 217
,D/qdlights(  854): set_light_backlight: 213
,D/qdlights(  854): set_light_backlight: 210
,D/qdlights(  854): set_light_backlight: 207
,D/qdlights(  854): set_light_backlight: 203
,D/qdlights(  854): set_light_backlight: 200
,D/qdlights(  854): set_light_backlight: 197
,D/qdlights(  854): set_light_backlight: 193
,D/qdlights(  854): set_light_backlight: 190
,D/qdlights(  854): set_light_backlight: 187
,D/qdlights(  854): set_light_backlight: 183
,D/qdlights(  854): set_light_backlight: 180
,D/qdlights(  854): set_light_backlight: 177
,D/qdlights(  854): set_light_backlight: 173
,D/qdlights(  854): set_light_backlight: 170
,D/qdlights(  854): set_light_backlight: 167
,D/qdlights(  854): set_light_backlight: 163
,D/qdlights(  854): set_light_backlight: 160
,D/qdlights(  854): set_light_backlight: 157
,D/qdlights(  854): set_light_backlight: 153
,D/qdlights(  854): set_light_backlight: 150
,D/qdlights(  854): set_light_backlight: 147
,D/qdlights(  854): set_light_backlight: 143
,D/qdlights(  854): set_light_backlight: 140
,D/qdlights(  854): set_light_backlight: 137
,D/qdlights(  854): set_light_backlight: 133
,D/qdlights(  854): set_light_backlight: 130
,D/qdlights(  854): set_light_backlight: 127
,D/qdlights(  854): set_light_backlight: 123
,D/qdlights(  854): set_light_backlight: 120
,D/qdlights(  854): set_light_backlight: 117
,D/qdlights(  854): set_light_backlight: 113
,D/qdlights(  854): set_light_backlight: 110
,D/qdlights(  854): set_light_backlight: 107
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/qdlights(  854): set_light_backlight: 103
D/qdlights(  854): set_light_backlight: 100
,D/qdlights(  854): set_light_backlight: 97
,D/qdlights(  854): set_light_backlight: 93
,D/qdlights(  854): set_light_backlight: 90
,D/qdlights(  854): set_light_backlight: 87
,D/qdlights(  854): set_light_backlight: 83
,D/qdlights(  854): set_light_backlight: 80
,D/qdlights(  854): set_light_backlight: 77
,D/qdlights(  854): set_light_backlight: 73
,D/qdlights(  854): set_light_backlight: 70
,D/qdlights(  854): set_light_backlight: 67
,D/qdlights(  854): set_light_backlight: 63
,D/qdlights(  854): set_light_backlight: 60
,D/qdlights(  854): set_light_backlight: 57
,D/qdlights(  854): set_light_backlight: 53
,D/qdlights(  854): set_light_backlight: 50
,D/qdlights(  854): set_light_backlight: 47
,D/qdlights(  854): set_light_backlight: 43
,D/qdlights(  854): set_light_backlight: 40
,D/qdlights(  854): set_light_backlight: 37
,D/qdlights(  854): set_light_backlight: 33
,D/qdlights(  854): set_light_backlight: 30
,D/qdlights(  854): set_light_backlight: 27
,D/qdlights(  854): set_light_backlight: 23
,D/qdlights(  854): set_light_backlight: 20
,D/qdlights(  854): set_light_backlight: 17
,D/qdlights(  854): set_light_backlight: 13
,D/qdlights(  854): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 154900612862; DSPS: 5174291; Offset : -3015804626
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1363): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  854): ALS enabled for SRE
D/PowerManagerServiceEx(  854): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (38060 ms ago)
I/PowerManagerService(  854): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  854): ALS enabled for SRE
D/PowerManagerServiceEx(  854): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (38074 ms ago)
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  854): Sleeping (uid 1000)...
D/LPWGController(  854): [updateScreenState] screen on = false
D/LPWGController(  854): disable proximity sensor
,D/LPWGController(  854): enable proximity sensor
I/SensorManager(  854): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@c98bd4] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  854): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  854): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  854): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  854): activate: handle is 48, enable
,V/sensors_hal_Ctx(  854): activate sensors is 1400000000000
D/sensors_hal_Thresh(  854): enable: handle=48
I/sensors_hal_SAM(  854): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  854): waitForResponse: timeout=1000
V/sensors_hal_SAM(  854): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  854): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  854): enable: Received response: 0
,D/PowerManagerServiceEx(  854): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (38135 ms ago)
I/Adreno-EGL(  854): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  854): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  854): Build Date: 03/02/15 Mon
I/Adreno-EGL(  854): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  854): Remote Branch: 
I/Adreno-EGL(  854): Local Patches: 
I/Adreno-EGL(  854): Reconstruct Branch: 
,D/PermissionCache(  244): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1251 us)
,I/Sensors (  428): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  854): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  854): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  854): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  854): processInd: handle 48, count=1
V/sensors_hal_Thresh(  854): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  854): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  854): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  854): poll: count: 256
I/sensors_hal_Ctx(  854): poll: released wakelock sensor_ind
D/sensors_hal_Util(  854): waitForResponse: timeout=0
D/LPWGController(  854): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  854): current mode = 1  value = 1 1
I/LPWGController(  854): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  854): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/qdlights(  854): set_light_backlight: 0
,I/SensorManager(  854): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  854): activate: handle is 46, disable
,V/sensors_hal_Ctx(  854): activate sensors is 1000000000000
,D/sensors_hal_LP2(  854): enable: handle=46
D/sensors_hal_LP2(  854): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  854): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  244): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  244): hwc_blank: Blanking display: 0
I/DisplayManagerService(  854): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  854): Display changed displayId=0
,V/sensors_hal_SAM(  854): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
,D/sensors_hal_LP2(  854): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1751): Display #0 changed.
,D/qdhwcomposer(  244): hwc_blank: Done blanking display: 0
D/SurfaceControl(  854): Excessive delay in setPowerMode(): 245ms
I/qdhwcomposer(  244): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  854): Got set_interactive hint
,D/KeyguardViewMediator( 1363): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1363): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1335): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1335): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1335): handleNotifyScreenOFF
D/KeyguardViewMediator( 1363): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1363): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1363): unregisterProximitySensor
D/WifiServerServiceExt(  854): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=on, calling pid 854
D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=on
V/voice   (  279): voice_set_parameters: enter: screen_state=on
V/compress_voip(  279): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  279): voice_extn_compress_voip_set_parameters: exit
V/voice   (  279): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  279): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  279): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  279): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  279): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  279): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  279): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  279): adev_set_parameters: exit with code(0)
D/StatusBarWindowView( 1363): onScreenTurnedOff why = 3
,D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/WifiServerServiceExt(  854): set CMD_KT_SCAN_INTERVAL
,D/GpsLocationProvider(  854): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1803): lockStatus = 0
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
D/LEDHandler( 1803): RESTART MSG
,D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 3
D/NfcService( 1785): Discovery configuration equal, not updating.
D/Ulp_jni (  854): JNI:system_update. Event-0
D/SplitWindow(  854): check instance of lgWin Window{3eb7b4c3 u0 SearchPanel}
,D/InputDispatcher(  854): Window went away: Window{339e66a5 u0 SearchPanel}
,I/[SystemUI]Clock( 1363): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1363): time changed, timezoneChanged : false
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2643): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:47:51
,D/WeatherService( 2643): 2 : ACTION screen on
,D/WeatherService( 2643): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2643): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2643): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:47:51
,W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): ACTION_SCREEN_ON
D/AppCleanupService( 4089): android.intent.action.SCREEN_ON
,I/Sensors (  428): sns_pwr.c(301):releasing wakelock
V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=off, calling pid 854
,D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=off
V/voice   (  279): voice_set_parameters: enter: screen_state=off
V/compress_voip(  279): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  279): voice_extn_compress_voip_set_parameters: exit
V/voice   (  279): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  279): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  279): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  279): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  279): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  279): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  279): adev_set_parameters: exit with code(0)
D/WifiController(  854): CMD_SCREEN_OFF 
D/WifiController(  854): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  854): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1803): clear
I/LEDService( 1803): updateLightsLocked : turn on led
E/LEDService( 1803): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1803): Can't handle this request of patternId:0
D/LEDHandler( 1803): RESTART MSG
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2643): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:47:52
D/WeatherService( 2643): 2 : ACTION screen off
D/WeatherService( 2643): 2 : TimeTick Receiver Unregister
D/WeatherService( 2643): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:47:52
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  854): ACTION_SCREEN_OFF
D/AppCleanupService( 4089): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4089): AppUsageStatsSaveTask
E/NxpNfcJni( 1785): getReconnectState = 0x0
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1785): getDefaultRoute
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: 0
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 1
E/NxpNfcJni( 1785): getReconnectState = 0x0
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1363): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{3f1d9140 type 2 when 164017 com.android.systemui} when 164017
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1751): getCallState : 0
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1363): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1363): doKeyguard: not showing because lockscreen is off
I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 174901373324; DSPS: 5829676; Offset : -3015807207
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  854): acquireWakeLockInternal: lock=962103417, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=854
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{2add29be type 2 when 183640 android} when 183640
D/PowerManagerServiceEx(  854): releaseWakeLockInternal: lock=962103417 [*alarm*], flags=0x0
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  479): init target 500000
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1974): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  854): ELAPSED_WAKEUP set : Alarm{29d6da1f type 2 when 189983 com.google.android.gms} when 189983
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 194902057483; DSPS: 6485058; Offset : -3015795295
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 214902812266; DSPS: 7140443; Offset : -3015802436
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 234903568874; DSPS: 7795828; Offset : -3015809340
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  479): init target 500000
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1974): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 254904243761; DSPS: 8451210; Offset : -3015805605
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
D/charger_monitor(  479): init target 500000
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1974): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1974): Disconnected process message: 10, size: 0
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  854): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 274905050681; DSPS: 9106596; Offset : -3015791855
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1974): Disconnected process message: 10, size: 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  854): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1974): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  854): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  854): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  854): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  854): tsOffsetIs: Apps: 294905730726; DSPS: 9761979; Offset : -3015813976
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5720): --= Surplus to requirements =--
I/jxcore-log( 5720): 
I/jxcore-log( 5720): ****TEST TOOK:  ms ****
I/jxcore-log( 5720): 
I/jxcore-log( 5720): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5720): 
,D/AndroidRuntime( 7926): 
D/AndroidRuntime( 7926): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7926): CheckJNI is OFF
,D/AndroidRuntime( 7926): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  854): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  854): Killing 5720:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,W/PackageSettings(  854): Skipping PackageSetting{346527c com.example.hello/10317} due to missing metadata
,I/WindowState(  854): WIN DEATH: Window{15bd0de8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  854): Focus left window: Window{15bd0de8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  854): Window went away: Window{15bd0de8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  854):   Force finishing activity ActivityRecord{14c4c540 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  854): Display changed displayId=0
D/DSDPConnection( 1751): Display #0 changed.
,W/ActivityManager(  854): Spurious death for ProcessRecord{19ea816c 5720:com.test.thalitest/u0a316}, curProc for 5720: null
,I/ActivityManager(  854): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  854):   Force finishing activity ActivityRecord{14c4c540 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  854): Duplicate finish request for ActivityRecord{14c4c540 u0 com.test.thalitest/.MainActivity t222 f}
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardModel( 1363): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
,W/System.err( 3598): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3598): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3598): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3598): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3598): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3598): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3598): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3598): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3598): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3598): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3598): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3598): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/InputReader(  854): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  854): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7952 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1878): [Launcher.java:5203:onStart()]onStart
I/art     ( 5549): Explicit concurrent mark sweep GC freed 19636(1107KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 13MB/17MB, paused 774us total 156.833ms
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 310us total 30.405ms
,I/[LGHome]EVENT( 1878): [Launcher.java:776:onResume()]onResume
I/art     ( 1937): Explicit concurrent mark sweep GC freed 16058(1020KB) AllocSpace objects, 3(71KB) LOS objects, 39% free, 12MB/21MB, paused 2.059ms total 174.665ms
I/[LGHome]EVENT( 1878): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 22.945ms
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/[SystemUI]QSlideListController( 1363): onReceive = android.intent.action.PACKAGE_REMOVED
,D/KeyguardModel( 1363): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1363): createShortcutInfo...
D/KeyguardModel( 1363): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1363): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1878): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1878): [Launcher.java:929:onResume()]onResume end
I/Activity( 1878): Activity.onPostResume() called 
W/ResourceType( 1363): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1363): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 22.075ms
D/KeyguardModel( 1363): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1363): createShortcutInfo...
,I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1363): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1363): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1363): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1363): createShortcutInfo...
,W/ResourceType( 1363): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1363): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1363): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1363): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1363): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1363): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/art     (  854): Explicit concurrent mark sweep GC freed 67998(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 2.943ms total 313.237ms
I/art     (  854): WaitForGcToComplete blocked for 311.710ms for cause Explicit
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/administrator(  854): Handling package changes for user 0
,W/ActivityManager(  854): Activity pause timeout for ActivityRecord{18cf12fd u0 com.lge.launcher2/.Launcher t221}
,I/art     (  854): Explicit concurrent mark sweep GC freed 7461(425KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.395ms total 222.766ms
,I/art     (  854): WaitForGcToComplete blocked for 322.242ms for cause Explicit
I/NotificationService(  854): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService(  854): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  854): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/TaskPersister(  854): removeObsoleteFile: deleting file=222_task.xml
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
,D/WifiController(  854): battery changed pluggedType: 2
W/Settings(  854): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  854): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1974): Disconnected process message: 10, size: 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/AndroidRuntime( 7926): Shutting down VM
I/art     (  854): Explicit concurrent mark sweep GC freed 4449(268KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 5.116ms total 164.708ms
,D/KeyguardModel( 1363): handleShortcutListChanged...
I/Choreographer( 1878): Skipped 41 frames!  The application may be doing too much work on its main thread.
D/KeyguardModel( 1363): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1363): createShortcutInfo...
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
D/KeyguardModel( 1363): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1363): createShortcutInfo...
,W/ResourceType( 1363): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1363): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1363): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1363): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1878): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1878): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourceType( 1363): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1363): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1363): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1363): createShortcutInfo...
W/ResourceType( 1363): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1363): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1363): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1363): createShortcutInfo...
D/KeyguardModel( 1363): handleShortcutListChanged...
,W/ResourcesManager( 7952): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7952): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7952): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemUI[Framework](  854): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/PhoneStatusBar( 1363): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
W/PhoneWindowManagerEx(  854): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  854): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  854): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  854): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2aed8ae6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  854): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  854): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  854): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  854): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  854): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SystemUI[Framework](  854): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2aed8ae6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  854): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1363): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1363): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1363):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1363): , Keyguard show=false, IME shown=false, Panel expanded=false
D/InputDispatcher(  854): Focus entered window: Window{2a5ecce5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1878): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  854): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  854): Got RemoteException sending setActive(false) notification to pid 5720 uid 10316
I/LGEmail ( 7952): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7952): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  854): Timeline: Activity_windows_visible id: ActivityRecord{18cf12fd u0 com.lge.launcher2/.Launcher t221} time:308439
,W/ResourcesManager(  854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/IInputConnectionWrapper( 1878): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1569): Unable to connect to the editor to retrieve text... will retry later
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/PackageChangeReceiver( 7952): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/SQLiteLog( 7585): (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
,E/SQLiteDatabase( 7585): Error inserting package=com.test.thalitest
E/SQLiteDatabase( 7585): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 7585): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 7585): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
E/SQLiteDatabase( 7585): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 7585): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 7585): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
E/SQLiteDatabase( 7585): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
E/SQLiteDatabase( 7585): 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
E/SQLiteDatabase( 7585): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 7585): 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
E/SQLiteDatabase( 7585): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
E/SQLiteDatabase( 7585): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
E/SQLiteDatabase( 7585): 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
E/SQLiteDatabase( 7585): 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
E/SQLiteDatabase( 7585): 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
E/SQLiteDatabase( 7585): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/SQLiteDatabase( 7585): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/SQLiteDatabase( 7585): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/SQLiteDatabase( 7585): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7585): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7585): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 7585): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7585): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7585): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 7585): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
I/ActivityManager(  854): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7987 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  854): Killing 7351:com.google.android.talk/u0a61 (adj 15): empty #11
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/ResourceType(  854): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}

```
