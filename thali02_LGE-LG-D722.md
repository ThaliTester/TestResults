#### Test 50388019c82294c_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
I/ActivityManager(  848): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=3722 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  848): Killing 3479:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_3479/cgroup.procs: No such file or directory
--------- beginning of main
I/MusicWidget( 2607): pushUpdate()_4x1
I/MusicWidget( 2607): performViewUpdater handleMessage() msg.what::1
I/MusicWidget( 2607): beingMusicWidget_4x2() result::false
D/AirTest ( 3722): Set airtest_enable to false
I/ActivityManager(  848): Killing 3502:com.lge.clock/u0a10 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1872): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1872): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
W/libprocessgroup(  848): failed to open /acct/uid_10010/pid_3502/cgroup.procs: No such file or directory
V/LGSC    ( 2723): [104] 401
I/ActivityManager(  848): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=3746 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/TARGETVALIDLATION_RECEIVER( 3746): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
D/TARGETVALIDLATION_RECEIVER( 3746): updateFlag = new File(TARGET_FLAG_PATH)
D/TARGETVALIDLATION_RECEIVER( 3746): Do Not display result dialog. it is not used Update Tool!!
I/ActivityManager(  848): Killing 3530:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_10011/pid_3530/cgroup.procs: No such file or directory
V/LGSC    ( 1746): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
W/ContextImpl( 2942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2663 
E/AtFwd AutoBoot( 2942): AtFwd Auto Boot Started Successfully
I/ActivityManager(  848): Killing 3547:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_10011/pid_3547/cgroup.procs: No such file or directory
I/GoogleHttpClient( 2002): GMS http client unavailable, use old client
I/ActivityManager(  848): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=3768 uid=10062 gids={50062, 9997} abi=armeabi-v7a
I/ActivityManager(  848): Waited long enough for: ServiceRecord{4b65ac5 u0 com.lge.sizechangable.weather/.service.WeatherService}
I/InsertAccount( 3768): The account already exists
I/ActivityManager(  848): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=3786 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  848): Killing 2874:com.android.defcontainer/u0a4 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_10004/pid_2874/cgroup.procs: No such file or directory
W/ResourcesManager( 3786): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3786): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/InsertAccount( 3768): The account info in contact DB already exists
I/[SMS_AD]( 3786): Intent action: android.intent.action.BOOT_COMPLETED
I/[SMS_AD]( 3786): Intent action: android.intent.action.BOOT_COMPLETED
I/ActivityManager(  848): Killing 3447:com.android.providers.calendar/u0a14 (adj 9): empty #11
I/InsertAccount( 3768): The account info in calendar DB already exists
W/libprocessgroup(  848): failed to open /acct/uid_10014/pid_3447/cgroup.procs: No such file or directory
I/Process ( 3768): Sending signal. PID: 3768 SIG: 9
D/WeatherAncestor( 2679): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 18:42:41
D/UpdateThreadPoolManager( 2679): 2 : This is isUpdating : false
I/ActivityManager(  848): Process com.lge.defaultaccount (pid 3768) has died
D/Weather_cast( 2679): 2 : set auto-update time : 11/17 21:42
D/WeatherAncestor( 2679): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 18:42:41
D/WeatherService( 2679): 2 : onStartCommand, intent!=null, action: android.intent.action.BOOT_COMPLETED
I/ActivityManager(  848): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=3806 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  848): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2679): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2679): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2679): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/LockScreenSettings( 3806): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
I/LockScreenSettings( 3806): Received Broadcast : android.intent.action.BOOT_COMPLETED
I/ActivityManager(  848): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=3824 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BootCompleteReceiver( 3824): hasclipTray = true
W/ContextImpl( 3824): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
I/ActivityManager(  848): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=3843 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 375us total 31.816ms
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 21.854ms
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.579ms
I/ActivityManager(  848): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3869 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  848): Killing 3598:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_3598/cgroup.procs: No such file or directory
D/AndroidRuntime( 3841): 
D/AndroidRuntime( 3841): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3841): CheckJNI is OFF
I/art     (  848): Explicit concurrent mark sweep GC freed 13794(639KB) AllocSpace objects, 2(221KB) LOS objects, 33% free, 22MB/33MB, paused 2.338ms total 138.624ms
V/AppCleanupService( 3843): registerAlarm
D/AppCleanupService( 3843): noticeInterval = 2592000000
D/AppCleanupService( 3843): notiDateStr = 2015-11-20 22:23:56
D/AppCleanupService( 3843): noticeStart = 2015-11-20 22:23:56
D/AppCleanupService( 3843): noticeStart = 1448054636000
E/UpdateRequestReceiver( 3869): ignoring update request
D/AppUsageDbAdapter( 3843): initPreloadedAppToTheDB() : row count = 86
E/UpdateRequestReceiver( 3869): ignoring update request
E/UpdateRequestReceiver( 3869): ignoring update request
E/UpdateRequestReceiver( 3869): ignoring update request
E/UpdateRequestReceiver( 3869): ignoring update request
E/UpdateRequestReceiver( 3869): ignoring update request
I/ActivityManager(  848): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=3911 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  848): Killing 3626:com.android.managedprovisioning/u0a111 (adj 15): empty #11
D/sensors_hal_Time(  848): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  848): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  848): tsOffsetIs: Apps: 52665197796; DSPS: 1824030; Offset : -3013642285
W/libprocessgroup(  848): failed to open /acct/uid_10111/pid_3626/cgroup.procs: No such file or directory
D/AndroidRuntime( 3841): Calling main entry com.android.commands.am.Am
D/SIMObserver( 3911): action:android.intent.action.BOOT_COMPLETED
D/SIMObserver( 3911): handle ACTION_BOOT_COMPLETED
I/ActivityManager(  848): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  848): setTaskToReturnTo : TaskRecord{1c8d9bbe #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  848): setTaskToReturnTo : TaskRecord{1c8d9bbe #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  848): AppWindowTokenEx init.. 
D/ContextHelper(  848): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/[LGHome]EVENT( 1872): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  848): Focus left window: Window{311e5400 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/ActivityManager(  848): Killing 3652:com.lge.voicerecorder/u0a34 (adj 15): empty #11
D/AndroidRuntime( 3841): Shutting down VM
D/SplitWindow(  848): check instance of lgWin Window{19112a58 u0 Starting com.example.hello}
W/libprocessgroup(  848): failed to open /acct/uid_10034/pid_3652/cgroup.procs: No such file or directory
I/ActivityManager(  848): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3931 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1872): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
E/QcrilMsgTunnelAutoboot( 2289): Received Intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot (has extras) } canStartService = false
D/PhoneInterfaceManager( 1746): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/HotwordDetector( 1938): Closing mic
D/PhoneInterfaceManager( 1746): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/MicrophoneInputStream( 1938): mic_close com.google.android.apps.gsa.speech.audio.u@3f9d5ab3
V/AudioRecord( 1938): stop()
D/AudioRecord( 1938): AudioRecord->stop()
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
V/AudioFlinger(  280): Record stopped OK
V/AudioPolicyManager(  280): stopInput() input 17
V/AudioPolicyService(  280): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  280): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  280): ThreadBase::setParameters() routing=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb4393000
D/audio_hw_primary(  280): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
I/[LGHome]EVENT( 1872): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  848): Starting window displayed
I/SystemUI[Framework](  848): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
V/audio_hw_primary(  280): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  280): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): disable_audio_route: reset and update mixer path: audio-record
W/PhoneWindowManagerEx(  848): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  848): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  848): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  848): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@30d59edb,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  848): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/audio_hw_primary(  280): disable_audio_route: exit
E/audio_hw_primary(  280): disable_snd_device: enter 144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): disable_snd_device: snd_device(144: lg-vr-handset-mic)
,D/BarTransitions( 1372): draw background and invalidate : color = 8000000
V/audio_hw_primary(  280): stop_input_stream: exit: status(0)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  280): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  280): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  280): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyService(  280): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  280): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  280): setParameters(): io 17, keyvalue hotword_active=0, calling pid 280
V/AudioFlinger(  280): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb4393000
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
D/BarTransitions( 1372): draw background and invalidate : color = b0b0b0b
V/AudioRecord( 1938): stop()
V/AudioRecord( 1938): stop()
V/AudioRecord( 1938): stop()
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
V/AudioPolicyManager(  280): releaseInput() 17
V/AudioPolicyManager(  280): closeInput(17)
V/AudioFlinger(  280): closeInput() 17
V/AudioSystem(  280): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  848): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): ThreadBase::exit
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioSystem( 1938): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2696): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3133): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1746): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): RecordThread 0xb4393000 exiting
V/AudioFlinger(  280): releasing 16 from 1938 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
D/audio_hw_primary(  280): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  280): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): releaseInput() exit
V/AudioFlinger(  280): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  280): removeClient_l() pid 1938, calling pid 280
I/HotwordRecognitionRnr( 1938): Hotword detection finished
I/HotwordRecognitionRnr( 1938): Stopping hotword detection.
D/ContextHelper( 3931): convertTheme. context->name=com.example.hello themeResourceId=16973833
V/AlarmManager(  848): ELAPSED_WAKEUP set : Alarm{322eec70 type 2 when 53129 com.android.providers.calendar} when 53129
I/WebViewFactory( 3931): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3931): Time to load native libraries: 2 ms (timestamps 3276-3278)
I/LibraryLoader( 3931): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3931): Binding Chromium to main looper Looper (main, tid 1) {23fbbfbb}
I/LibraryLoader( 3931): Expected native library version number "",actual native library version number ""
I/chromium( 3931): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3931): Initializing chromium process, singleProcess=true
W/art     ( 3931): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3931): ApplicationContext is null in ApplicationStatus
D/FileApkUtils( 2265): Spent 62ms computing apk sha1.
D/FileApkUtils( 2265): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 2265): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
W/chromium( 3931): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3931): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/DexOptUtils( 2265): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 2265): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
E/libEGL  ( 3931): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3931): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3931): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3931): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3931): Build Date: 03/02/15 Mon
I/Adreno-EGL( 3931): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 3931): Remote Branch: 
I/Adreno-EGL( 3931): Local Patches: 
I/Adreno-EGL( 3931): Reconstruct Branch: 
D/GmsModuleFndr( 2265): Beginning GMS chimera module scan
D/GmsModuleFndr( 2265): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 2265): Beginning module configuration check
D/ChimeraCfgMgr( 2265): Module APKs unchanged, check complete
V/AudioPolicyService(  280): registerClient() client 0xb3827da0, uid 10030
D/BluetoothManagerService(  848): Message: 20
D/BluetoothManagerService(  848): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b4d0634:true
D/BluetoothAdapter( 3931): 741269124: getState() :  mService = null. Returning STATE_OFF
D/GCM     ( 2265): COMPAT: Multi user not supported
,D/GCM     ( 2002): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
I/GCoreUlr( 2265): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1728): DispatchingService.onCreate()
,I/CheckinService( 2265): Checkin interval check for package: unspecified last checkin: 1447767540798 min interval config: 0 actual interval: 14622610
I/CheckinService( 2265): Disabling old GoogleServicesFramework version
,D/SystemUpdateService( 2265): onCreate
,D/SystemUpdateService( 2265): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/GLSActivity( 2002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AuthZen ( 2265): Handling intent: android.intent.action.BOOT_COMPLETED
,V/GLSActivity( 2002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AuthZenEventHandler( 2265): Handling event: android.intent.action.BOOT_COMPLETED
,W/art     ( 3931): Attempt to remove local handle scope entry from IRT, ignoring
I/GCoreUlr( 1728): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
W/AwContents( 3931): onDetachedFromWindow called when already detached. Ignoring
,I/SystemUpdateService( 2265): cancelUpdate (empty URL)
I/SystemUpdateService( 2265): active receiver: disabled
D/SystemWebViewEngine( 3931): CordovaWebView is running on device made by: LGE
,W/art     ( 3931): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3931): Attempt to remove local handle scope entry from IRT, ignoring
,D/ChimeraCfgMgr( 2265): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/NotificationManager( 2265): com.google.android.gms: cancel(2130838130) by com.google.android.gms
,I/NotificationManager( 2265): com.google.android.gms: cancel(2130838131) by com.google.android.gms
,I/CheckinService( 2265): Checking schedule, now: 1447782163707 next: 1448294789754
,I/CheckinService( 2265): active receiver: disabled
D/ChimeraCfgMgr( 2265): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Activity( 3931): Activity.onPostResume() called 
D/SystemUpdateService( 2265): onDestroy
,I/NotificationManager( 2265): com.google.android.gms: cancel(10436) by com.google.android.gms
D/OpenGLRenderer( 3931): Render dirty regions requested: true
I/OpenGLRenderer( 3931): Initialized EGL, version 1.4
,W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 2265): location=null
D/OpenGLRenderer( 3931): Enabling debug mode 0
D/Atlas   ( 3931): Validating map...
,D/SplitWindow(  848): check instance of lgWin Window{232d39a9 u0 com.example.hello/com.example.hello.MainActivity}
W/chromium( 3931): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/art     ( 2002): Explicit concurrent mark sweep GC freed 6080(355KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 11MB/18MB, paused 1.652ms total 107.019ms
,W/BaseAppContext( 2265): Using Auth Proxy for data requests.
D/InputDispatcher(  848): Focus entered window: Window{232d39a9 u0 com.example.hello/com.example.hello.MainActivity}
,W/Auth    ( 2002): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
I/EventLogService( 2265): Aggregate from 1447780234838 (log), 1447780234838 (data)
,V/GLSActivity( 2002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1728): No location to return for getLastLocation()
,W/FusedLocationProvider( 2265): location=null
W/Kids    ( 2265): [AbstractKidsOperation] Invalid device state 3
,I/Kids    ( 2265): [KidAccountFixer] No network connection
W/InputMethodManagerService(  848): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  848): Displayed com.example.hello/.MainActivity: +1s307ms
I/Timeline(  848): Timeline: Activity_windows_visible id: ActivityRecord{b3641f u0 com.example.hello/.MainActivity t217} time:54174
,I/Timeline( 3931): Timeline: Activity_idle id: android.os.BinderProxy@7c7d987 time:54188
,I/AuthZen ( 2265): Fetching signing key...
V/GLSActivity( 2002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 2265): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
I/AuthZen ( 2265): Signing key fetched successfully!
I/GCoreUlr( 1728): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/BaseAppContext( 2265): Using Auth Proxy for data requests.
,I/GCoreUlr( 1728): Unbound from all location providers
D/PersistentNotificationBroadcastReceiver( 2002): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
D/a       ( 2265): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 2265): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2265): Clearing transaction cache
,I/ActivityManager(  848): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4033 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/BindingManager( 3931): Cannot call determinedVisibility() - never saw a connection for the pid: 3931
,I/GCoreUlr( 1728): DispatchingService.onDestroy()
I/GCoreUlr( 1728): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1728): Unbound from all location providers
I/chromium( 3931): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,W/ResourcesManager( 4033): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/JsMessageQueue( 3931): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 3931): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/Babel_SMS( 4033): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4033): MmsConfig.loadMmsSettings
I/Babel_SMS( 4033): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/Babel_SMS( 4033): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4033): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4033): MmsConfig.loadFromResources
E/Babel_SMS( 4033): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4033): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 4033): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4033): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4033): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 4033): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4033): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4033): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4033): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4033): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4033): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4033): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4033): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4033): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4033): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4033): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4033): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4033): found sensor: Motion Accel, handle=46
D/jxcore_app_log( 3931): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618818048
D/JX-Cordova( 3931): jxcore cordova android initializing
,I/ActivityManager(  848): Waited long enough for: ServiceRecord{24c5b15f u0 com.google.android.gms/.gcm.GcmService}
W/art     ( 4033): Suspending all threads took: 15.797ms
,I/art     ( 4033): CheckpointMarkThreadRoots callback created = 0xb042d8d0
,W/Settings( 4033): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 4033): startup - clean
,W/jxcore-log( 3931): Initializing JXcore engine
W/jxcore-log( 3931): JXcore engine is ready
I/art     ( 4033): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,W/jxcore-log( 3931): Starting JXcore engine
I/Babel   ( 4033): deleted: false for 0
W/m.example.hello( 3931): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5698]" dev="sockfs" ino=5698 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3931): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3931): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6818]" dev="sockfs" ino=6818 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3931): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3931): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3931): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[21522]" dev="sockfs" ino=21522 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/AudioCapabilities( 4033): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4033): Unsupported mime audio/adpcm
W/AudioCapabilities( 4033): Unsupported mime audio/g726
W/AudioCapabilities( 4033): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4033): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4033): Unsupported mime video/mjpg
,W/VideoCapabilities( 4033): Unsupported mime video/theora
,W/AudioCapabilities( 4033): Unsupported mime audio/evrc
,W/AudioCapabilities( 4033): Unsupported mime audio/qcelp
W/VideoCapabilities( 4033): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4033): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4033): Unsupported mime audio/qcelp
W/AudioCapabilities( 4033): Unsupported mime audio/evrc
W/VideoCapabilities( 4033): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 4033): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4033): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4033): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4033): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4033): Unrecognized profile 2130706433 for video/avc
W/jxcore-log( 3931): Platform android
W/jxcore-log( 3931): 
W/jxcore-log( 3931): Process ARCH arm
W/jxcore-log( 3931): 
,I/vclib   ( 4033): onServiceConnected
,W/Babel   ( 4033): Attempted to change video mute state without an active call.
I/jxcore-log( 3931): JXcore Cordova bridge is ready!
I/jxcore-log( 3931): 
,W/jxcore-log( 3931): JXcore engine is started
I/NotificationManager( 4033): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ActivityManager(  848): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4065 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/jxcore-log( 3931): >> LGE-LG-D722
E/jxcore-log( 3931): 
,I/jxcore-log( 3931): Total memory 906309632
I/jxcore-log( 3931): 
I/jxcore-log( 3931): Free memory 33603584
I/jxcore-log( 3931): 
I/jxcore-log( 3931): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3931): 
I/jxcore-log( 3931): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3931): 
I/jxcore-log( 3931): userPath [ 'www' ]
I/jxcore-log( 3931): 
I/jxcore-log( 3931): Size 720 1196
I/jxcore-log( 3931): 
,I/jxcore-log( 3931): Screen Brightness 255
I/jxcore-log( 3931): 
E/jxcore-log( 3931): Dummy Error Log.
E/jxcore-log( 3931): 
,W/ResourcesManager( 4065): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4065): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4065): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 4065): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4065): Installed default security provider GmsCore_OpenSSL
I/art     (  848): Explicit concurrent mark sweep GC freed 17479(905KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 22MB/34MB, paused 3.159ms total 164.721ms
,W/CursorWrapperInner( 3701): Cursor finalized without prior close()
,W/ActivityManager(  848): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,V/AlarmManager(  848): RTC_WAKEUP set : Alarm{7b309b7 type 0 when 1447695745104 com.android.providers.contacts} when 1447695745104
V/AlarmManager(  848): ELAPSED_WAKEUP set : Alarm{ebb1524 type 2 when 55158 com.google.android.talk} when 55158
V/AlarmManager(  848): ELAPSED_WAKEUP set : Alarm{3f1288d type 2 when 55982 com.google.android.gms} when 55982
I/jxcore-log( 3931): getBuffer is called!!!!
I/jxcore-log( 3931): 
,E/YouTube MDX( 4065): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/art     ( 4065): CheckpointMarkThreadRoots callback created = 0xb042dc00
,D/libc-netbsd( 4065): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4065): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 4065): CheckpointMarkThreadRoots callback created = 0xb4958de0
W/ResourcesManager( 4065): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4065): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4065): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/dex2oat ( 4114): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1745831057.jar --oat-fd=34 --oat-location=/data/data/com.google.android.youtube/cache/ads1745831057.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4114): dex2oat took 108.628ms (threads: 4)
,I/NotificationManager( 4065): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4065): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4065): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4065): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4065): Found 10006
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
,W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4065): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  848): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4159 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/NotificationManager( 4065): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,I/ActivityManager(  848): Killing 3680:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  848): failed to open /acct/uid_10051/pid_3680/cgroup.procs: No such file or directory
W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4159): getAccountsCursor
,V/GLSActivity( 2002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4159): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 4159): Error finding the version of the Email provider.....
E/Gmail   ( 4159): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4159): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4159): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4159): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4159): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4159): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4159): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4159): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 4159): We do not support migrating this version of the Email provider.
I/Gmail   ( 4159): getAccountsCursor
V/GLSActivity( 2002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  848): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4218 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  848): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 2002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4159): Observing account changes for notifications
,W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4159): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3b563a02 that was originally bound here
E/ActivityThread( 4159): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3b563a02 that was originally bound here
E/ActivityThread( 4159): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4159): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4159): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4159): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4159): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4159): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4159): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4159): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4159): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4159): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4159): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4159): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4159): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4159): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4159): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4159): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  848): Unbind failed: could not find connection for android.os.BinderProxy@2c58ec6f
V/[BNRBootReceiver]( 4218): boot receiver action = android.intent.action.BOOT_COMPLETED
,V/[BNRBootReceiver]( 4218): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4218): End of BootComplted IF
V/[BNRBootReceiver]( 4218): Boot Receiver Return
V/[BNRBootCompletedThread]( 4218): run
W/linker  ( 4238): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/bnrd    ( 4238): BNRD > wait starting [4238-3058102400] <
E/bnrd    ( 4238): /data/data/.bnr_fifo_req
V/[BNRBootCompletedThread]( 4218): End of BNRProcess
,I/Gmail   ( 4159): notifyAccountChanged
V/[BNRBootCompletedThread]( 4218): End of BNRViaWifiProcess
I/Gmail   ( 4159): getAccountsCursor
V/[BNRBootCompletedThread]( 4218): End of SpriteProcess
V/[BNRBootCompletedThread]( 4218): exit
I/Gmail   ( 4159): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  848): Process com.lge.cloudhub (pid 3701) has died
,I/Gmail   ( 4159): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4159): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4159): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  848): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4247 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 2002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  848): Process com.lge.hiddenmenu (pid 3786) has died
,I/Gmail   ( 4159): getAccountsCursor
,V/GLSActivity( 2002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4247): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 4247): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 4247): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4247): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 4247): com.android.vending: cancel(-1050172287) by com.android.vending
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/Volley  ( 4247): [431] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4247): [438] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 4247): Skipping gmscore version check
V/DownloadManager( 2752): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2752): created cursor android.database.sqlite.SQLiteCursor@2d9bb79b on behalf of 4247
,I/ActivityManager(  848): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4309 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  848): Killing 3722:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
,W/libprocessgroup(  848): failed to open /acct/uid_10054/pid_3722/cgroup.procs: No such file or directory
D/Finsky  ( 4247): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4247): [1] 2.run: Finished loading 1 libraries.
I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
D/Finsky  ( 4247): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/ResourcesManager( 4309): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/Finsky  ( 4247): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/App     ( 4309): [App][onCreate()] 4.40.21
,I/ActivityManager(  848): Killing 3746:com.lge.lgfota.permission/1000 (adj 15): empty #11
,D/AccountManager( 4309): setSyncFrequency
W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_3746/cgroup.procs: No such file or directory
,W/ContextImpl( 4309): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
,D/WeatherAncestor( 2679): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:42:48
D/UpdateThreadPoolManager( 2679): 2 : This is isUpdating : false
D/WeatherAncestor( 2679): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:42:48
D/ReminderService( 4309): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
D/WeatherService( 2679): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,W/ActivityManager(  848): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2679): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2679): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2679): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2679): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2679): 2 : This is isUpdating : false
D/WeatherService( 2679): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2679): 2 : buildUpdate, appWidgetId: 2
D/LocationReminderManager( 4309): [connect] Request location client connection.
D/WeatherTheme( 2679): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2679): 2 : Fixed theme : optimus
,D/WeatherReflect( 2679): 2 : Map key string is -2
D/lim     ( 2679): 2 : time = 18:42
I/WeatherReflect( 2679): Model Name : LG-D722
D/WeatherTheme( 2679): 2 : exactly same view!
,D/WeatherTheme( 2679): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ActivityManager(  848): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2679): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2679): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2679): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/UserPresentBroadcastReceiver( 1728): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,W/ContextImpl( 4309): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
,I/ActivityManager(  848): Waited long enough for: ServiceRecord{3f82c2a9 u0 com.android.mms/.service.SwitchedService}
,I/ActivityManager(  848): Killing 3806:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
D/LocationReminderManager( 4309): location cilent is connected.
D/LocationReminderManager( 4309): [removeAllReminders]
,W/libprocessgroup(  848): failed to open /acct/uid_10069/pid_3806/cgroup.procs: No such file or directory
,W/GeofencerStateMachine( 1728): Ignoring removeGeofence because network location is disabled.
,D/LocationReminderManager( 4309): [removeAllReminders] statusCode : 1000
D/LocationReminderManager( 4309): [removeAllReminders] Failed to remove reminder
I/ActivityManager(  848): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4338 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/GCoreFlp( 1728): No location to return for getLastLocation()
,W/GCoreFlp( 1728): No location to return for getLastLocation()
,D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 4338): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
,V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4338): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/ActivityManager(  848): Killing 3824:com.lge.springcleaning/1000 (adj 15): empty #11
,W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_3824/cgroup.procs: No such file or directory
,V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
,I/ActivityManager(  848): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4367 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 21.310ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.941ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.263ms
,W/ResourcesManager( 4367): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  848): Message: 20
D/BluetoothManagerService(  848): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b0f77e0:true
,D/BluetoothAdapter( 4367): 916233367: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4367): 916233367: getState() :  mService = null. Returning STATE_OFF
I/art     (  848): Explicit concurrent mark sweep GC freed 19711(926KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.007ms total 157.908ms
,I/ActivityManager(  848): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4389 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 4367): Create singleton instance
,D/UEI.SmartControl( 4389): Quickset Services start...
I/UEI.SmartControl( 4389): Manufacture = LGE
,D/UEI.SmartControl( 4389): File observer start...
E/UEI.SmartControl( 4389): IR Port is disabled: false
D/UEI.SmartControl( 4389): Starting file observer...
D/UEI.SmartControl( 4389): Extracting JNI libs...
D/UEI.SmartControl( 4389): --- this system supports 32-bit or 64-bit only
I/AudioManager( 4367): getMode name:com.lge.qremote
,D/UEI.SmartControl( 4389): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4389): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4389): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
,I/AudioManager( 4367): getMode name:com.lge.qremote
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
I/UEI.SmartControl( 4389): --- Selecting new region: 2
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
I/UEI.SmartControl( 4389): -- Running on KitKat(19) and above! JNI will be used.
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
D/UEI.SmartControl( 4389): Platform has CIR...
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
D/UEI.SmartControl( 4389): NO CIR support, need to check package...
I/UEI.SmartControl( 4389): Model: LG-D722 uses JNI
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
D/UEI.SmartControl( 4389): QS Service created
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3133): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3133): ANY_DATA_STATE event received: DISCONNECTED
,E/UEI.SmartControl( 4389): QS start get config
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4338): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4338): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/AudioManager( 4367): getMode name:com.lge.qremote
D/LGDMClient( 4338): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
D/LGDMClient( 4338): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,D/WearableService( 1728): callingUid 10006, callindPid: 1728
,E/MDM     ( 1728): [89] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/UEI.SmartControl( 4389): Loading JNI Libs...
,D/UEI.SmartControl( 4389):  configuring local db...
D/GCM     ( 2002): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2002): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 2265): Restart initialization of location
V/GLSActivity( 2002): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 2002): com.google.android.gms: cancel(0) by com.google.android.gms
V/GmsCoreStatsServiceLauncher( 2265): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/AudioManager( 4367): getMode name:com.lge.qremote
,I/art     ( 2002): Explicit concurrent mark sweep GC freed 9468(590KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 11MB/18MB, paused 1.414ms total 96.542ms
,W/GCoreFlp( 1728): No location to return for getLastLocation()
,W/FusedLocationProvider( 2002): location=null
I/ActivityManager(  848): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4417 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/UEI.SmartControl( 4389):  ---- Has DB8: true
,D/UEI.SmartControl( 4389): QS start statue = true Error code = 0
,D/UEI.SmartControl( 4389): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4389): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4389): IRRCDataComm has AudioManager!!!!.
D/BluetoothManagerService(  848): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  848): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  848): Message: 2
,D/WifiServiceImplEx(  848): setWifiEnabled: false pid=3931, uid=10030, package= com.example.hello, App Lable : HelloWorld
D/WifiService(  848): setWifiEnabled: false pid=3931, uid=10030
I/jxcore-log( 3931): ****TEST TOOK:  5064  ms ****
I/jxcore-log( 3931): 
I/jxcore-log( 3931): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3931): 
W/irrc_jni( 4389): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4389): IrrcClient ++ 
D/irrcClient( 4389): getIrrcService ++ 
,D/irrcClient( 4389): getIrrcService -- 
D/irrcClient( 4389): IrrcClient -- 
W/irrc_jni( 4389): IRRCPlayer_nativeInit -- 
W/ResourcesManager( 4417): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4417): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4417): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 4389): Services init done
I/UEI.SmartControl( 4389): Device manager: loading config....
D/UEI.SmartControl( 4389): QS Service init finished
D/UEI.SmartControl( 4389): QS Service version name: 0.1.73
D/UEI.SmartControl( 4389): QS Service version code: 1073
,D/UEI.SmartControl( 4389): Service requested: Control
D/UEI.SmartControl( 4389): Config is loaded...
V/AlarmManager(  848): RTC_WAKEUP set : Alarm{a8040e6 type 0 when 1447782170344 com.google.android.gms} when 1447782170344
D/UEI.SmartControl( 4389):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 4389): Notify AllClients services are ready: 0
D/UEI.SmartControl( 4389): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 4389): Internal service binding...
I/iu.UploadsManager( 2265): End new media; added: 0, uploading: 0, time: 53 ms
,D/UEI.SmartControl( 4389): -----IControl: 11
D/UEI.SmartControl( 4389): Caller: com.lge.qremote
D/UEI.SmartControl( 4389): ------------ IControl registerCallback...
I/UEI.SmartControl( 4389): Registering callback...
D/UEI.SmartControl( 4389): -----IControl: 19
D/UEI.SmartControl( 4389): Caller: com.lge.qremote
,I/UEI.SmartControl( 4389): Registering Services Ready callback...
I/UEI.SmartControl( 4389): Notify client services are ready...
D/UEI.SmartControl( 4389): -----IControl: 8
D/UEI.SmartControl( 4389): Caller: com.lge.qremote
I/ActivityManager(  848): Killing 3869:com.google.android.configupdater/u0a3 (adj 15): empty #11
,W/libprocessgroup(  848): failed to open /acct/uid_10003/pid_3869/cgroup.procs: No such file or directory
,I/LGEmail ( 4417): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 4417): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/PackageChangeReceiver( 4417): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  848): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4446 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  848): Killing 3911:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_3911/cgroup.procs: No such file or directory
,D/AndroidRuntime( 4439): 
D/AndroidRuntime( 4439): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4439): CheckJNI is OFF
I/ActivityManager(  848): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4466 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 4065:com.google.android.youtube/u0a100 (adj 15): empty #11
,W/libprocessgroup(  848): failed to open /acct/uid_10100/pid_4065/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 4466): onCreate
W/AppUp4:DB( 4466):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 4466):  setFingerPrint start
I/AppUp4:DB( 4466):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 4466):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4466):  SDK version = 0
I/AppUp4:DB( 4466):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 4466): AppBoxApplication onCreate()
,I/ActivityManager(  848): Killing 4159:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  848): failed to open /acct/uid_10053/pid_4159/cgroup.procs: No such file or directory
,D/AndroidRuntime( 4439): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  848): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4501 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/ActivityManager(  848): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  848): Killing 3931:com.example.hello/u0a30 (adj 0): stop com.example.hello
,I/WindowState(  848): WIN DEATH: Window{232d39a9 u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  848): Focus left window: Window{232d39a9 u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  848): Window went away: Window{232d39a9 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  848): Skipping PackageSetting{2f33a0a0 com.test.thalitest/10316} due to missing metadata
,W/ActivityManager(  848): Force removing ActivityRecord{b3641f u0 com.example.hello/.MainActivity t217}: app died, no saved state
,W/ActivityManager(  848): Spurious death for ProcessRecord{32d0af96 3931:com.example.hello/u0a30}, curProc for 3931: null
I/ActivityManager(  848): Force stopping com.example.hello appid=10030 user=0: pkg removed
I/[LGHome]EVENT( 1872): [Launcher.java:5203:onStart()]onStart
,D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1728): Ignoring removeGeofence because network location is disabled.
W/System.err( 3402): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
I/QCNEJ   ( 1835): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/System.err( 3402): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3402): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3402): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3402): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3402): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3402): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3402): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3402): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3402): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3402): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3402): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/InputReader(  848): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 1872): [Launcher.java:776:onResume()]onResume
W/ResourcesManager( 4501): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4501): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4501): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/administrator(  848): Handling package changes for user 0
,I/ActivityManager(  848): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4521 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]LGActivityUtil( 1872): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1872): [Launcher.java:929:onResume()]onResume end
I/Activity( 1872): Activity.onPostResume() called 
,I/SystemUI[Framework](  848): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  848): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  848): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  848): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  848): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@30d59edb,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  848): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/[LGHome]LGWallpaperInfo( 1872): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1872): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,D/InputDispatcher(  848): Focus entered window: Window{311e5400 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1872): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1872): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1872): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1872): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1872): [setNavigationBarColor] color=0x 0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/art     ( 1781): CheckpointMarkThreadRoots callback created = 0xaaf21b90
I/LockScreenSettings( 4521): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,I/art     ( 1781): CheckpointMarkThreadRoots callback created = 0xb042d6d0
,D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
I/ActivityManager(  848): Killing 4218:com.lge.bnr/1000 (adj 15): empty #11
,W/InputMethodManagerService(  848): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  848): Got RemoteException sending setActive(false) notification to pid 3931 uid 10030
D/KeyguardModel( 1372): handleShortcutListChanged...
,W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_4218/cgroup.procs: No such file or directory
,I/Timeline( 1872): Timeline: Activity_idle id: android.os.BinderProxy@31474561 time:61973
I/SystemUI[Framework](  848): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  848): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  848): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  848): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  848): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@30d59edb,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  848): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/NotificationService(  848): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  848): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  848): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/TaskPersister(  848): removeObsoleteFile: deleting file=217_task.xml
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
,W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
D/BarTransitions( 1372): draw background and invalidate : color = ef000000
,W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/BarTransitions( 1372): draw background and invalidate : color = ebe2e2e2
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
I/AppConfig( 4501): Total System Memory = 906309632
,I/GalleryUtils( 4501): Application Heap = 96 MB
I/AppConfig( 4501): App Tier : NOT_DEF
D/KeyguardModel( 1372): handleShortcutListChanged...
,I/HotwordRecognitionRnr( 1938): Starting hotword detection.
D/SystemHelper( 4501): region [EU], country [EU], operator [OPEN], sub-operator []
I/MicrophoneInputStream( 1938): mic_starting com.google.android.apps.gsa.speech.audio.u@59ac615
,V/AudioRecord( 1938): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1938): set(): mSessionId 22
V/AudioPolicyManager(  280): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  280): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  280): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  280): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb4036660)
V/audio_hw_primary(  280): adev_open_input_stream: exit
V/AudioFlinger(  280): openInput_l() openInputStream returned input 0xb4036660, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
,I/AudioFlinger(  280): AudioFlinger's thread 0xb4393000 ready to run
D/audio_hw_primary(  280): in_standby: enter: stream (0xb4036660) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioFlinger(  280): openInput_l() created record thread: ID 23 thread 0xb4393000
V/AudioSystem(  280): ioConfigChanged() event 3, ioHandle 23
,D/audio_hw_primary(  280): in_standby: enter: stream (0xb4036660) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioSystem(  848): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioSystem( 1372): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioSystem( 1746): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioSystem( 1938): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 2696): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 3133): ioConfigChanged() event 3, ioHandle 23
V/AudioFlinger(  280): openRecord() lSessionId: 22 input 23
V/AudioFlinger(  280): getOrphanEffectChain_l session 22 index -2
V/AudioFlinger(  280): acquiring 22 from 1938, for -1
V/AudioFlinger(  280):  added new entry for 22
V/AudioRecord( 1938): start, sync event 0 trigger session 0
V/AudioRecord( 1938): mAudioRecord->start()
V/AudioFlinger(  280): RecordHandle::start()
V/AudioFlinger(  280): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  280): startInput() module primary->input primary(23)
V/AudioPolicyManager(  280): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  280): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  280): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  280): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  280): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  280): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  280): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  280): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  280): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb4393000
V/AudioFlinger::PatchPanel(  280): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  280): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  280): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  280): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  280): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  280): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  280): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  280): setParameters(): io 23, keyvalue hotword_active=1, calling pid 280
V/AudioPolicyService(  280): AudioCommandThread() going to sle,ep
V/AudioFlinger(  280): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb4393000
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1938): mic_started com.google.android.apps.gsa.speech.audio.u@59ac615
I/art     (  848): Explicit concurrent mark sweep GC freed 21267(1310KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 14.679ms total 474.765ms
V/msm8974_platform(  280): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  280): start_input_stream: enter: stream(0xb4036660)usecase(7: audio-record)
V/voice   (  280): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  280): start_input_stream: usecase(7)
E/audio_hw_primary(  280): select_devices: enter and usecase(7)
V/msm8974_platform(  280): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  280): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  280): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  280): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  280): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  280): enable_snd_device: enter  144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  280): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  280): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  280): ACDB -> send_adm_topology
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  280): ACDB -> send_asm_topology
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  280): ACDB -> send_audtable
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  280): ACDB -> send_audvoltable
D/ACDB-LOADER(  280): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  280): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  280): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  280): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  280): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  280): enable_audio_route: exit
D/audio_hw_primary(  280): select_devices: done
V/audio_hw_primary(  280): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  280): start_input_stream: exit
,I/ActivityManager(  848): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4552 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 4247:com.android.vending/u0a36 (adj 15): empty #11
D/charger_monitor(  491): init target 500000
,D/AndroidRuntime( 4439): Shutting down VM
,W/ResourcesManager(  848): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/HotwordWorker( 1938): onReady
,W/libprocessgroup(  848): failed to open /acct/uid_10036/pid_4247/cgroup.procs: No such file or directory
,I/Timeline(  848): Timeline: Activity_windows_visible id: ActivityRecord{35eb701a u0 com.lge.launcher2/.Launcher t216} time:62273
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  491): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 310
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/WifiController(  848): battery changed pluggedType: 2
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 310, mChargingStatus=5, mChargingStop=false
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 312, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 310
I/QCNEJ   ( 1835): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/WifiController(  848): battery changed pluggedType: 2
I/QCNEJ   ( 1835): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LCardEmulationManager( 1781): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1781): getDefaultRoute
,W/ResourcesManager( 4552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4552): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4552): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 4552): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 4552): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 312
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 312
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/ResourceType(  848): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1872): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/SystemConfig( 4552): BUILD Country: EU
I/SystemConfig( 4552): BUILD Operator: OPEN
,I/SystemConfig( 4552): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 4552): existFile = false
I/SystemConfig( 4552): canReadFile = false
I/SystemConfig( 4552): systemFeature RCS result false
D/SystemConfig( 4552): refreshRcsSupport() :false
,I/LockScreenSettings( 4521): New app installed broadcast received ..
I/LockScreenSettings( 4521): Number of installed packages  1
,I/ActivityManager(  848): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=4578 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  848): Killing 4309:com.lge.qmemoplus/1000 (adj 15): empty #11
,I/ActivityManager(  848): Waited long enough for: ServiceRecord{2d90f1ab u0 com.lge.mlt/.MltMonitorService}
,W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_4309/cgroup.procs: No such file or directory

```
