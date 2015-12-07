#### Test 502422852e23b2c_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
E/MPT MptOnPowerWatcher( 3465): startListen
--------- beginning of system
I/ActivityManager(  880): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=3511 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
W/ResourcesManager( 3511): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/RlzPingService( 3482): Setting next ping for 1450102054214
I/ActivityManager(  880): Killing 3143:com.android.browser/u0a12 (adj 15): empty #11
D/CalendarProvider2( 3511): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@745ae27
W/libprocessgroup(  880): failed to open /acct/uid_10012/pid_3143/cgroup.procs: No such file or directory
D/CalendarProvider2( 3511): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 3511): Created com.android.providers.calendar.CalendarAlarmManager@35c70e40(com.android.providers.calendar.CalendarProvider2@745ae27)
D/CalendarReceiver( 3511): [onReceive] intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.calendar/.CalendarReceiver (has extras) }
D/CalendarReceiver( 3511): [onReceive] WakeLock new : CalendarReceiver_Provider, ReferenceCounted = true
D/CalendarReceiver( 3511): [onReceive] WakeLock acquire : CalendarReceiver_Provider
D/CalendarReceiver( 3511): [onReceive] android.intent.action.BOOT_COMPLETED
D/CalendarProvider2( 3511): Scheduling check of next Alarm
D/AndroidRuntime( 3540): 
D/AndroidRuntime( 3540): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3540): CheckJNI is OFF
I/art     (  880): Explicit concurrent mark sweep GC freed 19452(1189KB) AllocSpace objects, 16(304KB) LOS objects, 33% free, 22MB/33MB, paused 2.233ms total 152.443ms
D/CalendarProvider2( 3511): SCHEDULE_ALARM_REMOVE
D/CalendarReceiver( 3511): [onReceive] WakeLock release : CalendarReceiver_Provider
I/ActivityManager(  880): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.receiver.DmReceiver: pid=3561 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/LAlarm  (  880): Service started flags 0 startId 3
W/ContextImpl( 3561): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmNotiService.bootCompleted:575 com.lge.lgdmsclient.receiver.DmReceiver.onReceive:94 
E/LGDMClient( 3561): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 3561): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 3561): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_BOOTUP_COMPLETE
D/LGDMClient( 3561): [DmUtil.java] [removeSilenceBootFile()] : [894] : Try to remove a Silence file
D/LGDMClient( 3561): [DmNotiService.java] [actionSystemBootComplete()] : [459] : CHECK_AUTO_UPDATE_PROCESS : 0 Call removeSilenceBootFile() 
I/LGDMClient( 3561): [DmNotiService.java] [actionSystemBootComplete()] : [467] : DM Service on boot completed
D/LGDMClient( 3561): [DmClientController.java] [startService()] : [400] : startService(), DownloadService will be started in order to follow the start of DmClientController
W/ContextImpl( 3561): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.controller.DmClientController.startService:404 com.lge.lgdmsclient.dmclient.controller.DmClientController.getInstance:345 com.lge.lgdmsclient.service.DmNotiService.actionSystemBootComplete:474 
D/AndroidRuntime( 3540): Calling main entry com.android.commands.am.Am
I/ActivityManager(  880): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=3580 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/LGDMClient( 3561): [DmAgent.java] [<init>()] : [164] : DmAgent is started -> DmConstants.DMAgentState.mDmaState = 0
D/LGDMClient( 3561): [DmClientController.java] [run()] : [178] : LooperSTART
I/LGDMClient( 3561): [DmCAConfigParser.java] [getInstance()] : [73] : DmsCAConfigParser sInstance null
D/ActivityManager(  880): setTaskToReturnTo : TaskRecord{5f1a906 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  880): setTaskToReturnTo : TaskRecord{5f1a906 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  880): AppWindowTokenEx init.. 
D/ContextHelper(  880): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  880): Focus left window: Window{342d37b5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 3540): Shutting down VM
I/[LGHome]EVENT( 1908): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  880): check instance of lgWin Window{1dc58d60 u0 Starting com.example.hello}
D/LGDMClient( 3561): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [204] : Current MultiSimEnabled is false
D/LGDMClient( 3561): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [239] : getPhoneSpecificInfo: sim mccmnc(),spn(),gid(null),imsi(null)
I/LGDMClient( 3561): [DmCAConfigParser.java] [parse()] : [108] : parse
D/LGDMClient( 3561): [DmCAConfigParser.java] [setDefaultProfile()] : [490] : setDefaultProfile
D/LGDMClient( 3561): [DmCAConfigParser.java] [setDefaultProfile()] : [493] : filename : fota_dm_settings.xml
D/LGDMClient( 3561): [DmCAConfigParser.java] [setDefaultProfile()] : [506] : [UI4.1] Search [fota_dm_settings.xml]
I/ActivityManager(  880): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3600 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/LGDMClient( 3561): [DmCAConfigParser.java] [parse()] : [134] : [UI4.1] Search [fota_dm_settings.xml]
D/LGDMClient( 3561): [DmAgentUtil.java] [setAutoAgentSchedule()] : [117] : IN setAutoAgentSchedule()
D/LGDMClient( 3561): [DmAgentUtil.java] [setAutoAgentSchedule()] : [126] :  cursor != null setAutoAgentSchedule()
I/[LGHome]EVENT( 1908): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/LGDMClient( 3561): [DmAgentUtil.java] [setAutoAgentSchedule()] : [167] : SET ALARM setAutoAgentSchedule() = 20151210T212428
I/HotwordDetector( 1966): Closing mic
I/MicrophoneInputStream( 1966): mic_close com.google.android.apps.gsa.speech.audio.u@25907231
V/AudioRecord( 1966): stop()
D/AudioRecord( 1966): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioFlinger(  282): Record stopped OK
V/AudioPolicyManager(  282): stopInput() input 17
V/AudioPolicyService(  282): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  282): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  282): ThreadBase::setParameters() routing=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
D/LGDMClient( 3561): [DmAgentUtil.java] [setAutoAgentSchedule()] : [185] : OUT setAutoAgentSchedule()
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/LGDMClient( 3561): [DmAgent.java] [checkPostponed()] : [2062] : DMAGentState is: DmConstants.DMAgentState.mDmaState = 0
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3857000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/LGDMClient( 3561): [DmClientController.java] [handleMessage()] : [181] : DmClientController: run() - msg.what=31
D/LGDMClient( 3561): [DmAgent.java] [processRestartHandler()] : [1241] : DMAGentState is: DmConstants.DMAgentState.mDmaState = 0
I/[LGHome]EVENT( 1908): [Launcher.java:5214:onStop()]onStop
E/[LGE_FOTA] ( 3561): FOTA JNI_OnLoad
E/[LGE_FOTA] ( 3561):  FOTAJNI_GetUAResult in
E/[LGE_FOTA] ( 3561): FOTAFS_Open /cache/fota/usd.dat, 0, handle : 1c
E/[LGE_FOTA] ( 3561): enUpdateState                : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.enState             : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[0]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[0]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[1]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[1]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[2]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[2]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[3]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[3]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[4]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[4]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[5]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[5]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[6]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[6]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[7]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[7]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[8]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[8]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[9]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[9]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[10]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[10]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[11]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[11]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[12]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[12]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[13]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[13]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[14]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[14]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgOffset[15]     : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiPkgSize[15]       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiCurrSection       : 0x00000000
E/[LGE_FOTA] ( 3561): stFWInfo.uiResult            : 0x00000000
E/[LGE_FOTA] ( 3561): stFSInfo.enState             : 0x00000000
E/[LGE_FOTA] ( 3561): stFSInfo.uiFilePackageOffset : 0xa09037d4
E/[LGE_FOTA] ( 3561): stFSInfo.uiFilePackageSize   : 0xa09037f4
E/[LGE_FOTA] ( 3561): stFSInfo.uiResult            : 0x00000000
E/[LGE_FOTA] ( 3561): stPkgInfo.enPackageType      : 0x00000000
E/[LGE_FOTA] ( 3561): stPkgInfo.uiSize             : 0x00000000
E/[LGE_FOTA] ( 3561): stPkgInfo.uiWrittenAddr      : 0x00000000
E/[LGE_FOTA] ( 3561): stPkgInfo.uiWrittenSize      : 0x00000000
E/[LGE_FOTA] ( 3561): stPkgInfo.szPackagePath      : 
E/[LGE_FOTA] ( 3561): stCommand.enCommand	 		: 0x00000000
E/[LGE_FOTA] ( 3561): uiBackupBufferAddr			: 0x00000000
E/[LGE_FOTA] ( 3561): uiLanguage					: 0x00000000
E/[LGE_FOTA] ( 3561): stDebug.uiResetCount			: 0x00000000
E/[LGE_FOTA] ( 3561): stDebug.uiRetryCount			: 0x00000000
E/[LGE_FOTA] ( 3561): FOTAFS_Close 1c
E/[LGE_FOTA] ( 3561): FOTAJNI_GetConvertedUAResult : 450
E/[LGE_FOTA] ( 3561): FOTAJNI_GetUAResult : 450
D/LGDMClient( 3561): [SwUpdate.java] [getSwUpdateStatus()] : [244] : Software update result:450
I/WindowStateAnimator(  880): Starting window displayed
D/LGDMClient( 3561): [DmAgent.java] [restartIdleSession()] : [1084] : skymymy is: iSwUpdateStatus = 450, isUpgradedByLGUP() = false
W/ActivityThread( 1908): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1908): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1908): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1908): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1908): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1908): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1908): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1908): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1908): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1908): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/LGDMClient( 3561): [DmAgent.java] [clearContext()] : [1774] : [Enter] clearContext
I/LGDMClient( 3561): [DmAgent.java] [setState()] : [1875] : Setting Agent State and State is : DmConstants.DMAgentState.mDmaState = 0
D/LGDMClient( 3561): [DmAgent.java] [clearContext()] : [1791] : [Exit] clearContext
V/LGDMClient( 3561): [DmClientController.java] [handleMessage()] : [181] : DmClientController: run() - msg.what=33
D/LGDMClient( 3561): [DmClientController.java] [stopService()] : [408] : stopDownloadService(), DownloadService will be stopped in order to follow the end of DmClientController
W/ContextImpl( 3561): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 com.lge.lgdmsclient.dmclient.controller.DmClientController.stopService:412 com.lge.lgdmsclient.dmclient.controller.DmClientController.clearController:383 com.lge.lgdmsclient.dmclient.controller.DmClientController.access$200:68 
I/SystemUI[Framework](  880): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  880): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  880): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  880): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  880): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3dc7825,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  880): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1370): draw background and invalidate : color = f000000
D/BarTransitions( 1370): draw background and invalidate : color = 100f0f0f
V/audio_hw_primary(  282): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  282): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): disable_audio_route: reset and update mixer path: audio-record
E/LGDMClient( 3561): [DmDownloadService.java] [onCreate()] : [56] : DmDownloadService.onCreate()
V/audio_hw_primary(  282): disable_audio_route: exit
E/audio_hw_primary(  282): disable_snd_device: enter 144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): disable_snd_device: snd_device(144: lg-vr-handset-mic)
D/LGDMClient( 3561): [DmDownloadService.java] [onStartCommand()] : [92] : DmDownloadService.onStartCommand()
V/audio_hw_primary(  282): stop_input_stream: exit: status(0)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  282): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  282): setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3857000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
D/LGDMClient( 3561): [DmDownloadService.java] [handleStart()] : [103] : DmDownloadService  intend : Intent { cmp=com.lge.lgdmsclient/.service.DmDownloadService }
V/AudioRecord( 1966): stop()
V/AudioRecord( 1966): stop()
V/AudioRecord( 1966): stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioSystem( 1370): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioSystem( 1782): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  880): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2700): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread 0xb3857000 exiting
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioFlinger(  282): removeClient_l() pid 1966, calling pid 282
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioSystem( 3165): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1966): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): releasing 16 from 1966 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
I/HotwordRecognitionRnr( 1966): Stopping hotword detection.
,D/LGDMClient( 3561): [DmDownloadService.java] [onDestroy()] : [117] : DmDownloadService.onDestroy()
I/ActivityManager(  880): Killing 3234:com.android.settings/1000 (adj 15): empty #11
I/HotwordRecognitionRnr( 1966): Hotword detection finished
I/ActivityManager(  880): Activity reported stop, but no longer stopping: ActivityRecord{1daddf42 u0 com.lge.launcher2/.Launcher t219}
W/libprocessgroup(  880): failed to open /acct/uid_1000/pid_3234/cgroup.procs: No such file or directory
D/ContextHelper( 3600): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/ALBootInit( 3580): ====action==>android.intent.action.BOOT_COMPLETED
D/ALBootInit( 3580): Alarm ALBootInit: BOOT_COMPLETED
I/ALProvider( 3580): delete where======= time <= 1449497255067  and  aindex > 0
D/Alarms  ( 3580):  --- disableExpiredAlarms!!! isBooting : true
D/Alarms  ( 3580): count ===>0
D/Alarms  ( 3580): snoozeActivating scount==>0
D/Alarms  ( 3580): [setNextAlert] start
D/Alarms  ( 3580): [setNextAlert] (1)
D/Alarms  ( 3580):  minTime  = 0
D/Alarms  ( 3580):  -- OK multi -- 0
E/jeny.kim( 3580): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 3580): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 3580): BUILD Operator: OPEN
D/Alarms  ( 3580): broadcastToWidgetProvider : false
D/Alarms  ( 3580): Enter formatDayAndTime(final Context context, long timeInMiliSec)
I/WebViewFactory( 3600): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
V/SettingsProvider(  880): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
W/BackupManagerService(  880): dataChanged but no participant pkg='com.android.providers.settings' uid=10010
D/CommonUtil( 3580): Enter deleteUnnecessaryToneItem() enter excepted tone uri value is null, preferparent value is  ALARM
D/CommonUtil( 3580): deleteUnnecessaryToneItem() -> Alarm Surviv Count is 0
D/CommonUtil( 3580): Exit deleteUnnecessaryToneItem()
I/CommonUtil( 3580): BUILD Country: EU
I/TimerReceiver( 3580): onReceiveIntent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.lge.clock/.timer.TimerReceiver (has extras) }
D/TimerReceiver( 3580): onReceive() : android.intent.action.BOOT_COMPLETED
I/TimerReceiver( 3580): setTimerDone
D/TimerObj( 3580): --------------------- getTimersFromSharedPrefs
V/TimerObj( 3580): --------------------- timers list is empty
I/LibraryLoader( 3600): Time to load native libraries: 5 ms (timestamps 9703-9708)
I/LibraryLoader( 3600): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3600): Binding Chromium to main looper Looper (main, tid 1) {35c70e40}
I/LibraryLoader( 3600): Expected native library version number "",actual native library version number ""
I/chromium( 3600): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  880): Start proc com.lge.appbox.client:SingleBinaryService for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver: pid=3627 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  880): Killing 3314:com.android.providers.partnerbookmarks/u0a71 (adj 15): empty #11
I/BrowserStartupController( 3600): Initializing chromium process, singleProcess=true
W/art     ( 3600): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3600): ApplicationContext is null in ApplicationStatus
W/chromium( 3600): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3600): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3600): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3600): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3600): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3600): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3600): Build Date: 03/02/15 Mon
I/Adreno-EGL( 3600): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 3600): Remote Branch: 
I/Adreno-EGL( 3600): Local Patches: 
I/Adreno-EGL( 3600): Reconstruct Branch: 
W/libprocessgroup(  880): failed to open /acct/uid_10071/pid_3314/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 3627): AppBoxApplication onCreate()
D/AppUp4:SingleBinary( 3627): /cust/OPEN_EU/config/app-enabled-conf.json is selected!!
D/AppUp4:SingleBinary( 3627):  Starting isFingerChanged 
V/AudioPolicyService(  282): registerClient() client 0xb551cd40, uid 10030
D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@106264b7:true
D/BluetoothAdapter( 3600): 1043254892: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  880): Start proc com.lge.appbox.client for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider: pid=3658 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 23.408ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 21.042ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 317us total 22.423ms
W/ActivityManager(  880): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  880): RTC_WAKEUP set : Alarm{1b861fa8 type 0 when 1449497240725 com.android.providers.contacts} when 1449497240725
D/ActivityManager(  880): enqueue in BackgroundQueue #58 Intent=Intent { act=com.google.android.intent.action.GCM_RECONNECT flg=0x14 (has extras) }
V/AlarmManager(  880): ELAPSED_WAKEUP set : Alarm{39b0dac1 type 2 when 50005 com.google.android.gms} when 50005
I/AppUp4:AppBoxCP( 3658): onCreate
,W/AppUp4:DB( 3658):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 3658):  setFingerPrint start
,I/AppUp4:DB( 3658):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/CalendarProvider2( 3511): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3511): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  880): Killing 3332:com.lge.eula/1000 (adj 15): empty #11
I/AppUp4:DB( 3658):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 3658):  SDK version = 0
I/AppUp4:DB( 3658):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  880): failed to open /acct/uid_1000/pid_3332/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 3658): AppBoxApplication onCreate()
,D/AppUp4:SingleBinary( 3627):  The value of isFingerChanged null
D/AppUp4:SingleBinary( 3627): Device : jagnm
D/AppUp4:SingleBinary( 3627): First Boot - ignore boot completed
,D/AppUp4:NTCodeSingleBinary( 3627): Starting isFingerChanged 
D/AppUp4:NTCodeSingleBinary( 3627): The value of isFingerChanged lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
D/AppUp4:SingleBinary( 3627): Device : jagnm
D/AppUp4:SingleBinary( 3627): Config file is not exist - nothing
I/ActivityManager(  880): Killing 3263:com.android.contacts/u0a18 (adj 15): empty #11
W/art     ( 3600): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3600): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3600): CordovaWebView is running on device made by: LGE
,W/libprocessgroup(  880): failed to open /acct/uid_10018/pid_3263/cgroup.procs: No such file or directory
I/AppUp4:SDKReflector( 3658): +myUserId : 0
D/AppUp4:BootUpPollingReceiver( 3658): onReceive on user ID : 0
W/art     ( 3600): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3600): Attempt to remove local handle scope entry from IRT, ignoring
V/AppUp4:FotaPlusService( 3658):  isFotaPlusTriedOnce : true
D/AppUp4:BootUpPollingReceiver( 3658): Starting getSdkVersion 
,D/AppUp4:BootUpPollingReceiver( 3658): SDK version is : 0
D/AppUp4:BootUpPollingReceiver( 3658): currentSdkVersion : 0
D/AppUp4:BootUpPollingReceiver( 3658): isSdkVersionChanged : true
V/AppUp4:FotaPlusService( 3658):  setFotaPlusCompleted : false
D/AppUp4:BootUpPollingReceiver( 3658): isFotaPlusNeeded : true
D/AppUp4:BootUpPollingReceiver( 3658): Fota Plus already tried once, show notification
V/NotificationService(  880): enqueueNotificationInternal: pkg=com.lge.appbox.client id=22319582 notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
,D/AppUp4:BootUpPollingReceiver( 3658): isFotaPlusRunning after : true
D/ZenLog  (  880): intercepted: 0|com.lge.appbox.client|22319582|null|10011,none
D/AppUp4:BootUpPollingReceiver( 3658):  installPreloadedValuePackIfNeeded 
D/AppUp4:BootUpPollingReceiver( 3658):  file is : /system/apps/bootup
D/AppUp4:BootUpPollingReceiver( 3658): file false
V/NotificationService(  880): pkg=com.lge.appbox.client canInterrupt=false intercept=true
D/AppUp4:BootUpPollingReceiver( 3658): [BootUpPollingReceiver] No preload installation.
I/NotificationServiceEx(  880): LED remove() : mLights=0|com.lge.appbox.client|22319582|null|10011
D/NotificationServiceEx(  880): updateLightListLocked :r=0|com.lge.appbox.client|22319582|null|10011, action=2
D/NotificationServiceEx(  880): notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
D/AppUp4:dwnld( 3658): [removeAllIncompletedDownload] ... 
D/SmartCoverUpdateMonitor( 1331): onNotificationPosted() : StatusBarNotification(pkg=com.lge.appbox.client user=UserHandle{0} id=22319582 tag=null score=0 key=0|com.lge.appbox.client|22319582|null|10011: Notification(pri=0 contentView=com.lge.appbox.client/0x1090079 vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE))
D/SmartCoverUpdateMonitor( 1331): onNotificationPosted() !qcn.isEnableToShowNotification()
V/AppUp4:BootUpPollingReceiver( 3658): [BootUpPollingReceiver] start bootup Polling.
,D/AppUp4  ( 3658): getUpdatePollingPeriod
D/AppUp4  ( 3658): getUpdatePollingPeriod
D/AppUp4:BackgroundPollingService ( 3658): register polling alarm when : 2015/12/10 21:31:58
,D/AppUp4:LightWeightPollingService ( 3658):  [buildRemotePollingIntent]
D/AppUp4:LightWeightPollingService ( 3658): This means remote config is N, so skip it
I/ActivityManager(  880): Killing 3370:com.android.keychain/1000 (adj 15): empty #11
,W/libprocessgroup(  880): failed to open /acct/uid_1000/pid_3370/cgroup.procs: No such file or directory
,I/Activity( 3600): Activity.onPostResume() called 
D/OpenGLRenderer( 3600): Render dirty regions requested: true
I/OpenGLRenderer( 3600): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3600): Enabling debug mode 0
D/Atlas   ( 3600): Validating map...
,D/SplitWindow(  880): check instance of lgWin Window{30dccdbb u0 com.example.hello/com.example.hello.MainActivity}
I/ActivityManager(  880): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3689 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/MmsConfig( 3165): isNotAllowedSms: currentUser:0
D/MmsConfig( 3165): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3165): isUserMode:false
D/SmsReceiverService( 3165): handleMessage isUserMode:false
W/chromium( 3600): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/[SystemUI]PhoneStatusBar( 1370): updateMediaMetaData(false): mMediaMetadata = null
W/ResourcesManager( 3165): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/SmsReceiverService( 3165): handleMessage action: android.intent.action.BOOT_COMPLETED error: 0
,D/InputDispatcher(  880): Focus entered window: Window{30dccdbb u0 com.example.hello/com.example.hello.MainActivity}
W/ResourcesManager( 3689): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/InputMethodManagerService(  880): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  880): Displayed com.example.hello/.MainActivity: +1s268ms
I/Timeline(  880): Timeline: Activity_windows_visible id: ActivityRecord{2a08fbc7 u0 com.example.hello/.MainActivity t220} time:50535
,I/Timeline( 3600): Timeline: Activity_idle id: android.os.BinderProxy@10b8aa9c time:50537
W/BindingManager( 3600): Cannot call determinedVisibility() - never saw a connection for the pid: 3600
,D/CalendarApplication( 3689): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 3689): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 3689): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3ce1fa7d, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@37ed72, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3a5505c3, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@35c70e40, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1198c179, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@25936ebe, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@10783b1f, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3e2ece6c, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@105afc35, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3593b8ca, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@86f6a3b, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2e706558, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3ecc26b1, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@e9c9796, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2e06f17, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1e327f04, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3f4b7ced, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3f829722, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1af2e5b3, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@16da8770, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@effae9, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3dd7036e, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2cac2a0f, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@10b8aa9c, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@33445ca5, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@34f3e87a, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@250b582b, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@16f3d488, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@39c31e21, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@39c81246, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@37e54c07, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3e35b134, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1b127b5d, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2f630cd2, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1780a1a3, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1a16aca0, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@28007059, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2841241e, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@9f1b4ff, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1d49f2cc, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@163eb915, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@105764
I/chromium,( 3600): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/GeneralPreferenceUtils( 3689): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 3689): [init]
I/Config  ( 3689): LGCalendar ver.4.40.17
I/Config  ( 3689): start check model
I/Config  ( 3689): start check native_ca
I/Config  ( 3689): Config Operator=OPEN, Country=EU
D/Config  ( 3689): [setDefaultValuesToPref]
D/Config  ( 3689): [parseProfiles]
D/ProfilesParser( 3689): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 3689): [debug_displayParseInfos] profile.operator = null
D/Config  ( 3689): [updateProfiletoCountryInfo]
D/GeneralPreference( 3689): [checkAndMigrateOldPreference]
,D/AlertReceiver( 3689): onReceive: a=android.intent.action.BOOT_COMPLETED Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.calendar/.alerts.AlertReceiver (has extras) }
,I/InitNotificationRingtoneService( 3689): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 3689): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/ActivityManager(  880): Start proc com.android.settings for broadcast com.android.settings/.lockscreen.LockSettingsReceiver: pid=3714 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/JsMessageQueue( 3600): Set native->JS mode to OnlineEventsBridgeMode
,W/ResourcesManager( 3714): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/AndroidProtocolHandler( 3600): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/AlertUtils( 3689): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/IndexDatabaseHelper( 3714): Using schema version: 115
I/IndexDatabaseHelper( 3714): Index is fine
,I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 3689): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3689): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3689): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3689): End InitializeAlertRingtoneService.onHandleIntent
,D/UsbSettingsReceiver( 3714): [AUTORUN] onReceive() : action = android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3714): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3714): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3714): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3714): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,W/HolidayIntentService( 3689): onHandleIntent
D/HolidayDataLoader( 3689): readJsonAsset : holiday.json
D/AlertService( 3689): 0 Action = android.intent.action.BOOT_COMPLETED
D/UsbSettingsControl( 3714): [AUTORUN] setTetherStatus() : status=false
D/UsbSettingsReceiver( 3714): [AUTORUN] onReceive() : android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3714): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3714): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3714): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/StoreModeReceiver( 3714): intent.getAction() : android.intent.action.BOOT_COMPLETED
D/StoreModeReceiver( 3714): sim state :null
D/StoreModeReceiver( 3714): Back LED don't supported.
D/AlertService( 3689): [Widget]com.android.calendar.widget.CalendarAppWidgetProvider enabled
D/Feature ( 3689): MemoryLevel - 5:NOT_DEF:Not UI4.2 LOS
D/AlertService( 3689): [Widget]com.android.calendar.widget.MonthWidgetProvider enabled
D/AlertService( 3689): [Widget]com.android.calendar.widget.WeekWidgetProvider enabled
D/AlertService( 3689): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,V/SettingsProvider(  880): call_put(system:emotional_led_back_led=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  880): call_put(system:emotional_led_back_incoming_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  880): call_put(system:emotional_led_back_alarm=0) for 0 calling package = com.android.settings
V/SettingsProvider(  880): call_put(system:emotional_led_back_missed_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  880): call_put(system:emotional_led_back_missed_messages=0) for 0 calling package = com.android.settings
V/SettingsProvider(  880): call_put(system:emotional_led_back_missed_emails=0) for 0 calling package = com.android.settings
V/SettingsProvider(  880): call_put(system:emotional_led_back_calendar_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  880): call_put(system:emotional_led_back_voice_recording=0) for 0 calling package = com.android.settings
V/SettingsProvider(  880): call_put(system:emotional_led_back_camera_timer_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  880): call_put(system:emotional_led_back_camera_face_detecting_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  880): call_put(system:notification_light_pulse_back=0) for 0 calling package = com.android.settings
D/StoreModeReceiver( 3714): SystemProperty Default brightness value [0-255] : 143
,D/StoreModeReceiver( 3714): Default brightness[0-255] : 143
E/HolidayIntentService( 3689): onHandleIntent:holiday data empty
,W/ResourcesManager( 3714): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/StoreModeReceiver( 3714): Default Screen off timeout value : 30000
D/StoreModeReceiver( 3714): SystemProperty Default brightness Mode value[true/false] : false
D/AlarmScheduler( 3689): No events found starting within 1 week.
D/StoreModeReceiver( 3714): BRIGHTNESS_MODE - 0
D/StoreModeReceiver( 3714): Default brightness Mode [0/1] : 0
D/StoreModeReceiver( 3714): Default NIGHT_MODE : 0
D/StoreModeReceiver( 3714): Set MaxBrightness : 255
E/PhoneInterfaceManager( 1782): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/StoreModeReceiver( 3714): getPhoneNumber is empty
D/StoreModeReceiver( 3714): go to StoreModeCheck()
D/StoreModeReceiver( 3714): isStoremode not null
D/PhoneInterfaceManager( 1782): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
V/SettingsProvider(  880): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
,D/StoreModeReceiver( 3714): product_name : jagnm_global_com
D/StoreModeReceiver( 3714): Store mode start!
V/SettingsProvider(  880): call_put(system:shop_mode=1) for 0 calling package = com.android.settings
V/SettingsProvider(  880): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
I/PowerManagerService(  880): ALS enabled for SRE
D/PowerManagerServiceEx(  880): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=120000 (in 68644 ms)
,D/StoreModeReceiver( 3714): setBrightness() : NoMultiALC=255
W/ContextImpl( 3714): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.StoreModeReceiver.sendBroadcast:500 com.android.settings.StoreModeReceiver.setMode:473 
V/SettingsProvider(  880): call_put(system:screen_brightness_mode=0) for 0 calling package = com.android.settings
D/SettingsProvider(  880): Set screen_off_timeout in entry value : 120000
V/SettingsProvider(  880): call_put(system:screen_off_timeout=120000) for 0 calling package = com.android.settings
V/SettingsProvider(  880): call_put(system:screen_brightness=255) for 0 calling package = com.android.settings
,V/SettingsProvider(  880): call_put(system:check_night_mode=0) for 0 calling package = com.android.settings
,D/SettingBootReceiver( 3714): onReceive
D/SettingBootReceiver( 3714): Boot Completed intent received, action=android.intent.action.BOOT_COMPLETED
,I/ActivityManager(  880): Killing 3296:com.lge.hiddenmenu/1000 (adj 15): empty #11
D/SettingBootReceiver( 3714): setStyle()
D/SettingBootReceiver( 3714): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3714): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3714): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3714): SettingStyle=1
,D/SettingBootReceiver( 3714): setAccountMenu()
D/TAG     ( 3714): setKidsMode
D/TAG     ( 3714): mIsOwner, setKidsMode
D/SettingBootReceiver( 3714): setAccountMenu()
D/YSY     ( 3714): not support Quiet mode notification
,D/jxcore_app_log( 3600): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426109440
D/JX-Cordova( 3600): jxcore cordova android initializing
W/libprocessgroup(  880): failed to open /acct/uid_1000/pid_3296/cgroup.procs: No such file or directory
,I/[SystemUI]LGBootReceiver( 1370): onReceive = android.intent.action.BOOT_COMPLETED
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.statusbar.bootcompleted
I/[SystemUI]PhoneStatusBar( 1370): got ACTION_STICKY_BOOT_COMPLETED
I/BOOT    ( 1370): got ACTION_STICKY_BOOT_COMPLETED
W/jxcore-log( 3600): Initializing JXcore engine
,W/jxcore-log( 3600): JXcore engine is ready
V/SettingsProvider(  880): call_put(system:gentle_vibration_status=1) for 0 calling package = com.android.settings
W/jxcore-log( 3600): Starting JXcore engine
,V/SettingsProvider(  880): call_put(system:smart_ringtone=0) for 0 calling package = com.android.settings
,D/SettingBootReceiver( 3714): timezoneID is null
I/ActivityManager(  880): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3742 uid=10111 gids={50111, 9997, 1028, 3003} abi=armeabi-v7a
,I/SettingBootReceiver( 3714): disable au
,I/TAG     ( 3714): disable WirelessSettingsActivity
I/TAG     ( 3714): disable SKTPhoneMode
,D/SettingBootReceiver( 3714): [Nightmode] Enter receiver
D/SettingBootReceiver( 3714): [Nightmode] BOOT_COMPLETED
,D/NightModeInfo( 3714): [Nightmode] setNightNodeTabSettings
D/NightModeInfo( 3714): [Nightmode] getAlreadyNightModeDB() : 0
D/NightModeInfo( 3714): [Nightmode] getUserBrightnessChange() : 0
D/NightModeInfo( 3714): [Nightmode] getUserBrightnessChangeNoNight() : 0
V/SettingsProvider(  880): call_put(system:already_night_mode=0) for 0 calling package = com.android.settings
V/SettingsProvider(  880): call_put(system:user_change_brightness=0) for 0 calling package = com.android.settings
V/SettingsProvider(  880): call_put(system:user_change_brightness_no_night=0) for 0 calling package = com.android.settings
V/SettingsProvider(  880): call_put(system:night_mode_enabled=0) for 0 calling package = com.android.settings
D/NightModeInfo( 3714): [Nightmode] setTabNightCheck : 0
,V/SettingsProvider(  880): call_put(system:save_tab_night_check=0) for 0 calling package = com.android.settings
W/m.example.hello( 3600): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5494]" dev="sockfs" ino=5494 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 3600): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3600): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6448]" dev="sockfs" ino=6448 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3600): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3600): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3600): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[18039]" dev="sockfs" ino=18039 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
D/NightModeInfo( 3714): [Nightmode] cancelPendingIntent
D/NightModeInfo( 3714): [Nightmode] requestPendingIntent
D/NightModeInfo( 3714): [Nightmode] setAlarmStart~!!~!!~!!
D/NightModeInfo( 3714): [Nightmode] currentHour > 6
D/NightModeInfo( 3714): [Nightmode] currentHour > 6
I/NightModeInfo( 3714): JW getStartTime201512080000
D/NightModeInfo( 3714): [Nightmode] setAlarmEnd~!!~!!~!!
D/NightModeInfo( 3714): [Nightmode] currentHour > 6
D/NightModeInfo( 3714): [Nightmode] currentHour > 6
I/NightModeInfo( 3714): JW getEndTime201512080600
D/NightModeInfo( 3714): [Nightmode] currentHour > 6
I/NightModeInfo( 3714): getStartTime201512080000
D/NightModeInfo( 3714): [Nightmode] currentHour > 6
I/NightModeInfo( 3714): getEndTime201512080600
D/jw      ( 3714): Only VZW Supported end return
,I/ActivityManager(  880): Killing 3399:com.google.android.onetimeinitializer/u0a8 (adj 15): empty #11
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_3399/cgroup.procs: No such file or directory
,V/DownloadManager( 3187): Received broadcast intent for android.intent.action.BOOT_COMPLETED
V/DownloadManager( 3187): DownloadService onCreate
I/DownloadManager( 3187): in removeSpuriousFiles
V/DownloadManager( 3187): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/NotificationManager( 3187): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3187): created cursor android.database.sqlite.SQLiteCursor@effae9 on behalf of 3187
V/DownloadManager( 3187): DownloadService onStartCommand
V/DownloadManager( 3187): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3187): created cursor android.database.sqlite.SQLiteCursor@10b8aa9c on behalf of 3187
D/MediaScannerReceiver( 3187): [MediaScanner] ACTION_BOOT_COMPLETED scan INTERNAL_VOLUME, EXTERNAL_VOLUME
I/DownloadManager( 3187): in trimDatabase
V/DownloadManager( 3187): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3187): created cursor android.database.sqlite.SQLiteCursor@33445ca5 on behalf of 3187
,W/jxcore-log( 3600): Platform android
W/jxcore-log( 3600): 
W/jxcore-log( 3600): Process ARCH arm
W/jxcore-log( 3600): 
D/MediaScannerService( 3187): [MediaScanner] start scanning volume internal: [/system/media, /oem/media, /cust/OPEN_EU/media]
V/LGMediaProvider( 3187): insertInternal: content://media/none/media_scanner, initValues=volume=internal
,D/MediaScannerService( 3187): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///system/media
I/MusicBrowser( 2700): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 }}
I/MusicBrowser( 2700): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/WiseScreenService( 1853): [OnBootReceiver.java:24:onReceive()] iKeepScreenOn: 0
,D/MusicBrowser( 2700): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
D/WiseScreenService( 1853): [OnBootReceiver.java:28:onReceive()] iSmartVideo: 0
D/MtpService( 3187): updating state; isCurrentUser=true, mMtpLocked=false
W/ContextImpl( 1853): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.lge.keepscreenon.OnBootReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
D/MtpService( 3187): addStorageLocked 65537 /storage/emulated/0
,E/MtpStorageEx( 3187): setAccessCapability false
D/MediaScannerEx( 3187): [MediaScanner] scanDirectories()[0] = /system/media
D/MediaScannerEx( 3187): [MediaScanner] scanDirectories()[1] = /oem/media
D/MediaScannerEx( 3187): [MediaScanner] scanDirectories()[2] = /cust/OPEN_EU/media
,I/jxcore-log( 3600): JXcore Cordova bridge is ready!
I/jxcore-log( 3600): 
,W/jxcore-log( 3600): JXcore engine is started
I/ActivityManager(  880): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=3765 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,E/jxcore-log( 3600): >> LGE-LG-D722
E/jxcore-log( 3600): 
,I/jxcore-log( 3600): Total memory 906309632
I/jxcore-log( 3600): 
I/jxcore-log( 3600): Free memory 22474752
I/jxcore-log( 3600): 
I/jxcore-log( 3600): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3600): 
I/jxcore-log( 3600): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3600): 
D/MtpService( 3187): updating state; isCurrentUser=true, mMtpLocked=false
I/jxcore-log( 3600): userPath [ 'www' ]
I/jxcore-log( 3600): 
I/jxcore-log( 3600): Size 720 1196
I/jxcore-log( 3600): 
,I/jxcore-log( 3600): Screen Brightness 255
I/jxcore-log( 3600): 
E/jxcore-log( 3600): Dummy Error Log.
E/jxcore-log( 3600): 
I/art     ( 3187): Thread[1,tid=3187,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/MediaProfilesEx-JNI( 3187): register_com_lge_media_MediaProfilesEx
E/MediaRecorderEx-JNI( 3187): register_com_lge_media_MediaRecorderEx
D/AudioSystemEx( 3187): register_com_lge_media_LGAudioSystem
E/SurfaceControlEx( 3187): register_com_lge_view_SurfaceControlEx
,I/art     ( 3187): Thread[1,tid=3187,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/LGMtpDatabaseJNI( 3187): register_android_mtp_LGMtpDatabase
D/LGMtpServerJNI( 3187): register_android_mtp_LGMtpServer
I/art     ( 3187): Thread[1,tid=3187,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/MediaPlayerEx-jni( 3187): register_com_lge_view_MediaPlayerEx
I/art     ( 3187): Thread[1,tid=3187,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/        ( 3187): register_com_lge_emoji_EmojiUtil
E/LGMtpDatabaseJNI( 3187): android_mtp_LGMtpDatabase_setup
D/MtpService( 3187): starting MTP server in PTP mode
D/LGMtpServer( 3187): LGMtpServer
D/LGMtpServerJNI( 3187): android_mtp_LGMtpServer_setup
,D/MtpService( 3187): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 3187): setAccessCapability false
D/MtpServerEx( 3187): ANR FIX - addStorage!
D/LGMtpServerJNI( 3187): android_mtp_LGMtpServer_run
V/DownloadManager( 3187): DownloadService onDestroy
,V/MediaScannerClient( 3187): [MediaScanner]setLocale: = en_US
,E/MediaFileEx( 3187): Duplicate type = AVI
E/MediaFileEx( 3187): Duplicate type = ASF
,V/MediaScannerClient( 3187): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3187): Error opening directory '/oem/media/', skipping: No such file or directory.
V/MediaScannerClient( 3187): [MediaScanner]setLocale: = en_US
,W/MediaScanner( 3187): Error opening directory '/cust/OPEN_EU/media/', skipping: No such file or directory.
D/LGMediaProvider( 3187): [MediaScanner] delete() uri = content://media/internal/file
D/LGMediaProvider( 3187): [MediaScanner] delete() completed notifyChange, uri = content://media/internal
V/MediaScannerEx( 3187): [MediaScanner] isInternalStorage : true
V/MediaScannerEx( 3187): [MediaScanner] isInternalStorage : true
V/MediaScannerEx( 3187): [MediaScanner] isInternalStorage : true
I/VRBookmarkProvider( 3765): [BookmarkProvider.java:76:<init>()-[Thread:Other] BookmarkProvider
I/VRBookmarkProvider( 3765): [BookmarkProvider.java:254:onCreate()-[Thread:Other] onCreate
D/MediaScanner( 3187): [MediaScanner] prescan time: 154ms
D/MediaScanner( 3187): [MediaScanner] scan time: 28ms
D/MediaScanner( 3187): [MediaScanner] postscan time: 7ms
D/MediaScanner( 3187): [MediaScanner] total time: 189ms
D/LGMediaProvider( 3187): [MediaScanner] delete() uri = content://media/none/media_scanner
I/VRBookmarkProvider( 3765): [BookmarkProvider.java:504:registerObservers()-[Thread:Other] registerObservers : content://media/external/audio/media
,D/VRBootCompletedReceiver( 3765): [BootCompletedReceiver.java:25:onReceive()-[Thread:Other] Controller has been started on Boot complete
D/VRBootCompletedReceiver( 3765): [BootCompletedReceiver.java:47:onReceive()-[Thread:Other] Voice Recorder launcher enable(1)/disable(2) : 1
I/ActivityManager(  880): Killing 3419:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
D/MediaScannerService( 3187): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///system/media
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_3419/cgroup.procs: No such file or directory
D/LGMediaProvider( 3187): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///system/media, path = /system/media
I/MusicBrowser( 2700): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 }}
D/MediaScannerService( 3187): [MediaScanner] done scanning volume internal
I/MusicBrowser( 2700): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MediaScannerService( 3187): [MediaScanner] start scanning volume external: [/storage/emulated/0, /storage/external_SD]
,D/MusicBrowser( 2700): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
V/LGMediaProvider( 3187): insertInternal: content://media/none/media_scanner, initValues=volume=external
D/MediaScannerService( 3187): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///storage/emulated/0
V/LGMediaProvider( 3187): insertInternal: content://media/, initValues=name=external
I/MusicWidget( 2653): _mediaDataObserver onChange()
D/MediaScannerEx( 3187): [MediaScanner] scanDirectories()[0] = /storage/emulated/0
D/MediaScannerEx( 3187): [MediaScanner] scanDirectories()[1] = /storage/external_SD
W/VRBookmarkProvider( 3765): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/
,I/MusicWidget( 2653): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
,D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2700): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2700): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
,D/MusicBrowser( 2700): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2700): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2700): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicBrowser( 2700): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2700): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2653): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicWidget( 2653): beingMusicWidget_4x2() result::false
I/MusicWidget( 2653): beingMusicWidget_Quick() result::false
,I/MusicWidget( 2653): beingMusicWidget_4x1() result::true
D/LGBootCompleteReceiver( 1782): onReceive : android.intent.action.BOOT_COMPLETED
D/ConfigUtils( 1782): setUsimOperator() : card operator = 
D/ConfigUtils( 1782): setUsimOperator() : result = null
D/MusicBrowser( 2700): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
I/MusicWidget( 2653): send mDelayedStopHandler
I/MusicWidget( 2653): performViewUpdater handleMessage() msg.what::3
D/MusicBrowser( 2700): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2700): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/ConfigUtils( 1782): setUsimOperator() : simOperator = 
D/ConfigUtils( 1782): setUsimOperator() : usimoperator = 0
D/MusicBrowser( 2700): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicWidget( 2653): beingMusicWidget_Quick() result::false
D/ConfigUtils( 1782): setSupportedUsimMobilityForVoLTE() : false
I/MusicBrowser( 2700): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2700): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2700): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2700): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2653): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicWidget( 2653): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2700): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicWidget( 2653): beingMusicWidget_Quick() result::false
I/MusicWidget( 2653): beingMusicWidget_4x1() result::true
I/MusicWidget( 2653): send mDelayedStopHandler
I/MusicWidget( 2653): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2653): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2700): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2700): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,D/ConfigUtils( 1782): This Model Voice Clarity Support : false
I/MusicBrowser( 2700): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
D/MusicBrowser( 2700): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
,I/MusicBrowser( 2700): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
I/MusicBrowser( 2700): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2700): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2700): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2700): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
D/LGBootCompleteReceiver( 1782): onReceive : updateCallrejectNotify rejectCallOption : 1
I/MusicBrowser( 2700): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 2700): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
I/MusicBrowser( 2700): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
D/MusicBrowser( 2700): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
D/CallRejectInfoToNotify( 1782): update : tPhoneMode : false
I/NotificationManager( 1782): com.android.phone: cancel(2131493582) by com.android.phone
,W/MusicBrowser( 2700): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2700): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2700): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2700): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2700): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2700): - End   trace [MusicUtils.query]---------------------------------------------------------------
I/PhoneApp( 1782): saveDefaultRingtoneUriOfOwner = content://media/internal/audio/media/55
V/MediaScannerClient( 3187): [MediaScanner]setLocale: = en_US
,I/ActivityManager(  880): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=3789 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/iu.UploadsManager( 2300): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,I/MusicWidget( 2653): performViewUpdater handleMessage() msg.what::0
I/MusicWidget( 2653): beingMusicWidget_4x1() result::true
I/MusicWidget( 2653): performUpdate()_4x1
I/MusicWidget( 2653): defaultAppWidget()_4x1
I/MusicWidget( 2653): getCurrentTheme : com.lge.launcher2.theme.optimus
,I/MusicWidget( 2653): 4x1_currentTheme :: null
I/MusicWidget( 2653): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2653): setDefaultViewLayoutId()_4x1
I/MusicWidget( 2653): appWidgetViewUpdate()_4x1
I/MusicWidget( 2653): linkButtons()_4x1
,I/MusicWidget( 2653): pushUpdate()_4x1
D/MediaScannerEx( 3187): [MediaScanner] beginFile() path = /storage/emulated/0/QuicksetLite Setup/data
,V/MediaScannerClient( 3187): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3187): Error opening directory '/storage/external_SD/', skipping: Permission denied.
D/LGMediaProvider( 3187): [MediaScanner] delete() uri = content://media/external/file
,I/MusicWidget( 2653): _mediaDataObserver onChange()
W/VRBookmarkProvider( 3765): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/external
W/MusicBrowser( 2700): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/VRBookmarkProvider( 3765): [BookmarkProvider.java:563:onChange()-[Thread:Other] EXTERNAL Change!!
W/MusicBrowser( 2700): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2700): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2700): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2700): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2700): - End   trace [MusicUtils.query]---------------------------------------------------------------
D/LGMediaProvider( 3187): [MediaScanner] delete() completed notifyChange, uri = content://media/external
I/MusicWidget( 2653): beingMusicWidget_4x2() result::false
I/iu.UploadsManager( 2300): End new media; added: 0, uploading: 0, time: 63 ms
I/ActivityManager(  880): Killing 3441:com.lge.email/u0a21 (adj 15): empty #11
V/MediaScanner( 3187): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@2f630cd2
,V/DrmBroadcastReceiver( 3789): Receive ACTION_BOOT_COMPLETED
V/MediaScanner( 3187): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@2f630cd2
D/MediaScanner( 3187): [MediaScanner] prescan time: 82ms
D/MediaScanner( 3187): [MediaScanner] scan time: 146ms
D/MediaScanner( 3187): [MediaScanner] postscan time: 23ms
D/MediaScanner( 3187): [MediaScanner] total time: 251ms
D/LGMediaProvider( 3187): [MediaScanner] delete() uri = content://media/none/media_scanner
D/MediaScannerService( 3187): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///storage/emulated/0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1908): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/MusicWidget( 2653): performViewUpdater handleMessage() msg.what::1
I/art     (  880): Explicit concurrent mark sweep GC freed 17416(825KB) AllocSpace objects, 2(126KB) LOS objects, 33% free, 22MB/33MB, paused 2.538ms total 166.492ms
,I/MusicWidget( 2653): beingMusicWidget_4x2() result::false
E/[LgeWidgetLib]LgeAppWidgetHostView( 1908): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/libprocessgroup(  880): failed to open /acct/uid_10021/pid_3441/cgroup.procs: No such file or directory
V/DrmService( 3789): Service onCreate
I/MusicBrowser( 2700): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 }}
D/DrmService( 3789): Received new request = 4
I/MusicBrowser( 2700): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2700): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
D/DrmServiceHandler( 3789): updateDrmPushNotification() : No notification
,D/DrmService( 3789): Completed !! request = 4
D/DrmService( 3789): Request count = 0
D/LGMediaProvider( 3187): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///storage/emulated/0, path = /storage/emulated/0
,D/MediaScannerService( 3187): [MediaScanner] done scanning volume external
I/ActivityManager(  880): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=3810 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 3600): getBuffer is called!!!!
I/jxcore-log( 3600): 
V/DrmService( 3789): Service onDestroy
,I/ActivityManager(  880): Killing 3482:com.google.android.partnersetup/u0a9 (adj 15): empty #11
I/VRBookmarkProvider( 3765): [BookmarkProvider.java:530:handleMessage()-[Thread:Other] -- syncTable() START --
,I/ActivityManager(  880): Waited long enough for: ServiceRecord{d9b112d u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
,W/libprocessgroup(  880): failed to open /acct/uid_10009/pid_3482/cgroup.procs: No such file or directory
I/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2700): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2700): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2700): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2700): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2700): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
,I/MusicWidget( 2653): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicWidget( 2653): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2700): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2700): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2653): beingMusicWidget_Quick() result::false
I/MusicWidget( 2653): beingMusicWidget_4x1() result::true
I/MusicWidget( 2653): send mDelayedStopHandler
I/MusicWidget( 2653): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2653): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2700): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2700): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2700): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/MusicBrowser( 2700): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2700): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2700): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2700): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2700): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2653): intentReceiver onReceive() action::com.lge.music.metachanged
,I/MusicWidget( 2653): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2700): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicWidget( 2653): beingMusicWidget_Quick() result::false
I/MusicWidget( 2653): beingMusicWidget_4x1() result::true
I/MusicWidget( 2653): send mDelayedStopHandler
I/MusicWidget( 2653): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2653): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2700): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2700): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2700): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2700): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/VRBookmarkProvider( 3765): [BookmarkProvider.java:532:handleMessage()-[Thread:Other] -- syncTable() END --
I/MusicBrowser( 2700): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2700): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2700): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2700): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
I/MusicBrowser( 2700): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
V/CloudHub( 3810): [DATABASE][DBConnection|open] open database
,E/CloudHub( 3810): [DATABASE][DBConnection|getUserId] User id: 0
E/CloudHub( 3810): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
I/MusicWidget( 2653): performViewUpdater handleMessage() msg.what::0
,I/MusicWidget( 2653): beingMusicWidget_4x1() result::true
I/MusicWidget( 2653): performUpdate()_4x1
I/MusicWidget( 2653): defaultAppWidget()_4x1
I/MusicWidget( 2653): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2653): 4x1_currentTheme :: null
I/MusicWidget( 2653): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2653): setDefaultViewLayoutId()_4x1
I/MusicWidget( 2653): appWidgetViewUpdate()_4x1
I/MusicWidget( 2653): linkButtons()_4x1
I/MusicWidget( 2653): pushUpdate()_4x1
V/CloudHub( 3810): [SERVICE][CloudHubReceiver|queryUploadCount] # of contents to upload: 0
,V/DownloadManager( 3187): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3187): created cursor android.database.sqlite.SQLiteCursor@1780a1a3 on behalf of 3810
V/CloudHub( 3810): [SERVICE][CloudHubReceiver|queryDownloadCount] # of contents to download: 0
I/[LgeWidgetLib]LgeAppWidgetHostView( 1908): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1908): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ActivityManager(  880): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=3835 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 3511:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/MusicWidget( 2653): performViewUpdater handleMessage() msg.what::1
,I/MusicWidget( 2653): beingMusicWidget_4x2() result::false
W/libprocessgroup(  880): failed to open /acct/uid_10014/pid_3511/cgroup.procs: No such file or directory
,D/AirTest ( 3835): Set airtest_enable to false
I/ActivityManager(  880): Killing 3561:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  880): failed to open /acct/uid_1000/pid_3561/cgroup.procs: No such file or directory
,V/LGSC    ( 2805): [104] 401
I/ActivityManager(  880): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=3853 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/TARGETVALIDLATION_RECEIVER( 3853): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
D/TARGETVALIDLATION_RECEIVER( 3853): updateFlag = new File(TARGET_FLAG_PATH)
D/TARGETVALIDLATION_RECEIVER( 3853): Do Not display result dialog. it is not used Update Tool!!
,I/ActivityManager(  880): Killing 3580:com.lge.clock/u0a10 (adj 15): empty #11
V/LGSC    ( 1782): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
W/libprocessgroup(  880): failed to open /acct/uid_10010/pid_3580/cgroup.procs: No such file or directory
,W/ContextImpl( 2745): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2663 
,E/AtFwd AutoBoot( 2745): AtFwd Auto Boot Started Successfully
I/GoogleHttpClient( 1996): GMS http client unavailable, use old client
,I/ActivityManager(  880): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=3875 uid=10062 gids={50062, 9997} abi=armeabi-v7a
I/ActivityManager(  880): Waited long enough for: ServiceRecord{241cc9b6 u0 com.lge.sizechangable.weather/.service.WeatherService}
,I/InsertAccount( 3875): The account already exists
,I/ActivityManager(  880): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=3893 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  880): Killing 3627:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
W/libprocessgroup(  880): failed to open /acct/uid_10011/pid_3627/cgroup.procs: No such file or directory
,W/ResourcesManager( 3893): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3893): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/[SMS_AD]( 3893): Intent action: android.intent.action.BOOT_COMPLETED
,I/[SMS_AD]( 3893): Intent action: android.intent.action.BOOT_COMPLETED
I/ActivityManager(  880): Killing 3658:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/InsertAccount( 3875): The account info in contact DB already exists
W/libprocessgroup(  880): failed to open /acct/uid_10011/pid_3658/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2692): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 15:7:38
I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3911 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UpdateThreadPoolManager( 2692): 2 : This is isUpdating : false
I/art     (  306): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 297us total 22.362ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 20.969ms
I/ActivityManager(  880): Killing 3714:com.android.settings/1000 (adj 15): empty #11
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 20.906ms
,W/libprocessgroup(  880): failed to open /acct/uid_1000/pid_3714/cgroup.procs: No such file or directory
,D/Weather_cast( 2692): 2 : set auto-update time : 12/7 18:7
D/WeatherAncestor( 2692): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 15:7:39
D/WeatherService( 2692): 2 : onStartCommand, intent!=null, action: android.intent.action.BOOT_COMPLETED
W/ResourcesManager( 3911): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=3932 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  880): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2692): 2 : Utils getTopActivity com.lge.launcher2 / true
D/CalendarProvider2( 3911): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@745ae27
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/CalendarProvider2( 3911): [getOrCreateCalendarAlarmManager]
D/WeatherService( 2692): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
,D/WeatherService( 2692): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/CalendarProvider2( 3911): Created com.android.providers.calendar.CalendarAlarmManager@35c70e40(com.android.providers.calendar.CalendarProvider2@745ae27)
,I/InsertAccount( 3875): The account info in calendar DB already exists
,I/Process ( 3875): Sending signal. PID: 3875 SIG: 9
I/ActivityManager(  880): Process com.lge.defaultaccount (pid 3875) has died
,I/LockScreenSettings( 3932): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
I/LockScreenSettings( 3932): Received Broadcast : android.intent.action.BOOT_COMPLETED
,I/ActivityManager(  880): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=3952 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BootCompleteReceiver( 3952): hasclipTray = true
,W/ContextImpl( 3952): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
I/ActivityManager(  880): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=3969 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3986 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 3742:com.android.managedprovisioning/u0a111 (adj 15): empty #11
,W/libprocessgroup(  880): failed to open /acct/uid_10111/pid_3742/cgroup.procs: No such file or directory
,V/AlarmManager(  880): ELAPSED_WAKEUP set : Alarm{2e7a8905 type 2 when 54026 com.android.providers.calendar} when 54026
V/AppCleanupService( 3969): registerAlarm
D/AppCleanupService( 3969): noticeInterval = 2678399999
,D/AppCleanupService( 3969): notiDateStr = 2015-12-20 22:35:42
D/AppCleanupService( 3969): noticeStart = 2015-12-20 22:35:42
D/AppCleanupService( 3969): noticeStart = 1450647342000
D/sensors_hal_Time(  880): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  880): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  880): tsOffsetIs: Apps: 54067765869; DSPS: 1870200; Offset : -3010556004
,D/AppUsageDbAdapter( 3969): initPreloadedAppToTheDB() : row count = 131
E/UpdateRequestReceiver( 3986): ignoring update request
,E/UpdateRequestReceiver( 3986): ignoring update request
E/UpdateRequestReceiver( 3986): ignoring update request
E/UpdateRequestReceiver( 3986): ignoring update request
,E/UpdateRequestReceiver( 3986): ignoring update request
E/UpdateRequestReceiver( 3986): ignoring update request
I/ActivityManager(  880): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4017 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 3765:com.lge.voicerecorder/u0a34 (adj 15): empty #11
W/libprocessgroup(  880): failed to open /acct/uid_10034/pid_3765/cgroup.procs: No such file or directory
,D/SIMObserver( 4017): action:android.intent.action.BOOT_COMPLETED
D/SIMObserver( 4017): handle ACTION_BOOT_COMPLETED
,I/ActivityManager(  880): Killing 2300:com.google.android.gms/u0a6 (adj 15): empty #11
,W/libprocessgroup(  880): failed to open /acct/uid_10006/pid_2300/cgroup.procs: No such file or directory
,E/QcrilMsgTunnelAutoboot( 2324): Received Intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot (has extras) } canStartService = false
D/PhoneInterfaceManager( 1782): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/PhoneInterfaceManager( 1782): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/ActivityManager(  880): Start proc com.google.android.gms for broadcast com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver: pid=4035 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 4035): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4035): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 4035): VM with version 2.1.0 has multidex support
I/MultiDex( 4035): install
I/MultiDex( 4035): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4035): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 4035): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4035): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31372a18: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4035): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 4035): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 4035): com.google.android.gms: cancel(39789) by com.google.android.gms
W/InstanceID/Rpc( 4035): Found 10006
,D/NativeLibraryUtils( 4035): Install completed successfully. count=13 extracted=0
D/FileApkUtils( 4035): Spent 133ms computing apk sha1.
,D/FileApkUtils( 4035): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 4035): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 4035): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 4035): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
W/art     ( 4035): Suspending all threads took: 8.502ms
,D/GmsModuleFndr( 4035): Beginning GMS chimera module scan
,D/GCM     ( 4035): COMPAT: Multi user not supported
,D/GCM     ( 1996): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 4035): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1764): DispatchingService.onCreate()
,I/CheckinService( 4035): Checkin interval check for package: unspecified last checkin: 1449484456781 min interval config: 0 actual interval: 12804022
,D/GmsModuleFndr( 4035): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 4035): Beginning module configuration check
D/ChimeraCfgMgr( 4035): Module APKs unchanged, check complete
I/CheckinService( 4035): Disabling old GoogleServicesFramework version
I/art     ( 4035): CheckpointMarkThreadRoots callback created = 0xb04a4520
,D/SystemUpdateService( 4035): onCreate
I/art     ( 4035): CheckpointMarkThreadRoots callback created = 0xb04a4510
I/GCoreUlr( 1764): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/SystemUpdateService( 4035): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
V/AuthZen ( 4035): Handling intent: android.intent.action.BOOT_COMPLETED
,W/art     ( 4035): Suspending all threads took: 7.474ms
,V/GLSActivity( 1996): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1996): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AuthZenEventHandler( 4035): Handling event: android.intent.action.BOOT_COMPLETED
,I/art     ( 4035): Background partial concurrent mark sweep GC freed 15176(1104KB) AllocSpace objects, 10(160KB) LOS objects, 40% free, 10MB/16MB, paused 21.652ms total 102.459ms
I/SystemUpdateService( 4035): cancelUpdate (empty URL)
I/SystemUpdateService( 4035): active receiver: disabled
,I/art     ( 4035): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 4035): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/NotificationManager( 4035): com.google.android.gms: cancel(2130838130) by com.google.android.gms
I/NotificationManager( 4035): com.google.android.gms: cancel(2130838131) by com.google.android.gms
,I/CheckinService( 4035): Checking schedule, now: 1449497260979 next: 1450011705706
I/CheckinService( 4035): active receiver: disabled
,I/GCoreUlr( 1764): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1764): Unbound from all location providers
,I/art     ( 1996): Explicit concurrent mark sweep GC freed 4449(248KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 999us total 60.235ms
,W/BaseAppContext( 4035): Using Auth Proxy for data requests.
D/ChimeraCfgMgr( 4035): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GCoreUlr( 1764): DispatchingService.onDestroy()
I/GCoreUlr( 1764): Stopping handler for UlrDispSvcFast
,D/ChimeraCfgMgr( 4035): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 4035): onDestroy
I/AuthZen ( 4035): Fetching signing key...
,W/GCoreFlp( 1764): No location to return for getLastLocation()
W/FusedLocationProvider( 4035): location=null
I/NotificationManager( 4035): com.google.android.gms: cancel(10436) by com.google.android.gms
V/GLSActivity( 1996): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1996): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1764): No location to return for getLastLocation()
W/FusedLocationProvider( 4035): location=null
W/Kids    ( 4035): [AbstractKidsOperation] Invalid device state 3
,I/AuthZen ( 4035): Signing key fetched successfully!
I/Kids    ( 4035): [KidAccountFixer] No network connection
W/BaseAppContext( 4035): Using Auth Proxy for data requests.
D/a       ( 4035): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 4035): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 4035): Clearing transaction cache
I/art     (  880): Explicit concurrent mark sweep GC freed 17427(869KB) AllocSpace objects, 6(190KB) LOS objects, 33% free, 22MB/33MB, paused 1.824ms total 171.583ms
,I/GCoreUlr( 1764): Unbound from all location providers
W/Auth    ( 1996): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1996): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 4035): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
D/PersistentNotificationBroadcastReceiver( 1996): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4122 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 4122): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 4122): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4122): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4122): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4122): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4122): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4122): MmsConfig.loadFromResources
E/Babel_SMS( 4122): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4122): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 4122): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4122): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4122): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4122): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 4122): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4122): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4122): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4122): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4122): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4122): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4122): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4122): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4122): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4122): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4122): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4122): found sensor: Motion Accel, handle=46
W/Settings( 4122): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4122): startup - clean
I/art     ( 4122): CheckpointMarkThreadRoots callback created = 0xb042d870
I/art     ( 4122): CheckpointMarkThreadRoots callback created = 0xb042d850
,I/Babel   ( 4122): deleted: false for 0
,W/AudioCapabilities( 4122): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4122): Unsupported mime audio/adpcm
W/AudioCapabilities( 4122): Unsupported mime audio/g726
W/AudioCapabilities( 4122): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4122): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4122): Unsupported mime video/mjpg
W/VideoCapabilities( 4122): Unsupported mime video/theora
,W/AudioCapabilities( 4122): Unsupported mime audio/evrc
,W/AudioCapabilities( 4122): Unsupported mime audio/qcelp
W/VideoCapabilities( 4122): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4122): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4122): Unsupported mime audio/qcelp
W/AudioCapabilities( 4122): Unsupported mime audio/evrc
,W/VideoCapabilities( 4122): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 4122): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4122): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4122): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4122): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4122): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4122): onServiceConnected
,W/Babel   ( 4122): Attempted to change video mute state without an active call.
I/NotificationManager( 4122): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  880): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4159 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 3789:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  880): failed to open /acct/uid_10051/pid_3789/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  880): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  880): Message: 2
D/WifiServiceImplEx(  880): setWifiEnabled: false pid=3600, uid=10030, package= com.example.hello, App Lable : HelloWorld
,D/WifiService(  880): setWifiEnabled: false pid=3600, uid=10030
I/jxcore-log( 3600): ****TEST TOOK:  5066  ms ****
I/jxcore-log( 3600): 
I/jxcore-log( 3600): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3600): 
W/ResourcesManager( 4159): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4159): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4159): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 4159): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4159): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 4159): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4159): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AndroidRuntime( 4185): 
D/AndroidRuntime( 4185): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/art     ( 4159): CheckpointMarkThreadRoots callback created = 0xb042dbe0
D/AndroidRuntime( 4185): CheckJNI is OFF
,E/YouTube MDX( 4159): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/art     ( 4159): CheckpointMarkThreadRoots callback created = 0xb4958de0
,D/libc-netbsd( 4159): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4159): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
I/dex2oat ( 4202): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads146245933.jar --oat-fd=25 --oat-location=/data/data/com.google.android.youtube/cache/ads146245933.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ContextImpl( 4159): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/dex2oat ( 4202): dex2oat took 93.214ms (threads: 4)
,W/CursorWrapperInner( 3810): Cursor finalized without prior close()
,D/AndroidRuntime( 4185): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  880): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 3600:com.example.hello/u0a30 (adj 0): stop com.example.hello
I/WindowState(  880): WIN DEATH: Window{30dccdbb u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  880): Focus left window: Window{30dccdbb u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  880): Window went away: Window{30dccdbb u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  880): Skipping PackageSetting{2cae52c6 com.test.thalitest/10316} due to missing metadata
,W/ActivityManager(  880): Force removing ActivityRecord{2a08fbc7 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  880): Spurious death for ProcessRecord{36309c72 3600:com.example.hello/u0a30}, curProc for 3600: null
,I/ActivityManager(  880): Force stopping com.example.hello appid=10030 user=0: pkg removed
,D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/QCNEJ   ( 1870): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3465): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/GeofencerStateMachine( 1764): Ignoring removeGeofence because network location is disabled.
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 1908): [Launcher.java:5203:onStart()]onStart
I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_REMOVED
,W/System.err( 3465): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3465): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3465): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3465): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3465): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3465): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3465): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3465): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3465): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3465): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3465): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,I/[LGHome]EVENT( 1908): [Launcher.java:776:onResume()]onResume
D/administrator(  880): Handling package changes for user 0
,D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/art     ( 1817): CheckpointMarkThreadRoots callback created = 0xaaf1eb60
I/[LGHome]LGActivityUtil( 1908): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1908): [Launcher.java:929:onResume()]onResume end
I/Activity( 1908): Activity.onPostResume() called 
I/NotificationManager( 4159): com.google.android.youtube: cancel(2) by com.google.android.youtube
,D/KeyguardModel( 1370): handleShortcutListChanged...
,D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/SystemUI[Framework](  880): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  880): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  880): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  880): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  880): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3dc7825,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  880): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/art     ( 1817): CheckpointMarkThreadRoots callback created = 0xaaf481e0
D/InputDispatcher(  880): Focus entered window: Window{342d37b5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1370): createShortcutInfo...
,W/[LGHome]LGWallpaperInfo( 1908): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1908): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1370): createShortcutInfo...
I/[LGHome]EVENT( 1908): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1908): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1908): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1908): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1908): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1370): handleShortcutListChanged...
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4159): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4159): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4159): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4159): Found 10006
,W/InputMethodManagerService(  880): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  880): Got RemoteException sending setActive(false) notification to pid 3600 uid 10030
I/NotificationService(  880): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/SystemUI[Framework](  880): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  880): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  880): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  880): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  880): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3dc7825,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  880): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/Timeline( 1908): Timeline: Activity_idle id: android.os.BinderProxy@3b74ce2e time:58355
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4159): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,D/TaskPersister(  880): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1370): draw background and invalidate : color = ee000000
I/HotwordRecognitionRnr( 1966): Starting hotword detection.
,D/BarTransitions( 1370): draw background and invalidate : color = ebe2e2e2
I/MicrophoneInputStream( 1966): mic_starting com.google.android.apps.gsa.speech.audio.u@217fb7ab
V/AudioRecord( 1966): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1966): set(): mSessionId 22
V/AudioPolicyManager(  282): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  282): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  282): isPlaybackThread 0,isRecordThread 1
,D/audio_hw_primary(  282): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb40365c0)
V/audio_hw_primary(  282): adev_open_input_stream: exit
V/AudioFlinger(  282): openInput_l() openInputStream returned input 0xb40365c0, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  282): openInput_l() created record thread: ID 23 thread 0xb4303000
V/AudioSystem(  282): ioConfigChanged() event 3, ioHandle 23
I/AudioFlinger(  282): AudioFlinger's thread 0xb4303000 ready to run
D/audio_hw_primary(  282): in_standby: enter: stream (0xb40365c0) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb40365c0) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioSystem(  880): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioSystem( 1782): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioSystem( 1966): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioSystem( 2700): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioSystem( 1370): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 3165): ioConfigChanged() event 3, ioHandle 23
V/AudioFlinger(  282): openRecord() lSessionId: 22 input 23
,V/AudioFlinger(  282): getOrphanEffectChain_l session 22 index -2
V/AudioFlinger(  282): acquiring 22 from 1966, for -1
V/AudioFlinger(  282):  added new entry for 22
V/AudioRecord( 1966): start, sync event 0 trigger session 0
V/AudioRecord( 1966): mAudioRecord->start()
V/AudioFlinger(  282): RecordHandle::start()
V/AudioFlinger(  282): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  282): startInput() module primary->input primary(23)
V/AudioPolicyManager(  282): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  282): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  282): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  282): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  282): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  282): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  282): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  282): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  282): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb4303000
V/AudioFlinger::PatchPanel(  282): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  282): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  282): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  282): setParameters(): io 23, keyvalue hotword_active=1, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=1
,V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb4303000
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1966): mic_started com.google.android.apps.gsa.speech.audio.u@217fb7ab
V/msm8974_platform(  282): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  282): start_input_stream: enter: stream(0xb40365c0)usecase(7: audio-record)
V/voice   (  282): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  282): start_input_stream: usecase(7)
E/audio_hw_primary(  282): select_devices: enter and usecase(7)
V/msm8974_platform(  282): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  282): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  282): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  282): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  282): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  282): enable_snd_device: enter  144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  282): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  282): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  282): ACDB -> send_adm_topology
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  282): ACDB -> send_asm_topology
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  282): ACDB -> send_audtable
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  282): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  282): ACDB -> send_audvoltable
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  282): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  282): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  282): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  282): ACDB -> AUDIO_SET_AFE_CAL
,V/audio_hw_primary(  282): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  282): enable_audio_route: exit
D/audio_hw_primary(  282): select_devices: done
V/audio_hw_primary(  282): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  282): start_input_stream: exit
,I/HotwordWorker( 1966): onReady
,I/art     (  880): Explicit concurrent mark sweep GC freed 19955(1288KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 22MB/34MB, paused 3.552ms total 500.627ms
I/Timeline(  880): Timeline: Activity_windows_visible id: ActivityRecord{1daddf42 u0 com.lge.launcher2/.Launcher t219} time:58617
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/AndroidRuntime( 4185): Shutting down VM
,W/ResourcesManager(  880): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  880): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4274 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LCardEmulationManager( 1817): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1817): getDefaultRoute
,I/NotificationManager( 4159): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,W/ResourceType(  880): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1908): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/ActivityManager(  880): Killing 3810:com.lge.cloudhub/u0a49 (adj 15): empty #11
,W/libprocessgroup(  880): failed to open /acct/uid_10049/pid_3810/cgroup.procs: No such file or directory
,W/ActivityManager(  880): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4274): getAccountsCursor
,V/GLSActivity( 1996): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4274): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.

```
