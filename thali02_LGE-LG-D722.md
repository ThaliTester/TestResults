#### Test 5761781115ba656_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
I/ActivityManager(  980): Process com.android.contacts (pid 5446) has died
W/ActivityManager(  980): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  980): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
--------- beginning of main
I/Gmail   ( 5669): Observing account changes for notifications
W/ActivityManager(  980): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 5669): Error finding the version of the Email provider.....
E/Gmail   ( 5669): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5669): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5669): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5669): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5669): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5669): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5669): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5669): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5669): We do not support migrating this version of the Email provider.
I/Gmail   ( 5669): getAccountsCursor
I/Icing   ( 4318): Internal init done: storage state 0
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/Icing   ( 4318): Post-init done
I/art     ( 1729): Explicit concurrent mark sweep GC freed 18425(1093KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 13MB/22MB, paused 1.629ms total 90.121ms
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  980): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5724 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
D/ChimeraCfgMgr( 4318): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4318): Module APK com.google.android.play.games already loaded
I/Gmail   ( 5669): notifyAccountChanged
I/Gmail   ( 5669): getAccountsCursor
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5669): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/PhoneMonitor( 5724): Register our PhoneStateListener
I/Gmail   ( 5669): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  980): Killing 5472:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/Gmail   ( 5669): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5669): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PhoneMonitor( 5724): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5724): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5724): [parse] Load xml
I/art     ( 4008): Explicit concurrent mark sweep GC freed 3192(124KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 409us total 35.258ms
V/TelephonyAutoProfiling( 5724): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5724): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 5724): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  980): failed to open /acct/uid_10069/pid_5472/cgroup.procs: No such file or directory
D/AndroidRuntime( 5720): 
D/AndroidRuntime( 5720): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5720): CheckJNI is OFF
D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 4318): Checkin interval check for package: unspecified last checkin: 1454056106357 min interval config: 0 actual interval: 2074
W/GCoreFlp( 1729): No location to return for getLastLocation()
W/FusedLocationProvider( 1729): location=null
I/CheckinService( 4318): Checking schedule, now: 1454056108464 next: 1454056136304
I/CheckinService( 4318): active receiver: disabled
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@2ea8d1e0 on behalf of 4318
I/Gmail   ( 5669): getAccountsCursor
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@113cc99 on behalf of 4318
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@151aeb5e on behalf of 4318
D/AndroidRuntime( 5720): Calling main entry com.android.commands.am.Am
I/art     (  980): Explicit concurrent mark sweep GC freed 22382(1041KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.473ms total 190.262ms
I/ActivityManager(  980): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager(  980): setTaskToReturnTo : TaskRecord{15cfb011 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  980): setTaskToReturnTo : TaskRecord{15cfb011 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WindowStateEx(  980): AppWindowTokenEx init.. 
D/ContextHelper(  980): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  980): Focus left window: Window{1f8aa1b5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5720): Shutting down VM
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  980): check instance of lgWin Window{1f932413 u0 Starting com.test.thalitest}
I/ActivityManager(  980): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5771 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/ActivityManager(  980): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5788 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/HotwordDetector( 1934): Closing mic
I/CheckinService( 4318): Done disabling old GoogleServicesFramework version
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
,I/MicrophoneInputStream( 1934): mic_close com.google.android.apps.gsa.speech.audio.u@b3fcb01
V/AudioRecord( 1934): stop()
D/AudioRecord( 1934): AudioRecord->stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
D/InitAlarmsService( 3835): Clearing and rescheduling alarms.
V/AudioFlinger(  281): Record stopped OK
V/AudioPolicyManager(  281): stopInput() input 17
V/AudioPolicyService(  281): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  281): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  281): ThreadBase::setParameters() routing=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
I/WindowStateAnimator(  980): Starting window displayed
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb4399000
D/audio_hw_primary(  281): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
I/SystemUI[Framework](  980): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  980): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  980): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  980): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  980): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@ece7e4c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  980): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1373): draw background and invalidate : color = 6000000
D/BarTransitions( 1373): draw background and invalidate : color = f0e0e0e
D/CalendarProvider2( 5565): Scheduling check of next Alarm
D/CalendarProvider2( 5565): SCHEDULE_ALARM_REMOVE
V/audio_hw_primary(  281): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  281): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  281): disable_audio_route: exit
E/audio_hw_primary(  281): disable_snd_device: enter 144
D/hardware_info(  281): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  281): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  281): stop_input_stream: exit: status(0)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  281): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  281): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  281): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyService(  281): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  281): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  281): setParameters(): io 17, keyvalue hotword_active=0, calling pid 281
V/AudioFlinger(  281): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb4399000
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
I/Icing   ( 4318): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
V/AudioRecord( 1934): stop()
V/AudioRecord( 1934): stop()
V/AudioRecord( 1934): stop()
V/AudioFlinger(  281): releasing 16 from 1934 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 17
V/AudioPolicyManager(  281): closeInput(17)
V/AudioFlinger(  281): closeInput() 17
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  980): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): ThreadBase::exit
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioSystem( 1934): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3142): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread 0xb4399000 exiting
V/AudioSystem( 2074): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1373): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb40367a0)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioSystem( 2035): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  281): removeClient_l() pid 1934, calling pid 281
V/AudioSystem( 1748): ioConfigChanged() event 4, ioHandle 17
W/ResourcesManager( 5788): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/HotwordRecognitionRnr( 1934): Stopping hotword detection.
I/HotwordRecognitionRnr( 1934): Hotword detection finished
D/Icing   ( 4318): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 4318): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
D/ContextHelper( 5771): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5771): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5771): Time to load native libraries: 2 ms (timestamps 5561-5563)
I/LibraryLoader( 5771): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5771): Binding Chromium to main looper Looper (main, tid 1) {2a12e05a}
I/LibraryLoader( 5771): Expected native library version number "",actual native library version number ""
I/chromium( 5771): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5771): Initializing chromium process, singleProcess=true
W/art     ( 5771): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5771): ApplicationContext is null in ApplicationStatus
W/chromium( 5771): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5771): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5771): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5771): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5771): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5771): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5771): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5771): Remote Branch: 
I/Adreno-EGL( 5771): Local Patches: 
I/Adreno-EGL( 5771): Reconstruct Branch: 
,I/Babel_SMS( 5788): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5788): MmsConfig.loadMmsSettings
V/AudioPolicyService(  281): registerClient() client 0xb57e86a0, uid 10316
I/Babel_SMS( 5788): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5788): MmsConfig.loadFromDatabase
,D/BluetoothManagerService(  980): Message: 20
D/BluetoothManagerService(  980): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24afddb9:true
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
,E/Babel_SMS( 5788): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5788): MmsConfig.loadFromResources
E/Babel_SMS( 5788): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5788): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5788): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5788): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5788): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5788): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5788): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5788): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5788): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5788): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5788): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5788): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5788): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5788): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5788): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5788): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5788): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5788): found sensor: Motion Accel, handle=46
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/Settings( 5788): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5788): startup - clean
,I/art     ( 5788): CheckpointMarkThreadRoots callback created = 0xb042d850
,W/art     ( 5771): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 5788): CheckpointMarkThreadRoots callback created = 0xb042d830
W/AwContents( 5771): onDetachedFromWindow called when already detached. Ignoring
,I/Babel   ( 5788): deleted: false for 0
D/SystemWebViewEngine( 5771): CordovaWebView is running on device made by: LGE
,W/art     ( 5771): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5771): Attempt to remove local handle scope entry from IRT, ignoring
W/AudioCapabilities( 5788): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5788): Unsupported mime audio/adpcm
W/AudioCapabilities( 5788): Unsupported mime audio/g726
W/AudioCapabilities( 5788): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5788): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5788): Unsupported mime video/mjpg
W/VideoCapabilities( 5788): Unsupported mime video/theora
,I/Activity( 5771): Activity.onPostResume() called 
D/OpenGLRenderer( 5771): Render dirty regions requested: true
I/OpenGLRenderer( 5771): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5771): Enabling debug mode 0
,D/Atlas   ( 5771): Validating map...
,D/SplitWindow(  980): check instance of lgWin Window{3166fa47 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5771): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
W/AudioCapabilities( 5788): Unsupported mime audio/evrc
,W/AudioCapabilities( 5788): Unsupported mime audio/qcelp
W/VideoCapabilities( 5788): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5788): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5788): Unsupported mime audio/qcelp
W/AudioCapabilities( 5788): Unsupported mime audio/evrc
D/InputDispatcher(  980): Focus entered window: Window{3166fa47 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/VideoCapabilities( 5788): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5788): Unsupported profile 4 for video/mp4v-es
,I/CalendarProvider2( 5565): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/InputMethodManagerService(  980): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/ContentResolver( 5565): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  980): Killing 3835:com.android.calendar/u0a13 (adj 15): empty #11
W/VideoCapabilities( 5788): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5788): Unrecognized profile 2130706433 for video/avc
I/Timeline( 5771): Timeline: Activity_idle id: android.os.BinderProxy@2f4faaf1 time:86315
,W/VideoCapabilities( 5788): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5788): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  980): failed to open /acct/uid_10013/pid_3835/cgroup.procs: No such file or directory
,I/ActivityManager(  980): Displayed com.test.thalitest/.MainActivity: +1s350ms
I/Timeline(  980): Timeline: Activity_windows_visible id: ActivityRecord{f395576 u0 com.test.thalitest/.MainActivity t222} time:86374
W/BindingManager( 5771): Cannot call determinedVisibility() - never saw a connection for the pid: 5771
,I/vclib   ( 5788): onServiceConnected
,W/Babel   ( 5788): Attempted to change video mute state without an active call.
W/ResourcesManager( 5788): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5788): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5788): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/JsMessageQueue( 5771): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  980): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5859 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 22.920ms
,I/AudioManager( 5171): getMode name:com.lge.qremote
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 37.156ms
I/AudioManager( 5171): getMode name:com.lge.qremote
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 23.139ms
W/System  ( 5788): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5788): Installed default security provider GmsCore_OpenSSL
I/AudioManager( 5171): getMode name:com.lge.qremote
I/NotificationManager( 5788): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AudioManager( 5171): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5859): Quickset Services start...
,I/UEI.SmartControl( 5859): Manufacture = LGE
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/UEI.SmartControl( 5859): File observer start...
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/UEI.SmartControl( 5859): IR Port is disabled: false
D/UEI.SmartControl( 5859): Starting file observer...
D/UEI.SmartControl( 5859): Extracting JNI libs...
D/WearableService( 1729): callingUid 10006, callindPid: 1729
D/UEI.SmartControl( 5859): --- this system supports 32-bit or 64-bit only
,E/MDM     ( 1729): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 4318): Restart initialization of location
,D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5171): getMode name:com.lge.qremote
,W/GCoreFlp( 1729): No location to return for getLastLocation()
W/FusedLocationProvider( 1729): location=null
I/AudioManager( 5171): getMode name:com.lge.qremote
,I/NotificationManager( 5788): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  980): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5886 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  980): Process com.google.android.apps.docs (pid 5506) has died
,D/UEI.SmartControl( 5859): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5859): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5859): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/AppUp4:AppBoxCP( 5886): onCreate
W/AppUp4:DB( 5886):  [AppBoxDatabaseHelper] construct
,I/UEI.SmartControl( 5859): --- Selecting new region: 2
I/UEI.SmartControl( 5859): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5859): Platform has CIR...
D/UEI.SmartControl( 5859): NO CIR support, need to check package...
I/UEI.SmartControl( 5859): Model: LG-D722 uses JNI
I/AppUp4:DB( 5886):  setFingerPrint start
I/AppUp4:DB( 5886):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
D/jxcore_app_log( 5771): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426127360
D/UEI.SmartControl( 5859): QS Service created
I/AppUp4:DB( 5886):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5886):  SDK version = 0
I/AppUp4:DB( 5886):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5886): AppBoxApplication onCreate()
,E/UEI.SmartControl( 5859): QS start get config
I/chromium( 5771): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/AppUp4:CustModeStarterReceiver( 5886): onReceive
I/AppUp4:CustModeStarterReceiver( 5886): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5886): Context : android.app.ReceiverRestrictedContext@30be277c
D/AppUp4:CustFacade( 5886): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5886): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5886): begin check event
I/AppUp4:CustModeStarterReceiver( 5886): Event For Nothing, skip.
,D/UEI.SmartControl( 5859): Loading JNI Libs...
,D/UEI.SmartControl( 5859):  configuring local db...
I/ActivityManager(  980): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5907 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/art     ( 5771): CheckpointMarkThreadRoots callback created = 0x9b22c4a0
,I/art     ( 5771): CheckpointMarkThreadRoots callback created = 0x9b22c470
W/ResourcesManager( 5907): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5907): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5907): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5859):  ---- Has DB8: true
,D/UEI.SmartControl( 5859): QS start statue = true Error code = 0
D/UEI.SmartControl( 5859): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5859): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5859): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5859): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5859): IrrcClient ++ 
D/irrcClient( 5859): getIrrcService ++ 
,D/irrcClient( 5859): getIrrcService -- 
D/irrcClient( 5859): IrrcClient -- 
W/irrc_jni( 5859): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5859): Services init done
,D/UEI.SmartControl( 5859): QS Service init finished
D/UEI.SmartControl( 5859): QS Service version name: 0.1.73
D/UEI.SmartControl( 5859): QS Service version code: 1073
I/UEI.SmartControl( 5859): Device manager: loading config....
D/UEI.SmartControl( 5859): Service requested: Control
D/UEI.SmartControl( 5859): Config is loaded...
,I/AppConfig( 5907): Total System Memory = 906309632
,I/GalleryUtils( 5907): Application Heap = 96 MB
I/AppConfig( 5907): App Tier : NOT_DEF
D/UEI.SmartControl( 5859):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5859): Notify AllClients services are ready: 0
,D/SystemHelper( 5907): region [EU], country [EU], operator [OPEN], sub-operator []
D/UEI.SmartControl( 5859): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5859): Internal service binding...
D/UEI.SmartControl( 5859): -----IControl: 11
,D/UEI.SmartControl( 5859): Caller: com.lge.qremote
D/UEI.SmartControl( 5859): ------------ IControl registerCallback...
I/UEI.SmartControl( 5859): Registering callback...
D/UEI.SmartControl( 5859): -----IControl: 19
D/UEI.SmartControl( 5859): Caller: com.lge.qremote
I/UEI.SmartControl( 5859): Registering Services Ready callback...
,I/UEI.SmartControl( 5859): Notify client services are ready...
D/UEI.SmartControl( 5859): -----IControl: 8
D/UEI.SmartControl( 5859): Caller: com.lge.qremote
,I/ActivityManager(  980): Killing 5267:com.lge.bnr/1000 (adj 15): empty #11
,I/ActivityManager(  980): Killing 5489:com.lge.eula/1000 (adj 15): empty #12
,W/libprocessgroup(  980): failed to open /acct/uid_1000/pid_5267/cgroup.procs: No such file or directory
,I/ActivityManager(  980): Killing 5537:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  980): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5932 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
W/libprocessgroup(  980): failed to open /acct/uid_1000/pid_5489/cgroup.procs: No such file or directory
,W/libprocessgroup(  980): failed to open /acct/uid_10086/pid_5537/cgroup.procs: No such file or directory
,W/ResourcesManager( 5932): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5932): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5932): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5932): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5932): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 5932): BUILD Country: EU
I/SystemConfig( 5932): BUILD Operator: OPEN
,I/ActivityManager(  980): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5956 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  980): Killing 5598:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_10036/pid_5598/cgroup.procs: No such file or directory
,I/SystemConfig( 5932): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5932): existFile = false
I/SystemConfig( 5932): canReadFile = false
I/SystemConfig( 5932): systemFeature RCS result false
D/SystemConfig( 5932): refreshRcsSupport() :false
I/LockScreenSettings( 5956): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5956): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5956): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5956): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5956): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5956): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  980): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5974 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  980): Killing 5037:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_10006/pid_5037/cgroup.procs: No such file or directory
,W/ResourcesManager( 5974): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GAV2    ( 5669): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
,I/art     ( 4318): Explicit concurrent mark sweep GC freed 48505(3MB) AllocSpace objects, 30(480KB) LOS objects, 40% free, 14MB/23MB, paused 1.727ms total 140.457ms
,W/SQLiteConnectionPool( 4318): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/UpdateIcingCorporaServi( 1934): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/jxcore-log( 5771): Initializing JXcore engine
W/jxcore-log( 5771): JXcore engine is ready
,I/ActivityManager(  980): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6001 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  980): Killing 5669:com.google.android.gm/u0a53 (adj 15): empty #11
I/UpdateIcingCorporaServi( 1934): UpdateCorporaTask done [took 91 ms] updated apps [took 91 ms] 
,W/libprocessgroup(  980): failed to open /acct/uid_10053/pid_5669/cgroup.procs: No such file or directory
,W/Thread-672( 5904): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8255]" dev="sockfs" ino=8255 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-672( 5904): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-672( 5904): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6069]" dev="sockfs" ino=6069 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-672( 5904): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-672( 5904): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-672( 5904): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26980]" dev="sockfs" ino=26980 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5771): Starting JXcore engine
,W/jxcore-log( 5771): Platform android
W/jxcore-log( 5771): 
W/jxcore-log( 5771): Process ARCH arm
W/jxcore-log( 5771): 
,D/Finsky  ( 6001): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/Finsky  ( 6001): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6001): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6001): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6001): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@18e10b3f on behalf of 6001
,D/Finsky  ( 6001): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6001): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6001): Skipping gmscore version check
I/ActivityManager(  980): Killing 5724:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  980): failed to open /acct/uid_10038/pid_5724/cgroup.procs: No such file or directory
,I/AudioManager( 5171): getMode name:com.lge.qremote
D/PackageBroadcastService( 4318): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 6001): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/jxcore-log( 5771): JXcore Cordova bridge is ready!
I/jxcore-log( 5771): 
W/jxcore-log( 5771): JXcore engine is started
,I/art     (  980): Explicit concurrent mark sweep GC freed 23998(1165KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.914ms total 202.460ms
,V/AlarmManager(  980): ELAPSED_WAKEUP set : Alarm{144c6917 type 2 when 90231 com.android.providers.calendar} when 90231
I/PackageBroadcastService( 4318): Null package name or gms related package.  Ignoreing.
V/AlarmManager(  980): RTC_WAKEUP set : Alarm{cf906ed type 0 when 1454056114294 com.google.android.googlequicksearchbox} when 1454056114294
,D/Finsky  ( 6001): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  980): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6051 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/Icing   ( 4318): updateResources: need to parse f{com.google.android.gms}
,I/jxcore-log( 5771): Toggling radios to true
I/jxcore-log( 5771): 
,D/BluetoothAdapter( 5771): enable(): BT is already enabled..!
D/WifiServiceImplEx(  980): setWifiEnabled: true pid=5771, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  980): setWifiEnabled: true pid=5771, uid=10316
D/WifiServiceImplEx(  980): disconnect pid=5771, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  980): reconnect pid=5771, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5771): Radios toggled
I/jxcore-log( 5771): 
I/jxcore-log( 5771): My device name is: LGE-LG-D722
I/jxcore-log( 5771): 
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2685): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2685): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  980): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  980): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/WfdsMonitor( 1800): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/ActivityManager(  980): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6079 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,D/LGWifiP2pService(  980): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  980): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  276): Clearing all IP addresses on wlan0
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 7
,D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/NativeCrypto( 1729): Read error: ssl=0xaaedde00: I/O error during system call, Connection timed out
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  980): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  980): ignoring duplicate network state non-change
D/WifiHS20(  980): hidePasspointNotification off =false
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  980): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  980): hidePasspointNotification off =false
E/WifiStateMachine(  980): Start Disconnecting Watchdog 1
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:34.776 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/wpa_supplicant( 2685): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:34.787 DNS addrs= 0.0.0.0, 0.0.0.0, 
V/NativeCrypto( 1729): SSL shutdown failed: ssl=0xaaedde00: I/O error during system call, Broken pipe
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  980): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): ValidatedState{ when=-7ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): DefaultState{ when=-24ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): Forcing reevaluation
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
,D/CommandListener(  276): Clearing all IP addresses on wlan0
D/ConnectivityService(  980): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  980): disableDataServiceNotify
D/DSQN    (  980): stop dsqn bin
D/WifiHS20(  980): hidePasspointNotification off =false
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:34.893 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiNetworkAgent(  980): NetworkAgent: NetworkAgent channel lost
,D/WifiHS20(  980): hidePasspointNotification off =false
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:34.918 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  980): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:34.924 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,D/WifiServerServiceExt(  980): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  980): setSupplicantStateDISCONNECTED
D/ConnectivityService(  980):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  980):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/DhcpStateMachine(  980): StoppedState
D/DhcpStateMachine(  980): StoppedState{ when=-152ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt(  980): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  980): setSupplicantStateSCANNING
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  980): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/Nat464Xlat(  980): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  980): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  980): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/ConnectivityService(  980): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/Tethering(  980): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1836): |CORE| No family connected
D/ConnectivityService(  980): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  980): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  980): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  980): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  980): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  980): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  980): [LG_RESTRICTED] !!!isConnected  type  :1
D/WIFI    (  980): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  980):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  980): Removing idletimer
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/Tethering(  980): MasterInitialState.processMessage what=3
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1748): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,E/UpdateRequestReceiver( 6079): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6079): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  980): Killing 5565:com.android.providers.calendar/u0a14 (adj 15): empty #11
,E/UpdateRequestReceiver( 6079): Received malformed URL while handling Gservices.CHANGED_ACTION
W/libprocessgroup(  980): failed to open /acct/uid_10014/pid_5565/cgroup.procs: No such file or directory
,E/UpdateRequestReceiver( 6079): Received malformed URL while handling Gservices.CHANGED_ACTION
I/ActivityManager(  980): Killing 5886:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_10011/pid_5886/cgroup.procs: No such file or directory
,I/CheckinService( 4318): Checkin interval check for package: unspecified last checkin: 1454056106357 min interval config: 0 actual interval: 8974
,I/CheckinService( 4318): Checking schedule, now: 1454056115344 next: 1454056136304
I/CheckinService( 4318): active receiver: disabled
,I/GservicesUpdateTask( 1934): Updating Gservices keys
I/SystemUpdateService( 4318): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 4318): onCreate
D/SystemUpdateService( 4318): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 4318): cancelUpdate (empty URL)
I/SystemUpdateService( 4318): active receiver: disabled
,I/NotificationManager( 4318): com.google.android.gms: cancel(2130838165) by com.google.android.gms
I/NotificationManager( 4318): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,I/GStaticConfiguration( 1934): #getNewConfigurationUrl [pref=2015_09_15_14_04_18, gservice=2016_01_27_20_58_17]
I/art     ( 4008): Explicit concurrent mark sweep GC freed 4066(175KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.094ms total 41.225ms
,W/GStaticConfiguration( 1934): IOException error in updating the configuration
I/GStaticConfiguration( 1934): Configuration not updated - error
,I/art     ( 4008): Explicit concurrent mark sweep GC freed 2776(108KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 981us total 24.679ms
,I/art     ( 4318): Explicit concurrent mark sweep GC freed 15588(857KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 14MB/23MB, paused 1.394ms total 69.933ms
,I/Icing   ( 4318): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2685): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/SystemUpdateService( 4318): onDestroy
,D/LocSvc_java(  980): onReceive
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:35.964 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  980): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  980): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:35.967 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
E/DynamiteModule( 4318): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 4318): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 4318): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 4318): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 4318): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 4318): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 4318): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 4318): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 4318): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 4318): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 4318): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 4318): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 4318): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 4318): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 4318): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 4318): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 4318): 	at android.app.ActivityThread.main(Activi,tyThread.java:5376)
E/DynamiteModule( 4318): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 4318): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 4318): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 4318): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 4318): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 4318): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 4318): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 4318): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 4318): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 4318): 		... 17 more
E/DynamiteModule( 4318): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,I/wpa_supplicant( 2685): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  980): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  980): setSupplicantStateASSOCIATED
I/DynamiteModule( 4318): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 4318): Selected local version of com.google.android.gms.flags
I/Icing   ( 4318): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:36.041 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:36.044 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/WifiServerServiceExt(  980): SUPPLICANT_STATE_CHANGED_ACTION
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
D/WifiServerServiceExt(  980): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,I/wpa_supplicant( 2685): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiServerServiceExt(  980): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  980): setSupplicantStateGROUP_HANDSHAKE
I/wpa_supplicant( 2685): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
,I/WifiServiceExtension(  980): setVHTCapabilityType  : false
I/WifiServerServiceExt(  980): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  980): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  980): setSecurityType  : 2
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:36.118 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:36.123 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/ConnectivityService(  980): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  980): Got NetworkAgent Messenger
D/ConnectivityService(  980): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  980): NetworkAgent connected
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
E/WifiConfigStore(  980): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/ActivityManager(  980): Killing 5788:com.google.android.talk/u0a61 (adj 15): empty #11
,E/WifiConfigStore(  980): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/SystemEventReceiver( 4318): Received GSERVICES_CHANGED broadcast
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  276): Setting iface cfg
E/WifiStateMachine(  980): Start Dhcp Watchdog 2
D/DhcpStateMachine(  980): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  980): WaitBeforeStartState
D/ConnectivityService(  980): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,W/libprocessgroup(  980): failed to open /acct/uid_10061/pid_5788/cgroup.procs: No such file or directory
,I/OcrUtils( 4318): Updating ocr activity enabled=false
E/WifiStateMachine(  980): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  980): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  980): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@cd45126 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@cd45126 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  980): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  980): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  980): DHCP Start wake lock is acquired.
D/CommandListener(  276): Setting iface cfg
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  276): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  980): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  980): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  980): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  980): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  980): setSupplicantStateCOMPLETED
D/ConnectivityService(  980): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/LGWifiP2pService(  980): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  980): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  980): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/ConnectivityService(  980): ignoring duplicate network state non-change
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:36.329 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  980): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:36.335 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
D/ConnectivityService(  980): Adding iface wlan0 to network 101
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/WifiHS20(  980): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  980): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine(  980): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:36.351 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:36.355 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
E/ConnectivityService(  980): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  980): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  980): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  276): netlink response contains error (File exists)
D/ConnectivityService(  980): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  980): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  980): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  980): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  980): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  980): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  980): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  980): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  980):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  980):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  980):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  980):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  980):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  980): currentScore = 0, newScore = 20
D/ConnectivityService(  980):    accepting network in place of null
D/ConnectivityService(  980): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  980): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  980):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  980): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  980): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  980): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): [LWD] Start DNSResolver start to wait
,D/ConnectivityService(  980): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  980): [e] list.add(nai) empty : false size: 1
,D/ConnectivityService(  980): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  980): validation of new default Network = false
D/ConnectivityService(  980): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  980): enableDataServiceNotify 
D/DSQN    (  980): start dsqn bin
I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): [LWD] wait 500ms before dns check
D/ConnectivityService(  980): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  980):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  980):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  980): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = 1
I/DSQN    ( 6140): DSQN samuel.seo ver 141203
E/DSQN    ( 6140): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6140): created command queue thread
I/DSQN    ( 6140): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6140): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/InputReader(  980): Reconfiguring input devices.  changes=0x00000010
,V/NetworkPolicy(  980): [LG_RESTRICTED] checkMobilePolicy_type()
D/administrator(  980): Handling package changes for user 0
,D/DhcpStateMachine(  980): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  980): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  980): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/dhcpcd  ( 6144): version 5.5.6 starting
E/dhcpcd  ( 6144): get_duid: Read-only file system
W/ActivityManager(  980): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,I/dhcpcd  ( 6144): wlan0: rebinding lease of 192.168.1.134
,D/OcrModelManager( 4318): Updating downloaded model state (gservices changed)
,I/NotificationService(  980): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  980): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  980): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  980): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/Tethering(  980): MasterInitialState.processMessage what=3
I/art     ( 4008): Explicit concurrent mark sweep GC freed 2431(97KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.433ms total 32.865ms
,D/UEI.SmartControl( 5859): Internal timer expired: 1
W/ResourcesManager(  980): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): [LWD] DNSResolver start dns
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
,V/AlarmManager(  980): ELAPSED_WAKEUP set : Alarm{1cfaa7fd type 2 when 92991 com.google.android.gms} when 92991
,W/ResourceType(  980): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/art     ( 1729): Explicit concurrent mark sweep GC freed 15283(839KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 13MB/22MB, paused 1.546ms total 104.824ms
D/GCM     ( 1729): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
V/BackupManagerService(  980): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
V/BackupManagerService(  980): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@37ff084a
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  980): Killing 5907:com.android.gallery3d/u0a23 (adj 15): empty #11
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
W/libprocessgroup(  980): failed to open /acct/uid_10023/pid_5907/cgroup.procs: No such file or directory
,I/ActivityManager(  980): Process com.google.android.apps.plus (pid 5974) has died
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 1729): propertyValue:false
D/ConnectivityService(  980): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  980): identical MTU - not setting
D/Nat464Xlat(  980): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  980): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  980):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  980):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  980): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  980): Wi-Fi IP changed. Lp difference / No Route difference
,D/DSQN    (  980): enableDataServiceNotify 
D/DSQN    (  980): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524295
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:37.363 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/DSQN    (  980): dsqn is running restart
I/NotificationManager(  980): android: cancelAsUser(-591465577) by android
I/DSQN    ( 6160): DSQN samuel.seo ver 141203
,E/DSQN    ( 6160): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6160): created command queue thread
I/DSQN    ( 6160): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6160): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  980): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): [LWD] DNSResolver end dns
,I/DSQN    ( 6160): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6160): restart monitoring
D/LGDataListener(  276): argv[0]=dsqncommand
D/LGDataListener(  276): argv[1]=wlan0
D/LGDataListener(  276): argv[2]=1
D/LGDataListener(  276): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  980): DSQM DsqnNotification wlan0  1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): Checking http://clients3.google.com/generate_204 on "NG700"
D/DSQN    (  980): start to monitor internet connection
I/DSQN    ( 6160): dsqn report finish
D/ConnectivityService(  980): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/GCoreNlp( 1729): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/sensors_hal_Time(  980): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  980): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  980): tsOffsetIs: Apps: 93644291426; DSPS: 3159866; Offset : -2796922498
,D/LocationProviderProxy(  980): applying state to connected service
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 08:28:37 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454056117689], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454056117458]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): Validated
D/ConnectivityService(  980): Validated NetworkAgentInfo [WIFI () - 101]
D/WifiDataContinuityService(  980): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  980): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  980):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  980):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  980):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  980): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  980): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  980):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  980):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  980): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  980): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  980): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1748): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/WifiServerServiceExt(  980): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  980): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  980):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,I/GCoreUlr( 1729): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
I/GCoreUlr( 1729): DispatchingService.onCreate()
,D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/dhcpcd  ( 6144): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/ActivityManager(  980): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6171 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/dhcpcd  ( 6144): wlan0: leased 192.168.1.134 for 86400 seconds
,W/GeofencerStateMachine( 1729): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1729): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/GCoreUlr( 1729): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
D/ConnectivityService(  980): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  980): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  980): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  980): onReceive
D/LocSvc_java(  980): got connectivity action
D/LocSvc_java(  980): broadcast - no network connections
D/LocSvc_java(  980): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  980): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  980): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  980): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  980): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  980): onReceive
D/LocSvc_java(  980): got connectivity action
D/LocSvc_java(  980): broadcast - no network connections
D/LocSvc_java(  980): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  980): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  980): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  980): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  980): ignore wifi update if we are not in OPENING or CLOSING
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  980): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  980): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  980): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PhoneMonitor( 6171): Register our PhoneStateListener
,D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  980): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  980): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  980): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  980): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  980): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  980): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  980): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  980): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  980): RunningState
V/SetupWizard( 6171): Connected to Gservices successfully
,V/AlarmManager(  980): RTC_WAKEUP set : Alarm{3a951b5a type 0 when 1454056118153 com.android.vending} when 1454056118153
,D/Finsky  ( 6001): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/art     (  980): Explicit concurrent mark sweep GC freed 83930(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.967ms total 173.350ms
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneMonitor( 6171): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6171): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6171): [parse] Load xml
V/TelephonyAutoProfiling( 6171): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6171): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PhoneMonitor( 6171): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  980): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6214 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ctxmgr  ( 1729): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1729): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
I/NotificationManager(  980): android: cancelAsUser(2) by android
,I/GCoreUlr( 1729): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1729): Unbound from all location providers
I/GCoreUlr( 1729): Place inference reporting - stopped
,I/GCoreUlr( 1729): DispatchingService.onDestroy()
I/GCoreUlr( 1729): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1729): Unbound from all location providers
I/GCoreUlr( 1729): Place inference reporting - stopped
D/libc-netbsd( 6001): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6001): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6001): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6001): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  980): Process com.android.contacts (pid 5932) has died
,W/ActivityManager(  980): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6214): getAccountsCursor
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6214): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  980): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6214): Error finding the version of the Email provider.....
E/Gmail   ( 6214): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6214): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6214): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6214): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6214): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6214): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6214): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6214): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6214): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6214): getAccountsCursor
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  980): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  980): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6214): Observing account changes for notifications
I/ActivityManager(  980): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6261 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 364us total 23.805ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.136ms
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:28:39.252 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 24.469ms
,I/Gmail   ( 6214): notifyAccountChanged
I/Gmail   ( 6214): getAccountsCursor
I/Gmail   ( 6214): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6214): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6214): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6214): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/ResourcesManager( 6261): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     ( 4008): Explicit concurrent mark sweep GC freed 2946(117KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 487us total 42.502ms
V/WifiInternetCheck(  980): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
D/ConnectivityService(  980): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/NotificationManager( 1934): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ActivityManager(  980): Process com.lge.qremote (pid 5171) has died
,D/UEI.SmartControl( 5859): Service.onUnbind: IControl
D/UEI.SmartControl( 5859): Service.onDestroy
D/CalendarApplication( 6261): CalendarApplication.onCreate()
D/UEI.SmartControl( 5859): Shutdown IRRCPlayer... 
D/LocSvc_java(  980): onReceive
D/LocSvc_java(  980): got connectivity action
D/LocSvc_java(  980): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  980): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  980): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  980): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  980): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  980): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  980): ignore wifi update if we are not in OPENING or CLOSING
,D/PreferenceKeysParser( 6261): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6261): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@16580e6f, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@30be277c, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@36e6c805, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2a12e05a, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@a01228b, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1d843f68, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@f10df81, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2d0ea826, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@19dd5c67, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1411ea14, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@206af2bd, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1ead20b2, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@b595803, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@232d9380, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3258fdb9, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@34895fe, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@40f715f, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3d9867ac, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@482bc75, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3894140a, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3ee3c47b, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1efa5298, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2f4faaf1, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@126766d6, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@36e02d57, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@138e0044, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1023052d, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@384b1a62, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@23d047f3, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@e8cdcb0, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3d57c729, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@fc47aae, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@249d704f, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3b5b13dc, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3dfcace5, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3f6193ba, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@336ac26b, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@357391c8, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1503261, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@16853186, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3f711a47, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1314027
W/irrc_jni,( 5859): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5859): ~IrrcClient ++ 
D/irrcClient( 5859): ~IrrcClient -- 
W/irrc_jni( 5859): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5859): Blaster closed
D/UEI.SmartControl( 5859): Blaster closed
D/UEI.SmartControl( 5859): Shut down QS...
D/UEI.SmartControl( 5859): Stopped file observer...
I/UEI.SmartControl( 5859): QS lib stop result = true
,D/UEI.SmartControl( 5859): QS shutdown complete
D/GeneralPreferenceUtils( 6261): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,D/Config  ( 6261): [init]
I/Config  ( 6261): LGCalendar ver.4.40.17
I/Config  ( 6261): start check model
I/Config  ( 6261): start check native_ca
I/Config  ( 6261): Config Operator=OPEN, Country=EU
D/Config  ( 6261): [setDefaultValuesToPref]
D/Config  ( 6261): [parseProfiles]
D/ProfilesParser( 6261): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6261): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6261): [updateProfiletoCountryInfo]
,D/GeneralPreference( 6261): [checkAndMigrateOldPreference]
D/AlertReceiver( 6261): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6261): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6261): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/Gmail   ( 6214): getAccountsCursor
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AlertUtils( 6261): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 6001): propertyValue:false
D/libc-netbsd( 6001): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6001): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 6261): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6261): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6261): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6261): End InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6261): onHandleIntent
D/HolidayDataLoader( 6261): readJsonAsset : holiday.json
,D/AlertService( 6261): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6261): [updateWidgets] 
,D/MonthWidgetProvider( 6261): [onReceive]
D/CalendarWidgetProvider( 6261): [onReceive]
D/CalendarWidgetProvider( 6261): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6261): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6261): [onReceive]
D/CalendarWidgetProvider( 6261): [onReceive]
D/CalendarWidgetProvider( 6261): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6261): [onCreate] mContext.getPackageName() = com.android.calendar
,D/libc-netbsd( 6001): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6001): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  980): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6293 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,E/HolidayIntentService( 6261): onHandleIntent:holiday data empty
,W/ResourcesManager( 6293): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/BluetoothManagerService(  980): Message: 20
D/BluetoothManagerService(  980): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b4e730e:true
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
,D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  980): Process com.uei.lg.quicksetsdk.lite (pid 5859) has died
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  980): propertyValue:false
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  980): propertyValue:false
I/ActivityManager(  980): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6317 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6293): Create singleton instance
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  980): android: cancelAsUser(2) by android
,V/WifiInternetCheck(  980): isHttpConnectionAvailable - We got a valid response : 204
,I/qtaguid ( 6001): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6001): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6001): untagSocket(41) failed with errno -22
D/UEI.SmartControl( 6317): Quickset Services start...
I/UEI.SmartControl( 6317): Manufacture = LGE
D/UEI.SmartControl( 6317): File observer start...
E/UEI.SmartControl( 6317): IR Port is disabled: false
D/UEI.SmartControl( 6317): Starting file observer...
,D/UEI.SmartControl( 6317): Extracting JNI libs...
D/UEI.SmartControl( 6317): --- this system supports 32-bit or 64-bit only
I/AudioManager( 6293): getMode name:com.lge.qremote
D/Finsky  ( 6001): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/UEI.SmartControl( 6317): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6317): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6317): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ActivityManager(  980): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6342 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UEI.SmartControl( 6317): --- Selecting new region: 2
I/UEI.SmartControl( 6317): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6317): Platform has CIR...
D/UEI.SmartControl( 6317): NO CIR support, need to check package...
I/UEI.SmartControl( 6317): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6317): QS Service created
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/UEI.SmartControl( 6317): QS start get config
,I/ActivityManager(  980): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6360 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/UEI.SmartControl( 6317): Loading JNI Libs...
D/UEI.SmartControl( 6317):  configuring local db...
,W/ResourcesManager( 6342): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     ( 1729): Explicit concurrent mark sweep GC freed 26283(1765KB) AllocSpace objects, 24(384KB) LOS objects, 39% free, 13MB/23MB, paused 1.895ms total 96.044ms
I/NotificationManager(  980): android: cancelAsUser(2) by android
,D/CalendarProvider2( 6342): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@38107049
,I/art     (  980): Explicit concurrent mark sweep GC freed 23023(1225KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.772ms total 180.221ms
,D/CalendarProvider2( 6342): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6342): Created com.android.providers.calendar.CalendarAlarmManager@2a12e05a(com.android.providers.calendar.CalendarProvider2@38107049)
D/CalendarProviderBroadcastReceiver( 6342): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 6342): [IntentService] WakeLock acquire, start IntentSerivce
I/AudioManager( 6293): getMode name:com.lge.qremote
W/ResourcesManager( 6360): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6360): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6342): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6342): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6342): [getOrCreateCalendarAlarmManager]
I/AudioManager( 6293): getMode name:com.lge.qremote
D/UEI.SmartControl( 6317):  ---- Has DB8: true
,D/UEI.SmartControl( 6317): QS start statue = true Error code = 0
D/UEI.SmartControl( 6317): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6317): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6317): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6317): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6317): IrrcClient ++ 
D/irrcClient( 6317): getIrrcService ++ 
,D/irrcClient( 6317): getIrrcService -- 
D/irrcClient( 6317): IrrcClient -- 
W/irrc_jni( 6317): IRRCPlayer_nativeInit -- 
I/ActivityManager(  980): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6379 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/UEI.SmartControl( 6317): Services init done
,I/UEI.SmartControl( 6317): Device manager: loading config....
D/UEI.SmartControl( 6317): QS Service init finished
,D/UEI.SmartControl( 6317): QS Service version name: 0.1.73
I/MultiDex( 6360): VM with version 2.1.0 has multidex support
I/MultiDex( 6360): install
I/MultiDex( 6360): VM has multidex support, MultiDex support library is disabled.
D/UEI.SmartControl( 6317): QS Service version code: 1073
D/UEI.SmartControl( 6317): Service requested: Control
D/UEI.SmartControl( 6317): Config is loaded...
,D/UEI.SmartControl( 6317):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6317): Notify AllClients services are ready: 0
,D/CalendarProvider2( 6342): [IntentService] Release Lock
D/CalendarProvider2( 6342): CalendarProviderIntentService.onDestroy()
D/UEI.SmartControl( 6317): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6317): Internal service binding...
D/UEI.SmartControl( 6317): -----IControl: 11
D/UEI.SmartControl( 6317): Caller: com.lge.qremote
D/UEI.SmartControl( 6317): ------------ IControl registerCallback...
I/UEI.SmartControl( 6317): Registering callback...
I/qtaguid ( 6001): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6001): Untagging socket 41 failed errno=-22
D/UEI.SmartControl( 6317): -----IControl: 19
,D/UEI.SmartControl( 6317): Caller: com.lge.qremote
I/UEI.SmartControl( 6317): Registering Services Ready callback...
W/NetworkManagementSocketTagger( 6001): untagSocket(41) failed with errno -22
I/UEI.SmartControl( 6317): Notify client services are ready...
D/UEI.SmartControl( 6317): -----IControl: 8
D/UEI.SmartControl( 6317): Caller: com.lge.qremote
W/ResourcesManager( 6379): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6379): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
V/JNIHelp ( 6360): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ResourcesManager( 6379): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6379): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6379): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ActivityThread( 6360): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6360): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1af92c0c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6360): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6360): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6360): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 6360): Reading stored module config
,I/IndexDatabaseHelper( 6379): Using schema version: 115
I/IndexDatabaseHelper( 6379): Index is fine
,D/ChimeraCfgMgr( 6360): Loading module com.google.android.gms.car from APK com.google.android.gms
,V/AlarmManager(  980): RTC_WAKEUP set : Alarm{3caa3f46 type 0 when 1454056121706 com.android.vending} when 1454056121706
,D/CAR.SERVICE( 6360): Connecting to CarCallService...
,D/NativeLibraryUtils( 6360): Install completed successfully. count=14 extracted=0
,I/art     ( 6001): CheckpointMarkThreadRoots callback created = 0xb057c380
I/art     ( 6360): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6360): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/art     ( 6001): CheckpointMarkThreadRoots callback created = 0xb057c340
,D/CAR.SERVICE( 6360): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 6360): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6360): Creating a new PhoneAdapter instance
,W/ActivityManager(  980): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6360): setListener: com.google.android.gms.car.dn@2c61d24b
W/ActivityManager(  980): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6360): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6360): Starting CarCallService with initial phone null
D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
I/NotificationManager( 6360): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
I/ActivityManager(  980): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6410 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  980): Killing 5956:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
D/CAR.SERVICE( 6360): Package validated; name: com.android.vending
,I/ActivityManager(  980): Process com.google.android.partnersetup (pid 6051) has died
,W/libprocessgroup(  980): failed to open /acct/uid_10069/pid_5956/cgroup.procs: No such file or directory
I/NotificationManager( 6001): com.android.vending: cancel(10436) by com.android.vending
,D/Finsky  ( 6001): [710] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
V/Finsky  ( 6001): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/Finsky  ( 6001): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/PCSuite ( 6410): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6410): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6410): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  980): Process com.google.android.gm (pid 6214) has died
,V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
I/PCSuite ( 6410): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6410): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6410): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  980): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6435 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  980): android: cancelAsUser(2) by android
,W/ResourcesManager( 6435): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6435): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6435): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6435): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6435): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6435): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6435): MmsConfig.loadFromResources
E/Babel_SMS( 6435): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6435): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6435): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6435): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6435): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6435): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6435): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6435): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6435): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6435): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6435): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6435): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6435): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6435): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6435): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6435): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6435): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6435): found sensor: Motion Accel, handle=46
,I/qtaguid ( 6001): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6001): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6001): untagSocket(41) failed with errno -22
D/Finsky  ( 6001): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.apps.maps to true
,I/ActivityManager(  980): Process com.google.android.configupdater (pid 6079) has died
,I/art     ( 6435): CheckpointMarkThreadRoots callback created = 0xb042d410
,W/Settings( 6435): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6435): startup - clean
I/art     ( 6435): CheckpointMarkThreadRoots callback created = 0xb042d3f0
,I/Babel   ( 6435): deleted: false for 0
V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
I/PCSuite ( 6410): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6410): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6410): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
W/AudioCapabilities( 6435): Unsupported mime audio/x-lg-flac
I/PCSuite ( 6410): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6410): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6410): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/AudioCapabilities( 6435): Unsupported mime audio/adpcm
V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6435): Unsupported mime audio/g726
,W/AudioCapabilities( 6435): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6435): Unsupported mime audio/wma-voice
D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
W/VideoCapabilities( 6435): Unsupported mime video/mjpg
W/VideoCapabilities( 6435): Unsupported mime video/theora
,D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/ResourcesManager( 6001): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6001): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/AudioCapabilities( 6435): Unsupported mime audio/evrc
,V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6379): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6435): Unsupported mime audio/qcelp
,D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
W/VideoCapabilities( 6435): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6435): Unsupported mime audio/amr-wb-plus
D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
W/AudioCapabilities( 6435): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6435): Unsupported mime audio/evrc
W/ResourcesManager( 6001): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
W/VideoCapabilities( 6435): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6435): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6435): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6435): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6435): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  980): Process com.google.process.gapps (pid 4008) has died
W/VideoCapabilities( 6435): Unrecognized profile 2130706433 for video/avc
D/Finsky  ( 6001): [1] DailyHygiene.access$600: Logging device features
V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
V/AlarmManager(  980): RTC_WAKEUP set : Alarm{3fb502e7 type 0 when 1454056123826 com.android.vending} when 1454056123826
,I/vclib   ( 6435): onServiceConnected
W/Babel   ( 6435): Attempted to change video mute state without an active call.
V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
I/NotificationManager( 6435): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/DeviceConnectionService( 1729): client connected with version: 8296000
,D/WearableService( 1729): callingUid 10006, callindPid: 1729
V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
I/jxcore-log( 5771): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5771): 
,D/Finsky  ( 6001): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 6001): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  980): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6472 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
I/PCSuite ( 6410): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6410): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6379): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/GservicesProvider( 6472): Gservices pushing to system: true; secure/global: true
,D/WiFiOffLoadBroadcast( 6379): MCCMNC not supported: null
I/ActivityManager(  980): Process com.google.android.talk (pid 6435) has died
,I/PCSuite ( 6410): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6410): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/GoogleHttpClient( 6472): GMS http client unavailable, use old client
,I/ActivityManager(  980): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6492 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/GoogleHttpClient( 6472): GMS http client unavailable, use old client
W/ResourcesManager( 6492): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  980): RTC_WAKEUP set : Alarm{2a0dd6f5 type 0 when 1454056124514 com.google.android.googlequicksearchbox} when 1454056124514
,I/Babel_SMS( 6492): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6492): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6492): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6492): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6492): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6492): MmsConfig.loadFromResources
E/Babel_SMS( 6492): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6492): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6492): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6492): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6492): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6492): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6492): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6492): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6492): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6492): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6492): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6492): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6492): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6492): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6492): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6492): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6492): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6492): found sensor: Motion Accel, handle=46
,W/Settings( 6492): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6492): startup - clean
I/art     ( 6492): CheckpointMarkThreadRoots callback created = 0xb042d8b0
,W/PackageSettings(  980): Skipping PackageSetting{3273f85c com.example.hello/10317} due to missing metadata
,I/art     ( 6492): CheckpointMarkThreadRoots callback created = 0xb042d890
I/Babel   ( 6492): deleted: false for 0
,W/AudioCapabilities( 6492): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6492): Unsupported mime audio/adpcm
W/AudioCapabilities( 6492): Unsupported mime audio/g726
W/AudioCapabilities( 6492): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6492): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6492): Unsupported mime video/mjpg
W/VideoCapabilities( 6492): Unsupported mime video/theora
I/ActivityManager(  980): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6525 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 6492): Unsupported mime audio/evrc
W/AudioCapabilities( 6492): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6492): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6492): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6492): Unsupported mime audio/qcelp
W/AudioCapabilities( 6492): Unsupported mime audio/evrc
W/VideoCapabilities( 6492): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6492): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6492): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6492): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6492): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6492): Unrecognized profile 2130706433 for video/avc
I/AppUp4:AppBoxCP( 6525): onCreate
W/AppUp4:DB( 6525):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6525):  setFingerPrint start
I/AppUp4:DB( 6525):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6525):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6525):  SDK version = 0
I/AppUp4:DB( 6525):  beforefinger == newfinger no write in DB
D/AlertService( 6261): Beginning updateAlertNotification
,I/ActivityManager(  980): Process com.google.android.gms (pid 4318) has died
,D/AppUp4:AppBoxApplication( 6525): AppBoxApplication onCreate()
I/vclib   ( 6492): onServiceConnected
W/Babel   ( 6492): Attempted to change video mute state without an active call.
,I/AppUp4:CustModeStarterReceiver( 6525): onReceive
I/AppUp4:CustModeStarterReceiver( 6525): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6525): Context : android.app.ReceiverRestrictedContext@30be277c
D/AppUp4:CustFacade( 6525): isCustomizationCompleted : false
I/NotificationManager( 6492): com.google.android.talk: cancel(8) by com.google.android.talk
,D/AppUp4:CustFacade( 6525): isSimDevice : true
D/AlertService( 6261): No fired or scheduled alerts
I/NotificationManager( 6261): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6261): com.android.calendar: cancel(1) by com.android.calendar
D/AppUp4:CustModeStarterReceiver( 6525): begin check event
I/NotificationManager( 6261): com.android.calendar: cancel(2) by com.android.calendar
I/AppUp4:CustModeStarterReceiver( 6525): Event For Nothing, skip.
I/NotificationManager( 6261): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6261): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6261): com.android.calendar: cancel(5) by com.android.calendar
,I/NotificationManager( 6261): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6261): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6261): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6261): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6261): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6261): com.android.calendar: cancel(11) by com.android.calendar
W/ResourcesManager( 6492): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6492): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/NotificationManager( 6261): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6261): com.android.calendar: cancel(13) by com.android.calendar
,I/NotificationManager( 6261): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6261): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6261): com.android.calendar: cancel(16) by com.android.calendar
I/jxcore-log( 5771): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5771): 
,I/NotificationManager( 6261): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6261): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6261): com.android.calendar: cancel(19) by com.android.calendar
,I/NotificationManager( 6261): com.android.calendar: cancel(20) by com.android.calendar
I/ActivityManager(  980): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6547 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/AlertService( 6261): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 23.370ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 22.187ms
,V/JNIHelp ( 6492): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 22.198ms
,D/AlarmScheduler( 6261): No events found starting within 1 week.
,I/jxcore-log( 5771): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5771): 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  980): Killing 6261:com.android.calendar/u0a13 (adj 15): empty #11
I/jxcore-log( 5771): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5771): 
W/ResourcesManager( 6547): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6547): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6547): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/System  ( 6492): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6492): Installed default security provider GmsCore_OpenSSL
I/jxcore-log( 5771): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5771): 
,W/libprocessgroup(  980): failed to open /acct/uid_10013/pid_6261/cgroup.procs: No such file or directory
I/NotificationManager( 6492): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 6547): Total System Memory = 906309632
,I/GalleryUtils( 6547): Application Heap = 96 MB
I/jxcore-log( 5771): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5771): 
I/AppConfig( 6547): App Tier : NOT_DEF
D/SystemHelper( 6547): region [EU], country [EU], operator [OPEN], sub-operator []
,I/jxcore-log( 5771): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5771): 
I/jxcore-log( 5771): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5771): 
,I/ActivityManager(  980): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6568 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  980): Killing 6342:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_10014/pid_6342/cgroup.procs: No such file or directory
,W/ResourcesManager( 6568): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6568): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6568): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6568): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6568): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6568): BUILD Country: EU
I/SystemConfig( 6568): BUILD Operator: OPEN
,I/ActivityManager(  980): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6590 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  980): Killing 6171:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_10038/pid_6171/cgroup.procs: No such file or directory
,I/SystemConfig( 6568): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6568): existFile = false
I/SystemConfig( 6568): canReadFile = false
I/SystemConfig( 6568): systemFeature RCS result false
D/SystemConfig( 6568): refreshRcsSupport() :false
I/LockScreenSettings( 6590): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6590): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6590): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6590): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,D/LockScreenSettings( 6590): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6590): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  980): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6607 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  980): Killing 6360:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_10006/pid_6360/cgroup.procs: No such file or directory
W/ActivityManager(  980): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,W/ResourcesManager( 6607): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 6317): Internal timer expired: 1
,I/rmt_storage(  274): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  274): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  274): wakelock acquired: 1, error no: 42
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  274): 
I/rmt_storage(  274): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/UpdateIcingCorporaServi( 1934): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1934): UpdateCorporaTask done [took 91 ms] updated apps [took 91 ms] 
,I/ActivityManager(  980): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=6642 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  980): Killing 6379:com.android.settings/1000 (adj 15): empty #11
,I/art     (  980): Explicit concurrent mark sweep GC freed 24691(1393KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.774ms total 203.316ms
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,W/libprocessgroup(  980): failed to open /acct/uid_1000/pid_6379/cgroup.procs: No such file or directory
,W/ResourcesManager( 6642): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6642): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  980): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6663 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MultiDex( 6642): VM with version 2.1.0 has multidex support
I/MultiDex( 6642): install
,I/MultiDex( 6642): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  980): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6681 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6681): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6681): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6681): VM with version 2.1.0 has multidex support
I/MultiDex( 6681): install
I/MultiDex( 6681): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6681): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/JNIHelp ( 6642): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 6642): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6642): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@64bcf72: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6642): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6642): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6642): com.google.android.gms: cancel(39789) by com.google.android.gms
,W/ActivityThread( 6681): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6681): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1af92c0c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6681): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6681): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6681): com.google.android.gms: cancel(39789) by com.google.android.gms
,D/ChimeraCfgMgr( 6681): Reading stored module config
,D/PackageBroadcastService( 6642): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/NativeLibraryUtils( 6681): Installer failed to acquire lock.
D/NativeLibraryUtils( 6681): java.io.IOException: fcntl failed: EAGAIN (Try again)
D/NativeLibraryUtils( 6681): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
D/NativeLibraryUtils( 6681): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
D/NativeLibraryUtils( 6681): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
D/NativeLibraryUtils( 6681): 	at com.google.android.gms.common.util.ay.b(SourceFile:335)
D/NativeLibraryUtils( 6681): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
D/NativeLibraryUtils( 6681): Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
D/NativeLibraryUtils( 6681): 	at libcore.io.Posix.fcntlFlock(Native Method)
D/NativeLibraryUtils( 6681): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
D/NativeLibraryUtils( 6681): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
D/NativeLibraryUtils( 6681): 	... 4 more
,I/PackageBroadcastService( 6642): Null package name or gms related package.  Ignoreing.
D/ChimeraCfgMgr( 6681): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/MusicStore( 6663): Database version: 120
,D/CAR.SERVICE( 6681): Connecting to CarCallService...
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6663): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/NativeLibraryUtils( 6642): Install completed successfully. count=14 extracted=0
,I/art     ( 6681): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6681): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/Icing   ( 6642): Storage manager: low false usage 1.71MB avail 2.37GB capacity 4.06GB
,D/CAR.SERVICE( 6681): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6681): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6681): Creating a new PhoneAdapter instance
W/ActivityManager(  980): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
I/art     ( 6642): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.TEL.PhoneAdapter( 6681): setListener: com.google.android.gms.car.dn@2c61d24b
I/art     ( 6642): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/ActivityManager(  980): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6681): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6681): Starting CarCallService with initial phone null
I/NotificationManager( 6681): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/art     ( 6642): CheckpointMarkThreadRoots callback created = 0xaaf91110
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6663): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6663): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/art     ( 6642): CheckpointMarkThreadRoots callback created = 0xaaf91100
,W/ResourcesManager( 6663): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6663): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6663): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6663): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6663): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1cae8917: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6663): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6663): GMSCore installation verified
I/ActivityManager(  980): Process com.lge.qremote (pid 6293) has died
D/UEI.SmartControl( 6317): Service.onUnbind: IControl
D/UEI.SmartControl( 6317): Service.onDestroy
,D/UEI.SmartControl( 6317): Shutdown IRRCPlayer... 
I/ConfigStore( 6663): Config Database version: 1
W/irrc_jni( 6317): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6317): ~IrrcClient ++ 
D/irrcClient( 6317): ~IrrcClient -- 
W/irrc_jni( 6317): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6317): Blaster closed
D/UEI.SmartControl( 6317): Blaster closed
D/UEI.SmartControl( 6317): Shut down QS...
D/UEI.SmartControl( 6317): Stopped file observer...
,I/UEI.SmartControl( 6317): QS lib stop result = true
D/UEI.SmartControl( 6317): QS shutdown complete
,I/Icing   ( 6642): updateResources: need to parse f{com.google.android.gms}
,I/MediaRouter( 6663): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6663): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6663): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6663): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  980): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6743 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6663): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6663): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 6663): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6743): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6743): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6743): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/Icing   ( 6642): Internal init done: storage state 0
,I/ActivityManager(  980): Killing 6317:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_10089/pid_6317/cgroup.procs: No such file or directory
,I/NotificationManager( 6642): com.google.android.gms: cancel(10436) by com.google.android.gms
I/Icing   ( 6642): Post-init done
,I/Icing   ( 6642): updateResources: need to parse f{com.google.android.gms}
I/LGEmail ( 6743): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6743): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6743): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  980): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6769 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  980): Process com.android.contacts (pid 6568) has died
,I/HubEmail( 6743): JNI_OnLoad()
I/HubEmail( 6743): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6743): registerNatives()
I/HubEmail( 6743): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6743): registerNativeMethods()
I/HubEmail( 6743): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6743): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6743): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  980): Process com.android.gallery3d (pid 6547) has died
,D/LGDMClient( 6769): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6769): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/NetworkStateForAutoUpdateMonitor( 6525): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6525): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6525): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6525): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6525): onReceive
I/AppUp4:CustModeStarterReceiver( 6525): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6525): Context : android.app.ReceiverRestrictedContext@30be277c
D/AppUp4:CustFacade( 6525): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6525): isSimDevice : true
D/LGDMClient( 6769): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustModeStarterReceiver( 6525): begin check event
I/AppUp4:CustModeStarterReceiver( 6525): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6525): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/LGDMClient( 6769): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 6769): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/AppUp4:CustModeStarterReceiver( 6525): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6525): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6525): handleAsyncCustNotification do not startCustService
I/LGDMClient( 6769): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 6769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/LgeMiscReceiver( 3142): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3142): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3142): networkInfo.isConnected() = false
E/LGDMClient( 6769): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6769): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6769): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6769): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6769): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  980): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6804 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6804): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6804): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6804): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  980): Killing 6410:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_1000/pid_6410/cgroup.procs: No such file or directory
,V/DownloadManager( 3255): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3255): DownloadService onCreate
I/NotificationManager( 3255): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3255): in removeSpuriousFiles
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/PhoneMonitor( 6804): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@1af92c0c on behalf of 3255
V/TelephonyAutoProfiling( 6804): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6804): [parse] Load xml
I/DownloadManager( 3255): in trimDatabase
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/TelephonyAutoProfiling( 6804): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6804): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/ActivityManager(  980): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6830 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3255): DownloadService onStartCommand
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@37651c5b on behalf of 3255
,V/DownloadManager( 3255): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 6642): Checkin interval check for package: unspecified last checkin: 1454056106357 min interval config: 0 actual interval: 23755
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@2e12fcf8 on behalf of 3255
D/PhoneMonitor( 6804): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/CheckinService( 6642): Disabling old GoogleServicesFramework version
I/Icing   ( 6642): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,V/DownloadManager( 3255): DownloadService onDestroy
,I/CheckinService( 6642): Checking schedule, now: 1454056130211 next: 1454056136304
I/CheckinService( 6642): active receiver: disabled
I/ActivityManager(  980): Killing 6590:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
D/Icing   ( 6642): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6642): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
W/libprocessgroup(  980): failed to open /acct/uid_10069/pid_6590/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2731): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:28:50
D/UpdateThreadPoolManager( 2731): 2 : This is isUpdating : false
,D/WeatherAncestor( 2731): connectivity changed - connection : true
D/Weather_cast( 2731): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2731): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:28:50
D/WeatherService( 2731): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  980): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2731): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2731): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2731): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  980): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6858 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 22.161ms
,I/ActivityManager(  980): Killing 6607:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 24.173ms
D/libc-netbsd( 6492): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6492): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6492): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6492): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  276): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 310us total 23.888ms
,W/libprocessgroup(  980): failed to open /acct/uid_10086/pid_6607/cgroup.procs: No such file or directory
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6858): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
I/GAv4    ( 6858): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6858):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6858):   adb logcat -s GAv4
W/ContextImpl( 6858): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6858): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6858): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6858): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6858): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6858): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 6492): propertyValue:false
I/WebViewFactory( 6858): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/Babel   ( 6492): connection state changed from UNKNOWN to CONNECTED
,I/LibraryLoader( 6858): Time to load native libraries: 1 ms (timestamps 7257-7258)
I/LibraryLoader( 6858): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6858): Binding Chromium to main looper Looper (main, tid 1) {3025b03c}
I/LibraryLoader( 6858): Expected native library version number "",actual native library version number ""
I/chromium( 6858): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6858): Initializing chromium process, singleProcess=true
W/art     ( 6858): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6858): ApplicationContext is null in ApplicationStatus
,W/chromium( 6858): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6858): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6858): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6858): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6858): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6858): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6858): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6858): Remote Branch: 
I/Adreno-EGL( 6858): Local Patches: 
I/Adreno-EGL( 6858): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/AudioPolicyService(  281): registerClient() client 0xb57e8f80, uid 10079
,W/AudioManagerAndroid( 6858): Requires BLUETOOTH permission
I/art     (  980): Explicit concurrent mark sweep GC freed 17314(890KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.420ms total 145.529ms
,I/NSApplication( 6858): Starting up...
,I/ActivityManager(  980): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6935 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  980): Killing 6681:com.google.android.gms:car/u0a6 (adj 15): empty #11
,I/ActivityManager(  980): Killing 6001:com.android.vending/u0a36 (adj 15): empty #12
,I/ActivityManager(  980): Process com.google.android.music:main (pid 6663) has died
,W/libprocessgroup(  980): failed to open /acct/uid_10006/pid_6681/cgroup.procs: No such file or directory
W/ActivityManager(  980): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 4000ms
W/libprocessgroup(  980): failed to open /acct/uid_10036/pid_6001/cgroup.procs: No such file or directory
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  980): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6957 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6957): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.SyncManager( 6642): SYNC; picasa accounts
,D/NetworkLogImpl( 6642): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6642): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ActivityManager(  980): Killing 6743:com.lge.email/u0a21 (adj 15): empty #11
,I/iu.UploadsManager( 6642): num queued entries: 0
I/iu.UploadsManager( 6642): num updated entries: 0
I/iu.SyncManager( 6642): NEXT; no task
W/libprocessgroup(  980): failed to open /acct/uid_10021/pid_6743/cgroup.procs: No such file or directory
,I/ActivityManager(  980): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6994 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MusicStore( 6994): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6994): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6994): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6994): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6994): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6994): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6994): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6994): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6994): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1cae8917: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6994): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6994): GMSCore installation verified
,I/ConfigStore( 6994): Config Database version: 1
,I/MediaRouter( 6994): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6994): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6994): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6994): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  980): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7031 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6994): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6994): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7031): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7031): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7031): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  980): Killing 6525:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  980): failed to open /acct/uid_10011/pid_6525/cgroup.procs: No such file or directory
,I/NotificationManager( 6994): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7031): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7031): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7031): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 6769): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6769): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6769): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6769): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 6769): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6769): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/HubEmail( 7031): JNI_OnLoad()
I/HubEmail( 7031): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7031): registerNatives()
I/HubEmail( 7031): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7031): registerNativeMethods()
I/HubEmail( 7031): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7031): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  980): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7064 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/Settings( 7031): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 6769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6769): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6769): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6769): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6769): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6769): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  980): Killing 6804:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  980): failed to open /acct/uid_10038/pid_6804/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7064): onCreate
,W/AppUp4:DB( 7064):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7064):  setFingerPrint start
I/AppUp4:DB( 7064):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7064):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7064):  SDK version = 0
I/AppUp4:DB( 7064):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7064): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7064): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7064): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7064): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7064): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7064): onReceive
I/AppUp4:CustModeStarterReceiver( 7064): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7064): Context : android.app.ReceiverRestrictedContext@a01228b
D/AppUp4:CustFacade( 7064): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7064): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7064): begin check event
I/AppUp4:CustModeStarterReceiver( 7064): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7064): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7064): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7064): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7064): handleAsyncCustNotification do not startCustService
I/ActivityManager(  980): Killing 6830:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_10051/pid_6830/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3142): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3142): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3142): networkInfo.isConnected() = false
I/ActivityManager(  980): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7086 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7086): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7086): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7086): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  980): Killing 6492:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 7086): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7086): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7086): [parse] Load xml
V/TelephonyAutoProfiling( 7086): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7086): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7086): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  980): failed to open /acct/uid_10061/pid_6492/cgroup.procs: No such file or directory
,V/DownloadManager( 3255): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3255): DownloadService onCreate
,I/DownloadManager( 3255): in removeSpuriousFiles
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3255): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@2ac30836 on behalf of 3255
I/ActivityManager(  980): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7108 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3255): DownloadService onStartCommand
,V/DownloadManager( 3255): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3255): in trimDatabase
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/CheckinService( 6642): Checkin interval check for package: unspecified last checkin: 1454056106357 min interval config: 0 actual interval: 28905
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@13af71c2 on behalf of 3255
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@1f4e9e0d on behalf of 3255
I/CheckinService( 6642): Checking schedule, now: 1454056135273 next: 1454056136304
I/CheckinService( 6642): active receiver: disabled
,V/DownloadManager( 3255): DownloadService onDestroy
I/jxcore-log( 5771): Test app app.js loaded
I/jxcore-log( 5771): 
,I/ActivityManager(  980): Killing 6858:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 5771): BLE advertisement is supported
I/jxcore-log( 5771): 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/chromium( 5771): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/libprocessgroup(  980): failed to open /acct/uid_10079/pid_6858/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2731): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:28:55
D/UpdateThreadPoolManager( 2731): 2 : This is isUpdating : false
D/WeatherAncestor( 2731): connectivity changed - connection : true
D/Weather_cast( 2731): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2731): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:28:55
D/WeatherService( 2731): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  980): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7137 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  980): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2731): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2731): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2731): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7137): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7137): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7137): MmsConfig.loadMmsSettings
I/Babel_SMS( 7137): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7137): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7137): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7137): MmsConfig.loadFromResources
E/Babel_SMS( 7137): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7137): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7137): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7137): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7137): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7137): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 7137): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7137): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7137): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7137): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7137): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7137): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7137): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7137): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7137): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7137): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7137): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7137): found sensor: Motion Accel, handle=46
I/ActivityManager(  980): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7168 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7137): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     ( 7137): CheckpointMarkThreadRoots callback created = 0xb042d510
I/Babel_Crash( 7137): startup - clean
,I/art     ( 7137): CheckpointMarkThreadRoots callback created = 0xb042d4f0
,W/ResourcesManager( 7168): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7168): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel   ( 7137): deleted: false for 0
,I/MultiDex( 7168): VM with version 2.1.0 has multidex support
I/MultiDex( 7168): install
,I/MultiDex( 7168): VM has multidex support, MultiDex support library is disabled.
W/AudioCapabilities( 7137): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7137): Unsupported mime audio/adpcm
W/AudioCapabilities( 7137): Unsupported mime audio/g726
W/AudioCapabilities( 7137): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7137): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7137): Unsupported mime video/mjpg
W/VideoCapabilities( 7137): Unsupported mime video/theora
I/ActivityManager(  980): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7196 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7137): Unsupported mime audio/evrc
,W/AudioCapabilities( 7137): Unsupported mime audio/qcelp
W/VideoCapabilities( 7137): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7137): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7137): Unsupported mime audio/qcelp
W/AudioCapabilities( 7137): Unsupported mime audio/evrc
V/JNIHelp ( 7168): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/VideoCapabilities( 7137): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7137): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7137): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7137): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7137): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7137): Unrecognized profile 2130706433 for video/avc
W/ActivityThread( 7168): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7168): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1af92c0c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7168): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7168): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7168): com.google.android.gms: cancel(39789) by com.google.android.gms
I/vclib   ( 7137): onServiceConnected
W/Babel   ( 7137): Attempted to change video mute state without an active call.
,D/ChimeraCfgMgr( 7168): Reading stored module config
D/libc-netbsd( 7137): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7137): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7137): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7137): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  276): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/NotificationManager( 7137): com.google.android.talk: cancel(10436) by com.google.android.talk
I/System.out( 7137): propertyValue:false
D/ChimeraCfgMgr( 7168): Loading module com.google.android.gms.car from APK com.google.android.gms
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7196): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 7196): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7196):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7196):   adb logcat -s GAv4
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7196): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7196): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7196): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7196): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7196): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7196): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  980): RTC_WAKEUP set : Alarm{1500c148 type 0 when 1454056136304 com.google.android.gms} when 1454056136304
,D/CAR.SERVICE( 7168): Connecting to CarCallService...
,D/NativeLibraryUtils( 7168): Install completed successfully. count=14 extracted=0
I/art     ( 7168): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7168): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 7168): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 7168): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 7168): Creating a new PhoneAdapter instance
,W/ActivityManager(  980): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 7168): setListener: com.google.android.gms.car.dn@2c61d24b
W/ActivityManager(  980): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 7168): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 7168): Starting CarCallService with initial phone null
,I/Babel   ( 7137): connection state changed from UNKNOWN to CONNECTED
,I/art     (  980): Explicit concurrent mark sweep GC freed 17672(844KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.367ms total 139.401ms
,I/ActivityManager(  980): Killing 6935:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_10048/pid_6935/cgroup.procs: No such file or directory
,I/NotificationManager( 7168): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/WebViewFactory( 7196): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7196): Time to load native libraries: 3 ms (timestamps 2909-2912)
I/LibraryLoader( 7196): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7196): Binding Chromium to main looper Looper (main, tid 1) {3025b03c}
I/LibraryLoader( 7196): Expected native library version number "",actual native library version number ""
I/chromium( 7196): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7196): Initializing chromium process, singleProcess=true
,W/art     ( 7196): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7196): ApplicationContext is null in ApplicationStatus
W/chromium( 7196): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7196): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7196): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7196): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7196): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7196): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7196): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7196): Remote Branch: 
I/Adreno-EGL( 7196): Local Patches: 
I/Adreno-EGL( 7196): Reconstruct Branch: 
V/AudioPolicyService(  281): registerClient() client 0xb57e8fa0, uid 10079
,W/AudioManagerAndroid( 7196): Requires BLUETOOTH permission
I/NSApplication( 7196): Starting up...
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  980): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7272 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  980): Killing 6994:com.google.android.music:main/u0a81 (adj 15): empty #11
I/art     (  305): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 437us total 25.975ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 24.020ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.678ms
,I/ActivityManager(  980): Killing 6957:com.google.android.apps.plus/u0a86 (adj 15): empty #12
,W/libprocessgroup(  980): failed to open /acct/uid_10081/pid_6994/cgroup.procs: No such file or directory
W/libprocessgroup(  980): failed to open /acct/uid_10086/pid_6957/cgroup.procs: No such file or directory
I/ActivityManager(  980): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7291 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  980): Killing 7031:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_10021/pid_7031/cgroup.procs: No such file or directory
,W/ResourcesManager( 7291): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  980): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7308 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  980): RTC_WAKEUP set : Alarm{3a269da7 type 0 when 1454056137436 com.android.vending} when 1454056137436
,D/sensors_hal_Time(  980): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  980): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  980): tsOffsetIs: Apps: 113645262825; DSPS: 3815257; Offset : -2796895530
,D/Finsky  ( 7308): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager(  980): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7348 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 7308): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7308): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7308): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7308): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@32047310 on behalf of 7308
D/Ads     ( 7308): Skipping gmscore version check
,D/Finsky  ( 7308): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7308): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  980): Killing 6769:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_1000/pid_6769/cgroup.procs: No such file or directory
,D/Finsky  ( 7308): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager(  980): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/Finsky  ( 7308): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Gmail   ( 7348): getAccountsCursor
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 7348): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ActivityManager(  980): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7348): Error finding the version of the Email provider.....
E/Gmail   ( 7348): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7348): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7348): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7348): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7348): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7348): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7348): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7348): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Gmail   ( 7348): getAccountsCursor
W/EmailMigration( 7348): We do not support migrating this version of the Email provider.
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7308): [910] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7308): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  980): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7403 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  980): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/ActivityManager(  980): Killing 7064:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/Gmail   ( 7348): Observing account changes for notifications
,W/libprocessgroup(  980): failed to open /acct/uid_10011/pid_7064/cgroup.procs: No such file or directory
,W/ActivityManager(  980): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  980): Killing 7086:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_10038/pid_7086/cgroup.procs: No such file or directory
,I/MusicStore( 7403): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7403): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Gmail   ( 7348): notifyAccountChanged
I/Gmail   ( 7348): getAccountsCursor
I/Gmail   ( 7348): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7348): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7348): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7348): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7348): getAccountsCursor
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7403): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7403): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7403): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7403): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7403): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7403): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7403): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1cae8917: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7403): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7403): GMSCore installation verified
I/ConfigStore( 7403): Config Database version: 1
,I/MediaRouter( 7403): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7403): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7403): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7403): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  980): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7444 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7403): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7403): Using platform SSLCertificateSocketFactory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     (  980): Explicit concurrent mark sweep GC freed 20819(961KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.960ms total 154.208ms
,W/ResourcesManager( 7444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7444): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7444): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  980): Killing 7108:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_10051/pid_7108/cgroup.procs: No such file or directory
,I/NotificationManager( 7403): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7444): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7444): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7444): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  980): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7484 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7444): JNI_OnLoad()
I/HubEmail( 7444): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7444): registerNatives()
I/HubEmail( 7444): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7444): registerNativeMethods()
I/HubEmail( 7444): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7444): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  980): Killing 7196:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/Settings( 7444): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/libprocessgroup(  980): failed to open /acct/uid_10079/pid_7196/cgroup.procs: No such file or directory
,D/LGDMClient( 7484): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7484): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7484): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7484): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7484): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7484): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7484): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7484): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  980): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7513 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7484): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7484): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7484): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7484): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7484): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7484): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
D/WeatherService( 2731): 2 : TimeTick Intent has been received, Time(hour:min:sec) 9:29:0
,D/WeatherService( 2731): 2 : TimeTick Intent And Screen On
D/WeatherService( 2731): 2 : SDK version : 21
W/ActivityManager(  980): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2731): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2731): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2731): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2731): 2 : requestRefreshAppWidget, isUpdateStart : false
I/ActivityManager(  980): Killing 7168:com.google.android.gms:car/u0a6 (adj 15): empty #11
D/UpdateThreadPoolManager( 2731): 2 : This is isUpdating : false
D/WeatherService( 2731): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2731): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2731): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2731): 2 : Fixed theme : optimus
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
D/WeatherReflect( 2731): 2 : Map key string is -2
,I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
W/libprocessgroup(  980): failed to open /acct/uid_10006/pid_7168/cgroup.procs: No such file or directory
,W/ActivityManager(  980): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 16000ms
D/lim     ( 2731): 2 : time = 09:29
,I/WeatherReflect( 2731): Model Name : LG-D722
,D/WeatherTheme( 2731): 2 : Different view - status_min_formatted : 28 != 29
D/WeatherTheme( 2731): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2731): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/AppUp4:AppBoxCP( 7513): onCreate
W/AppUp4:DB( 7513):  [AppBoxDatabaseHelper] construct
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
,I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/AppUp4:DB( 7513):  setFingerPrint start
I/AppUp4:DB( 7513):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
D/Theme   ( 2731): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2731): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/AppUp4:DB( 7513):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7513):  SDK version = 0
I/AppUp4:DB( 7513):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7513): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7513): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7513): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7513): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7513): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7513): onReceive
I/AppUp4:CustModeStarterReceiver( 7513): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7513): Context : android.app.ReceiverRestrictedContext@a01228b
,D/AppUp4:CustFacade( 7513): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7513): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7513): begin check event
I/AppUp4:CustModeStarterReceiver( 7513): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7513): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7513): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7513): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7513): handleAsyncCustNotification do not startCustService
I/ActivityManager(  980): Killing 7272:com.android.chrome/u0a48 (adj 15): empty #11
,D/Weather4x2_optimus( 2731): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2731): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2731): forecast size is 0
,D/Theme   ( 2731): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2731): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2731): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2731): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2731): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2731): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2731): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2731): setTouchIntent, appWidgetId: 2
I/[SystemUI]DateView( 1373): called onTimeUpdated()
W/libprocessgroup(  980): failed to open /acct/uid_10048/pid_7272/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/LgeMiscReceiver( 3142): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3142): action = android.net.conn.CONNECTIVITY_CHANGE
D/Theme_WeatherAncestor_optimus( 2731): url is : null
I/MusicWidget( 2637): mDelayedStopHandler : unbind
I/LgeMiscReceiver( 3142): networkInfo.isConnected() = true
D/PhoneState( 3142): setPdpRejectCasuse : false
I/MusicBrowser( 2074): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2074): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2074): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2074): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2074): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2074): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/ActivityManager(  980): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7534 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/Theme   ( 2731): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2731): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2731): 2 : update view, appWidgetId: 2
I/MusicBrowser( 2074): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,D/WeatherService( 2731): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 9:29:0
I/MediaFocusControl(  980):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2f4faaf1com.lge.music.MediaPlaybackService$6@126766d6
,D/MusicBrowser( 2074): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@19dd5c67
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,I/MusicBrowser( 2074): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2074): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2074): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2074): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2074): reset
V/MediaPlayer[Native]( 2074): setListener
,V/MediaPlayer[Native]( 2074): disconnect
V/MediaPlayer[Native]( 2074): destructor
V/AudioFlinger(  281): releasing 19 from 2074 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/MediaPlayer[Native]( 2074): disconnect
D/MusicBrowser( 2074): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2074): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2074): [SmartShareManagerClient] smartshare client enabled
D/PhoneMonitor( 7534): Register our PhoneStateListener
I/MusicBrowser( 2074): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2074): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2074): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2074): [SmartShareManagerClient] unregisterListener: 920661335
W/SmartShareClient( 2074): [SmartShareManagerClient] unregisterListener invalid listener: 920661335
I/SmartShareClient( 2074): [SmartShareManagerClient] terminate service: 2074/MediaPlaybackService/921094149
,E/HomeCloudIF( 2074): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2074): [SmartShareManagerClient] unbindService context:android.app.Application@138e0044
V/CloudHub( 2074): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/CloudHub( 2074): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2074): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2074): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2074): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
D/MobileConnectivityChangeReceiver( 7534): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7534): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  980): Killing 7291:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/CloudHub( 2074): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29990
D/PhoneMonitor( 7534): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 7534): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7534): [parse] Load xml
V/TelephonyAutoProfiling( 7534): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7534): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7534): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  980): Killing 7137:com.google.android.talk/u0a61 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/libprocessgroup(  980): failed to open /acct/uid_10086/pid_7291/cgroup.procs: No such file or directory
V/DownloadManager( 3255): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  980): failed to open /acct/uid_10061/pid_7137/cgroup.procs: No such file or directory
V/DownloadManager( 3255): DownloadService onCreate
I/DownloadManager( 3255): in removeSpuriousFiles
,V/DownloadManager( 3255): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3255): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@35540e09 on behalf of 3255
I/DownloadManager( 3255): in trimDatabase
V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@3779422f on behalf of 3255
I/ActivityManager(  980): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7563 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3255): DownloadService onStartCommand
V/DownloadManager( 3255): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@62681c5 on behalf of 3255
I/CheckinService( 6642): Checkin interval check for package: unspecified last checkin: 1454056106357 min interval config: 0 actual interval: 34261
I/CheckinService( 6642): Checking schedule, now: 1454056140624 next: 1454056136304
I/CheckinService( 6642): active receiver: enabled
,I/CheckinService( 6642): Preparing to send checkin request
V/DownloadManager( 3255): DownloadService onDestroy
,I/EventLogService( 6642): Accumulating logs since 1454056095257
D/WeatherAncestor( 2731): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:29:0
,D/UpdateThreadPoolManager( 2731): 2 : This is isUpdating : false
D/WeatherAncestor( 2731): connectivity changed - connection : true
D/Weather_cast( 2731): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2731): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:29:0
D/WeatherService( 2731): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  980): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7583 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  980): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2731): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2731): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2731): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/art     ( 6472): Explicit concurrent mark sweep GC freed 2422(105KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 411us total 30.252ms
W/ResourcesManager( 7583): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 6642): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6642): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 7583): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7583): MmsConfig.loadMmsSettings
I/Babel_SMS( 7583): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7583): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7583): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7583): MmsConfig.loadFromResources
E/Babel_SMS( 7583): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7583): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7583): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7583): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7583): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7583): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7583): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7583): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7583): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7583): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7583): found sensor: LGE Step Counter Sensor, handle=44
,D/SensorManager( 7583): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7583): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7583): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7583): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7583): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7583): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7583): found sensor: Motion Accel, handle=46
W/Settings( 7583): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7583): startup - clean
I/art     ( 7583): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/Babel   ( 7583): deleted: false for 0
,I/art     ( 7583): CheckpointMarkThreadRoots callback created = 0xb042d870
,I/ActivityManager(  980): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7615 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 22.009ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.438ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.955ms
,I/ActivityManager(  980): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7632 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7583): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7583): Unsupported mime audio/adpcm
W/AudioCapabilities( 7583): Unsupported mime audio/g726
W/AudioCapabilities( 7583): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7583): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7583): Unsupported mime video/mjpg
W/VideoCapabilities( 7583): Unsupported mime video/theora
,W/ResourcesManager( 7615): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7615): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/AudioCapabilities( 7583): Unsupported mime audio/evrc
W/AudioCapabilities( 7583): Unsupported mime audio/qcelp
W/VideoCapabilities( 7583): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7583): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7583): Unsupported mime audio/qcelp
W/AudioCapabilities( 7583): Unsupported mime audio/evrc
I/MultiDex( 7615): VM with version 2.1.0 has multidex support
I/MultiDex( 7615): install
I/MultiDex( 7615): VM has multidex support, MultiDex support library is disabled.
,W/VideoCapabilities( 7583): Unsupported mime video/mp4v-esdp
,V/JNIHelp ( 7615): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/VideoCapabilities( 7583): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7583): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7583): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7583): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7583): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7583): onServiceConnected
,W/Babel   ( 7583): Attempted to change video mute state without an active call.
I/NotificationManager( 7583): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7583): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7583): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7583): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7583): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  276): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 7583): propertyValue:false
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7632): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7632): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/ActivityThread( 7615): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7615): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1af92c0c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7615): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7615): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7615): com.google.android.gms: cancel(39789) by com.google.android.gms
,I/GAv4    ( 7632): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7632):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7632):   adb logcat -s GAv4
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7632): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7632): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7632): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 7615): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7615): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/GAv4    ( 7632): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7632): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7583): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  980): Killing 7308:com.android.vending/u0a36 (adj 15): empty #11
D/NativeLibraryUtils( 7615): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  980): failed to open /acct/uid_10036/pid_7308/cgroup.procs: No such file or directory
,D/WVCdm   (  281): Instantiating CDM.
I/WVCdm   (  281): CdmEngine::OpenSession
,I/WVCdm   (  281): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  281): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  281): Properties::GetOEMCryptoPath: null. applies level3
,W/WVCdm   (  281): L1 library not specified. Falling Back to L3
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  281): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  281): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
D/WVCdm   (  281): PrepareKeyRequest: nonce=1657010629
I/WebViewFactory( 7632): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7632): Time to load native libraries: 3 ms (timestamps 8051-8054)
I/LibraryLoader( 7632): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7632): Binding Chromium to main looper Looper (main, tid 1) {3025b03c}
I/LibraryLoader( 7632): Expected native library version number "",actual native library version number ""
I/chromium( 7632): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7632): Initializing chromium process, singleProcess=true
,W/art     ( 7632): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7632): ApplicationContext is null in ApplicationStatus
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,W/chromium( 7632): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7632): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7632): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7632): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7632): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7632): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7632): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7632): Remote Branch: 
I/Adreno-EGL( 7632): Local Patches: 
I/Adreno-EGL( 7632): Reconstruct Branch: 
I/NSApplication( 7632): Starting up...
V/AudioPolicyService(  281): registerClient() client 0xb57eea80, uid 10079
W/AudioManagerAndroid( 7632): Requires BLUETOOTH permission
,I/art     ( 7615): CheckpointMarkThreadRoots callback created = 0xb04cbe40
,I/ActivityManager(  980): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7696 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  980): Killing 7348:com.google.android.gm/u0a53 (adj 15): empty #11
I/art     ( 7615): CheckpointMarkThreadRoots callback created = 0xb04cbe30
,W/libprocessgroup(  980): failed to open /acct/uid_10053/pid_7348/cgroup.procs: No such file or directory
,I/dex2oat ( 7712): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  980): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7721 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  980): Killing 7403:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/dex2oat ( 7712): dex2oat took 139.735ms (threads: 4)
,I/Adreno-EGL( 7615): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7615): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7615): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7615): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7615): Remote Branch: 
I/Adreno-EGL( 7615): Local Patches: 
I/Adreno-EGL( 7615): Reconstruct Branch: 
,W/libprocessgroup(  980): failed to open /acct/uid_10081/pid_7403/cgroup.procs: No such file or directory
,W/ResourcesManager( 7721): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WVCdm   (  281): CdmEngine::OpenSession
,I/ActivityManager(  980): Killing 7444:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  980): failed to open /acct/uid_10021/pid_7444/cgroup.procs: No such file or directory
,I/ActivityManager(  980): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7751 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7751): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  980): Message: 20
D/BluetoothManagerService(  980): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35891085:true
,D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
,I/art     (  980): Explicit concurrent mark sweep GC freed 19826(945KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.224ms total 144.910ms
,I/ActivityManager(  980): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7769 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7751): Create singleton instance
,D/UEI.SmartControl( 7769): Quickset Services start...
,I/UEI.SmartControl( 7769): Manufacture = LGE
D/UEI.SmartControl( 7769): File observer start...
E/UEI.SmartControl( 7769): IR Port is disabled: false
D/UEI.SmartControl( 7769): Starting file observer...
D/UEI.SmartControl( 7769): Extracting JNI libs...
D/UEI.SmartControl( 7769): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7751): getMode name:com.lge.qremote
,I/AudioManager( 7751): getMode name:com.lge.qremote
,D/WearableService( 1729): callingUid 10006, callindPid: 1729
,E/MDM     ( 1729): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6642): Restart initialization of location
,D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  980): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver: pid=7795 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1729): No location to return for getLastLocation()
W/FusedLocationProvider( 1729): location=null
,W/IcingInternalCorpora( 6642): getNumBytesRead when not calculated.
,D/UEI.SmartControl( 7769): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7769): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7769): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/WVCdm   (  281): CdmEngine::CloseSession
I/UEI.SmartControl( 7769): --- Selecting new region: 2
I/UEI.SmartControl( 7769): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7769): Platform has CIR...
D/UEI.SmartControl( 7769): NO CIR support, need to check package...
I/UEI.SmartControl( 7769): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7769): QS Service created
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  281): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  281): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
E/UEI.SmartControl( 7769): QS start get config
D/WVCdm   (  281): PrepareKeyRequest: nonce=2047775369
,D/Finsky  ( 7795): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 7769): Loading JNI Libs...
,D/UEI.SmartControl( 7769):  configuring local db...
,D/Finsky  ( 7795): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7795): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7795): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7795): com.android.vending: cancel(-1050172287) by com.android.vending
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@2c61d24b on behalf of 7795
D/Ads     ( 7795): Skipping gmscore version check
D/Finsky  ( 7795): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7795): [1] Libraries$2.run: Finished loading 1 libraries.
D/LocationInitializer( 6642): Restart initialization of location
,E/MDM     ( 1729): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/Finsky  ( 7795): [989] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7795): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7795): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/GCoreFlp( 1729): No location to return for getLastLocation()
W/FusedLocationProvider( 1729): location=null
I/NotificationManager(  980): android: cancelAsUser(2) by android
,D/LocationInitializer( 6642): Restart initialization of location
D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1729): [117] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1729): No location to return for getLastLocation()
,D/UEI.SmartControl( 7769):  ---- Has DB8: true
W/FusedLocationProvider( 1729): location=null
D/UEI.SmartControl( 7769): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7769): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7769): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7769): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7769): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7769): IrrcClient ++ 
D/irrcClient( 7769): getIrrcService ++ 
,D/irrcClient( 7769): getIrrcService -- 
D/irrcClient( 7769): IrrcClient -- 
W/irrc_jni( 7769): IRRCPlayer_nativeInit -- 
D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/UEI.SmartControl( 7769): Services init done
D/UEI.SmartControl( 7769): QS Service init finished
D/UEI.SmartControl( 7769): QS Service version name: 0.1.73
I/UEI.SmartControl( 7769): Device manager: loading config....
,D/UEI.SmartControl( 7769): QS Service version code: 1073
D/UEI.SmartControl( 7769): Service requested: Control
D/UEI.SmartControl( 7769): Config is loaded...
D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/MDM     ( 1729): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/libc-netbsd( 7795): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7795): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7795): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7795): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6642): Restart initialization of location
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 7769): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7769):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7769): Notify AllClients services are ready: 0
I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,I/CheckinService( 6642): Checkin interval check for package: unspecified last checkin: 1454056106357 min interval config: 0 actual interval: 38338
D/UEI.SmartControl( 7769): Internal service binding...
D/UEI.SmartControl( 7769): -----IControl: 11
,D/UEI.SmartControl( 7769): Caller: com.lge.qremote
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
D/UEI.SmartControl( 7769): ------------ IControl registerCallback...
I/UEI.SmartControl( 7769): Registering callback...
D/UEI.SmartControl( 7769): -----IControl: 19
I/System.out( 7795): propertyValue:false
D/UEI.SmartControl( 7769): Caller: com.lge.qremote
I/UEI.SmartControl( 7769): Registering Services Ready callback...
W/GCoreFlp( 1729): No location to return for getLastLocation()
W/FusedLocationProvider( 1729): location=null
I/UEI.SmartControl( 7769): Notify client services are ready...
D/UEI.SmartControl( 7769): -----IControl: 8
,D/UEI.SmartControl( 7769): Caller: com.lge.qremote
W/ContextImpl( 3658): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/AudioFlinger(  281): 2074 died, releasing its sessions
V/AudioFlinger(  281):  pid 1748 @ 0
V/AudioFlinger(  281):  pid 3142 @ 1
V/AudioFlinger(  281):  pid 3142 @ 2
I/ActivityManager(  980): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7864 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  980): Process com.lge.music (pid 2074) has died
,I/ActivityManager(  980): Killing 7484:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  980): failed to open /acct/uid_1000/pid_7484/cgroup.procs: No such file or directory
I/ActivityManager(  980): Killing 7513:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  980): failed to open /acct/uid_10011/pid_7513/cgroup.procs: No such file or directory
,W/ActivityManager(  980): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7864): getAccountsCursor
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7864): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  980): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  980): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
E/Gmail   ( 7864): Error finding the version of the Email provider.....
E/Gmail   ( 7864): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7864): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7864): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7864): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7864): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7864): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7864): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7864): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7864): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7864): getAccountsCursor
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7864): Observing account changes for notifications
W/ActivityManager(  980): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/LocationInitializer( 6642): Restart initialization of location
E/MDM     ( 1729): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/ActivityManager(  980): Killing 7563:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  980): failed to open /acct/uid_10051/pid_7563/cgroup.procs: No such file or directory
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 7751): getMode name:com.lge.qremote
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1729): No location to return for getLastLocation()
W/FusedLocationProvider( 1729): location=null
I/AudioManager( 7751): getMode name:com.lge.qremote
I/AudioManager( 7751): getMode name:com.lge.qremote
,I/AudioManager( 7751): getMode name:com.lge.qremote
,I/Gmail   ( 7864): notifyAccountChanged
,I/Gmail   ( 7864): getAccountsCursor
I/Gmail   ( 7864): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7864): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7864): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7864): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/art     (  980): Explicit concurrent mark sweep GC freed 20643(940KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.374ms total 145.427ms
,I/Gmail   ( 7864): getAccountsCursor
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/WVCdm   (  281): CdmEngine::CloseSession
D/WifiController(  980): battery changed pluggedType: 2
I/WVCdm   (  281): L3 Terminate.
D/HeadsetStateMachine( 2035): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2035): Disconnected process message: 10, size: 0
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  980): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Adreno-EGL( 7615): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7615): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7615): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7615): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7615): Remote Branch: 
I/Adreno-EGL( 7615): Local Patches: 
I/Adreno-EGL( 7615): Reconstruct Branch: 
,I/Adreno-EGL( 7615): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7615): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7615): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7615): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7615): Remote Branch: 
I/Adreno-EGL( 7615): Local Patches: 
I/Adreno-EGL( 7615): Reconstruct Branch: 
,I/CheckinRequestBuilder( 6642): Classify the device as Phone.
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/libc-netbsd( 6642): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6642): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6642): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6642): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 6642): propertyValue:false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd( 6642): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6642): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6642): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6642): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6642): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6642): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 6642): Sending checkin request (9804 bytes)
,I/CheckinRequestBuilder( 6642): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6642): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 6642): Explicit concurrent mark sweep GC freed 17167(1253KB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 11MB/19MB, paused 1.213ms total 66.674ms
,I/CheckinRequestBuilder( 6642): Classify the device as Phone.
,I/CheckinTask( 6642): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6642): Checking schedule, now: 1454056149351 next: 1454583398345
I/CheckinService( 6642): active receiver: disabled
,I/CheckinService( 6642): Checking schedule, now: 1454056149392 next: 1454583398345
,I/CheckinService( 6642): active receiver: disabled
D/CheckinService( 6642): Recording last checkin time for package unspecified as 1454056149402
,I/art     ( 6472): Explicit concurrent mark sweep GC freed 3369(138KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 391us total 33.025ms
,V/SetupWizard( 7534): Connected to Gservices successfully
D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7769): Internal timer expired: 1
,I/CheckinService( 6642): Done disabling old GoogleServicesFramework version
,I/GAv4-SVC( 6642): Google Analytics 8.4.89 is starting up.
,I/GAV2    ( 7864): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  980): Killing 7632:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/ActivityManager(  980): Killing 7583:com.google.android.talk/u0a61 (adj 15): empty #12
,W/libprocessgroup(  980): failed to open /acct/uid_10079/pid_7632/cgroup.procs: No such file or directory
,W/libprocessgroup(  980): failed to open /acct/uid_10061/pid_7583/cgroup.procs: No such file or directory
I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  980): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/ActivityManager(  980): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7963 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/administrator(  980): Handling package changes for user 0
,W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/NotificationService(  980): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  980): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  980): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  980): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2035): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/WifiController(  980): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
V/BackupManagerService(  980): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  980): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1baa8c4f
I/Babel_SMS( 7963): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7963): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7963): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7963): MmsConfig.loadFromDatabase
W/ResourcesManager(  980): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/Babel_SMS( 7963): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7963): MmsConfig.loadFromResources
E/Babel_SMS( 7963): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7963): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7963): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7963): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7963): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7963): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 7963): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7963): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7963): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7963): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7963): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7963): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7963): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7963): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7963): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7963): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7963): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7963): found sensor: Motion Accel, handle=46
W/Settings( 7963): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
I/Babel_Crash( 7963): startup - clean
I/art     ( 7963): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/Babel   ( 7963): deleted: false for 0
,W/ResourceType(  980): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/art     ( 7963): CheckpointMarkThreadRoots callback created = 0xb042d880
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1729): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  980): applying state to connected service
,W/AudioCapabilities( 7963): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7963): Unsupported mime audio/adpcm
W/AudioCapabilities( 7963): Unsupported mime audio/g726
W/AudioCapabilities( 7963): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7963): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7963): Unsupported mime video/mjpg
W/VideoCapabilities( 7963): Unsupported mime video/theora
,I/ActivityManager(  980): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7997 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 7963): Unsupported mime audio/evrc
W/AudioCapabilities( 7963): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7963): Unrecognized profile 2130706433 for video/avc
I/AppUp4:AppBoxCP( 7997): onCreate
,W/AppUp4:DB( 7997):  [AppBoxDatabaseHelper] construct
W/AudioCapabilities( 7963): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7963): Unsupported mime audio/qcelp
W/AudioCapabilities( 7963): Unsupported mime audio/evrc
I/AppUp4:DB( 7997):  setFingerPrint start
,I/AppUp4:DB( 7997):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7997):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7997):  SDK version = 0
I/AppUp4:DB( 7997):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7997): AppBoxApplication onCreate()
,W/VideoCapabilities( 7963): Unsupported mime video/mp4v-esdp
I/AppUp4:CustModeStarterReceiver( 7997): onReceive
I/AppUp4:CustModeStarterReceiver( 7997): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7997): Context : android.app.ReceiverRestrictedContext@30be277c
D/AppUp4:CustFacade( 7997): isCustomizationCompleted : false
,I/VideoCapabilities( 7963): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7963): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7963): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7963): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7963): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  980): Process com.google.android.apps.plus (pid 7721) has died
,D/AppUp4:CustFacade( 7997): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7997): begin check event
I/AppUp4:CustModeStarterReceiver( 7997): Event For Nothing, skip.
I/ActivityManager(  980): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8018 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 7963): onServiceConnected
,W/Babel   ( 7963): Attempted to change video mute state without an active call.
I/NotificationManager( 7963): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 8018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8018): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8018): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7963): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 7963): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,W/System  ( 7963): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7963): Installed default security provider GmsCore_OpenSSL
I/AppConfig( 8018): Total System Memory = 906309632
I/GalleryUtils( 8018): Application Heap = 96 MB
I/NotificationManager( 7963): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 8018): App Tier : NOT_DEF
D/SystemHelper( 8018): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  980): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8040 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  980): Killing 7696:com.android.chrome/u0a48 (adj 15): empty #11
,I/art     (  305): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 312us total 21.830ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.977ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 20.896ms
,W/libprocessgroup(  980): failed to open /acct/uid_10048/pid_7696/cgroup.procs: No such file or directory
W/ResourcesManager( 8040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8040): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 8040): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 8040): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 8040): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/ActivityManager(  980): Process com.android.vending (pid 7795) has died
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/SystemConfig( 8040): BUILD Country: EU
I/SystemConfig( 8040): BUILD Operator: OPEN
,I/ActivityManager(  980): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8065 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 8040): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8040): existFile = false
I/SystemConfig( 8040): canReadFile = false
I/SystemConfig( 8040): systemFeature RCS result false
D/SystemConfig( 8040): refreshRcsSupport() :false
,I/LockScreenSettings( 8065): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 8065): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 8065): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 8065): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 8065): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 8065): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  980): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8082 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  980): Killing 7864:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  980): failed to open /acct/uid_10053/pid_7864/cgroup.procs: No such file or directory
,W/ResourcesManager( 8082): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1934): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  980): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8107 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  980): Killing 7769:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7751): android.os.DeadObjectException
,I/UpdateIcingCorporaServi( 1934): UpdateCorporaTask done [took 91 ms] updated apps [took 91 ms] 
W/System.err( 7751): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7751): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7751): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7751): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7751): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7751): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7751): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7751): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7751): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7751): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7751): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7751): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7751): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7751): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7751): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7751): android.os.DeadObjectException
W/System.err( 7751): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7751): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7751): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7751): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7751): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7751): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7751): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7751): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7751): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7751): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7751): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7751): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7751): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7751): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7751): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  980): failed to open /acct/uid_10089/pid_7769/cgroup.procs: No such file or directory
W/ActivityManager(  980): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 12840ms
,I/ActivityManager(  980): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=8128 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 8128): Quickset Services start...
,I/UEI.SmartControl( 8128): Manufacture = LGE
D/UEI.SmartControl( 8128): File observer start...
E/UEI.SmartControl( 8128): IR Port is disabled: false
D/UEI.SmartControl( 8128): Starting file observer...
D/UEI.SmartControl( 8128): Extracting JNI libs...
D/UEI.SmartControl( 8128): --- this system supports 32-bit or 64-bit only
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/Finsky  ( 8107): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 8128): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 8128): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8128): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,D/Finsky  ( 8107): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/UEI.SmartControl( 8128): --- Selecting new region: 2
I/UEI.SmartControl( 8128): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 8128): Platform has CIR...
D/UEI.SmartControl( 8128): NO CIR support, need to check package...
I/UEI.SmartControl( 8128): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 8128): QS Service created
W/Settings( 8107): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8107): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 8107): com.android.vending: cancel(-1050172287) by com.android.vending
E/UEI.SmartControl( 8128): QS start get config
,V/DownloadManager( 3255): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3255): created cursor android.database.sqlite.SQLiteCursor@24bb9428 on behalf of 8107
D/UEI.SmartControl( 8128): Loading JNI Libs...
,D/UEI.SmartControl( 8128):  configuring local db...
I/art     (  980): Explicit concurrent mark sweep GC freed 28409(1471KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.482ms total 147.829ms
,D/Finsky  ( 8107): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8107): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8107): Skipping gmscore version check
D/Finsky  ( 8107): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 6642): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 6642): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 8107): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Icing   ( 6642): updateResources: need to parse f{com.google.android.gms}
,D/UEI.SmartControl( 8128):  ---- Has DB8: true
,D/UEI.SmartControl( 8128): QS start statue = true Error code = 0
D/UEI.SmartControl( 8128): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 8128): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 8128): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 8128): IRRCPlayer_nativeInit ++ 
D/irrcClient( 8128): IrrcClient ++ 
D/irrcClient( 8128): getIrrcService ++ 
D/irrcClient( 8128): getIrrcService -- 
D/irrcClient( 8128): IrrcClient -- 
W/irrc_jni( 8128): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 8128): Services init done
,I/UEI.SmartControl( 8128): Device manager: loading config....
D/UEI.SmartControl( 8128): QS Service init finished
D/UEI.SmartControl( 8128): QS Service version name: 0.1.73
,D/UEI.SmartControl( 8128): QS Service version code: 1073
D/UEI.SmartControl( 8128): Service requested: Control
D/UEI.SmartControl( 8128): Config is loaded...
D/UEI.SmartControl( 8128):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 8128): Request IControl service: devices are loaded...
I/UEI.SmartControl( 8128): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 8128): -----IControl: 11
I/ActivityManager(  980): Killing 7751:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 8128): Caller: com.lge.qremote
D/UEI.SmartControl( 8128): ------------ IControl registerCallback...
I/UEI.SmartControl( 8128): Registering callback...
D/UEI.SmartControl( 8128): Internal service binding...
W/libprocessgroup(  980): failed to open /acct/uid_10106/pid_7751/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 6642): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 6642): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  980): Killing 7534:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  980): failed to open /acct/uid_10038/pid_7534/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/SQLiteConnectionPool( 6642): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ActivityManager(  980): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=8192 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 8192): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8192): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8192): VM with version 2.1.0 has multidex support
,I/MultiDex( 8192): install
I/MultiDex( 8192): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 8192): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8192): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8192): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1af92c0c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8192): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 8192): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 8192): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1729): callingUid 10006, callindPid: 1729
,E/MDM     ( 1729): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6642): Restart initialization of location
D/ChimeraCfgMgr( 8192): Reading stored module config
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1729): No location to return for getLastLocation()
,W/FusedLocationProvider( 1729): location=null
D/ChimeraCfgMgr( 8192): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/NativeLibraryUtils( 8192): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 8192): Connecting to CarCallService...
,I/art     ( 8192): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8192): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 8192): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 8192): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 8192): Creating a new PhoneAdapter instance
,W/ActivityManager(  980): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 8192): setListener: com.google.android.gms.car.dn@2c61d24b
W/ActivityManager(  980): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 8192): Returning an existing PhoneAdapter instance.
,D/CAR.TEL.Service( 8192): Starting CarCallService with initial phone null
I/NotificationManager( 8192): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  980): Killing 7615:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  980): failed to open /acct/uid_10006/pid_7615/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/sensors_hal_Time(  980): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  980): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  980): tsOffsetIs: Apps: 133646551567; DSPS: 4470660; Offset : -2796918575
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 8128): Internal timer expired: 1
,D/UEI.SmartControl( 8128): Service.onUnbind: IControl
D/UEI.SmartControl( 8128): Service.onDestroy
W/System.err( 8128): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@2d0ea826
W/System.err( 8128): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 8128): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 8128): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 8128): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 8128): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 8128): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 8128): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 8128): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 8128): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8128): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 8128): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 8128): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8128): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8128): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 8128): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 8128): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@2d0ea826
,D/UEI.SmartControl( 8128): Shutdown IRRCPlayer... 
W/irrc_jni( 8128): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 8128): ~IrrcClient ++ 
D/irrcClient( 8128): ~IrrcClient -- 
W/irrc_jni( 8128): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 8128): Blaster closed
D/UEI.SmartControl( 8128): Blaster closed
D/UEI.SmartControl( 8128): Shut down QS...
,D/UEI.SmartControl( 8128): Stopped file observer...
I/UEI.SmartControl( 8128): QS lib stop result = true
D/UEI.SmartControl( 8128): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  980): Killing 7997:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  980): failed to open /acct/uid_10011/pid_7997/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  980): ELAPSED_WAKEUP set : Alarm{3c8754e8 type 2 when 144809 com.google.android.gms} when 144809
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1729): Vacuum at: now=1454056169042 tag=VacuumService
,W/InstanceID/Rpc( 6642): Found 10006
I/art     ( 1729): Explicit concurrent mark sweep GC freed 39531(2MB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 14MB/23MB, paused 1.244ms total 102.677ms
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PhenotypeConfigurator( 1729): Scheduling Phenotype for one-off execution 11440 seconds from now (1454056169618)
,D/GetConfigurationSnapshotOperation( 1729): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1729): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1729): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  980): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 1729): propertyValue:false
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LocationManagerService(  980): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/PowerManagerService(  980): ALS enabled for SRE
,D/PowerManagerServiceEx(  980): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26947 ms ago)
D/qdlights(  980): set_light_backlight: 254,
,D/qdlights(  980): set_light_backlight: 250
,D/qdlights(  980): set_light_backlight: 247
,D/qdlights(  980): set_light_backlight: 244
,D/LocationManagerService(  980): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/qdlights(  980): set_light_backlight: 240
,D/qdlights(  980): set_light_backlight: 237
,D/qdlights(  980): set_light_backlight: 234
,D/qdlights(  980): set_light_backlight: 230
,D/qdlights(  980): set_light_backlight: 227
,D/LocationManagerService(  980): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/qdlights(  980): set_light_backlight: 224
D/qdlights(  980): set_light_backlight: 220
,D/qdlights(  980): set_light_backlight: 217
,D/qdlights(  980): set_light_backlight: 214
,D/qdlights(  980): set_light_backlight: 210
,D/qdlights(  980): set_light_backlight: 207
,D/qdlights(  980): set_light_backlight: 204
,D/LocationManagerService(  980): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/qdlights(  980): set_light_backlight: 200
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/qdlights(  980): set_light_backlight: 197
D/qdlights(  980): set_light_backlight: 194
,D/qdlights(  980): set_light_backlight: 190
,D/qdlights(  980): set_light_backlight: 187
,D/qdlights(  980): set_light_backlight: 184
,D/qdlights(  980): set_light_backlight: 180
,D/qdlights(  980): set_light_backlight: 177
,D/qdlights(  980): set_light_backlight: 174
,D/qdlights(  980): set_light_backlight: 170
,D/qdlights(  980): set_light_backlight: 167
,D/qdlights(  980): set_light_backlight: 164
,D/qdlights(  980): set_light_backlight: 160
,D/qdlights(  980): set_light_backlight: 157
,D/qdlights(  980): set_light_backlight: 154
,D/qdlights(  980): set_light_backlight: 150
,D/qdlights(  980): set_light_backlight: 147
,D/qdlights(  980): set_light_backlight: 144
,D/qdlights(  980): set_light_backlight: 140
,D/qdlights(  980): set_light_backlight: 137
,D/qdlights(  980): set_light_backlight: 134
,D/qdlights(  980): set_light_backlight: 130
,D/qdlights(  980): set_light_backlight: 127
,D/qdlights(  980): set_light_backlight: 124
,D/qdlights(  980): set_light_backlight: 120
,D/qdlights(  980): set_light_backlight: 117
,D/qdlights(  980): set_light_backlight: 114
,D/qdlights(  980): set_light_backlight: 110
,D/qdlights(  980): set_light_backlight: 107
,D/qdlights(  980): set_light_backlight: 104
,D/qdlights(  980): set_light_backlight: 100
,D/qdlights(  980): set_light_backlight: 97
,D/qdlights(  980): set_light_backlight: 94
,D/qdlights(  980): set_light_backlight: 90
,D/qdlights(  980): set_light_backlight: 87
,D/qdlights(  980): set_light_backlight: 84
,D/qdlights(  980): set_light_backlight: 80
,D/qdlights(  980): set_light_backlight: 77
,D/qdlights(  980): set_light_backlight: 74
,D/qdlights(  980): set_light_backlight: 70
,D/qdlights(  980): set_light_backlight: 67
,D/qdlights(  980): set_light_backlight: 64
,D/qdlights(  980): set_light_backlight: 60
,D/qdlights(  980): set_light_backlight: 57
,D/qdlights(  980): set_light_backlight: 54
,D/qdlights(  980): set_light_backlight: 50
,D/qdlights(  980): set_light_backlight: 47
,D/qdlights(  980): set_light_backlight: 44
,D/qdlights(  980): set_light_backlight: 40
,D/qdlights(  980): set_light_backlight: 37
,D/qdlights(  980): set_light_backlight: 34
,D/qdlights(  980): set_light_backlight: 30
,D/qdlights(  980): set_light_backlight: 27
,D/qdlights(  980): set_light_backlight: 24
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
D/qdlights(  980): set_light_backlight: 20
,D/qdlights(  980): set_light_backlight: 17
,D/qdlights(  980): set_light_backlight: 14
,D/qdlights(  980): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  980): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  980): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  980): tsOffsetIs: Apps: 153647275362; DSPS: 5126044; Offset : -2796927671
,I/PowerManagerService(  980): ALS enabled for SRE
D/PowerManagerServiceEx(  980): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33939 ms ago)
I/PowerManagerService(  980): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  980): ALS enabled for SRE
D/PowerManagerServiceEx(  980): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33957 ms ago)
,W/ContextImpl(  980): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  980): Sleeping (uid 1000)...
,D/LPWGController(  980): [updateScreenState] screen on = false
D/LPWGController(  980): disable proximity sensor
D/LPWGController(  980): enable proximity sensor
,I/SensorManager(  980): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@16898230] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  980): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  980): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  980): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  980): activate: handle is 48, enable
,V/sensors_hal_Ctx(  980): activate sensors is 1400000000000
D/sensors_hal_Thresh(  980): enable: handle=48
I/sensors_hal_SAM(  980): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  980): waitForResponse: timeout=1000
V/sensors_hal_SAM(  980): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  980): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  980): enable: Received response: 0
D/PowerManagerServiceEx(  980): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34024 ms ago)
I/Adreno-EGL(  980): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  980): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  980): Build Date: 03/02/15 Mon
I/Adreno-EGL(  980): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  980): Remote Branch: 
I/Adreno-EGL(  980): Local Patches: 
I/Adreno-EGL(  980): Reconstruct Branch: 
,D/PermissionCache(  244): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (990 us)
,I/Sensors (  410): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  980): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  980): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  980): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  980): processInd: handle 48, count=1
V/sensors_hal_Thresh(  980): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  980): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  980): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  980): poll: count: 256
I/sensors_hal_Ctx(  980): poll: released wakelock sensor_ind
D/sensors_hal_Util(  980): waitForResponse: timeout=0
D/LPWGController(  980): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  980): current mode = 1  value = 1 1
I/LPWGController(  980): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/ActivityManager(  980): Process com.google.android.talk (pid 7963) has died
,I/LPWGController(  980): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/qdlights(  980): set_light_backlight: 0
,I/SensorManager(  980): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  980): activate: handle is 46, disable
V/sensors_hal_Ctx(  980): activate sensors is 1000000000000
D/sensors_hal_LP2(  980): enable: handle=46
D/sensors_hal_LP2(  980): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  980): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  244): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  244): hwc_blank: Blanking display: 0
I/DisplayManagerService(  980): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  980): Display changed displayId=0
,V/sensors_hal_SAM(  980): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  980): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
D/DSDPConnection( 1748): Display #0 changed.
,D/qdhwcomposer(  244): hwc_blank: Done blanking display: 0
D/SurfaceControl(  980): Excessive delay in setPowerMode(): 215ms
,I/qdhwcomposer(  244): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  980): Got set_interactive hint
,D/KeyguardViewMediator( 1373): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1329): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1373): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1329): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1329): handleNotifyScreenOFF
D/KeyguardViewMediator( 1373): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1373): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1373): unregisterProximitySensor
,D/StatusBarWindowView( 1373): onScreenTurnedOff why = 3
D/WifiServerServiceExt(  980): sendKtScanInterval  mRtspPlay : false
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=on, calling pid 980
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=on
V/voice   (  281): voice_set_parameters: enter: screen_state=on
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: exit
V/voice   (  281): voice_set_parameters: exit with code(0)
,V/msm8974_platform_lge(  281): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  281): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  281): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  281): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  281): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  281): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_ON
D/GpsLocationProvider(  980): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/WifiServerServiceExt(  980): set CMD_KT_SCAN_INTERVAL
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:true
,I/LEDService( 1800): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1800): stopPatternFlashing()
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): updateLightsLocked : turn off led
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1800): RESTART MSG
,D/SplitWindow(  980): check instance of lgWin Window{234873cf u0 SearchPanel}
,I/Cliptray Service( 1800): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1800): lockStatus = 0
D/LNfcService( 1783): action : android.intent.action.SCREEN_ON
,D/NfcServiceNXP( 1783): mScreenState : 3, mInProvisionMode : false
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
D/InputDispatcher(  980): Window went away: Window{203156c6 u0 SearchPanel}
,I/[SystemUI]Clock( 1373): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
,D/Ulp_jni (  980): JNI:system_update. Event-0
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): ACTION_SCREEN_ON
D/WeatherService( 2731): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 9:29:39
,D/WeatherService( 2731): 2 : ACTION screen on
D/WeatherService( 2731): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2731): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2731): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 9:29:39
,D/AppCleanupService( 4137): android.intent.action.SCREEN_ON
,V/AudioFlinger(  281): setParameters(): io 0, keyvalue screen_state=off, calling pid 980
,D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=off
V/voice   (  281): voice_set_parameters: enter: screen_state=off
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  281): voice_extn_compress_voip_set_parameters: exit
V/voice   (  281): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  281): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  281): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  281): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  281): adev_set_parameters: exit with code(0)
D/WifiController(  980): CMD_SCREEN_OFF 
D/WifiController(  980): shouldWifiStayAwake TRUE
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_OFF
,D/GpsLocationProvider(  980): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:false
,I/LEDService( 1800): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1800): stopPatternFlashing()
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1800): clear
I/LEDService( 1800): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): updateLightsLocked : turn on led
E/LEDService( 1800): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1800): Can't handle this request of patternId:0
D/LEDHandler( 1800): RESTART MSG
I/Cliptray Service( 1800): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/LNfcService( 1783): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1783): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1875): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): ACTION_SCREEN_OFF
D/WeatherService( 2731): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 9:29:39
D/WeatherService( 2731): 2 : ACTION screen off
D/WeatherService( 2731): 2 : TimeTick Receiver Unregister
,D/WeatherService( 2731): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 9:29:39
D/AppCleanupService( 4137): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4137): AppUsageStatsSaveTask
,E/NxpNfcJni( 1783): getReconnectState = 0x0
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1783): getDefaultRoute
D/LNfcService( 1783): isRequireNfcCRouting() return true
D/LNfcService( 1783): isHCERoutingtoHost() return : true
D/NfcService( 1783): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): newParams.techmask= mTechMask: 0
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): screenState= 1
E/NxpNfcJni( 1783): getReconnectState = 0x0
,I/Sensors (  410): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1373): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  980): ELAPSED_WAKEUP set : Alarm{3a3c915c type 2 when 160010 com.android.systemui} when 160010
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1748): getCallState : 0
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1373): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1373): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  980): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  980): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  980): tsOffsetIs: Apps: 173648049312; DSPS: 5781429; Offset : -2796916608
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2035): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  980): battery changed pluggedType: 2
D/HeadsetStateMachine( 2035): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  980): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  980): acquireWakeLockInternal: lock=154934373, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=980
,V/AlarmManager(  980): ELAPSED_WAKEUP set : Alarm{1a5d0d3a type 2 when 185372 android} when 185372
I/ActivityManager(  980): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8326 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,V/AlarmManager(  980): ELAPSED_WAKEUP set : Alarm{8827deb type 2 when 185498 com.google.android.gms} when 185498
,I/DigitalAppWidgetProvider( 8326): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8326): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@30be277c
D/PowerManagerServiceEx(  980): releaseWakeLockInternal: lock=154934373 [*alarm*], flags=0x0
,I/ClearcutLoggerApiImpl( 1729): disconnect managed GoogleApiClient
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,D/HeadsetStateMachine( 2035): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  980): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  980): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  980): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  980): tsOffsetIs: Apps: 193648726388; DSPS: 6436811; Offset : -2796910737
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  980): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  980): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  980): tsOffsetIs: Apps: 213649479713; DSPS: 7092196; Offset : -2796922200
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  980): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  980): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  980): tsOffsetIs: Apps: 233650570487; DSPS: 7747592; Offset : -2796928730
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2035): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  980): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  980): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  980): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  980): tsOffsetIs: Apps: 253651330584; DSPS: 8402977; Offset : -2796931183
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  980): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  980): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  980): tsOffsetIs: Apps: 273652003233; DSPS: 9058359; Offset : -2796929841
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  980): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  980): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  980): tsOffsetIs: Apps: 293652756976; DSPS: 9713743; Offset : -2796908521
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 5771): TAP version 13
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # multiplex can send data
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 1 String should be length:200
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # enqueue and run in order
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 2 firstPromise setTimeout
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 3 firstPromise result
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 4 firstPromise testValue
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 5 secondPromise setTimeout
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 6 secondPromise result
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 7 secondPromise testValue
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 8 thirdPromise in promise
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 9 thirdPromise result
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 10 thirdPromise testValue
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # basic
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 11 sane
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # another
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 12 sane
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 13 should be equal
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 14 null
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 15 (unnamed assert)
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 16 should be equal
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 17 should not throw
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 18 (unnamed assert)
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 19 (unnamed assert)
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 20 should not throw
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 21 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 22 should be equal
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 23 should be equal
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # failed to get mobile documents path
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 24 should be equal
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5771): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 25 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 26 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 27 should be equal
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #init should register the networkChanged event
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 28 should be equal
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #startBroadcasting should throw on null device name
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 29 should throw
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 30 should throw
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #startBroadcasting should throw on non-number port
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 31 should throw
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #startBroadcasting should throw on NaN port
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 32 should throw
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #startBroadcasting should throw on negative port
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 33 should throw
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #startBroadcasting should throw on too large port
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 34 should throw
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 35 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 36 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 37 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 38 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 39 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 40 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 41 should be equal
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 42 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 43 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 44 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 45 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 46 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 47 should be equal
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 48 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 49 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # should call Mobile("Disconnect") without an error
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 50 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 51 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 52 should be equal
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 53 should be equal
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056328933.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
,D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056328933.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5771): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2035): BTA_JvCreateRecordByUser
,D/LGBluetoothServiceAdapter( 2035): [BTUI] createSocketChannel FD=87 mFd=85
,I/bt-btif ( 2035): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: OK
I/io.jxcore.node.ConnectionHelper( 5771): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056328933.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): createAdvertiseData: From: 1454056328933.5771 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): F8:95:C7:87:85:54
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5771): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056328933.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): start: {"pi":"F8:95:C7:87:85:54","pn":"1454056328933.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454056328933.5771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9adc6d60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9adc6d60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState add service
,D/LGWifiP2pService(  980): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): start: Starting P2P device discovery...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056328933.5771
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: STARTED
,D/LGWifiP2pService(  980): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5771): start: OK
I/jxcore-log( 5771): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 5771): 
I/io.jxcore.node.ConnectionHelper( 5771): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): onServerStopped
I/bt-btif ( 2035): BTA_JvDeleteRecord
I/bt-btif ( 2035): BTA_JvRfcommStopServer
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: NOT_STARTED
I/wpa_supplicant( 2685): p2p0: CTRL-EVENT-SCAN-STARTED 
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stop: Stopping peer discovery...
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothLeScanner( 5771): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): stop: Stopping services
D/WfdsMonitor( 1800): Event [CTRL-EVENT-SCAN-STARTED ]
,D/LGWifiP2pService(  980): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  980): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local services cleared successfully
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopWifiPeerDiscovery: Stopped
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): release: No more listeners, de-initializing...
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast false
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5771): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5771): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 5771): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329174.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329174.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5771): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2035): BTA_JvCreateRecordByUser
I/bt-btif ( 2035): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: OK
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5771): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329174.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Waiting for incoming connections...
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): createAdvertiseData: From: 1454056329174.5771 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5771): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329174.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): start: {"pi":"F8:95:C7:87:85:54","pn":"1454056329174.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454056329174.5771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  980): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@568c8e64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@568c8e64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState add service
D/LGWifiP2pService(  980): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329174.5771
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: OK
I/jxcore-log( 5771): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 5771): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): onServerStopped
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending],
,D/LGWifiP2pService(  980): discovery change broadcast true
I/bt-btif ( 2035): BTA_JvDeleteRecord
I/bt-btif ( 2035): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  980): InactiveState{ when=-5ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
,D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothLeScanner( 5771): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5771): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 5771): 
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service
D/LGWifiP2pService(  980): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local services cleared successfully
D/LGWifiP2pService(  980): InactiveState{ when=-4ms what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE
,D/LGWifiP2pService(  980): InactiveState{ when=-9ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-9ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5771): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329226.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329226.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5771): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2035): BTA_JvCreateRecordByUser
I/bt-btif ( 2035): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: OK
I/io.jxcore.node.ConnectionHelper( 5771): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329226.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): createAdvertiseData: From: 1454056329226.5771 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5771): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329226.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): start: {"pi":"F8:95:C7:87:85:54","pn":"1454056329226.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454056329226.5771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@78f3e268 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@78f3e268 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState add service
D/LGWifiP2pService(  980): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): start: Starting P2P device discovery...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2685): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_WIFI
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  980): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329226.5771
I/io.jxcore.node.ConnectionHelper( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/jxcore-log( 5771): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 5771): 
I/io.jxcore.node.ConnectionHelper( 5771): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): stopListeningForIncomingConnections: Stopping...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: NOT_STARTED
I/bt-btif ( 2035): BTA_JvDeleteRecord
I/bt-btif ( 2035): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stop: Stopping peer discovery...
I/wpa_supplicant( 2685): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Exiting thread
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): onServerStopped
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothLeScanner( 5771): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/LGWifiP2pService(  980): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: NOT_INITIALIZED
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: No more listeners, de-initializing...
D/LGWifiP2pService(  980): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: NOT_STARTED
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5771): Service requests cleared successfully
I/jxcore-log( 5771): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 5771): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE_AND_WIFI,
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329293.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329293.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5771): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2035): BTA_JvCreateRecordByUser
I/bt-btif ( 2035): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: OK
I/io.jxcore.node.ConnectionHelper( 5771): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329293.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): createAdvertiseData: From: 1454056329293.5771 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5771): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329293.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): start: {"pi":"F8:95:C7:87:85:54","pn":"1454056329293.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454056329293.5771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4627a2e0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4627a2e0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState add service
D/LGWifiP2pService(  980): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_WIFI
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329293.5771
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  980): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/jxcore-log( 5771): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 5771): 
I/io.jxcore.node.ConnectionHelper( 5771): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionM,anager( 5771): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): shutdown
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): onServerStopped
I/wpa_supplicant( 2685): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
I/bt-btif ( 2035): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: NOT_STARTED
I/bt-btif ( 2035): BTA_JvRfcommStopServer
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stop: Stopping peer discovery...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothLeScanner( 5771): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
,D/LGWifiP2pService(  980): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopWifiPeerDiscovery: Stopped
D/LGWifiP2pService(  980): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local services cleared successfully
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5771): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 5771): 
D/LGWifiP2pService(  980): InactiveState{ when=-2ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-2ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5771): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329334.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329334.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5771): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2035): BTA_JvCreateRecordByUser
I/bt-btif ( 2035): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: OK
I/io.jxcore.node.ConnectionHelper( 5771): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329334.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): createAdvertiseData: From: 1454056329334.5771 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): F8:95:C7:87:85:54
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5771): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329334.5771","ra":"F8:95:C7:87:85:54"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): start: {"pi":"F8:95:C7:87:85:54","pn":"1454056329334.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454056329334.5771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d123bbe8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d123bbe8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState add service
D/LGWifiP2pService(  980): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): start: Starting P2P device discovery...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329334.5771
D/LGWifiP2pService(  980): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5771): start: OK
I/jxcore-log( 5771): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 5771): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5771): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): shutdown
I/wpa_supplicant( 2685): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: NOT_STARTED
I/bt-btif ( 2035): BTA_JvDeleteRecord
I/bt-btif ( 2035): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothLeScanner( 5771): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): stop: Stopping services
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service
D/LGWifiP2pService(  980): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): release: No more listeners, de-initializing...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: NOT_STARTED
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service request
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5771): Service requests cleared successfully
I/jxcore-log( 5771): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 5771): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329370.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329370.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5771): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2035): BTA_JvCreateRecordByUser
I/bt-btif ( 2035): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: OK
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5771): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329370.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): createAdvertiseData: From: 1454056329370.5771 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5771): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329370.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): start: {"pi":"F8:95:C7:87:85:54","pn":"1454056329370.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454056329370.5771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): start: Starting P2P device discovery...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e96e5de8 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e96e5de8 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/LGWifiP2pService(  980): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_WIFI
D/LGWifiP2pService(  980): add a new client
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329370.5771
I/io.jxcore.node.ConnectionHelper( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local service added successfully
I/wpa_supplicant( 2685): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery started successfully
D/LGWifiP2pService(  980): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: STARTED
I/jxcore-log( 5771): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log,( 5771): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
I/io.jxcore.node.ConnectionHelper( 5771): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/LGWifiP2pService(  980): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast false
I/bt-btif ( 2035): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: 1 listener(s) left
I/bt-btif ( 2035): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stop: Stopping peer discovery...
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
,D/BluetoothLeScanner( 5771): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): stop: Stopping services
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: No more listeners, de-initializing...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service
D/LGWifiP2pService(  980): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local services cleared successfully
D/LGWifiP2pService(  980): InactiveState{ when=-2ms what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  980): InactiveState{ when=-2ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-2ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5771): Service requests cleared successfully
I/jxcore-log( 5771): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 5771): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329404.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329404.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothC,onnector( 5771): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5771): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 2035): BTA_JvCreateRecordByUser
I/bt-btif ( 2035): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: OK
I/io.jxcore.node.ConnectionHelper( 5771): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329404.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): createAdvertiseData: From: 1454056329404.5771 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5771): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329404.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): start: {"pi":"F8:95:C7:87:85:54","pn":"1454056329404.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454056329404.5771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ffb060ec target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ffb060ec target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState add service
D/LGWifiP2pService(  980): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329404.5771
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: OK
D/LGWifiP2pService(  980): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_BLE_AND_WIFI
I/jxcore-log( 5771): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 5771): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: 1 listener(s) left
I/bt-btif ( 2035): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: NOT_STARTED,
I/bt-btif ( 2035): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothLeScanner( 5771): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): stop: Stopping services
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): stop: Stopping P2P device discovery...
I/wpa_supplicant( 2685): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: false
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: NOT_STARTED
,D/LGWifiP2pService(  980): P2pEnabledState clear service
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  980): remove client information from framework
I/jxcore-log( 5771): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 5771): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local services cleared successfully
D/LGWifiP2pService(  980): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast false
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
,D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5771): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329434.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329434.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5771): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2035): BTA_JvCreateRecordByUser
I/bt-btif ( 2035): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: OK
I/io.jxcore.node.ConnectionHelper( 5771): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329434.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): createAdvertiseData: From: 1454056329434.5771 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5771): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329434.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): start: {"pi":"F8:95:C7:87:85:54","pn":"1454056329434.5771","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454056329434.5771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2bed3626 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2bed3626 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState add service
D/LGWifiP2pService(  980): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329434.5771
I/io.jxcore.node.ConnectionHelper( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
I/jxcore-log( 5771): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 5771): 
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: NOT_STARTED
I/bt-btif ( 2035): BTA_JvDeleteRecord
I/bt-btif ( 2035): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): onServerStopped
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.androi,d.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/LGWifiP2pService(  980): discovery change broadcast true
D/BluetoothLeScanner( 5771): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: STARTED
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: No more listeners, de-initializing...
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: NOT_STARTED
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service
D/LGWifiP2pService(  980): remove client information from framework
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local services cleared successfully
D/LGWifiP2pService(  980): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5771): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5771): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 5771): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329467.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329467.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5771): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2035): BTA_JvCreateRecordByUser
I/bt-btif ( 2035): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: OK
I/io.jxcore.node.ConnectionHelper( 5771): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329467.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): createAdvertiseData: From: 1454056329467.5771 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5771): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329467.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): start: {"pi":"F8:95:C7:87:85:54","pn":"1454056329467.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454056329467.5771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f22ee71a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f22ee71a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState add service
D/LGWifiP2pService(  980): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_WIFI
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329467.5771
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
,I/jxcore-log( 5771): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 5771): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 2685): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5771): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: NOT_STARTED
I/bt-btif ( 2035): BTA_JvDeleteRecord
I/bt-btif ( 2035): BTA_JvRfcommStopServer
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): onServerStopped
D/LGWifiP2pService(  980): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: STARTED
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothLeScanner( 5771): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): stop: Stopping services
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 2685): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): release: No more listeners, de-initializing...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139298 arg2=4 targ,et=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: NOT_STARTED
D/LGWifiP2pService(  980): remove client information from framework
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local services cleared successfully
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5771): Service requests cleared successfully
I/jxcore-log( 5771): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 5771): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329500.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329500.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5771): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2035): BTA_JvCreateRecordByUser
I/bt-btif ( 2035): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: OK
I/io.jxcore.node.ConnectionHelper( 5771): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329500.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): createAdvertiseData: From: 1454056329500.5771 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5771): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056329500.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): start: {"pi":"F8:95:C7:87:85:54","pn":"1454056329500.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454056329500.5771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@37c8b632 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@37c8b632 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState add service
D/LGWifiP2pService(  980): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_WIFI
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056329500.5771
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: OK
D/LGWifiP2pService(  980): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.,wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/jxcore-log( 5771): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 5771): 
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5771): stop
I/wpa_supplicant( 2685): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): shutdown
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): onServerStopped
I/bt-btif ( 2035): BTA_JvDeleteRecord
I/bt-btif ( 2035): BTA_JvRfcommStopServer,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stop: Stopping peer discovery...
,D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
,D/BluetoothLeScanner( 5771): could not find callback wrapper
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): stop: Stopping services
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  980): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: NOT_INITIALIZED
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
,D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5771): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5771): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # ThaliEmitter calls startBroadcasting twice with error,
I/jxcore-log( 5771): 
,I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 4
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056330172.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056330172.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5771): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2035): BTA_JvCreateRecordByUser
I/bt-btif ( 2035): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: OK
I/io.jxcore.node.ConnectionHelper( 5771): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056330172.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): createAdvertiseData: From: 1454056330172.5771 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5771): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056330172.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): start: {"pi":"F8:95:C7:87:85:54","pn":"1454056330172.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454056330172.5771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8d272e78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8d272e78 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState add service
D/LGWifiP2pService(  980): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Waiting for incoming connections...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast true
I/wpa_supplicant( 2685): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1800): Event [CTRL-EVENT-SCAN-STARTED ]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056330172.5771
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5771): start: OK
I/jxcore-log( 5771): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 75 Cannot call startBroadcasting twice
I/jxcore-log( 5771): 
I/io.jxcore.node.ConnectionHelper( 5771): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Exiting th,read
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): onServerStopped
,I/bt-btif ( 2035): BTA_JvDeleteRecord
I/bt-btif ( 2035): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stop: Stopping peer discovery...
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothLeScanner( 5771): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): stop: Stopping services
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service
D/LGWifiP2pService(  980): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: NOT_INITIALIZED
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5771): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5771): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056330458.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056330458.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5771): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2035): BTA_JvCreateRecordByUser
,I/bt-btif ( 2035): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: OK
I/io.jxcore.node.ConnectionHelper( 5771): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056330458.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
,D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): createAdvertiseData: From: 1454056330458.5771 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5771): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056330458.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): start: {"pi":"F8:95:C7:87:85:54","pn":"1454056330458.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454056330458.5771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Waiting for incoming connections...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b40f712a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b40f712a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState add service
D/LGWifiP2pService(  980): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): start: Starting P2P device discovery...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1800): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  980): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056330458.5771
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5771): start: OK
I/jxcore-log( 5771): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 5771): 
,I/io.jxcore.node.ConnectionHelper( 5771): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 5771): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 5771): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 5771): ok 78 Should not connect to a bad peer
I/jxcore-log( 5771): 
I/io.jxcore.node.ConnectionHelper( 5771): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): onServerStopped
I/bt-btif ( 2035): BTA_JvDeleteRecord
I/bt-btif ( 2035): BTA_JvRfcommStopServer
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stop: Stopping peer discovery...
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothLeScanner( 5771): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): stop: Stopping services
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service
D/LGWifiP2pService(  980): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: NOT_INITIALIZED
D/LGWifiP2pService(  980): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5771): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5771): ok 79 Should be able to call stopBroadcasting without error
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 4
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056331169.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056331169.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5771): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2035): BTA_JvCreateRecordByUser
I/bt-btif ( 2035): BTA_JvRfcommStartServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): start: OK
I/io.jxcore.node.ConnectionHelper( 5771): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056331169.5771
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): createAdvertiseData: From: 1454056331169.5771 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5771): F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5771): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5771): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5771): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454056331169.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): start: {"pi":"F8:95:C7:87:85:54","pn":"1454056331169.5771","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454056331169.5771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Waiting for incoming connections...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@972202a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@972202a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState add service
D/LGWifiP2pService(  980): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): start: Starting P2P device discovery...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast true
I/wpa_supplicant( 2685): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1800): Event [CTRL-EVENT-SCAN-STARTED ]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454056331169.5771
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2685): P2P-FIND-STOPPED 
D/WfdsMonitor( 1800): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): P2P device discovery stopped successfully
D/LGWifiP2pService(  980): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: RESTARTING
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5771): start: OK
I/jxcore-log( 5771): ok 80 Should be able to call startBroadcasting without error
I/jxcore-log( 5771): 
D/io.jxcore.node.ConnectionHelper( 5771): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 5771): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 5771): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 5771): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
I/jxcore-log( 5771): ok 81 Disconnect should fail to a non-existant peer 
I/jxcore-log( 5771): 
I/io.jxcore.node.ConnectionHelper( 5771): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5771): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5771): onServerStopped
,I/bt-btif ( 2035): BTA_JvDeleteRecord
I/bt-btif ( 2035): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5771): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5771): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stop: Stopping peer discovery...
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothLeScanner( 5771): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5771): stop: Stopping services
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=-1ms what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service
,D/LGWifiP2pService(  980): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5771): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5771): setState: NOT_INITIALIZED
D/LGWifiP2pService(  980): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5771): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5771): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5771): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5771): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5771): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5771): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 83 host address should match
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 84 port should match
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 85 peer should be available
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 86 peer should be unavailable
I/jxcore-log( 5771): 
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  980): battery changed pluggedType: 2
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2035): Disconnected process message: 10, size: 0
I/jxcore-log( 5771): # #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 87 when receiving the first byebye, the second USN should not be set yet
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 88 USN should have changed from the first one
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 89 when receiving the second byebye, the first USN should be already set
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # messages with invalid location or USN should be ignored
I/jxcore-log( 5771): 
,I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 4
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5771): WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 90 should not have emitted with invalid port
I/jxcore-log( 5771): 
I/jxcore-log( 5771): WARN thaliWifiInfrastructure Received an invalid USN value: 
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 91 should not have emitted with invalid USN
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 92 irrelevant messages should be ignored
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 93 relevant messages should not be ignored
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 94 messages from this device should be ignored
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #start should fail if called twice in a row
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 95 specific error should be received
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #startUpdateAdvertisingAndListening should fail invalid router has been passed
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,E/jxcore-log( 5771): ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
E/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 96 specific error should be received
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #startUpdateAdvertisingAndListening should fail if router server starting fails
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,E/jxcore-log( 5771): ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
E/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 97 specific error expected
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,D/libc-netbsd( 5771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=0; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10316
D/DnsProxyListener(  276): App 10316 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=0; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/jxcore-log( 5771): ok 98 server should respond with code 200
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #stop can be called multiple times in a row
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 99 should be in stopped state
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 100 should still be in stopped state
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #startListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 101 should be in listening state
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 102 should still be in listening state
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #stopListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 103 should not be in listening state
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 104 should still not be in listening state
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # #stopAdvertisingAndListening can be called multiple times in a row
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 105 should not be in advertising state
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ok 106 should still not be in advertising state
I/jxcore-log( 5771): 
I/jxcore-log( 5771): # setup
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # functions are run from a queue in the right order
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): # teardown
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): ok 107 call order must match
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): Tests Complete
I/jxcore-log( 5771): 
I/jxcore-log( 5771): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 5771): 
,I/jxcore-log( 5771): Toggling radios to false
I/jxcore-log( 5771): 
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  980): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3fd36547 mBinding = false
I/chromium( 5771): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 5771): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothManagerService(  980): Message: 2
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothManagerService(  980): Sending off request.
D/WifiServiceImplEx(  980): setWifiEnabled: false pid=5771, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  980): setWifiEnabled: false pid=5771, uid=10316
D/LocationManagerService(  980): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  980): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  980): JNI:system_update. Event-4
D/BluetoothAdapterService(755935270)( 2035): disable() called...
,D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
,D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterState( 2035): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2035): Setting state to 13
I/BluetoothAdapterState( 2035): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService(755935270)( 2035): updateAdapterState() - Broadcasting state to 1 receivers.
D/LocationManagerService(  980): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  980): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  980): JNI:system_update. Event-4
I/jxcore-log( 5771): Radios toggled
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ****TEST TOOK:  ms ****
I/jxcore-log( 5771): 
I/jxcore-log( 5771): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5771): 
E/WifiStateMachine(  980): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  980): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BluetoothAdapterProperties( 2035): onBluetoothDisable()
D/LGWifiP2pService(  980): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/BluetoothAdapterState( 2035): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/bt-btif ( 2035): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 2035): Scan Mode:20
D/BluetoothAdapterState( 2035): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 2035): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 2035): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/bt-btif ( 2035): btsock_ctrl_hci_cleanup(L202): poll handle:4
I/bt-btif ( 2035): BTA_JvDeleteRecord
I/bt-btif ( 2035): BTA_JvRfcommStopServer
I/bt-btif ( 2035): BTA_JvDeleteRecord
I/bt-btif ( 2035): BTA_JvRfcommStopServer
W/bt-btif ( 2035): invalid rfc slot id: 1
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/DhcpStateMachine(  980): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/IOP_DB_BT( 2035): db_close: nbr users 0
D/IOP_DB_BT( 2035): db_close: free database
W/bt-btif ( 2035): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/CommandListener(  276): Clearing all IP addresses on wlan0
E/bt-btif ( 2035): btif_hf_upstreams_evt: wrong handle = 29735 
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 7
D/btif_config_util( 2035): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/btif_config_util( 2035): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2035): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 2035): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 2035): enum_config(L344): out, value:f8:95:c7:87:85:54
D/btif_config_util( 2035): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:G3s-1
D/btif_config_util( 2035): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2035): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 2035): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2035): enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2035): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2035): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 2035): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2035): enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2035): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2035): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 2035): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2035): enum_config(L344): out, value:��8�\�婓��n�ScanMode
D/btif_config_util( 2035): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 2035): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 2035): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 2035): enum_config(L344): out, value:x
D/btif_config_util( 2035): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2035): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 2035): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2035): enum_config(L344): out, value:s!WE�(E��00:0F:F6
D/btif_config_util( 2035): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2035): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2035): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:,16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 2035): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2035): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2035): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 2035): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2035): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2035): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 2035): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2035): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2035): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 2035): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:�
D/btif_config_util( 2035): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 2035): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/b,tif_config_util( 2035): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2035): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:$
D/btif_config_util( 2035): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 2035): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:�
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:A5-1
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2035): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
W/bt-obex ( 2035): Ignore event 10 in state 1
D/btif_config_util( 2035): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
W/bt-obex ( 2035): Ignore event 10 in state 1
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:#
D/btif_config_util( 2035): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 2035): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
I/bt-btif ( 2035): HAL bt_op_callbacks->ops_state_cb
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/BluetoothOPPServiceJni( 2035): ops_state_cb(L223):  ops_state_cb state:3
D/btif_config_util( 2035): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2035): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:�
D/btif_config_util( 2035): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:XT1072
D/btif_config_util( 2035): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
E/bt-btif ( 2035): bta_gattc_deregister Deregister Failedm unknown client cif
D/btif_config_util( 2035): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:a
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:S5-1
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2035): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:	a
D/btif_config_util( 2035): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:G4-1
D/btif_config_util( 2035): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2035): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:a
D/btif_config_util( 2035): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:Thali Test (Galaxy S5)
D/btif_config_util( 2035): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string,
D/btif_config_util( 2035): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:�
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:Thali Test (Galaxy A5)
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
V/NativeCrypto( 1729): Read error: ssl=0xaaedf600: I/O error during system call, Connection timed out
D/OppService( 2035): onOpsStateChange() :3
D/OppService( 2035): Recieved MESSAGE_OPS_DISABLE
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:�
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:Thali Test (Galaxy A3)
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:A
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:Thali Test's G2
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
,D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:	a
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:Note3-1
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
,D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
,D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:�
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:A3-1
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevClass, value type:int
,D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevType,
,D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Service
,D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2035): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
,D/btif_config_util( 2035): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:�
D/btif_config_util( 2035): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:XT1039
D/btif_config_util( 2035): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevType
,D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
,D/btif_config_util( 2035): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpVer, value type:int
,D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:	a
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevClass, value type:int
,D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:GlobalTrust, value type:int
,D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2035): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpVer
,D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:�
D/btif_config_util( 2035): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:HTC One_M8
D/btif_config_util( 2035): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevClass
,D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 7
D/btif_config_util( 2035): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Manufacturer, value type:int
,D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:"
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
,D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:Note4-1
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:JustWorks
,D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2035): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Manufacturer
,D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:�
,D/btif_config_util( 2035): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Name
,D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 2035): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:80:01:84:8a:b3:68, value:JustWorks
,D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 2035): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:�
D/btif_config_util( 2035): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:G3-1
D/btif_config_util( 2035): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:5,8:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:	a
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Glob,alTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:�
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 2035): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:A
D/btif_config_util( 2035): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:S5mini-1
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/NativeCrypto( 1729): SSL shutdown failed: ssl=0xaaedf600: I/O error during system call, Broken pipe
D/BluetoothManagerService(  980): Message: 60
D/BluetoothManagerService(  980): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  980): Bluetooth State Change Intent: 12 -> 13
D/btif_config_util( 2035): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/ConnectivityService(  980): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  980): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
D/btif_config_util( 2035): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Service, value type:string
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/jxcore-log( 5771): Toggling radios to false
I/jxcore-log( 5771): 
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LGBluetoothAPIService( 1800): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/btif_config_util( 2035): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2035): enum_config(L300): in, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:T\���K�`�D�`�D�
D/btif_config_util( 2035): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:���
D/btif_config_util( 2035): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:ALE-L21
D/btif_config_util( 2035): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:#
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:onem9-1
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:H
D/btif_config_util( 2035): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:?C
D/btif_config_util( 2035): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:Tab4
D/btif_config_util( 2035): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Service, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 2035): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2035): enum_config(L300): in, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:41:0e, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:41:0e, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:�h�
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:41:0e, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:41:0e, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:��h
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:41:0e, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:41:0e, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:J���J�hrD�hrD�
D/btif_config_util( 2035): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:��P
D/btif_config_util( 2035): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevType, value type:int
,D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/btif_config_util( 2035): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:08:00:00:00:67:73, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:00:00:00:67:73, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:08:00:00:00:67:73, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:00:00:00:67:73, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/btif_config_util( 2035): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:�
D/btif_config_util( 2035): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:Galaxy S5-2
D/btif_config_util( 2035): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevType, value type:int
I/[SystemUI]BluetoothHandler( 1373): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
D/btif_config_util( 2035): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Manufacturer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpSubVer, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 2035): enum_config(L344): out, value:�
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:A3-1
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:Z
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:JustWorks, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:GlobalTrust, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:$��
D/btif_config_util( 2035): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:`��
D/btif_config_util( 2035): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:���
D/btif_config_util( 2035): enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:�_
D/btif_config_util( 2035): enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:41:9e, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:41:9e, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:4g�
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:41:9e, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:��f
D/btif_config_util( 2035): enum_config(L300): in, key:00:00:00:00:41:9e, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
D/btif_config_util( 2035): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:Name
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:Name, value type:string
D/btif_config_util( 2035): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:Name
D/btif_config_util( 2035): enum_config(L344): out, value:4g�������v��
D/btif_config_util( 2035): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevClass, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 2035): enum_config(L344): out, value:��\
D/btif_config_util( 2035): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevType
D/btif_config_util( 2035): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevType, value type:int
D/btif_config_util( 2035): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevType
D/btif_config_util( 2035): enum_config(L344): out, value:
I/BluetoothMapService( 2035): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 2035): STATE_TURNING_OFF
D/ConnectivityService(  980): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10006
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): ValidatedState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): DefaultState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): Forcing reevaluation
V/BluetoothMapService( 2035): Handler(): got msg=4
D/BluetoothMapService( 2035): MAP Service closeService in
D/BluetoothMapMasInstance( 2035): MAP Service shutdown
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
,D/ConnectivityService(  980): Default network via Wi-Fi disconnect. stop DSQN
V/BluetoothPbapService( 2035): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/DSQN    (  980): disableDataServiceNotify
D/DSQN    (  980): stop dsqn bin
V/BluetoothMapMasInstance( 2035): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2035): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2035): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 2035): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 2035): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 2035): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2035): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2035): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,D/LGBluetoothMapAdapter( 2035): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2035): MAP Service closeService out
I/ActivityManager(  980): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=8470 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/BluetoothManagerService(  980): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  980): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3fd36547 mBinding = false
D/WifiHS20(  980): hidePasspointNotification off =false
D/BluetoothManagerService(  980): Message: 2
D/BluetoothManagerService(  980): Sending off request.
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  980): hidePasspointNotification off =false
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  980): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  980): SCAN_AVAILABLE : 1
D/RttService(  980): SCAN_AVAILABLE : 1
D/LGWifiP2pService(  980): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  980): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): P2pDisablingState
D/LGWifiP2pService(  980): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  980): p2p socket connection lost
D/LGWifiP2pService(  980): P2pDisabledState
,D/WifiScanningService(  980): DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNetworkAgent(  980): NetworkAgent: NetworkAgent channel lost
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:32:14.242 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WfdsService( 1800): WifiP2pState is changed : false
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/LGWifiP2pService(  980): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/LGWifiP2pService(  980): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:32:14.243 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiServiceImplEx(  980): setWifiEnabled: false pid=5771, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  980): setWifiEnabled: false pid=5771, uid=10316
D/ConnectivityService(  980): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
I/jxcore-log( 5771): Radios toggled
I/jxcore-log( 5771): 
D/BluetoothAdapterService(755935270)( 2035): disable() called...
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothAdapterService( 2035): disable() : BT State is not STATE_ON. Can't disable BT
,E/BluetoothManagerService(  980): IBluetooth.disable() returned false
D/WfdsService( 1800): WfdsEnabledState: Receive the WFDS_DISABLE message
D/ConnectivityService(  980):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  980):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WfdsJNI ( 1800): doCommand: P2P_STOP_FIND
D/WfdsService( 1800): Set the WFDS Monitor: false
D/CommandListener(  276): Clearing all IP addresses on wlan0
,D/WifiHS20(  980): hidePasspointNotification off =false
W/Settings(  980): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  980): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  980): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:32:14.266 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  980): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  980): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  980): Disconnected - quitting
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:32:14.274 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/DhcpStateMachine(  980): StoppedState
D/DhcpStateMachine(  980): StoppedState{ when=-15ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  980): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  980): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  980): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/ConnectivityService(  980): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  980): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/QCNEJ   ( 1836): |CORE| No family connected
V/NetworkPolicy(  980): [LG_RESTRICTED] !!!isConnected  type  :1
I/WifiServerServiceExt(  980): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt(  980): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  980): setSupplicantStateDISCONNECTED
D/Tethering(  980): MasterInitialState.processMessage what=3
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/QCNEJ   ( 1836): |CORE| No family connected
,V/NetworkPolicy(  980): [LG_RESTRICTED] !!!isConnected  type  :1
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/Tethering(  980): MasterInitialState.processMessage what=3
D/ConnectivityService(  980): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  980): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  980): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  980): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  980):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  980): Removing idletimer
W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
E/ConnectivityService(  980): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.p2p.STATE_CHANGED at null
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/TelephonyNetworkFactory-1( 1748): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = -1
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WfdsMonitor( 1800): WFDS Monitor is stopped
D/CtrlSupplicant( 1800): Received on exit socket, terminate
E/CtrlSupplicant( 1800): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1800): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1800): WfdsMonitorThread is received the interrupt - closing
D/WfdsService( 1800): STATE : WfdsDisabledState - enter
D/WfdsService( 1800): WFDS: Scanner is paused
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/WfdsDiscoveryStore( 1800): Clear Discovery Method Map: ScanAlwaysMode false
W/WfdsSession:Controller( 1800): DefaultState - msg [9441355] is not handled
,I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 4
,I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 5
I/wpa_supplicant( 2685): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2685): monitor socket send errors count : 1
I/wpa_supplicant( 2685): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1800-2\x00 that cannot receive messages
I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 10
I/Netd    (  276): M: Get netlink event, ifname: p2p0 action: 7
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
,I/wpa_supplicant( 2685): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 2685): USIM:  scard_deinit function
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
D/libc-netbsd(  980): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  980): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 5
,I/wpa_supplicant( 2685): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  980): InitialState.processMessage what=4
D/Tethering(  980): sendTetherStateChangedBroadcast 0, 0, 0
,D/AndroidRuntime( 8449): 
D/AndroidRuntime( 8449): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8449): CheckJNI is OFF
,W/ResourcesManager( 8470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8470): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 8470): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8470): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8470): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/WfdsService( 1800): Supplicant Connection state is changed : false
D/WifiOffDelayIfNotUsed(  980): stopMonitoring
D/WfdsService( 1800): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1800): Set the WFDS Monitor: false
D/WfdsMonitor( 1800): WFDS Monitor is stopped
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 09:32:14.626 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/WifiServerServiceExt(  980): WIFI_STATE_CHANGED_ACTION [1]
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/WifiServerServiceExt(  980): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt(  980): batteryPsActivateMsgHandler : this is not treated
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.WIFI_STATE_CHANGED at null
W/Settings( 1729): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/IndexDatabaseHelper( 8470): Using schema version: 115
,I/IndexDatabaseHelper( 8470): Index is fine
,D/AndroidRuntime( 8449): Calling main entry com.android.commands.pm.Pm
,I/art     (  980): Explicit concurrent mark sweep GC freed 72520(3MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 2.759ms total 171.917ms
,I/ActivityManager(  980): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  980): Killing 5771:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,W/bt_userial( 2035): select_read return size <=0:0, exiting userial_read_thread
D/bt_hwcfg( 2035): hw_epilog_process
I/bt_userial_vendor( 2035): device fd = 68 close
W/bt-l2cap( 2035): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2035): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 2035): ag scb idx 1 not allocated
E/bt-btif ( 2035): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2035): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2035): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 2035): ag scb idx 1 not allocated
E/bt-btif ( 2035): BTA AG is already disabled, ignoring ...
E/bt-btif ( 2035): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 2035): bta_gattc_deregister Deregister Failedm unknown client cif
,E/bt_vendor( 2035): [BTUI] Proto is enabled. Set Proto disable!!
I/WindowState(  980): WIN DEATH: Window{3166fa47 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  980): Focus left window: Window{3166fa47 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  980): Window went away: Window{3166fa47 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  980): Skipping PackageSetting{3273f85c com.example.hello/10317} due to missing metadata
,W/ContextImpl( 8470): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,I/GKI_LINUX( 2035): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,I/ActivityManager(  980):   Force finishing activity ActivityRecord{f395576 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  980): Display changed displayId=0
,D/DSDPConnection( 1748): Display #0 changed.
,W/ActivityManager(  980): Spurious death for ProcessRecord{31c7f174 5771:com.test.thalitest/u0a316}, curProc for 5771: null
,V/BluetoothPbapReceiver( 2035): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2035): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2035): ***********state = 13
I/GKI_LINUX( 2035): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2035): GKI_destroy_task(): task [BTU] terminated
I/bt-btif ( 2035): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 2035): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2035): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
V/BluetoothPbapReceiver( 2035): ***********Calling start service!!!! with action = null
I/ActivityManager(  980): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,D/BtSettings.ProfileConfig( 2035): Unable to read settings
D/BtSettings.ProfileConfig( 2035): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2035): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2035): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2035): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2035): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 2035): 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
D/BtSettings.ProfileConfig( 2035): 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
D/BtSettings.ProfileConfig( 2035): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2035): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2035): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2035): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2035): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 2035): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(755935270)( 2035): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
V/BluetoothPbapService( 2035): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 2035): state: 13
V/BluetoothPbapService( 2035): Pbap Service closeService in
,D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2035): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2035): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(755935270)( 2035): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2035): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2035): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(755935270)( 2035): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1875): [Launcher.java:5203:onStart()]onStart
V/WiFiOffLoadBroadcast( 8470): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/System.err( 3658): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/InputReader(  980): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
,W/BluetoothAdapterService( 2035): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/GeofencerStateMachine( 1729): Ignoring removeGeofence because network location is disabled.
V/BluetoothPbapService( 2035): successfully stopped pbap service
V/BluetoothPbapService( 2035): Pbap Service closeService out
,W/System.err( 3658): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,W/System.err( 3658): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3658): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3658): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3658): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3658): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3658): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3658): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3658): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3658): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3658): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,D/WiFiOffLoadBroadcast( 8470): MCCMNC not supported: null
I/art     ( 1934): Explicit concurrent mark sweep GC freed 16988(1025KB) AllocSpace objects, 5(119KB) LOS objects, 40% free, 12MB/21MB, paused 1.984ms total 108.445ms
W/BluetoothAdapterService( 2035): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(755935270)( 2035): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
,D/HeadsetService( 2035): Received stop request...Stopping profile...
D/BluetoothManagerService(  980): Message: 20
D/BluetoothManagerService(  980): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c2bbf99:true
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2035): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.android.bluetooth.pan.PanService
I/LGBluetoothHfpAdapter( 2035): [BTUI] LGBluetoothHfpAdapter cleanup
D/HeadsetStateMachine( 2035): Exit Disconnected: -1
W/BluetoothAdapterService( 2035): Not skipping com.android.bluetooth.pan.PanService
W/LGBluetoothHeadsetServiceJni( 2035): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService(755935270)( 2035): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 2035): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0ea826
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2035): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/A2dpService( 2035): Received stop request...Stopping profile...
D/KeyguardModel( 1373): createShortcutInfo...
W/BluetoothAdapterService( 2035): Not skipping com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService(755935270)( 2035): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2035): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2035): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(755935270)( 2035): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2035): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2035): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(755935270)( 2035): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_REMOVED
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2035): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 2035): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(755935270)( 2035): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2035): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2035): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2035): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(755935270)( 2035): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterState( 2035): Stopping profile services that were post enabled
I/[LGHome]EVENT( 1875): [Launcher.java:776:onResume()]onResume
D/A2dpStateMachine( 2035): Exit Disconnected: -1
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
D/BluetoothHeadset( 1748): Proxy object disconnected
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/BluetoothHeadset( 1748): Proxy object disconnected
D/BluetoothHeadset( 1748): Proxy object disconnected
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothManagerService(  980): Message: 30
,D/LGBluetoothA2dpAdapter( 2035): [BTUI] LGBluetoothA2dpAdapter cleanup
,W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
W/LGBluetoothA2dpServiceJni( 2035): Cleaning up Bluetooth Handsfree callback object
D/LGBluetoothPowerControlManager( 2035): [BTUI] terminate
D/BluetoothManagerService(  980): Message: 31
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
D/BluetoothManagerService(  980): Message: 30
D/BluetoothAdapterService( 2035): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0ea826
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/HidService( 2035): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2035): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0ea826
V/BluetoothPbapService( 2035): Pbap Service onDestroy
V/BluetoothPbapService( 2035): Pbap Service closeService in
V/BluetoothPbapService( 2035): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 2035): [BTUI] cleanup
,D/HealthService( 2035): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2035): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0ea826
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - Message: 1
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 2035): isTurningOnRadio()=false
D/BluetoothAdapterState( 2035): isTurningOffRadio()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOff()=false
I/[LGHome]LGActivityUtil( 1875): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1875): [Launcher.java:929:onResume()]onResume end
D/BluetoothAdapterService( 2035): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2035): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/LocalBluetoothProfileManager( 8470): Adding local MAP profile
D/HeadsetStateMachine( 2035): Unbinding service...
I/Activity( 1875): Activity.onPostResume() called 
D/HeadsetPhoneState( 2035): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2035): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 2035): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2035): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 2035): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2035): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 2035): [BTUI] LGBluetoothHfpAdapter cleanup
D/PanService( 2035): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2035): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0ea826
D/BtGatt.DebugUtils( 2035): handleDebugAction() action=null
D/BtGatt.GattService( 2035): Received stop request...Stopping profile...
D/BtGatt.GattService( 2035): stop()
D/BtGatt.AdvertiseManager( 2035): advertise clients cleared
D/LGBluetoothGattAdapter( 2035): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 2035): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0ea826
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/BluetoothMapService( 2035): Received stop request...Stopping profile...
D/BluetoothMapService( 2035): stop()
D/BluetoothMapEmailAppObserver( 2035): deinitObservers()
D/BluetoothMapEmailAppObserver( 2035): removeReceiver()
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/BluetoothAdapterService( 2035): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0ea826
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/BluetoothMap( 8470): Create BluetoothMap proxy object
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/BluetoothManagerService(  980): Message: 30
D/SapService( 2035): Received stop request...Stopping profile...
D/SapService( 2035): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 2035): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 2035): [BTUI] terminateSapManager
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
,D/BluetoothAdapterService( 2035): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0ea826
D/KeyguardModel( 1373): handleShortcutListChanged...
D/**BluetoothFTPService( 2035): Received stop request...Stopping profile...
D/**BluetoothFTPService( 2035): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 2035): closeFtpServerNative
D/LgeBluetoothSimManager( 1748): [BTUI] SAP_DISABLE_EVT
D/BluetoothAdapterService( 2035): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0ea826
D/**OppService( 2035): Received stop request...Stopping profile...
D/OppService( 2035): Stopping Bluetooth OppService
D/OppService( 2035): cleanup OPP Service
W/BluetoothOPPServiceJni( 2035): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 2035): Cleaning up Bluetooth OPP callback object
,D/OppService( 2035): remove callbacks and handler
D/LGBluetoothOppAdapter( 2035): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 2035): cleanup done
D/BluetoothAdapterService( 2035): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0ea826
D/BluetoothManagerService(  980): Message: 30
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - Message: 1
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 2035): isTurningOnRadio()=false
D/BluetoothAdapterState( 2035): isTurningOffRadio()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2035): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2035): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/BluetoothA2dpServiceJni( 2035): cleanupNative
I/GKI_LINUX( 2035): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2035): gki_task task_id=2 [A2DP-MEDIA] terminating
D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
I/GKI_LINUX( 2035): GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - Message: 1
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 2035): isTurningOnRadio()=false
D/BluetoothAdapterState( 2035): isTurningOffRadio()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2035): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2035): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/[LGHome]LGWallpaperInfo( 1875): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1875): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/LocalBluetoothProfileManager( 8470): LocalBluetoothProfileManager construction complete
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,W/BluetoothHidServiceJni( 2035): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 2035): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - Message: 1
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 2035): isTurningOnRadio()=false
D/BluetoothAdapterState( 2035): isTurningOffRadio()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2035): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2035): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHealthServiceJni( 2035): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2035): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 2035): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - Message: 1
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/LGBluetoothFeatureConfig( 8470):  get() - isFeatureLoaded : false
D/BluetoothAdapterState( 2035): isTurningOnRadio()=false
D/BluetoothAdapterState( 2035): isTurningOffRadio()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2035): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2035): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 2035): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2035): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - Message: 1
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 2035): isTurningOnRadio()=false
D/BluetoothAdapterState( 2035): isTurningOffRadio()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2035): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2035): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 2035): Handler(): got msg=4
D/BluetoothMapService( 2035): MAP Service closeService in
D/LGBluetoothMapAdapter( 2035): [BTUI] LGBluetoothMapAdapter cl,eanup
V/BluetoothMapService( 2035): MAP Service closeService out
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - Message: 1
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
D/BluetoothAdapterState( 2035): isTurningOnRadio()=false
D/BluetoothAdapterState( 2035): isTurningOffRadio()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2035): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2035): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 2035): cleanup()
D/BluetoothMapService( 2035): MAP Service closeService in
D/LGBluetoothMapAdapter( 2035): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2035): MAP Service closeService out
,D/BluetoothAdapterService(755935270)( 2035): handleMessage() - Message: 1
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2035): isTurningOnRadio()=false
D/BluetoothAdapterState( 2035): isTurningOffRadio()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2035): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2035): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothSAPServiceJni( 2035): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2035): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - Message: 1
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
D/BluetoothAdapterState( 2035): isTurningOnRadio()=false
D/BluetoothAdapterState( 2035): isTurningOffRadio()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2035): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2035): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2035): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
,D/BluetoothFTPService( 2035): cleanup FTP Service
V/BluetoothFTPServiceJni( 2035): closeFtpServerNative
V/BluetoothFTPServiceJni( 2035): cleanupNative
W/BluetoothFTPServiceJni( 2035): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 2035): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 2035): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 2035): cleanup done
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - Message: 1
D/BluetoothAdapterService(755935270)( 2035): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/BluetoothAdapterState( 2035): isTurningOnRadio()=false
D/BluetoothAdapterState( 2035): isTurningOffRadio()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2035): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2035): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(755935270)( 2035): onProfileServiceStateChange() - All profile services stopped...
D/BluetoothAdapterState( 2035): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2035): Setting state to 10
I/BluetoothAdapterState( 2035): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(755935270)( 2035): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  980): Message: 60
I/BluetoothAdapterState( 2035): Entering OffState
D/OppService( 2035): cleanup OPP Service
D/OppService( 2035): remove callbacks and handler
D/LGBluetoothOppAdapter( 2035): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 2035): cleanup done
D/BluetoothManagerService(  980): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  980): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
D/BluetoothInputDevice( 8470): onBluetoothStateChange: up=false
D/administrator(  980): Handling package changes for user 0
D/BluetoothPbap( 8470): onBluetoothStateChange: up=false
D/BluetoothPan( 8470): onBluetoothStateChange on: false
D/BluetoothMap( 8470): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1748): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1748): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1748): onBluetoothStateChange: up=false
D/BluetoothHeadset(  980): onBluetoothStateChange: up=false
D/BluetoothA2dp(  980): onBluetoothStateChange: up=false
D/BluetoothAdapterService(755935270)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d9867ac
D/BluetoothManagerService(  980): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  980): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/KeyguardModel( 1373): handleShortcutListChanged...
I/SystemUI[Framework](  980): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  980): Call!!!getLGSystemUiVisibility. =0x0
,D/StatusBarManagerServiceEx(  980): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  980): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  980): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@ece7e4c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  980): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  980): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
D/BluetoothManagerService(  980): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService(  980): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService(  980): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3fd36547 mBinding = false
D/LGBluetoothUserBindClient( 8470): [BTUI] initUserBindClient
D/BluetoothManagerService(  980): Sending unbind request.
W/PhoneWindowManagerEx(  980): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  980): setLGSystemUiVisibility(0x0)
D/BluetoothManagerService(  980): Bluetooth State Change Intent: 13 -> 10
D/StatusBarManagerServiceEx(  980): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  980): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@ece7e4c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  980): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/BluetoothAdapterService(755935270)( 2035): onUnbind() - calling cleanup
D/LGBluetoothAPIService( 1800): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService(755935270)( 2035): cleanup()
D/BluetoothAdapter( 1373): 483520186: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1373): 483520186: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothAPIService( 1800): Message: 2
D/LGBluetoothAPIService( 1800): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1f4e9e0d mBinding = false
D/LGBluetoothAPIService( 1800): Sending unbind request.
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1373): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
D/InputDispatcher(  980): Focus entered window: Window{1f8aa1b5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ContextImpl( 8470): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/BluetoothAdapterService(755935270)( 2035): cleanup() - Cleaning up adapter native
I/bt-btif ( 2035): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 2035): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/bt-btif ( 2035): HAL bt_hal_cbacks->thread_evt_cb
I/GKI_LINUX( 2035): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2035): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 2035): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2035): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2035): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2035): GKI_exit_task 2 done
I/GKI_LINUX( 2035): GKI_exit_task 1 done
I/GKI_LINUX( 2035): GKI_exit_task 0 done
I/BluetoothServiceJni( 2035): cleanupNative: return from cleanup
W/LGBluetoothServiceJni( 2035): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 2035): [BTUI] unregister observer for LG device name DB
D/BluetoothAdapterService(755935270)( 2035): cleanup() - Bluetooth process exited normally.
D/BluetoothAdapterService(755935270)( 2035): cleanup() done
I/art     ( 2035): System.exit called, status: 0
I/AndroidRuntime( 2035): VM exiting with result code 0, cleanup skipped.
,D/DockEventReceiver( 8470): finishStartingService: stopping service
D/BluetoothAdapter( 1729): 289322867: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1729): 289322867: getState() :  mService = null. Returning STATE_OFF
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,V/AudioFlinger(  281): 2035 died, releasing its sessions
V/AudioFlinger(  281):  pid 1748 @ 0
V/AudioFlinger(  281):  pid 3142 @ 1
V/AudioFlinger(  281):  pid 3142 @ 2
D/FMFRW_FmProxy( 1800): Fm Proxy object disconnected
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
,I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1875): [setNavigationBarColor] color=0x 0
D/LGBluetoothFeatureConfig( 8470): isPrivacyLogsEnabled : true
,E/LGBluetoothEventManager( 8470): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 8470): [BTUI] clear device connection state
I/ActivityManager(  980): Process com.android.bluetooth (pid 2035) has died
,W/ActivityManager(  980): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 1000ms
W/ActivityManager(  980): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
D/LGBluetoothAuthorization( 8470): [BTUI] cancel All Notification
I/NotificationManager( 8470): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 8470): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 8470): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 8470): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 8470): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 8470): com.android.settings: cancel(-1000041) by com.android.settings
I/ActivityManager(  980): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8519 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BluetoothPermissionRequest( 8470): onReceive
D/LGBluetoothAuthorization( 8470): [BTUI] cancel All Notification
I/NotificationManager( 8470): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 8470): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 8470): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 8470): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 8470): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 8470): com.android.settings: cancel(-1000041) by com.android.settings
,I/art     (  980): Explicit concurrent mark sweep GC freed 15728(1152KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 13.380ms total 439.523ms
,W/InputMethodManagerService(  980): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  980): Got RemoteException sending setActive(false) notification to pid 5771 uid 10316
I/ActivityManager(  980): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=8537 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
,I/ActivityManager(  980): Killing 8018:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  980): failed to open /acct/uid_10023/pid_8018/cgroup.procs: No such file or directory
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/AndroidRuntime( 8449): Shutting down VM
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/Timeline(  980): Timeline: Activity_windows_visible id: ActivityRecord{d7004ce u0 com.lge.launcher2/.Launcher t221} time:311916
,I/NotificationService(  980): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  980): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  980): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/TaskPersister(  980): removeObsoleteFile: deleting file=222_task.xml
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,W/ResourcesManager( 8537): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
W/ResourcesManager( 8537): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8537): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 8537): Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
,I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BluetoothAdapterApp( 8537): Loading JNI Library
,W/IInputConnectionWrapper( 1875): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1619): Unable to connect to the editor to retrieve text... will retry later
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
E/BluetoothServiceJni( 8537): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1875): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/BluetoothAdapterApp( 8537): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@38107049 Instance Count = 1
D/BluetoothAdapterApp( 8537): onCreate
,I/LGBluetoothServiceJni( 8537): classInitNative: succeeds
D/BtSettings.ProfileConfig( 8537): [BTUI] HeadsetServiceis supported
,D/BtSettings.ProfileConfig( 8537): Adding HeadsetService
D/BtSettings.ProfileConfig( 8537): [BTUI] A2dpServiceis supported
D/BtSettings.ProfileConfig( 8537): Adding A2dpService
D/BtSettings.ProfileConfig( 8537): [BTUI] HidServiceis supported
D/BtSettings.ProfileConfig( 8537): Adding HidService
D/BtSettings.ProfileConfig( 8537): [BTUI] HealthServiceis supported
D/BtSettings.ProfileConfig( 8537): Adding HealthService
D/LGBluetoothFeatureConfig( 8537): isSupportPan() :  mTargetOp=OPEN
D/LGBluetoothFeatureConfig( 8537): isSupportPan() :  mTargetOp=OPEN
D/BtSettings.ProfileConfig( 8537): [BTUI] PanServiceis supported
D/BtSettings.ProfileConfig( 8537): Adding PanService
D/BtSettings.ProfileConfig( 8537): [BTUI] GattServiceis supported
D/BtSettings.ProfileConfig( 8537): Adding GattService
D/BtSettings.ProfileConfig( 8537): [BTUI] BluetoothMapServiceis supported
D/BtSettings.ProfileConfig( 8537): Adding BluetoothMapService
V/LGBluetoothServiceAdapter( 8537): [BTUI] region:EU country:EU
D/BtSettings.ProfileConfig( 8537): [BTUI] SapServiceis supported
D/BtSettings.ProfileConfig( 8537): Adding SapService
D/BtSettings.ProfileConfig( 8537): [BTUI] FTPServiceis supported
D/BtSettings.ProfileConfig( 8537): Adding FTPService
E/BtSettings.ProfileConfig( 8537): [BTUI] HeadsetClientServiceis NOT supported
D/BtSettings.ProfileConfig( 8537): [BTUI] OppServiceis supported
D/BtSettings.ProfileConfig( 8537): Adding OppService
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
D/BtSettings.ProfileConfig( 8537): deviceMode from shared preference   -1
D/BtSettings.ProfileConfig( 8537): checkAndAdjustDeviceModeConfiguration deviceMode1
D/BtSettings.ProfileConfig( 8537): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
D/BtSettings.ProfileConfig( 8537): Unable to read settings
D/BtSettings.ProfileConfig( 8537): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 8537): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 8537): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 8537): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 8537): 	at com.broadcom.bt.service.ProfileConfig.checkAndAdjustDeviceModeConfiguration(ProfileConfig.java:400)
D/BtSettings.ProfileConfig( 8537): 	at com.broadcom.bt.service.ProfileConfig.init(ProfileConfig.java:550)
D/BtSettings.ProfileConfig( 8537): 	at com.lge.bluetooth.adapter.LGBluetoothProfileConfigAdapter.init(LGBluetoothProfileConfigAdapter.java:30)
D/BtSettings.ProfileConfig( 8537): 	at com.android.bluetooth.btservice.AdapterApp.onCreate(AdapterApp.java:67)
D/BtSettings.ProfileConfig( 8537): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
D/BtSettings.ProfileConfig( 8537): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
D/BtSettings.ProfileConfig( 8537): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
D/BtSettings.ProfileConfig( 8537): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
D/BtSettings.ProfileConfig( 8537): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 8537): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 8537): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
D/BtSettings.ProfileConfig( 8537): 	at java.lang.reflect.Method.invoke(Native Method)
D/BtSettings.ProfileConfig( 8537): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BtSettings.ProfileConfig( 8537): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
D/BtSettings.ProfileConfig( 8537): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/BtSettings.ProfileConfig( 8537): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 8537): getProfileSaveSetting: com.android.bluetooth.hid.HidService
I/PCSuite ( 8519): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/BtSettings.ProfileConfig( 8537): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 8537): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 8537): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 8537): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 8537): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 8537): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 8537): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/LGBluetoothOppAdapter( 8537): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothOppReceiver( 8537): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,D/BluetoothOppNotification( 8537): [BTUI] cancel opp incoming file confirm notification
D/PCSuite ( 8519): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 8519): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/NotificationManager( 8537): com.android.bluetooth: cancel(-1) by com.android.bluetooth
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
D/BluetoothOppNotification( 8537): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 8537): com.android.bluetooth: cancel(-1) by com.android.bluetooth
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/ActivityManager(  980): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8561 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager(  980): Killing 8040:com.android.contacts/u0a18 (adj 15): empty #11
I/FmServiceJni( 8537): classInitNative: succeeds
D/FmService( 8537): FmReceiverServiceStub createdcom.broadcom.fm.fmreceiver.FmService$FmReceiverServiceStub@30be277cservicecom.broadcom.fm.fmreceiver.FmService@36e6c805
D/FmNativehandler( 8537): start
D/BluetoothRadioManager( 8537): [BTUI] getRadioManager()
,D/BluetoothRadioManager( 8537): [BTUI] BluetoothRadioManager()
D/BluetoothManagerService(  980): Message: 20
D/BluetoothManagerService(  980): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@273b27e8:true
,D/BluetoothRadioManager( 8537): doBind: com.broadcom.bt.service.radiomanager.IBluetoothRadioManager
,W/libprocessgroup(  980): failed to open /acct/uid_10018/pid_8040/cgroup.procs: No such file or directory
V/FmService( 8537): FM Service  onCreate
D/FmService( 8537): Binding service...
D/FMFRW_FmProxy( 1800): Fm proxy onServiceConnected() name = ComponentInfo{com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService}, service = android.os.BinderProxy@13af71c2
D/LGBluetoothUserBindClient( 8470): [BTUI] onServiceConnected
W/ResourcesManager(  980): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourcesManager( 8561): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothAdapterService( 8537): Set JNI Library before classInit
,D/BluetoothAdapterService(433937511)( 8537): AdapterService() - REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterService(433937511)( 8537): onCreate()
D/BluetoothAdapterState( 8537): make
E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/bluedroid( 8537): init
I/BluetoothAdapterState( 8537): Entering OffState
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/bte_conf( 8537): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 8537): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 8537): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 8537): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 8537): [BTUI] lge_load_bluetooth_address
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume

```
