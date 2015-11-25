#### Test 503880196dc97cd_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/LGDMClient( 3789): [DmAgent.java] [<init>()] : [164] : DmAgent is started -> DmConstants.DMAgentState.mDmaState = 0
I/LGDMClient( 3789): [DmCAConfigParser.java] [getInstance()] : [73] : DmsCAConfigParser sInstance null
D/LGDMClient( 3789): [DmClientController.java] [run()] : [178] : LooperSTART
D/LGDMClient( 3789): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [204] : Current MultiSimEnabled is false
D/LGDMClient( 3789): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [239] : getPhoneSpecificInfo: sim mccmnc(),spn(),gid(null),imsi(null)
I/LGDMClient( 3789): [DmCAConfigParser.java] [parse()] : [108] : parse
D/LGDMClient( 3789): [DmCAConfigParser.java] [setDefaultProfile()] : [490] : setDefaultProfile
D/LGDMClient( 3789): [DmCAConfigParser.java] [setDefaultProfile()] : [493] : filename : fota_dm_settings.xml
D/LGDMClient( 3789): [DmCAConfigParser.java] [setDefaultProfile()] : [506] : [UI4.1] Search [fota_dm_settings.xml]
D/LGDMClient( 3789): [DmCAConfigParser.java] [parse()] : [134] : [UI4.1] Search [fota_dm_settings.xml]
D/LGDMClient( 3789): [DmAgentUtil.java] [setAutoAgentSchedule()] : [117] : IN setAutoAgentSchedule()
D/ALBootInit( 3814): ====action==>android.intent.action.BOOT_COMPLETED
D/ALBootInit( 3814): Alarm ALBootInit: BOOT_COMPLETED
,D/LGDMClient( 3789): [DmAgentUtil.java] [setAutoAgentSchedule()] : [126] :  cursor != null setAutoAgentSchedule()
I/ALProvider( 3814): delete where======= time <= 1448460671468  and  aindex > 0
D/LGDMClient( 3789): [DmAgentUtil.java] [setAutoAgentSchedule()] : [167] : SET ALARM setAutoAgentSchedule() = 20151126T212428
D/LGDMClient( 3789): [DmAgentUtil.java] [setAutoAgentSchedule()] : [185] : OUT setAutoAgentSchedule()
D/LGDMClient( 3789): [DmAgent.java] [checkPostponed()] : [2062] : DMAGentState is: DmConstants.DMAgentState.mDmaState = 0
V/LGDMClient( 3789): [DmClientController.java] [handleMessage()] : [181] : DmClientController: run() - msg.what=31
D/LGDMClient( 3789): [DmAgent.java] [processRestartHandler()] : [1241] : DMAGentState is: DmConstants.DMAgentState.mDmaState = 0
E/LGDMClient( 3789): [DmDownloadService.java] [onCreate()] : [56] : DmDownloadService.onCreate()
D/LGDMClient( 3789): [DmDownloadService.java] [onStartCommand()] : [92] : DmDownloadService.onStartCommand()
D/LGDMClient( 3789): [DmDownloadService.java] [handleStart()] : [103] : DmDownloadService  intend : Intent { cmp=com.lge.lgdmsclient/.service.DmDownloadService }
D/Alarms  ( 3814):  --- disableExpiredAlarms!!! isBooting : true
E/[LGE_FOTA] ( 3789): FOTA JNI_OnLoad
E/[LGE_FOTA] ( 3789):  FOTAJNI_GetUAResult in
E/[LGE_FOTA] ( 3789): FOTAFS_Open /cache/fota/usd.dat, 0, handle : 1c
E/[LGE_FOTA] ( 3789): enUpdateState                : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.enState             : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[0]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[0]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[1]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[1]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[2]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[2]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[3]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[3]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[4]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[4]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[5]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[5]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[6]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[6]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[7]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[7]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[8]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[8]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[9]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[9]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[10]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[10]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[11]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[11]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[12]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[12]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[13]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[13]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[14]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[14]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgOffset[15]     : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiPkgSize[15]       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiCurrSection       : 0x00000000
E/[LGE_FOTA] ( 3789): stFWInfo.uiResult            : 0x00000000
E/[LGE_FOTA] ( 3789): stFSInfo.enState             : 0x00000000
E/[LGE_FOTA] ( 3789): stFSInfo.uiFilePackageOffset : 0xa0a297d4
E/[LGE_FOTA] ( 3789): stFSInfo.uiFilePackageSize   : 0xa0a297f4
E/[LGE_FOTA] ( 3789): stFSInfo.uiResult            : 0x00000000
E/[LGE_FOTA] ( 3789): stPkgInfo.enPackageType      : 0x00000000
E/[LGE_FOTA] ( 3789): stPkgInfo.uiSize             : 0x00000000
E/[LGE_FOTA] ( 3789): stPkgInfo.uiWrittenAddr      : 0x00000000
E/[LGE_FOTA] ( 3789): stPkgInfo.uiWrittenSize      : 0x00000000
E/[LGE_FOTA] ( 3789): stPkgInfo.szPackagePath      : 
E/[LGE_FOTA] ( 3789): stCommand.enCommand	 		: 0x00000000
E/[LGE_FOTA] ( 3789): uiBackupBufferAddr			: 0x00000000
E/[LGE_FOTA] ( 3789): uiLanguage					: 0x00000000
E/[LGE_FOTA] ( 3789): stDebug.uiResetCount			: 0x00000000
E/[LGE_FOTA] ( 3789): stDebug.uiRetryCount			: 0x00000000
E/[LGE_FOTA] ( 3789): FOTAFS_Close 1c
E/[LGE_FOTA] ( 3789): FOTAJNI_GetConvertedUAResult : 450
E/[LGE_FOTA] ( 3789): FOTAJNI_GetUAResult : 450
D/LGDMClient( 3789): [SwUpdate.java] [getSwUpdateStatus()] : [244] : Software update result:450
D/Alarms  ( 3814): count ===>0
D/LGDMClient( 3789): [DmAgent.java] [restartIdleSession()] : [1084] : skymymy is: iSwUpdateStatus = 450, isUpgradedByLGUP() = false
D/LGDMClient( 3789): [DmAgent.java] [clearContext()] : [1774] : [Enter] clearContext
D/Alarms  ( 3814): snoozeActivating scount==>0
D/Alarms  ( 3814): [setNextAlert] start
I/LGDMClient( 3789): [DmAgent.java] [setState()] : [1875] : Setting Agent State and State is : DmConstants.DMAgentState.mDmaState = 0
D/LGDMClient( 3789): [DmAgent.java] [clearContext()] : [1791] : [Exit] clearContext
V/LGDMClient( 3789): [DmClientController.java] [handleMessage()] : [181] : DmClientController: run() - msg.what=33
D/LGDMClient( 3789): [DmClientController.java] [stopService()] : [408] : stopDownloadService(), DownloadService will be stopped in order to follow the end of DmClientController
--------- beginning of system
W/ContextImpl( 3789): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 com.lge.lgdmsclient.dmclient.controller.DmClientController.stopService:412 com.lge.lgdmsclient.dmclient.controller.DmClientController.clearController:383 com.lge.lgdmsclient.dmclient.controller.DmClientController.access$200:68 
D/LGDMClient( 3789): [DmDownloadService.java] [onDestroy()] : [117] : DmDownloadService.onDestroy()
I/ActivityManager(  985): Killing 3535:com.google.android.onetimeinitializer/u0a8 (adj 15): empty #11
W/libprocessgroup(  985): failed to open /acct/uid_10008/pid_3535/cgroup.procs: No such file or directory
I/art     (  985): Explicit concurrent mark sweep GC freed 15619(689KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.263ms total 155.934ms
D/Alarms  ( 3814): [setNextAlert] (1)
D/Alarms  ( 3814):  minTime  = 0
D/Alarms  ( 3814):  -- OK multi -- 0
E/jeny.kim( 3814): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 3814): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 3814): BUILD Operator: OPEN
D/Alarms  ( 3814): broadcastToWidgetProvider : false
D/Alarms  ( 3814): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider(  985): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
D/CommonUtil( 3814): Enter deleteUnnecessaryToneItem() enter excepted tone uri value is null, preferparent value is  ALARM
D/CommonUtil( 3814): deleteUnnecessaryToneItem() -> Alarm Surviv Count is 0
D/CommonUtil( 3814): Exit deleteUnnecessaryToneItem()
I/CommonUtil( 3814): BUILD Country: EU
I/TimerReceiver( 3814): onReceiveIntent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.lge.clock/.timer.TimerReceiver (has extras) }
D/TimerReceiver( 3814): onReceive() : android.intent.action.BOOT_COMPLETED
I/TimerReceiver( 3814): setTimerDone
D/TimerObj( 3814): --------------------- getTimersFromSharedPrefs
V/TimerObj( 3814): --------------------- timers list is empty
I/ActivityManager(  985): Start proc com.lge.appbox.client:SingleBinaryService for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver: pid=3844 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  985): Killing 3475:com.android.gallery3d/u0a23 (adj 15): empty #11
D/AndroidRuntime( 3838): 
D/AndroidRuntime( 3838): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3838): CheckJNI is OFF
W/libprocessgroup(  985): failed to open /acct/uid_10023/pid_3475/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 3844): AppBoxApplication onCreate()
D/AppUp4:SingleBinary( 3844): /cust/OPEN_EU/config/app-enabled-conf.json is selected!!
D/AppUp4:SingleBinary( 3844):  Starting isFingerChanged 
I/ActivityManager(  985): Start proc com.lge.appbox.client for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider: pid=3874 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/AndroidRuntime( 3838): Calling main entry com.android.commands.am.Am
I/ActivityManager(  985): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  985): setTaskToReturnTo : TaskRecord{1e4363cd #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  985): setTaskToReturnTo : TaskRecord{1e4363cd #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  985): AppWindowTokenEx init.. 
I/CalendarProvider2( 3758): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3758): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/ContextHelper(  985): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  985): Focus left window: Window{b265772 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 3838): Shutting down VM
I/[LGHome]EVENT( 1965): [Launcher.java:986:onPause()]onPause
I/ActivityManager(  985): Killing 3556:com.qualcomm.timeservice/1000 (adj 15): empty #11
D/SplitWindow(  985): check instance of lgWin Window{13c1d9ef u0 Starting com.example.hello}
I/AppUp4:AppBoxCP( 3874): onCreate
W/AppUp4:DB( 3874):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 3874):  setFingerPrint start
I/AppUp4:DB( 3874):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 3874):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 3874):  SDK version = 0
I/AppUp4:DB( 3874):  beforefinger == newfinger no write in DB
W/libprocessgroup(  985): failed to open /acct/uid_1000/pid_3556/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 3874): AppBoxApplication onCreate()
I/ActivityManager(  985): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3904 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AppUp4:SingleBinary( 3844):  The value of isFingerChanged null
I/[LGHome]EVENT( 1965): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/AppUp4:SingleBinary( 3844): Device : jagnm
D/AppUp4:SingleBinary( 3844): First Boot - ignore boot completed
D/AppUp4:NTCodeSingleBinary( 3844): Starting isFingerChanged 
I/HotwordDetector( 2047): Closing mic
I/MicrophoneInputStream( 2047): mic_close com.google.android.apps.gsa.speech.audio.u@33d60520
V/AudioRecord( 2047): stop()
D/AudioRecord( 2047): AudioRecord->stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioFlinger(  283): Record stopped OK
V/AudioPolicyManager(  283): stopInput() input 17
V/AudioPolicyService(  283): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  283): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  283): ThreadBase::setParameters() routing=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
D/AppUp4:NTCodeSingleBinary( 3844): The value of isFingerChanged lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
D/AppUp4:SingleBinary( 3844): Device : jagnm
D/AppUp4:SingleBinary( 3844): Config file is not exist - nothing
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb42a5000
D/audio_hw_primary(  283): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
I/[LGHome]EVENT( 1965): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  985): Starting window displayed
I/SystemUI[Framework](  985): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
D/PhoneStatusBar( 1389): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  985): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  985): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  985): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  985): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@26f2eea5,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  985): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1389): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1389):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1389): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager(  985): Killing 3580:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
D/BarTransitions( 1389): draw background and invalidate : color = e000000
D/BarTransitions( 1389): draw background and invalidate : color = 100f0f0f
V/audio_hw_primary(  283): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  283): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  283): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  283): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  283): disable_audio_route: exit
E/audio_hw_primary(  283): disable_snd_device: enter 144
D/hardware_info(  283): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  283): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  283): stop_input_stream: exit: status(0)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  283): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  283): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  283): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyService(  283): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  283): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  283): setParameters(): io 17, keyvalue hotword_active=0, calling pid 283
V/AudioFlinger(  283): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  283): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  283): in_set_parameters: exit: status(0)
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb42a5000
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioRecord( 2047): stop()
V/AudioRecord( 2047): stop()
V/AudioRecord( 2047): stop()
V/AudioFlinger(  283): RecordHandle::stop()
,V/AudioFlinger(  283): RecordThread::stop
V/AudioPolicyManager(  283): releaseInput() 17
V/AudioPolicyManager(  283): closeInput(17)
V/AudioFlinger(  283): closeInput() 17
V/AudioSystem(  283): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): ThreadBase::exit
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioSystem( 2705): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  985): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): RecordThread 0xb42a5000 exiting
D/audio_hw_primary(  283): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  283): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioPolicyService(  283): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  283): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio port list
V/AudioPolicyManager(  283): releaseInput() exit
V/AudioFlinger(  283): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  283): removeClient_l() pid 2047, calling pid 283
V/AudioSystem( 3208): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1389): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2092): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioSystem( 2047): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1794): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): releasing 16 from 2047 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
I/HotwordRecognitionRnr( 2047): Hotword detection finished
I/HotwordRecognitionRnr( 2047): Stopping hotword detection.
W/libprocessgroup(  985): failed to open /acct/uid_10016/pid_3580/cgroup.procs: No such file or directory
I/AppUp4:SDKReflector( 3874): +myUserId : 0
D/AppUp4:BootUpPollingReceiver( 3874): onReceive on user ID : 0
D/ContextHelper( 3904): convertTheme. context->name=com.example.hello themeResourceId=16973833
V/AppUp4:FotaPlusService( 3874):  isFotaPlusTriedOnce : true
D/AppUp4:BootUpPollingReceiver( 3874): Starting getSdkVersion 
D/AppUp4:BootUpPollingReceiver( 3874): SDK version is : 0
D/AppUp4:BootUpPollingReceiver( 3874): currentSdkVersion : 0
D/AppUp4:BootUpPollingReceiver( 3874): isSdkVersionChanged : true
V/AppUp4:FotaPlusService( 3874):  setFotaPlusCompleted : false
D/AppUp4:BootUpPollingReceiver( 3874): isFotaPlusNeeded : true
D/AppUp4:BootUpPollingReceiver( 3874): Fota Plus already tried once, show notification
V/NotificationService(  985): enqueueNotificationInternal: pkg=com.lge.appbox.client id=22319582 notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
D/AppUp4:BootUpPollingReceiver( 3874): isFotaPlusRunning after : true
D/ZenLog  (  985): intercepted: 0|com.lge.appbox.client|22319582|null|10011,none
D/AppUp4:BootUpPollingReceiver( 3874):  installPreloadedValuePackIfNeeded 
D/AppUp4:BootUpPollingReceiver( 3874):  file is : /system/apps/bootup
D/AppUp4:BootUpPollingReceiver( 3874): file false
V/NotificationService(  985): pkg=com.lge.appbox.client canInterrupt=false intercept=true
I/NotificationServiceEx(  985): LED remove() : mLights=0|com.lge.appbox.client|22319582|null|10011
D/AppUp4:BootUpPollingReceiver( 3874): [BootUpPollingReceiver] No preload installation.
D/NotificationServiceEx(  985): updateLightListLocked :r=0|com.lge.appbox.client|22319582|null|10011, action=2
D/NotificationServiceEx(  985): notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
D/AppUp4:dwnld( 3874): [removeAllIncompletedDownload] ... 
D/SmartCoverUpdateMonitor( 1348): onNotificationPosted() : StatusBarNotification(pkg=com.lge.appbox.client user=UserHandle{0} id=22319582 tag=null score=0 key=0|com.lge.appbox.client|22319582|null|10011: Notification(pri=0 contentView=com.lge.appbox.client/0x1090079 vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE))
D/SmartCoverUpdateMonitor( 1348): onNotificationPosted() !qcn.isEnableToShowNotification()
V/AppUp4:BootUpPollingReceiver( 3874): [BootUpPollingReceiver] start bootup Polling.
D/AppUp4  ( 3874): getUpdatePollingPeriod
D/AppUp4  ( 3874): getUpdatePollingPeriod
D/AppUp4:BackgroundPollingService ( 3874): register polling alarm when : 2015/11/26 21:30:18
D/AppUp4:LightWeightPollingService ( 3874):  [buildRemotePollingIntent]
D/AppUp4:LightWeightPollingService ( 3874): This means remote config is N, so skip it
I/ActivityManager(  985): Killing 3614:com.lge.email/u0a21 (adj 15): empty #11
I/WebViewFactory( 3904): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/libprocessgroup(  985): failed to open /acct/uid_10021/pid_3614/cgroup.procs: No such file or directory
I/[SystemUI]PhoneStatusBar( 1389): updateMediaMetaData(false): mMediaMetadata = null
I/ActivityManager(  985): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3930 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/LibraryLoader( 3904): Time to load native libraries: 7 ms (timestamps 1224-1231)
I/LibraryLoader( 3904): Expected native library version number "",actual native library version number ""
I/ActivityManager(  985): Waited long enough for: ServiceRecord{2a6948eb u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
D/MmsConfig( 3208): isNotAllowedSms: currentUser:0
D/MmsConfig( 3208): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3208): isUserMode:false
D/SmsReceiverService( 3208): handleMessage isUserMode:false
W/ResourcesManager( 3208): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/WebViewChromiumFactoryProvider( 3904): Binding Chromium to main looper Looper (main, tid 1) {1103932b}
I/LibraryLoader( 3904): Expected native library version number "",actual native library version number ""
I/chromium( 3904): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
V/SmsReceiverService( 3208): handleMessage action: android.intent.action.BOOT_COMPLETED error: 0
I/BrowserStartupController( 3904): Initializing chromium process, singleProcess=true
W/ResourcesManager( 3930): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/art     ( 3904): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3904): ApplicationContext is null in ApplicationStatus
W/chromium( 3904): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/CalendarApplication( 3930): CalendarApplication.onCreate()
E/libEGL  ( 3904): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3904): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3904): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3904): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3904): Build Date: 03/02/15 Mon
I/Adreno-EGL( 3904): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 3904): Remote Branch: 
I/Adreno-EGL( 3904): Local Patches: 
I/Adreno-EGL( 3904): Reconstruct Branch: 
D/PreferenceKeysParser( 3930): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 3930): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@49fd99c, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@17055fa5, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@f0c2f7a, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1103932b, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@139ef388, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2c115121, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2a9dc946, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2aa63707, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@23f3c034, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2f90de5d, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3d5d33d2, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2ce53ca3, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3f26aba0, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@9820359, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1936bb1e, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@84ffff, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3cdae1cc, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@9c67c15, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@308f6b2a, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2c339d1b, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@29ba4eb8, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@229fc491, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@5110ff6, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2964eff7, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@31219e64, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@eeb18cd, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@37363582, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2aee9493, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@358c3cd0, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@201d74c9, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@29627ce, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3163e6ef, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3c055fc, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2fff9485, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@32f0f2da, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@932030b, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@cbad5e8, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3229f401, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1dfb62a6, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@e7bc4e7, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@125b6894, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2140cf3d, l
D/GeneralPreferenceUtils( 3930): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 3930): [init]
I/Config  ( 3930): LGCalendar ver.4.40.17
I/Config  ( 3930): start check model
I/Config  ( 3930): start check native_ca
I/Config  ( 3930): Config Operator=OPEN, Country=EU
D/Config  ( 3930): [setDefaultValuesToPref]
D/Config  ( 3930): [parseProfiles]
D/ProfilesParser( 3930): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 3930): [debug_displayParseInfos] profile.operator = null
D/Config  ( 3930): [updateProfiletoCountryInfo]
D/GeneralPreference( 3930): [checkAndMigrateOldPreference]
D/AlertReceiver( 3930): onReceive: a=android.intent.action.BOOT_COMPLETED Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.calendar/.alerts.AlertReceiver (has extras) }
I/InitNotificationRingtoneService( 3930): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3930): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
D/UsbSettingsReceiver( 3636): [AUTORUN] onReceive() : action = android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3636): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3636): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3636): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3636): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/AudioPolicyService(  283): registerClient() client 0xb4027080, uid 10030
I/AlertUtils( 3930): [getCalendarNotiSoundURIFromCursor] getCount()= 21
D/BluetoothManagerService(  985): Message: 20
D/BluetoothManagerService(  985): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1dec86a9:true
D/BluetoothAdapterService(715536135)( 2092): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c67c15
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
D/UsbSettingsControl( 3636): [AUTORUN] setTetherStatus() : status=false
D/UsbSettingsReceiver( 3636): [AUTORUN] onReceive() : android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3636): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3636): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3636): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
D/StoreModeReceiver( 3636): intent.getAction() : android.intent.action.BOOT_COMPLETED
D/StoreModeReceiver( 3636): sim state :null
D/StoreModeReceiver( 3636): Back LED don't supported.
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
V/SettingsProvider(  985): call_put(system:emotional_led_back_led=0) for 0 calling package = com.android.settings
V/SettingsProvider(  985): call_put(system:emotional_led_back_incoming_call=0) for 0 calling package = com.android.settings
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
V/SettingsProvider(  985): call_put(system:emotional_led_back_alarm=0) for 0 calling package = com.android.settings
V/SettingsProvider(  985): call_put(system:emotional_led_back_missed_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  985): call_put(system:emotional_led_back_missed_messages=0) for 0 calling package = com.android.settings
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
V/SettingsProvider(  985): call_put(system:emotional_led_back_missed_emails=0) for 0 calling package = com.android.settings
V/SettingsProvider(  985): call_put(system:emotional_led_back_calendar_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  985): call_put(system:emotional_led_back_voice_recording=0) for 0 calling package = com.android.settings
V/SettingsProvider(  985): call_put(system:emotional_led_back_camera_timer_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  985): call_put(system:emotional_led_back_camera_face_detecting_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  985): call_put(system:notification_light_pulse_back=0) for 0 calling package = com.android.settings
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
D/StoreModeReceiver( 3636): SystemProperty Default brightness value [0-255] : 143
D/StoreModeReceiver( 3636): Default brightness[0-255] : 143
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
W/HolidayIntentService( 3930): onHandleIntent
D/HolidayDataLoader( 3930): readJsonAsset : holiday.json
W/ResourcesManager( 3636): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/AlertUtils( 3930): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
D/StoreModeReceiver( 3636): Default Screen off timeout value : 30000
D/StoreModeReceiver( 3636): SystemProperty Default brightness Mode value[true/false] : false
I/AlertUtils( 3930): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
D/StoreModeReceiver( 3636): BRIGHTNESS_MODE - 0
D/StoreModeReceiver( 3636): Default brightness Mode [0/1] : 0
D/StoreModeReceiver( 3636): Default NIGHT_MODE : 0
D/StoreModeReceiver( 3636): Set MaxBrightness : 255
I/AlertUtils( 3930): set default noti to content://media/internal/audio/media/38
E/PhoneInterfaceManager( 1794): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/StoreModeReceiver( 3636): getPhoneNumber is empty
D/StoreModeReceiver( 3636): go to StoreModeCheck()
D/StoreModeReceiver( 3636): isStoremode not null
D/PhoneInterfaceManager( 1794): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/InitNotificationRingtoneService( 3930): End InitializeAlertRingtoneService.onHandleIntent
,D/AlertService( 3930): 0 Action = android.intent.action.BOOT_COMPLETED
V/SettingsProvider(  985): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
D/AlertService( 3930): [Widget]com.android.calendar.widget.CalendarAppWidgetProvider enabled
D/Feature ( 3930): MemoryLevel - 5:NOT_DEF:Not UI4.2 LOS
D/AlertService( 3930): [Widget]com.android.calendar.widget.MonthWidgetProvider enabled
D/AlertService( 3930): [Widget]com.android.calendar.widget.WeekWidgetProvider enabled
,D/StoreModeReceiver( 3636): product_name : jagnm_global_com
D/StoreModeReceiver( 3636): Store mode start!
V/SettingsProvider(  985): call_put(system:shop_mode=1) for 0 calling package = com.android.settings
V/SettingsProvider(  985): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
,D/AlertService( 3930): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/PowerManagerService(  985): ALS enabled for SRE
D/PowerManagerServiceEx(  985): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=120000 (in 68413 ms)
D/StoreModeReceiver( 3636): setBrightness() : NoMultiALC=255
W/ContextImpl( 3636): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.StoreModeReceiver.sendBroadcast:500 com.android.settings.StoreModeReceiver.setMode:473 
V/SettingsProvider(  985): call_put(system:screen_brightness_mode=0) for 0 calling package = com.android.settings
D/SettingsProvider(  985): Set screen_off_timeout in entry value : 120000
V/SettingsProvider(  985): call_put(system:screen_off_timeout=120000) for 0 calling package = com.android.settings
V/SettingsProvider(  985): call_put(system:screen_brightness=255) for 0 calling package = com.android.settings
V/SettingsProvider(  985): call_put(system:check_night_mode=0) for 0 calling package = com.android.settings
,D/SettingBootReceiver( 3636): onReceive
,D/SettingBootReceiver( 3636): Boot Completed intent received, action=android.intent.action.BOOT_COMPLETED
E/HolidayIntentService( 3930): onHandleIntent:holiday data empty
D/SettingBootReceiver( 3636): setStyle()
D/AlarmScheduler( 3930): No events found starting within 1 week.
I/[SystemUI]LGBootReceiver( 1389): onReceive = android.intent.action.BOOT_COMPLETED
D/SettingBootReceiver( 3636): SettingStyle=1
D/SettingBootReceiver( 3636): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
,D/SettingBootReceiver( 3636): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
I/[SystemUI]LGPowerUI( 1389): onReceive = com.lge.statusbar.bootcompleted
D/SettingBootReceiver( 3636): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3636): setAccountMenu()
I/[SystemUI]PhoneStatusBar( 1389): got ACTION_STICKY_BOOT_COMPLETED
D/TAG     ( 3636): setKidsMode
I/BOOT    ( 1389): got ACTION_STICKY_BOOT_COMPLETED
D/TAG     ( 3636): mIsOwner, setKidsMode
D/SettingBootReceiver( 3636): setAccountMenu()
W/art     ( 3904): Attempt to remove local handle scope entry from IRT, ignoring
,D/YSY     ( 3636): not support Quiet mode notification
W/AwContents( 3904): onDetachedFromWindow called when already detached. Ignoring
,V/SettingsProvider(  985): call_put(system:gentle_vibration_status=1) for 0 calling package = com.android.settings
,I/ActivityManager(  985): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3979 uid=10111 gids={50111, 9997, 1028, 3003} abi=armeabi-v7a
V/SettingsProvider(  985): call_put(system:smart_ringtone=0) for 0 calling package = com.android.settings
,D/SettingBootReceiver( 3636): timezoneID is null
,D/SystemWebViewEngine( 3904): CordovaWebView is running on device made by: LGE
I/SettingBootReceiver( 3636): disable au
I/TAG     ( 3636): disable WirelessSettingsActivity
W/art     ( 3904): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3904): Attempt to remove local handle scope entry from IRT, ignoring
I/TAG     ( 3636): disable SKTPhoneMode
,D/SettingBootReceiver( 3636): [Nightmode] Enter receiver
D/SettingBootReceiver( 3636): [Nightmode] BOOT_COMPLETED
,D/NightModeInfo( 3636): [Nightmode] setNightNodeTabSettings
D/NightModeInfo( 3636): [Nightmode] getAlreadyNightModeDB() : 0
D/NightModeInfo( 3636): [Nightmode] getUserBrightnessChange() : 0
D/NightModeInfo( 3636): [Nightmode] getUserBrightnessChangeNoNight() : 0
V/SettingsProvider(  985): call_put(system:already_night_mode=0) for 0 calling package = com.android.settings
V/SettingsProvider(  985): call_put(system:user_change_brightness=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  985): call_put(system:user_change_brightness_no_night=0) for 0 calling package = com.android.settings
V/SettingsProvider(  985): call_put(system:night_mode_enabled=0) for 0 calling package = com.android.settings
D/NightModeInfo( 3636): [Nightmode] setTabNightCheck : 0
V/SettingsProvider(  985): call_put(system:save_tab_night_check=0) for 0 calling package = com.android.settings
,D/NightModeInfo( 3636): [Nightmode] cancelPendingIntent
I/Activity( 3904): Activity.onPostResume() called 
D/NightModeInfo( 3636): [Nightmode] requestPendingIntent
D/NightModeInfo( 3636): [Nightmode] setAlarmStart~!!~!!~!!
D/NightModeInfo( 3636): [Nightmode] currentHour > 6
D/OpenGLRenderer( 3904): Render dirty regions requested: true
I/OpenGLRenderer( 3904): Initialized EGL, version 1.4
D/NightModeInfo( 3636): [Nightmode] currentHour > 6
I/NightModeInfo( 3636): JW getStartTime201511260000
D/NightModeInfo( 3636): [Nightmode] setAlarmEnd~!!~!!~!!
D/NightModeInfo( 3636): [Nightmode] currentHour > 6
D/NightModeInfo( 3636): [Nightmode] currentHour > 6
I/NightModeInfo( 3636): JW getEndTime201511260600
,D/NightModeInfo( 3636): [Nightmode] currentHour > 6
I/NightModeInfo( 3636): getStartTime201511260000
D/NightModeInfo( 3636): [Nightmode] currentHour > 6
I/NightModeInfo( 3636): getEndTime201511260600
D/jw      ( 3636): Only VZW Supported end return
D/OpenGLRenderer( 3904): Enabling debug mode 0
D/Atlas   ( 3904): Validating map...
,D/SplitWindow(  985): check instance of lgWin Window{3f3ed4de u0 com.example.hello/com.example.hello.MainActivity}
I/ActivityManager(  985): Killing 2272:com.google.android.gms/u0a6 (adj 15): empty #11
D/ConnectivityService(  985): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@145076bf)
,D/ConnectivityService(  985): dumpNetworkRequest
D/ConnectivityService(  985):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  985):     Requests:
D/ConnectivityService(  985):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  985):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  985):         NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  985):     Lingered:
D/ConnectivityService(  985): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  985): sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  985): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/libprocessgroup(  985): failed to open /acct/uid_10006/pid_2272/cgroup.procs: No such file or directory
,W/chromium( 3904): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/DownloadManager( 2737): Received broadcast intent for android.intent.action.BOOT_COMPLETED
,V/DownloadManager( 2737): DownloadService onCreate
I/DownloadManager( 2737): in removeSpuriousFiles
V/DownloadManager( 2737): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/InputDispatcher(  985): Focus entered window: Window{3f3ed4de u0 com.example.hello/com.example.hello.MainActivity}
I/NotificationManager( 2737): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 2737): created cursor android.database.sqlite.SQLiteCursor@29ba4eb8 on behalf of 2737
I/DownloadManager( 2737): in trimDatabase
V/DownloadManager( 2737): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 2737): created cursor android.database.sqlite.SQLiteCursor@229fc491 on behalf of 2737
V/DownloadManager( 2737): DownloadService onStartCommand
V/DownloadManager( 2737): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/MediaScannerReceiver( 2737): [MediaScanner] ACTION_BOOT_COMPLETED scan INTERNAL_VOLUME, EXTERNAL_VOLUME
V/DownloadManager( 2737): created cursor android.database.sqlite.SQLiteCursor@31219e64 on behalf of 2737
D/MediaScannerService( 2737): [MediaScanner] start scanning volume internal: [/system/media, /oem/media, /cust/OPEN_EU/media]
,V/LGMediaProvider( 2737): insertInternal: content://media/none/media_scanner, initValues=volume=internal
D/MediaScannerService( 2737): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///system/media
,D/MtpService( 2737): updating state; isCurrentUser=true, mMtpLocked=false
,W/InputMethodManagerService(  985): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/ActivityManager(  985): Displayed com.example.hello/.MainActivity: +1s91ms
I/Timeline(  985): Timeline: Activity_windows_visible id: ActivityRecord{28a82482 u0 com.example.hello/.MainActivity t220} time:51962
D/MtpService( 2737): addStorageLocked 65537 /storage/emulated/0
,D/WiseScreenService( 1909): [OnBootReceiver.java:24:onReceive()] iKeepScreenOn: 0
I/Timeline( 3904): Timeline: Activity_idle id: android.os.BinderProxy@5110ff6 time:51975
D/WiseScreenService( 1909): [OnBootReceiver.java:28:onReceive()] iSmartVideo: 0
E/MtpStorageEx( 2737): setAccessCapability false
D/MediaScannerEx( 2737): [MediaScanner] scanDirectories()[0] = /system/media
D/MediaScannerEx( 2737): [MediaScanner] scanDirectories()[1] = /oem/media
D/MediaScannerEx( 2737): [MediaScanner] scanDirectories()[2] = /cust/OPEN_EU/media
W/ContextImpl( 1909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.lge.keepscreenon.OnBootReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
I/MusicBrowser( 2705): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 }}
I/MusicBrowser( 2705): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
,D/MtpService( 2737): updating state; isCurrentUser=true, mMtpLocked=false
D/MusicBrowser( 2705): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
I/art     ( 2737): Thread[1,tid=2737,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31a8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
,I/ActivityManager(  985): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=4010 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
E/MediaProfilesEx-JNI( 2737): register_com_lge_media_MediaProfilesEx
,E/MediaRecorderEx-JNI( 2737): register_com_lge_media_MediaRecorderEx
D/AudioSystemEx( 2737): register_com_lge_media_LGAudioSystem
W/BindingManager( 3904): Cannot call determinedVisibility() - never saw a connection for the pid: 3904
,E/SurfaceControlEx( 2737): register_com_lge_view_SurfaceControlEx
I/art     ( 2737): Thread[1,tid=2737,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31a8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/LGMtpDatabaseJNI( 2737): register_android_mtp_LGMtpDatabase
,I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/LGMtpServerJNI( 2737): register_android_mtp_LGMtpServer
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/art     ( 2737): Thread[1,tid=2737,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31a8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/MediaPlayerEx-jni( 2737): register_com_lge_view_MediaPlayerEx
I/art     ( 2737): Thread[1,tid=2737,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31a8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/        ( 2737): register_com_lge_emoji_EmojiUtil
E/LGMtpDatabaseJNI( 2737): android_mtp_LGMtpDatabase_setup
,D/MtpService( 2737): starting MTP server in PTP mode
D/LGMtpServer( 2737): LGMtpServer
D/LGMtpServerJNI( 2737): android_mtp_LGMtpServer_setup
I/chromium( 3904): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/MtpService( 2737): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 2737): setAccessCapability false
D/MtpServerEx( 2737): ANR FIX - addStorage!
D/LGMtpServerJNI( 2737): android_mtp_LGMtpServer_run
V/DownloadManager( 2737): DownloadService onDestroy
,V/MediaScannerClient( 2737): [MediaScanner]setLocale: = en_US
,E/MediaFileEx( 2737): Duplicate type = AVI
E/MediaFileEx( 2737): Duplicate type = ASF
,I/VRBookmarkProvider( 4010): [BookmarkProvider.java:76:<init>()-[Thread:Other] BookmarkProvider
I/VRBookmarkProvider( 4010): [BookmarkProvider.java:254:onCreate()-[Thread:Other] onCreate
I/VRBookmarkProvider( 4010): [BookmarkProvider.java:504:registerObservers()-[Thread:Other] registerObservers : content://media/external/audio/media
D/VRBootCompletedReceiver( 4010): [BootCompletedReceiver.java:25:onReceive()-[Thread:Other] Controller has been started on Boot complete
D/VRBootCompletedReceiver( 4010): [BootCompletedReceiver.java:47:onReceive()-[Thread:Other] Voice Recorder launcher enable(1)/disable(2) : 1
,I/ActivityManager(  985): Killing 3703:com.lge.settings.easy/1000 (adj 15): empty #11
V/MediaScannerClient( 2737): [MediaScanner]setLocale: = en_US
W/MediaScanner( 2737): Error opening directory '/oem/media/', skipping: No such file or directory.
V/MediaScannerClient( 2737): [MediaScanner]setLocale: = en_US
W/MediaScanner( 2737): Error opening directory '/cust/OPEN_EU/media/', skipping: No such file or directory.
D/LGMediaProvider( 2737): [MediaScanner] delete() uri = content://media/internal/file
D/LGMediaProvider( 2737): [MediaScanner] delete() completed notifyChange, uri = content://media/internal
V/MediaScannerEx( 2737): [MediaScanner] isInternalStorage : true
V/MediaScannerEx( 2737): [MediaScanner] isInternalStorage : true
V/MediaScannerEx( 2737): [MediaScanner] isInternalStorage : true
,D/MediaScanner( 2737): [MediaScanner] prescan time: 214ms
D/MediaScanner( 2737): [MediaScanner] scan time: 53ms
D/MediaScanner( 2737): [MediaScanner] postscan time: 9ms
D/MediaScanner( 2737): [MediaScanner] total time: 276ms
D/LGMediaProvider( 2737): [MediaScanner] delete() uri = content://media/none/media_scanner
D/JsMessageQueue( 3904): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 3904): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/MediaScannerService( 2737): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///system/media
,W/libprocessgroup(  985): failed to open /acct/uid_1000/pid_3703/cgroup.procs: No such file or directory
D/LGMediaProvider( 2737): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///system/media, path = /system/media
I/MusicBrowser( 2705): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 }}
D/MediaScannerService( 2737): [MediaScanner] done scanning volume internal
I/MusicBrowser( 2705): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2705): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
,D/MediaScannerService( 2737): [MediaScanner] start scanning volume external: [/storage/emulated/0, /storage/external_SD]
V/LGMediaProvider( 2737): insertInternal: content://media/none/media_scanner, initValues=volume=external
D/MediaScannerService( 2737): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///storage/emulated/0
D/LGBootCompleteReceiver( 1794): onReceive : android.intent.action.BOOT_COMPLETED
D/ConfigUtils( 1794): setUsimOperator() : card operator = 
D/ConfigUtils( 1794): setUsimOperator() : result = null
V/LGMediaProvider( 2737): insertInternal: content://media/, initValues=name=external
D/ConfigUtils( 1794): setUsimOperator() : simOperator = 
D/ConfigUtils( 1794): setUsimOperator() : usimoperator = 0
D/ConfigUtils( 1794): setSupportedUsimMobilityForVoLTE() : false
D/ConfigUtils( 1794): This Model Voice Clarity Support : false
,D/LGBootCompleteReceiver( 1794): onReceive : updateCallrejectNotify rejectCallOption : 1
D/MediaScannerEx( 2737): [MediaScanner] scanDirectories()[0] = /storage/emulated/0
D/MediaScannerEx( 2737): [MediaScanner] scanDirectories()[1] = /storage/external_SD
I/MusicBrowser( 2705): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2705): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2705): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2705): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2705): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2705): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2705): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2705): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2705): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2705): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2705): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2705): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2705): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
,D/MusicBrowser( 2705): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2705): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2705): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
D/CallRejectInfoToNotify( 1794): update : tPhoneMode : false
I/NotificationManager( 1794): com.android.phone: cancel(2131493582) by com.android.phone
I/MusicBrowser( 2705): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2705): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,I/PhoneApp( 1794): saveDefaultRingtoneUriOfOwner = content://media/internal/audio/media/55
D/MusicBrowser( 2705): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2705): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2705): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/MusicBrowser( 2705): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2705): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2705): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2705): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2705): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2705): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
I/MusicWidget( 2614): _mediaDataObserver onChange()
D/MusicBrowser( 2705): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2705): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2705): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2705): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
,I/MusicWidget( 2614): beingMusicWidget_4x2() result::false
I/MusicWidget( 2614): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicWidget( 2614): beingMusicWidget_4x2() result::false
I/MusicWidget( 2614): beingMusicWidget_Quick() result::false
I/MusicWidget( 2614): beingMusicWidget_4x1() result::true
W/VRBookmarkProvider( 4010): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/
I/MusicWidget( 2614): send mDelayedStopHandler
,I/MusicWidget( 2614): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2614): beingMusicWidget_Quick() result::false
I/ActivityManager(  985): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4033 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/MusicBrowser( 2705): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicBrowser( 2705): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2705): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicBrowser( 2705): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2705): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
I/MusicWidget( 2614): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicWidget( 2614): beingMusicWidget_4x2() result::false
I/MusicWidget( 2614): beingMusicWidget_Quick() result::false
,D/MusicBrowser( 2705): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicWidget( 2614): beingMusicWidget_4x1() result::true
I/MusicBrowser( 2705): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2705): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicWidget( 2614): send mDelayedStopHandler
I/MusicWidget( 2614): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2614): beingMusicWidget_Quick() result::false
,I/MusicBrowser( 2705): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2705): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2705): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 2705): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
I/MusicBrowser( 2705): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
,D/MusicBrowser( 2705): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
W/MusicBrowser( 2705): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2705): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2705): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2705): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2705): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2705): - End   trace [MusicUtils.query]---------------------------------------------------------------
V/MediaScannerClient( 2737): [MediaScanner]setLocale: = en_US
,V/DrmBroadcastReceiver( 4033): Receive ACTION_BOOT_COMPLETED
,V/DrmService( 4033): Service onCreate
,D/DrmService( 4033): Received new request = 4
D/DrmServiceHandler( 4033): updateDrmPushNotification() : No notification
D/DrmService( 4033): Completed !! request = 4
D/DrmService( 4033): Request count = 0
,D/MediaScannerEx( 2737): [MediaScanner] beginFile() path = /storage/emulated/0/QuicksetLite Setup/data
,I/ActivityManager(  985): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=4052 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/MusicWidget( 2614): performViewUpdater handleMessage() msg.what::0
,I/MusicWidget( 2614): beingMusicWidget_4x1() result::true
I/MusicWidget( 2614): performUpdate()_4x1
V/DrmService( 4033): Service onDestroy
I/MusicWidget( 2614): defaultAppWidget()_4x1
I/ActivityManager(  985): Killing 3725:com.google.android.partnersetup/u0a9 (adj 15): empty #11
V/MediaScannerClient( 2737): [MediaScanner]setLocale: = en_US
W/MediaScanner( 2737): Error opening directory '/storage/external_SD/', skipping: Permission denied.
,D/LGMediaProvider( 2737): [MediaScanner] delete() uri = content://media/external/file
I/MusicWidget( 2614): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2614): 4x1_currentTheme :: null
I/MusicWidget( 2614): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2614): setDefaultViewLayoutId()_4x1
W/MusicBrowser( 2705): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/VRBookmarkProvider( 4010): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/external
W/MusicBrowser( 2705): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2705): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2705): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2705): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2705): - End   trace [MusicUtils.query]---------------------------------------------------------------
D/LGMediaProvider( 2737): [MediaScanner] delete() completed notifyChange, uri = content://media/external
W/VRBookmarkProvider( 4010): [BookmarkProvider.java:563:onChange()-[Thread:Other] EXTERNAL Change!!
V/MediaScanner( 2737): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@3c055fc
,V/MediaScanner( 2737): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@3c055fc
D/MediaScanner( 2737): [MediaScanner] prescan time: 97ms
D/MediaScanner( 2737): [MediaScanner] scan time: 121ms
D/MediaScanner( 2737): [MediaScanner] postscan time: 27ms
D/MediaScanner( 2737): [MediaScanner] total time: 245ms
D/LGMediaProvider( 2737): [MediaScanner] delete() uri = content://media/none/media_scanner
I/MusicWidget( 2614): appWidgetViewUpdate()_4x1
I/MusicWidget( 2614): linkButtons()_4x1
D/MediaScannerService( 2737): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///storage/emulated/0
,W/libprocessgroup(  985): failed to open /acct/uid_10009/pid_3725/cgroup.procs: No such file or directory
,I/MusicBrowser( 2705): [MediaPlaybackService.java:1995:onChange()] oooooo 
D/LGMediaProvider( 2737): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///storage/emulated/0, path = /storage/emulated/0
D/MediaScannerService( 2737): [MediaScanner] done scanning volume external
I/MusicWidget( 2614): pushUpdate()_4x1
,V/MusicBrowser( 2705): [MediaPlaybackService.java:5808:getPath()] oooooo {mFileToPlay=null}
I/MusicBrowser( 2705): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicWidget( 2614): _mediaDataObserver onChange()
I/MusicWidget( 2614): beingMusicWidget_4x2() result::false
I/MusicWidget( 2614): performViewUpdater handleMessage() msg.what::1
I/MusicBrowser( 2705): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2705): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
I/MusicWidget( 2614): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2705): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2705): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
,D/MusicBrowser( 2705): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2705): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2705): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2705): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2705): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2705): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2705): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2705): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2705): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2705): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2705): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2705): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2705): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2705): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicBrowser( 2705): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2705): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2614): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicWidget( 2614): beingMusicWidget_4x2() result::false
I/MusicWidget( 2614): beingMusicWidget_Quick() result::false
I/MusicWidget( 2614): beingMusicWidget_4x1() result::true
,I/MusicWidget( 2614): send mDelayedStopHandler
I/MusicWidget( 2614): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2614): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2705): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2705): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2705): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
,D/MusicBrowser( 2705): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2705): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2705): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2705): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2705): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2705): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2705): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2705): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2705): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2705): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicBrowser( 2705): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
,I/MusicWidget( 2614): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicWidget( 2614): beingMusicWidget_4x2() result::false
I/MusicWidget( 2614): beingMusicWidget_Quick() result::false
I/MusicWidget( 2614): beingMusicWidget_4x1() result::true
I/MusicWidget( 2614): send mDelayedStopHandler
I/MusicWidget( 2614): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2614): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2705): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2705): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2705): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2705): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2705): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2705): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2705): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2705): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
,I/MusicBrowser( 2705): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2705): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
D/jxcore_app_log( 3904): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426119168
I/[LgeWidgetLib]LgeAppWidgetHostView( 1965): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
D/JX-Cordova( 3904): jxcore cordova android initializing
,V/CloudHub( 4052): [DATABASE][DBConnection|open] open database
,E/CloudHub( 4052): [DATABASE][DBConnection|getUserId] User id: 0
E/CloudHub( 4052): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
E/[LgeWidgetLib]LgeAppWidgetHostView( 1965): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,V/CloudHub( 4052): [SERVICE][CloudHubReceiver|queryUploadCount] # of contents to upload: 0
V/DownloadManager( 2737): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 2737): created cursor android.database.sqlite.SQLiteCursor@2fff9485 on behalf of 4052
,I/VRBookmarkProvider( 4010): [BookmarkProvider.java:530:handleMessage()-[Thread:Other] -- syncTable() START --
V/CloudHub( 4052): [SERVICE][CloudHubReceiver|queryDownloadCount] # of contents to download: 0
I/MusicWidget( 2614): performViewUpdater handleMessage() msg.what::0
,I/MusicWidget( 2614): beingMusicWidget_4x1() result::true
I/MusicWidget( 2614): performUpdate()_4x1
I/MusicWidget( 2614): defaultAppWidget()_4x1
I/MusicWidget( 2614): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2614): 4x1_currentTheme :: null
I/MusicWidget( 2614): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2614): setDefaultViewLayoutId()_4x1
I/MusicWidget( 2614): appWidgetViewUpdate()_4x1
I/MusicWidget( 2614): linkButtons()_4x1
I/ActivityManager(  985): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=4071 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  985): Killing 3494:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/jxcore-log( 3904): Initializing JXcore engine
,W/jxcore-log( 3904): JXcore engine is ready
I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 21.130ms
W/jxcore-log( 3904): Starting JXcore engine
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.230ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.191ms
,W/m.example.hello( 3904): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6261]" dev="sockfs" ino=6261 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3904): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/m.example.hello( 3904): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8744]" dev="sockfs" ino=8744 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3904): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3904): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3904): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[19687]" dev="sockfs" ino=19687 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  985): failed to open /acct/uid_10086/pid_3494/cgroup.procs: No such file or directory
,I/MusicWidget( 2614): pushUpdate()_4x1
,I/VRBookmarkProvider( 4010): [BookmarkProvider.java:532:handleMessage()-[Thread:Other] -- syncTable() END --
W/jxcore-log( 3904): Platform android
W/jxcore-log( 3904): 
W/jxcore-log( 3904): Process ARCH arm
W/jxcore-log( 3904): 
I/MusicWidget( 2614): performViewUpdater handleMessage() msg.what::1
I/MusicWidget( 2614): beingMusicWidget_4x2() result::false
I/[LgeWidgetLib]LgeAppWidgetHostView( 1965): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,D/AirTest ( 4071): Set airtest_enable to false
I/ActivityManager(  985): Killing 3789:com.lge.lgdmsclient/1000 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1965): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/jxcore-log( 3904): JXcore Cordova bridge is ready!
I/jxcore-log( 3904): 
W/jxcore-log( 3904): JXcore engine is started
E/jxcore-log( 3904): >> LGE-LG-D722
E/jxcore-log( 3904): 
,I/jxcore-log( 3904): Total memory 906309632
I/jxcore-log( 3904): 
I/jxcore-log( 3904): Free memory 31895552
I/jxcore-log( 3904): 
I/jxcore-log( 3904): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3904): 
I/jxcore-log( 3904): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3904): 
W/libprocessgroup(  985): failed to open /acct/uid_1000/pid_3789/cgroup.procs: No such file or directory
I/jxcore-log( 3904): userPath [ 'www' ]
I/jxcore-log( 3904): 
I/jxcore-log( 3904): Size 720 1196
I/jxcore-log( 3904): 
V/LGSC    ( 2784): [104] 401
,I/jxcore-log( 3904): Screen Brightness 255
I/jxcore-log( 3904): 
E/jxcore-log( 3904): Dummy Error Log.
E/jxcore-log( 3904): 
I/ActivityManager(  985): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=4089 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,D/TARGETVALIDLATION_RECEIVER( 4089): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
D/TARGETVALIDLATION_RECEIVER( 4089): updateFlag = new File(TARGET_FLAG_PATH)
D/TARGETVALIDLATION_RECEIVER( 4089): Do Not display result dialog. it is not used Update Tool!!
I/ActivityManager(  985): Killing 3814:com.lge.clock/u0a10 (adj 15): empty #11
V/LGSC    ( 1794): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
W/libprocessgroup(  985): failed to open /acct/uid_10010/pid_3814/cgroup.procs: No such file or directory
,W/ContextImpl( 2831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2663 
E/AtFwd AutoBoot( 2831): AtFwd Auto Boot Started Successfully
I/GoogleHttpClient( 2073): GMS http client unavailable, use old client
,I/ActivityManager(  985): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=4111 uid=10062 gids={50062, 9997} abi=armeabi-v7a
,I/InsertAccount( 4111): The account already exists
,I/MusicBrowser( 2705): [MediaPlaybackService.java:2010:handleMessage()] oooooo mGroupIndexHandler msg.what : 0
I/MusicBrowser( 2705): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2705): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,I/MusicBrowser( 2705): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2705): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2705): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
I/ActivityManager(  985): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=4130 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  985): Killing 3844:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
W/libprocessgroup(  985): failed to open /acct/uid_10011/pid_3844/cgroup.procs: No such file or directory
,I/InsertAccount( 4111): The account info in contact DB already exists
,I/InsertAccount( 4111): The account info in calendar DB already exists
,I/Process ( 4111): Sending signal. PID: 4111 SIG: 9
I/jxcore-log( 3904): getBuffer is called!!!!
I/jxcore-log( 3904): 
,W/ResourcesManager( 4130): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4130): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/[SMS_AD]( 4130): Intent action: android.intent.action.BOOT_COMPLETED
,D/sensors_hal_Time(  985): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  985): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  985): tsOffsetIs: Apps: 53877804514; DSPS: 1863709; Offset : -3008944243
,I/ActivityManager(  985): Process com.lge.defaultaccount (pid 4111) has died
I/[SMS_AD]( 4130): Intent action: android.intent.action.BOOT_COMPLETED
,D/WeatherAncestor( 2689): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 15:11:15
D/UpdateThreadPoolManager( 2689): 2 : This is isUpdating : false
,D/Weather_cast( 2689): 2 : set auto-update time : 11/25 18:11
D/WeatherAncestor( 2689): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 15:11:15
D/WeatherService( 2689): 2 : onStartCommand, intent!=null, action: android.intent.action.BOOT_COMPLETED
I/ActivityManager(  985): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=4149 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  985): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2689): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  985): Explicit concurrent mark sweep GC freed 18939(912KB) AllocSpace objects, 3(237KB) LOS objects, 33% free, 23MB/34MB, paused 11.251ms total 181.318ms
,D/WeatherService( 2689): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2689): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/LockScreenSettings( 4149): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 4149): Received Broadcast : android.intent.action.BOOT_COMPLETED
,I/ActivityManager(  985): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=4169 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  985): Killing 3874:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  985): failed to open /acct/uid_10011/pid_3874/cgroup.procs: No such file or directory
,D/BootCompleteReceiver( 4169): hasclipTray = true
,W/ContextImpl( 4169): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
I/ActivityManager(  985): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=4190 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  985): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4207 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  985): Killing 3758:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  985): failed to open /acct/uid_10014/pid_3758/cgroup.procs: No such file or directory
V/AppCleanupService( 4190): registerAlarm
,D/AppCleanupService( 4190): noticeInterval = 2592000000
D/AppCleanupService( 4190): notiDateStr = 2015-12-20 22:35:42
D/AppCleanupService( 4190): noticeStart = 2015-12-20 22:35:42
,D/AppCleanupService( 4190): noticeStart = 1450647342000
D/AppUsageDbAdapter( 4190): initPreloadedAppToTheDB() : row count = 106
,E/UpdateRequestReceiver( 4207): ignoring update request
,E/UpdateRequestReceiver( 4207): ignoring update request
,E/UpdateRequestReceiver( 4207): ignoring update request
,E/UpdateRequestReceiver( 4207): ignoring update request
E/UpdateRequestReceiver( 4207): ignoring update request
E/UpdateRequestReceiver( 4207): ignoring update request
I/ActivityManager(  985): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4242 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  985): Killing 3636:com.android.settings/1000 (adj 15): empty #11
,W/libprocessgroup(  985): failed to open /acct/uid_1000/pid_3636/cgroup.procs: No such file or directory
,D/SIMObserver( 4242): action:android.intent.action.BOOT_COMPLETED
D/SIMObserver( 4242): handle ACTION_BOOT_COMPLETED
,I/ActivityManager(  985): Killing 3979:com.android.managedprovisioning/u0a111 (adj 15): empty #11
,W/libprocessgroup(  985): failed to open /acct/uid_10111/pid_3979/cgroup.procs: No such file or directory
,V/AlarmManager(  985): ELAPSED_WAKEUP set : Alarm{3550409f type 2 when 54734 com.android.providers.calendar} when 54734
E/QcrilMsgTunnelAutoboot( 2326): Received Intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot (has extras) } canStartService = false
,D/PhoneInterfaceManager( 1794): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
,D/PhoneInterfaceManager( 1794): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/ActivityManager(  985): Start proc com.google.android.gms for broadcast com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver: pid=4263 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 4263): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4263): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 4263): VM with version 2.1.0 has multidex support
I/MultiDex( 4263): install
I/MultiDex( 4263): VM has multidex support, MultiDex support library is disabled.
,I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  985): Waited long enough for: ServiceRecord{19295751 u0 com.google.android.gms/.gcm.GcmService}
,V/JNIHelp ( 4263): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 4263): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4263): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2df9c463: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4263): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 4263): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 4263): com.google.android.gms: cancel(39789) by com.google.android.gms
D/NativeLibraryUtils( 4263): Install completed successfully. count=13 extracted=0
,W/InstanceID/Rpc( 4263): Found 10006
,D/FileApkUtils( 4263): Spent 59ms computing apk sha1.
,D/FileApkUtils( 4263): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 4263): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 4263): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 4263): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/GmsModuleFndr( 4263): Beginning GMS chimera module scan
,D/GCM     ( 4263): COMPAT: Multi user not supported
,D/GmsModuleFndr( 4263): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/GCM     ( 2073): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/ChimeraCfgMgr( 4263): Beginning module configuration check
I/CheckinService( 4263): Checkin interval check for package: unspecified last checkin: 1448459952426 min interval config: 0 actual interval: 724756
I/CheckinService( 4263): Disabling old GoogleServicesFramework version
,D/ChimeraCfgMgr( 4263): Module APKs unchanged, check complete
,D/SystemUpdateService( 4263): onCreate
I/art     ( 4263): CheckpointMarkThreadRoots callback created = 0xb0485290
,I/GCoreUlr( 4263): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/GCoreUlr( 1766): DispatchingService.onCreate()
V/GLSActivity( 2073): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2073): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SystemUpdateService( 4263): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 4263): cancelUpdate (empty URL)
I/SystemUpdateService( 4263): active receiver: disabled
I/art     ( 4263): CheckpointMarkThreadRoots callback created = 0xb0485280
,V/AlarmManager(  985): RTC_WAKEUP set : Alarm{1d800f23 type 0 when 1448460677304 com.google.android.googlequicksearchbox} when 1448460677304
I/art     ( 4263): Background partial concurrent mark sweep GC freed 15321(1068KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 10MB/17MB, paused 10.960ms total 117.808ms
,I/NotificationManager( 4263): com.google.android.gms: cancel(2130838130) by com.google.android.gms
I/NotificationManager( 4263): com.google.android.gms: cancel(2130838131) by com.google.android.gms
D/ChimeraCfgMgr( 4263): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/CheckinService( 4263): Checking schedule, now: 1448460677392 next: 1448987201388
I/CheckinService( 4263): active receiver: disabled
,I/GCoreUlr( 1766): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/art     ( 4263): Background partial concurrent mark sweep GC freed 1532(164KB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 10MB/17MB, paused 10.046ms total 65.492ms
,V/AuthZen ( 4263): Handling intent: android.intent.action.BOOT_COMPLETED
D/AuthZenEventHandler( 4263): Handling event: android.intent.action.BOOT_COMPLETED
,I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/art     ( 4263): Suspending all threads took: 5.158ms
,I/art     ( 4263): Background sticky concurrent mark sweep GC freed 1304(84KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 11.144ms total 37.125ms
W/art     ( 2047): Verification of void com.google.android.apps.gsa.extradex.attemptedsearchhistory.d.run() took 173.086ms
,I/art     ( 4263): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 4263): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
W/art     ( 4263): Suspending all threads took: 6.533ms
,I/art     ( 4263): Background partial concurrent mark sweep GC freed 1409(123KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/17MB, paused 15.351ms total 63.584ms
,D/ChimeraCfgMgr( 4263): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/BaseAppContext( 4263): Using Auth Proxy for data requests.
D/SystemUpdateService( 4263): onDestroy
,W/Auth    ( 2073): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/art     ( 1766): Explicit concurrent mark sweep GC freed 17441(1135KB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 11MB/18MB, paused 1.269ms total 106.292ms
,V/GLSActivity( 2073): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2073): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 4263): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,W/GCoreFlp( 1766): No location to return for getLastLocation()
W/FusedLocationProvider( 4263): location=null
I/GCoreUlr( 1766): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/Kids    ( 4263): [AbstractKidsOperation] Invalid device state 3
I/GCoreUlr( 1766): Unbound from all location providers
,I/AuthZen ( 4263): Fetching signing key...
,D/PersistentNotificationBroadcastReceiver( 2073): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/NotificationManager( 4263): com.google.android.gms: cancel(10436) by com.google.android.gms
,W/GCoreFlp( 1766): No location to return for getLastLocation()
W/FusedLocationProvider( 4263): location=null
V/GLSActivity( 2073): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AuthZen ( 4263): Signing key fetched successfully!
,W/BaseAppContext( 4263): Using Auth Proxy for data requests.
I/art     ( 2073): Explicit concurrent mark sweep GC freed 6943(427KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 11MB/18MB, paused 1.303ms total 93.183ms
,I/ActivityManager(  985): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4353 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
V/GLSActivity( 2073): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/a       ( 4263): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 4263): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 4263): Clearing transaction cache
,I/GCoreUlr( 1766): DispatchingService.onDestroy()
I/GCoreUlr( 1766): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1766): Unbound from all location providers
W/ResourcesManager( 4353): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationManager(  985): android: cancelAsUser(-591465577) by android
,I/art     (  985): Explicit concurrent mark sweep GC freed 19450(967KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/34MB, paused 1.884ms total 135.499ms
,I/Babel_SMS( 4353): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4353): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4353): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4353): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4353): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4353): MmsConfig.loadFromResources
E/Babel_SMS( 4353): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4353): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 4353): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4353): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4353): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4353): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4353): found sensor: LGE Gravity Sensor, handle=29
,D/SensorManager( 4353): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4353): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4353): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4353): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4353): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4353): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4353): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4353): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4353): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4353): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4353): found sensor: Motion Accel, handle=46
I/art     ( 4353): CheckpointMarkThreadRoots callback created = 0xaaf37450
I/art     ( 4353): CheckpointMarkThreadRoots callback created = 0xaaf37430
,W/art     ( 4353): Suspending all threads took: 8.598ms
,W/Settings( 4353): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4353): startup - clean
I/Babel   ( 4353): deleted: false for 0
,W/AudioCapabilities( 4353): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4353): Unsupported mime audio/adpcm
W/AudioCapabilities( 4353): Unsupported mime audio/g726
W/AudioCapabilities( 4353): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4353): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4353): Unsupported mime video/mjpg
W/VideoCapabilities( 4353): Unsupported mime video/theora
,W/AudioCapabilities( 4353): Unsupported mime audio/evrc
W/AudioCapabilities( 4353): Unsupported mime audio/qcelp
W/VideoCapabilities( 4353): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4353): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4353): Unsupported mime audio/qcelp
W/AudioCapabilities( 4353): Unsupported mime audio/evrc
,W/VideoCapabilities( 4353): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 4353): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4353): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4353): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4353): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4353): Unrecognized profile 2130706433 for video/avc
W/art     ( 4353): Suspending all threads took: 20.314ms
,I/vclib   ( 4353): onServiceConnected
W/Babel   ( 4353): Attempted to change video mute state without an active call.
I/NotificationManager( 4353): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  985): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4393 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  985): Killing 4010:com.lge.voicerecorder/u0a34 (adj 15): empty #11
I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.137ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.415ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.165ms
,W/libprocessgroup(  985): failed to open /acct/uid_10034/pid_4010/cgroup.procs: No such file or directory
,W/CursorWrapperInner( 4052): Cursor finalized without prior close()
,W/ResourcesManager( 4393): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4393): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4393): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 4393): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4393): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 4393): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4393): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 4393): CheckpointMarkThreadRoots callback created = 0xb042db70
,I/art     ( 4393): CheckpointMarkThreadRoots callback created = 0xb4958de0
E/YouTube MDX( 4393): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd( 4393): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4393): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/BluetoothManagerService(  985): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  985): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@608f8c8 mBinding = false
D/BluetoothManagerService(  985): Message: 2
,D/BluetoothAdapterService(715536135)( 2092): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c67c15
D/BluetoothManagerService(  985): Sending off request.
D/WifiServiceImplEx(  985): setWifiEnabled: false pid=3904, uid=10030, package= com.example.hello, App Lable : HelloWorld
D/WifiService(  985): setWifiEnabled: false pid=3904, uid=10030
D/LocationManagerService(  985): getAllProviders()=[passive, gps, network]
D/BluetoothAdapterService(715536135)( 2092): disable() called...
D/BluetoothAdapterService(715536135)( 2092): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c67c15
D/Ulp_jni (  985): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/BluetoothAdapterService(715536135)( 2092): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c67c15
,D/BluetoothAdapterState( 2092): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2092): Setting state to 13
I/BluetoothAdapterState( 2092): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(715536135)( 2092): updateAdapterState() - Broadcasting state to 1 receivers.
D/Ulp_jni (  985): JNI:system_update. Event-4
I/dex2oat ( 4425): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads2012914955.jar --oat-fd=26 --oat-location=/data/data/com.google.android.youtube/cache/ads2012914955.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/BluetoothAdapterProperties( 2092): onBluetoothDisable()
I/BluetoothAdapterState( 2092): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/LocationManagerService(  985): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  985): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  985): JNI:system_update. Event-4
I/jxcore-log( 3904): ****TEST TOOK:  5074  ms ****
I/jxcore-log( 3904): 
I/jxcore-log( 3904): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3904): 
E/WifiStateMachine(  985): WifiStateMachine: Leaving Connected state
I/bt-btif ( 2092): HAL bt_hal_cbacks->adapter_properties_cb
E/WifiConfigStore(  985): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BluetoothAdapterProperties( 2092): Scan Mode:20
D/BluetoothAdapterState( 2092): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 2092): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 2092): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/bt-btif ( 2092): btsock_ctrl_hci_cleanup(L202): poll handle:4
I/bt-btif ( 2092): BTA_JvDeleteRecord
I/bt-btif ( 2092): BTA_JvRfcommStopServer
I/bt-btif ( 2092): BTA_JvDeleteRecord
I/bt-btif ( 2092): BTA_JvRfcommStopServer
D/IOP_DB_BT( 2092): db_close: nbr users 0
D/IOP_DB_BT( 2092): db_close: free database
V/BluetoothPbapService( 2092): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2092): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2092): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2092): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 2092): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 2092): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 2092): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2092): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2092): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,W/bt-btif ( 2092): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,E/bt-btif ( 2092): btif_hf_upstreams_evt: wrong handle = 1280 
D/btif_config_util( 2092): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/btif_config_util( 2092): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2092): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 2092): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 2092): enum_config(L344): out, value:f8:95:c7:87:85:54
D/btif_config_util( 2092): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:G3s-1
D/btif_config_util( 2092): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2092): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 2092): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
,D/btif_config_util( 2092): enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2092): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2092): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 2092): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2092): enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2092): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2092): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 2092): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2092): enum_config(L344): out, value:��8�\�婓��n�ScanMode
D/btif_config_util( 2092): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 2092): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
,D/btif_config_util( 2092): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 2092): enum_config(L344): out, value:x
D/btif_config_util( 2092): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2092): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 2092): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2092): enum_config(L344): out, value:s!WE�(E��00:0F:F6
D/btif_config_util( 2092): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2092): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2092): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 2092): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2092): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2092): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 2092): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2092): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2092): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 2092): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2092): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2092): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 2092): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
W/bt-obex ( 2092): Ignore event 10 in state 1
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:�
D/btif_config_util( 2092): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a,, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 2092): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
I/bt-btif ( 2092): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 2092): ops_state_cb(L223):  ops_state_cb state:3
D/btif_config_util( 2092): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/OppService( 2092): onOpsStateChange() :3
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2092): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 2092): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
W/bt-obex ( 2092): Ignore event 10 in state 1
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:$
D/btif_config_util( 2092): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 2092): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L344): out, value:
E/bt-btif ( 2092): bta_gattc_deregister Deregister Failedm unknown client cif
D/btif_config_util( 2092): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2092): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:�
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:A5-1
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/OppService( 2092): Recieved MESSAGE_OPS_DISABLE
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:#
D/btif_config_util( 2092): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 2092): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2092): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2092): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:�
D/btif_config_util( 2092): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:XT1072
D/btif_config_util( 2092): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 2092): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:a
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:S5-1
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 2092): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2092): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:	a
D/btif_config_util( 2092): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:G4-1
D/btif_config_util( 2092): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 2092): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2092): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:a
D/btif_config_util( 2092): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:Thali Test (Galaxy S5)
D/btif_config_util( 2092): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:�
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:Thali Test (Galaxy A5)
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:�
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:Thali Test (Galaxy A3)
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 2092): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:A
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
,D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:Thali Test's G2
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 2092): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2092): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:	a
D/btif_config_util( 2092): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:Note3-1
D/btif_config_util( 2092): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
D/LGWifiP2pService(  985): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
D/LGWifiP2pService(  985): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Service, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 2092): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Manufacturer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:�
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:A3-1
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/CommandListener(  279): Clearing all IP addresses on wlan0
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 7
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 2092): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 2092): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 2092): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2092): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 2092): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Manufacturer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 2092): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L344): out, value:Note4-1
D/btif_config_util( 2092): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 2092): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 2092): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 2092): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 2092): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 2092): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L344): out, value:�
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 2092): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 2092): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 2092): enum_config(L300): in, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 2092): enum_config(L343): out, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 2092): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 2092): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2092): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:�
D/btif_config_util( 2092): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 2092): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 2092): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 2092): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:JustWorks, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 2092): enum_config(L300): in, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L343): out, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Service, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:	a
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 2092): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Service, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 2092): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 2092): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:�
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 2092): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 2092): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 2092): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 2092): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Service, value type:string
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 2092): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 2092): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 2092): enum_config(L344): out, value:H
D/btif_config_util( 2092): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpSubVer, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 2092): enum_config(L344): out, value:?C
D/btif_config_util( 2092): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 2092): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:Z
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 2092): enum_config(L300): in, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 2092): enum_config(L343): out, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:GlobalTrust, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 2092): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 2092): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 2092): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2092): enum_config(L300): in, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L300): in, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 2092): enum_config(L343): out, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:Name, value type:string
D/btif_config_util( 2092): enum_config(L343): out, key:00:00:00:00:41:0e, value:Name
D/btif_config_util( 2092): enum_config(L300): in, key:00:00:00:00:41:0e, value:DevClass
D/btif_config_util( 2092): enum_config(L343): out, key:00:00:00:00:41:0e, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:��h
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:00:00:00:00:41:0e, value:DevType
D/btif_config_util( 2092): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:Name
D/btif_config_util( 2092): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:Name
D/btif_config_util( 2092): enum_config(L344): out, value:J���J�hrD�hrD�
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevClass, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevClass
D/btif_config_util( 2092): enum_config(L344): out, value:��P
D/btif_config_util( 2092): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevType
D/btif_config_util( 2092): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevType, value type:int
D/btif_config_util( 2092): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevType
D/btif_config_util( 2092): enum_config(L344): out, value:
D/DhcpStateMachine(  985): RunningState{ when=-9ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 10
D/BluetoothAdapterService(715536135)( 2092): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c67c15
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 7
D/BluetoothManagerService(  985): Message: 60
D/BluetoothManagerService(  985): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  985): Bluetooth State Change Intent: 12 -> 13
D/libc-netbsd(  985): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  985): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  985): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/LGBluetoothAPIService( 1889): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/ConnectivityService(  985): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/BluetoothMapService( 2092): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 2092): STATE_TURNING_OFF
V/BluetoothMapService( 2092): Handler(): got msg=4
D/BluetoothMapService( 2092): MAP Service closeService in
D/BluetoothMapMasInstance( 2092): MAP Service shutdown
D/LGBluetoothMapAdapter( 2092): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2092,): MAP Service closeService out
D/BluetoothAdapterService(715536135)( 2092): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c67c15
,D/BluetoothAdapterService(715536135)( 2092): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c67c15
D/libc-netbsd(  985): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  985): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1389): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
D/BluetoothAdapterService(715536135)( 2092): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c67c15
D/BluetoothAdapterService(715536135)( 2092): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c67c15
D/libc-netbsd(  985): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  985): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4393): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/ActivityManager(  985): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4451 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,D/WifiNetworkAgent(  985): NetworkAgent: NetworkAgent channel lost
D/WifiHS20(  985): hidePasspointNotification off =false
W/Settings(  985): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  985): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  985): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  985): InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  985): P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiHS20(  985): hidePasspointNotification off =false
D/ConnectivityService(  985): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  985): disableDataServiceNotify
,W/Settings(  985): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  985): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  985): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService(  985): SCAN_AVAILABLE : 1
D/WifiScanningService(  985): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  985): SCAN_AVAILABLE : 1
D/RttService(  985): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  985): P2pDisablingState
D/LGWifiP2pService(  985): P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  985): p2p socket connection lost
D/LGWifiP2pService(  985): P2pDisabledState
D/DSQN    (  985): stop dsqn bin
D/LGWifiP2pService(  985): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  985): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  279): Clearing all IP addresses on wlan0
D/WifiHS20(  985): hidePasspointNotification off =false
,W/Settings(  985): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  985): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  985): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/WifiServerServiceExt(  985): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt(  985): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  985): setSupplicantStateDISCONNECTED
I/QCNEJ   ( 1927): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1927): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-11-25 15:11:19.868 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1927): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WfdsService( 1889): WifiP2pState is changed : false
I/QCNEJ   ( 1927): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1927): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-11-25 15:11:19.87 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1927): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WfdsService( 1889): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsJNI ( 1889): doCommand: P2P_STOP_FIND
I/QCNEJ   ( 1927): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1927): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-11-25 15:11:19.873 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1927): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1927): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1927): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-11-25 15:11:19.874 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1927): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1389): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1389): Remote
I/[SystemUI]StatusBar.NetworkController( 1389): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  985): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  985):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  985):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  985): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  985): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
,D/ConnectivityManager.CallbackHandler( 1389): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  985): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  985): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  985): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  985): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  985): MasterInitialState.processMessage what=3
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  985): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  985): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  985): Disconnected - quitting
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1389): Remote
W/QCNEJ   ( 1927): |CORE| No family connected
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/ConnectivityService(  985): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1389): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  985): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  985): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  985): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1927): |CORE| No family connected
I/QCNEJ   ( 1927): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  985): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  985): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  985): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  985): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  985):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUp,Bandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1794): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  985): Removing idletimer
I/QCNEJ   ( 1927): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1794):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1389): Remote
,W/Settings(  985): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  985): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/DhcpStateMachine(  985): StoppedState
D/DhcpStateMachine(  985): StoppedState{ when=-69ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyIcons( 1389): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1389): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 4451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4451): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 4451): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4451): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 4451): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1389): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1389): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 5
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 10
I/wpa_supplicant( 2820): p2p0: CTRL-EVENT-TERMINATING 
I/Netd    (  279): M: Get netlink event, ifname: p2p0 action: 7
,D/WfdsMonitor( 1889): Event [CTRL-EVENT-TERMINATING ]
D/libc-netbsd(  985): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  985): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/wpa_supplicant( 2820): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 2820): USIM:  scard_deinit function
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
D/libc-netbsd(  985): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  985): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/IndexDatabaseHelper( 4451): Using schema version: 115
,I/IndexDatabaseHelper( 4451): Index is fine
I/dex2oat ( 4425): dex2oat took 407.730ms (threads: 4)
,D/AndroidRuntime( 4443): 
D/AndroidRuntime( 4443): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4443): CheckJNI is OFF
W/ContextImpl( 4451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/BluetoothPbapReceiver( 2092): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2092): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2092): ***********state = 13
,V/BluetoothPbapReceiver( 2092): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 2092): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 2092): state: 13
V/BluetoothPbapService( 2092): Pbap Service closeService in
V/BluetoothPbapService( 2092): successfully stopped pbap service
V/BluetoothPbapService( 2092): Pbap Service closeService out
V/BluetoothPbapService( 2092): Pbap Service onDestroy
V/BluetoothPbapService( 2092): Pbap Service closeService in
V/BluetoothPbapService( 2092): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 2092): [BTUI] cleanup
D/BluetoothManagerService(  985): Message: 20
D/BluetoothManagerService(  985): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fb30799:true
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 5
,I/wpa_supplicant( 2820): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  985): InitialState.processMessage what=4
D/BluetoothAdapterService(715536135)( 2092): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c67c15
D/Tethering(  985): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothManagerService(  985): Message: 30
D/BluetoothManagerService(  985): Message: 30
,D/LocalBluetoothProfileManager( 4451): Adding local MAP profile
D/BluetoothMap( 4451): Create BluetoothMap proxy object
D/BluetoothManagerService(  985): Message: 30
D/BluetoothManagerService(  985): Message: 30
D/LocalBluetoothProfileManager( 4451): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 4451):  get() - isFeatureLoaded : false
,D/LGBluetoothUserBindClient( 4451): [BTUI] initUserBindClient
,W/ContextImpl( 4451): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 4451): finishStartingService: stopping service
,D/BluetoothInputDevice( 4451): Proxy object connected
D/HidProfile( 4451): Bluetooth service connected
,D/BluetoothAdapterService(715536135)( 2092): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c67c15
D/WifiOffDelayIfNotUsed(  985): stopMonitoring
D/BluetoothPan( 4451): BluetoothPAN Proxy object connected
D/PanProfile( 4451): Bluetooth service connected
D/WfdsService( 1889): Supplicant Connection state is changed : false
W/Settings( 4353): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothAdapterService(715536135)( 2092): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c67c15
D/BluetoothMap( 4451): Proxy object connected
D/MapProfile( 4451): Bluetooth service connected
D/BluetoothMap( 4451): getConnectedDevices()
D/BluetoothAdapterService(715536135)( 2092): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c67c15
,D/BluetoothMap( 4451): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 4451): [BTUI] onServiceConnected
I/NotificationManager( 4393): com.google.android.youtube: cancel(2) by com.google.android.youtube
I/WifiServerServiceExt(  985): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt(  985): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt(  985): batteryPsActivateMsgHandler : this is not treated
I/QCNEJ   ( 1927): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1927): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-11-25 15:11:20.312 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1927): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings( 1766): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGBluetoothAuthorization( 4451): [BTUI] cancel All Notification
I/NotificationManager( 4451): com.android.settings: cancel(17301632) by com.android.settings
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.WIFI_STATE_CHANGED at null
,I/NotificationManager( 4451): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 4451): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 4451): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 4451): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 4451): com.android.settings: cancel(-1000041) by com.android.settings
D/BluetoothPermissionRequest( 4451): onReceive
,D/LGBluetoothAuthorization( 4451): [BTUI] cancel All Notification
I/NotificationManager( 4451): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 4451): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 4451): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 4451): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 4451): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 4451): com.android.settings: cancel(-1000041) by com.android.settings
I/ActivityManager(  985): Killing 4033:com.lge.drmservice/u0a51 (adj 15): empty #11
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4393): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4393): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4393): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
V/BluetoothOppReceiver( 2092): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
W/libprocessgroup(  985): failed to open /acct/uid_10051/pid_4033/cgroup.procs: No such file or directory
,D/BluetoothOppNotification( 2092): [BTUI] cancel opp incoming file confirm notification
I/NotificationManager( 2092): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/BluetoothOppNotification( 2092): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 2092): com.android.bluetooth: cancel(-1) by com.android.bluetooth
V/BluetoothSapReceiver( 2092): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 2092): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,D/AndroidRuntime( 4443): Calling main entry com.android.commands.pm.Pm
W/InstanceID/Rpc( 4393): Found 10006
,I/ActivityManager(  985): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4505 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/PackageSettings(  985): Skipping PackageSetting{12fdd749 com.test.thalitest/10316} due to missing metadata
,I/ActivityManager(  985): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  985): Killing 3904:com.example.hello/u0a30 (adj 0): stop com.example.hello
I/WindowState(  985): WIN DEATH: Window{3f3ed4de u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  985): Focus left window: Window{3f3ed4de u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  985): Window went away: Window{3f3ed4de u0 com.example.hello/com.example.hello.MainActivity}
W/bt-l2cap( 2092): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2092): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-btif ( 2092): ag scb idx 1 not allocated
E/bt-btif ( 2092): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2092): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2092): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 2092): ag scb idx 1 not allocated
E/bt-btif ( 2092): BTA AG is already disabled, ignoring ...
E/bt-btif ( 2092): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 2092): bta_gattc_deregister Deregister Failedm unknown client cif
W/bt_userial( 2092): select_read return size <=0:0, exiting userial_read_thread
D/bt_hwcfg( 2092): hw_epilog_process
I/bt_userial_vendor( 2092): device fd = 70 close
E/bt_vendor( 2092): [BTUI] Proto is enabled. Set Proto disable!!
,I/GKI_LINUX( 2092): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,E/libprocessgroup(  985): failed to kill 1 processes for processgroup 3904
W/ActivityManager(  985): Force removing ActivityRecord{28a82482 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,I/ActivityManager(  985): Force stopping com.example.hello appid=10030 user=0: pkg removed
W/ActivityManager(  985): Spurious death for ProcessRecord{1ae3d76c 3904:com.example.hello/u0a30}, curProc for 3904: null
,D/KeyguardModel( 1389): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/GKI_LINUX( 2092): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2092): GKI_destroy_task(): task [BTU] terminated
,I/bt-btif ( 2092): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 2092): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2092): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/PowerService( 1889): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4393): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/[LGHome]EVENT( 1965): [Launcher.java:5203:onStart()]onStart
,I/QCNEJ   ( 1927): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
D/BtSettings.ProfileConfig( 2092): Unable to read settings
D/BtSettings.ProfileConfig( 2092): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2092): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2092): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2092): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2092): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 2092): 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
D/BtSettings.ProfileConfig( 2092): 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
D/BtSettings.ProfileConfig( 2092): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2092): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2092): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2092): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2092): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 2092): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(715536135)( 2092): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
,I/InputReader(  985): Reconfiguring input devices.  changes=0x00000010
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2092): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2092): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(715536135)( 2092): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
D/HeadsetService( 2092): Received stop request...Stopping profile...
W/GeofencerStateMachine( 1766): Ignoring removeGeofence because network location is disabled.
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2092): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.android.bluetooth.hid.HidService
I/[SystemUI]QSlideListController( 1389): onReceive = android.intent.action.PACKAGE_REMOVED
W/ResourcesManager( 4505): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/BluetoothAdapterService( 2092): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(715536135)( 2092): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
I/LGBluetoothHfpAdapter( 2092): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 2092): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothAdapterService( 2092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa63707
D/HeadsetStateMachine( 2092): Exit Disconnected: -1
W/System.err( 3667): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2092): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/System.err( 3667): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3667): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3667): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3667): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3667): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3667): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3667): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3667): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3667): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3667): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3667): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1965): [Launcher.java:776:onResume()]onResume
W/BluetoothAdapterService( 2092): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(715536135)( 2092): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
,D/A2dpService( 2092): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2092): Exit Disconnected: -1
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2092): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2092): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(715536135)( 2092): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
D/KeyguardModel( 1389): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1389): createShortcutInfo...
D/LGBluetoothA2dpAdapter( 2092): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 2092): Cleaning up Bluetooth Handsfree callback object
D/LGBluetoothPowerControlManager( 2092): [BTUI] terminate
,D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2092): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2092): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(715536135)( 2092): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2092): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/KeyguardModel( 1389): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1389): createShortcutInfo...
W/BluetoothAdapterService( 2092): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(715536135)( 2092): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
D/BluetoothManagerService(  985): Message: 31
D/BluetoothAdapterService( 2092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa63707
,D/BluetoothAdapterService(715536135)( 2092): handleMessage() - Message: 1
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 2092): isTurningOnRadio()=false
D/BluetoothAdapterState( 2092): isTurningOffRadio()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2092): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2092): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2092): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/ResourceType( 1389): No package identifier when getting value for resource number 0x00000000
W/BluetoothAdapterService( 2092): Not skipping com.broadcom.bt.service.sap.SapService
W/PackageManager( 1389): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/BluetoothAdapterService(715536135)( 2092): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2092): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 2092): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(715536135)( 2092): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
D/HidService( 2092): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa63707
I/[LGHome]LGActivityUtil( 1965): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1389): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1389): createShortcutInfo...
D/AuthorizationBluetoothService( 2073): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/[LGHome]EVENT( 1965): [Launcher.java:929:onResume()]onResume end
I/Activity( 1965): Activity.onPostResume() called 
D/HeadsetStateMachine( 2092): Unbinding service...
,W/ResourceType( 1389): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1389): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2092): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2092): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2092): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(715536135)( 2092): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
D/BluetoothInputDevice( 4451): Proxy object disconnected
D/BluetoothAdapterState( 2092): Stopping profile services that were post enabled
D/HeadsetPhoneState( 2092): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2092): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 2092): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2092): [BTUI] listenForMultiSimPhoneState : start = false
D/BluetoothHeadset( 1794): Proxy object disconnected
W/BluetoothHeadsetServiceJni( 2092): Cleaning up Bluetooth Handsfree Interface...
D/BluetoothHeadset( 1794): Proxy object disconnected
W/BluetoothHeadsetServiceJni( 2092): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 2092): [BTUI] LGBluetoothHfpAdapter cleanup
D/BluetoothHeadset( 1794): Proxy object disconnected
D/HidProfile( 4451): Bluetooth service disconnected
D/HealthService( 2092): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa63707
D/KeyguardModel( 1389): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,D/KeyguardModel( 1389): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1389): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardUpdateMonitor( 1389): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1389): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1389): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1389): On Skip Timer : true
D/KeyguardModel( 1389): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/PanService( 2092): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa63707
D/BtGatt.DebugUtils( 2092): handleDebugAction() action=null
I/art     ( 1871): CheckpointMarkThreadRoots callback created = 0xaaf02bb0
D/BtGatt.GattService( 2092): Received stop request...Stopping profile...
D/BtGatt.GattService( 2092): stop()
W/[LGHome]LGWallpaperInfo( 1965): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/BtGatt.AdvertiseManager( 2092): advertise clients cleared
D/WallpaperManager( 1965): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/BluetoothPan( 4451): BluetoothPAN Proxy object disconnected
D/PanProfile( 4451): Bluetooth service disconnected
D/LGBluetoothGattAdapter( 2092): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 2092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa63707
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - Message: 1
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 2092): isTurningOnRadio()=false
D/BluetoothAdapterState( 2092): isTurningOffRadio()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2092): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2092): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 2092): Received stop request...Stopping profile...
D/BluetoothMapService( 2092): stop()
,W/ResourceType( 1389): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1389): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/BluetoothMapEmailAppObserver( 2092): deinitObservers()
D/BluetoothMapEmailAppObserver( 2092): removeReceiver()
D/KeyguardModel( 1389): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1389): createShortcutInfo...
D/BluetoothAdapterService( 2092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa63707
I/BluetoothA2dpServiceJni( 2092): cleanupNative
I/GKI_LINUX( 2092): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,I/GKI_LINUX( 2092): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2092): GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/SapService( 2092): Received stop request...Stopping profile...
D/SapService( 2092): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 2092): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 2092): [BTUI] terminateSapManager
D/LgeBluetoothSimManager( 1794): [BTUI] SAP_DISABLE_EVT
,I/art     ( 1871): CheckpointMarkThreadRoots callback created = 0xb042d6a0
I/SystemUI[Framework](  985): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  985): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  985): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  985): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  985): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@26f2eea5,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  985): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/BluetoothAdapterService( 2092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa63707
D/KeyguardModel( 1389): handleShortcutListChanged...
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - Message: 1
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/InputDispatcher(  985): Focus entered window: Window{b265772 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/BluetoothAdapterState( 2092): isTurningOnRadio()=false
D/BluetoothAdapterState( 2092): isTurningOffRadio()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2092): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2092): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHidServiceJni( 2092): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 2092): Cleaning up Bluetooth GID callback object
,D/**BluetoothFTPService( 2092): Received stop request...Stopping profile...
D/**BluetoothFTPService( 2092): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 2092): closeFtpServerNative
D/BluetoothAdapterService( 2092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa63707
D/**OppService( 2092): Received stop request...Stopping profile...
D/OppService( 2092): Stopping Bluetooth OppService
D/OppService( 2092): cleanup OPP Service
W/BluetoothOPPServiceJni( 2092): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 2092): Cleaning up Bluetooth OPP callback object
D/BluetoothMap( 4451): Proxy object disconnected
D/MapProfile( 4451): Bluetooth service disconnected
D/OppService( 2092): remove callbacks and handler
D/LGBluetoothOppAdapter( 2092): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 2092): cleanup done
D/BluetoothAdapterService( 2092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa63707
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - Message: 1
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 2092): isTurningOnRadio()=false
D/BluetoothAdapterState( 2092): isTurningOffRadio()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2092): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
,D/BluetoothAdapterService( 2092): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHealthServiceJni( 2092): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2092): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 2092): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - Message: 1
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAdapterState( 2092): isTurningOnRadio()=false
D/administrator(  985): Handling package changes for user 0
D/BluetoothAdapterState( 2092): isTurningOffRadio()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2092): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2092): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 2092): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2092): Cleaning up Bluetooth PAN callback object
D/KeyguardModel( 1389): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1389): createShortcutInfo...
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - Message: 1
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 2092): isTurningOnRadio()=false
D/BluetoothAdapterState( 2092): isTurningOffRadio()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2092): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2092): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 2092): Handler(): got msg=4
D/BluetoothMapService( 2092): MAP Service closeService in
D/LGBluetoothMapAdapter( 2092): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2092): MAP Service closeService out
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - Message: 1
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2092): isTurningOnRadio()=false
D/BluetoothAdapterState( 2092): isTurningOffRadio()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2092): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.P,rofileConfig( 2092): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2092): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 2092): cleanup()
D/BluetoothMapService( 2092): MAP Service closeService in
D/LGBluetoothMapAdapter( 2092): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2092): MAP Service closeService out
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - Message: 1
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2092): isTurningOnRadio()=false
D/BluetoothAdapterState( 2092): isTurningOffRadio()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2092): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2092): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
,W/BluetoothSAPServiceJni( 2092): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2092): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - Message: 1
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
D/BluetoothAdapterState( 2092): isTurningOnRadio()=false
D/BluetoothAdapterState( 2092): isTurningOffRadio()=false
D/KeyguardModel( 1389): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOn()=false
D/KeyguardModel( 1389): createShortcutInfo...
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2092): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2092): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2092): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothFTPService( 2092): cleanup FTP Service
V/BluetoothFTPServiceJni( 2092): closeFtpServerNative
V/BluetoothFTPServiceJni( 2092): cleanupNative
W/BluetoothFTPServiceJni( 2092): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 2092): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 2092): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 2092): cleanup done
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - Message: 1
D/BluetoothAdapterService(715536135)( 2092): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
D/BluetoothAdapterState( 2092): isTurningOnRadio()=false
D/BluetoothAdapterState( 2092): isTurningOffRadio()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2092): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2092): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(715536135)( 2092): onProfileServiceStateChange() - All profile services stopped...
D/BluetoothAdapterState( 2092): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2092): Setting state to 10
I/BluetoothAdapterState( 2092): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(715536135)( 2092): updateAdapterState() - Broadcasting state to 1 receivers.
D/OppService( 2092): cleanup OPP Service
D/OppService( 2092): remove callbacks and handler
D/LGBluetoothOppAdapter( 2092): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 2092): cleanup done
D/BluetoothManagerService(  985): Message: 60
D/BluetoothManagerService(  985): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  985): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 2092): Entering OffState
D/BluetoothA2dp(  985): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1794): onBluetoothStateChange: up=false
I/[LGHome]EVENT( 1965): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/BluetoothHeadset( 1794): onBluetoothStateChange: up=false
D/BluetoothHeadset(  985): onBluetoothStateChange: up=false
D/BluetoothPan( 4451): onBluetoothStateChange on: false
I/[,LGHome]LGPlusHomeDBManager( 1965): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
W/ResourceType( 1389): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1389): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/BluetoothMap( 4451): onBluetoothStateChange: up=false
D/KeyguardModel( 1389): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1389): createShortcutInfo...
I/[LGHome]LGPlusHomeDBManager( 1965): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/BluetoothInputDevice( 4451): onBluetoothStateChange: up=false
D/BluetoothPbap( 4451): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1794): onBluetoothStateChange: up=false
D/BluetoothAdapterService(715536135)( 2092): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9c67c15
D/BluetoothManagerService(  985): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  985): Broadcasting onBluetoothServiceDown() to 9 receivers.
I/[LGHome]EVENT( 1965): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1965): [setNavigationBarColor] color=0x 0
D/BluetoothManagerService(  985): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService(  985): Broadcasting onQBluetoothServiceDown() to 0 receivers.
,D/BluetoothManagerService(  985): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@608f8c8 mBinding = false
,D/BluetoothManagerService(  985): Sending unbind request.
W/ResourceType( 1389): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1389): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/BluetoothAdapterService(715536135)( 2092): onUnbind() - calling cleanup
D/BluetoothManagerService(  985): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService(715536135)( 2092): cleanup()
D/BluetoothAdapter( 1389): 361316875: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1389): 361316875: getState() :  mService = null. Returning STATE_OFF
,D/KeyguardModel( 1389): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1389): createShortcutInfo...
D/LGBluetoothAPIService( 1889): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1889): Message: 2
D/LGBluetoothAPIService( 1889): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@26069ce2 mBinding = false
D/LGBluetoothAPIService( 1889): Sending unbind request.
D/LGBluetoothFeatureConfig( 4451): isPrivacyLogsEnabled : true
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1389): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
D/LGBluetoothUtils( 4451): [BTUI] resetProperty - success
W/ResourceType( 1389): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1389): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
E/LGBluetoothEventManager( 4451): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 4451): [BTUI] clear device connection state
W/ContextImpl( 4451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/KeyguardModel( 1389): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1389): createShortcutInfo...
D/BluetoothAdapterService(715536135)( 2092): cleanup() - Cleaning up adapter native
I/bt-btif ( 2092): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 2092): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/bt-btif ( 2092): HAL bt_hal_cbacks->thread_evt_cb
I/GKI_LINUX( 2092): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2092): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 2092): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
,I/GKI_LINUX( 2092): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2092): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2092): GKI_exit_task 2 done
I/GKI_LINUX( 2092): GKI_exit_task 1 done
I/GKI_LINUX( 2092): GKI_exit_task 0 done
I/BluetoothServiceJni( 2092): cleanupNative: return from cleanup
W/LGBluetoothServiceJni( 2092): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 2092): [BTUI] unregister observer for LG device name DB
D/DockEventReceiver( 4451): finishStartingService: stopping service
D/BluetoothAdapterService(715536135)( 2092): cleanup() - Bluetooth process exited normally.
D/BluetoothAdapterService(715536135)( 2092): cleanup() done
I/art     ( 2092): System.exit called, status: 0
I/AndroidRuntime( 2092): VM exiting with result code 0, cleanup skipped.
D/BluetoothAdapter( 1766): 266001297: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1766): 266001297: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  985): Killing 4052:com.lge.cloudhub/u0a49 (adj 15): empty #11
V/AudioFlinger(  283): 2092 died, releasing its sessions
V/AudioFlinger(  283):  pid 1794 @ 0
V/AudioFlinger(  283):  pid 2705 @ 1
V/AudioFlinger(  283):  pid 3208 @ 2
V/AudioFlinger(  283):  pid 3208 @ 3
D/LGBluetoothUserBindClient( 4451): [BTUI] onServiceDisconnected
D/FMFRW_FmProxy( 1889): Fm Proxy object disconnected
D/KeyguardModel( 1389): handleShortcutListChanged...
,I/ActivityManager(  985): Process com.android.bluetooth (pid 2092) has died
,W/InputMethodManagerService(  985): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  985): Got RemoteException sending setActive(false) notification to pid 3904 uid 10030
W/ActivityManager(  985): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
W/ActivityManager(  985): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 10999ms
W/libprocessgroup(  985): failed to open /acct/uid_10049/pid_4052/cgroup.procs: No such file or directory
,I/ActivityManager(  985): Waited long enough for: ServiceRecord{389aa3a5 u0 com.android.mms/.service.SwitchedService}
D/BluetoothPermissionRequest( 4451): onReceive
,D/LGBluetoothUtils( 4451): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 4451): cancelDiscoverableAlarm(): Enter
I/Timeline( 1965): Timeline: Activity_idle id: android.os.BinderProxy@1974ea51 time:60000
I/SystemUI[Framework](  985): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  985): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  985): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  985): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  985): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@26f2eea5,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  985): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/HotwordRecognitionRnr( 2047): Starting hotword detection.
I/MicrophoneInputStream( 2047): mic_starting com.google.android.apps.gsa.speech.audio.u@23eea14
V/AudioRecord( 2047): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 2047): set(): mSessionId 23
,V/AudioPolicyManager(  283): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 23, flags 0
V/AudioPolicyManager(  283): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  283): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  283): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb40365c0)
V/audio_hw_primary(  283): adev_open_input_stream: exit
V/AudioFlinger(  283): openInput_l() openInputStream returned input 0xb40365c0, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  283): openInput_l() created record thread: ID 24 thread 0xb42a5000
I/AudioFlinger(  283): AudioFlinger's thread 0xb42a5000 ready to run
D/audio_hw_primary(  283): in_standby: enter: stream (0xb40365c0) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioSystem(  283): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 2047): ioConfigChanged() event 3, ioHandle 24
V/AudioPolicyService(  283): AudioCommandThread() adding update audio port list
D/audio_hw_primary(  283): in_standby: enter: stream (0xb40365c0) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioSystem(  985): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1389): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1794): ioConfigChanged() event 3, ioHandle 24
V/AudioPolicyService(  283): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio port list
V/AudioSystem( 2705): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 3208): ioConfigChanged() event 3, ioHandle 24
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
,V/AudioFlinger(  283): openRecord() lSessionId: 23 input 24
V/AudioFlinger(  283): getOrphanEffectChain_l session 23 index -2
V/AudioFlinger(  283): acquiring 23 from 2047, for -1
V/AudioFlinger(  283):  added new entry for 23
V/AudioRecord( 2047): start, sync event 0 trigger session 0
V/AudioRecord( 2047): mAudioRecord->start()
V/AudioFlinger(  283): RecordHandle::start()
V/AudioFlinger(  283): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  283): startInput() module primary->input primary(24)
V/AudioPolicyManager(  283): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  283): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  283): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  283): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  283): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  283): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  283): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  283): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  283): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  283): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  283): in_set_parameters: exit: status(0)
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb42a5000
V/AudioFlinger::PatchPanel(  283): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  283): createAudioPatch() added new patch handle 25 halHandle 0
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): setInputDevice() createAudioPatch returned 0 patchHandle 25
V/AudioPolicyManager(  283): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  283): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  283): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyService(  283): AudioCommandThread() adding set parameter string hotword_active=1, io 24 ,delay 0
V/AudioPolicyService(  283): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing set parameters string hotword_active=1, io 24
V/AudioFlinger(  283): setParameters(): io 24, keyvalue hotword_active=1, calling pid 283
V/AudioFlinger(  283): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
I/ActivityManager(  985): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=4564 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
I/NotificationService(  985): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  985): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  283): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  283): in_set_parameters: exit: status(0)
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb42a5000
V/AudioPolicyService(  283):, AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): AudioPolicyManager::startInput() input source = 1999
,D/JobSchedulerService(  985): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  985): Explicit concurrent mark sweep GC freed 36642(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 10.880ms total 489.957ms
V/msm8974_platform(  283): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  283): start_input_stream: enter: stream(0xb40365c0)usecase(7: audio-record)
V/voice   (  283): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  283): start_input_stream: usecase(7)
E/audio_hw_primary(  283): select_devices: enter and usecase(7)
V/msm8974_platform(  283): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  283): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  283): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  283): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  283): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  283): enable_snd_device: enter  144
D/hardware_info(  283): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  283): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  283): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  283): ACDB -> send_audio_cal, acdb_id = 65, path =  1
,D/ACDB-LOADER(  283): ACDB -> send_adm_topology
D/ACDB-LOADER(  283): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  283): ACDB -> send_asm_topology
D/ACDB-LOADER(  283): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  283): ACDB -> send_audtable
D/ACDB-LOADER(  283): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  283): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  283): ACDB -> send_audvoltable
D/ACDB-LOADER(  283): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  283): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  283): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  283): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  283): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  283): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  283): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  283): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  283): enable_audio_route: exit
D/audio_hw_primary(  283): select_devices: done
V/audio_hw_primary(  283): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  283): start_input_stream: exit
,D/PhoneStatusBar( 1389): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1389): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
D/TaskPersister(  985): removeObsoleteFile: deleting file=220_task.xml
I/[SystemUI]NavigationThemeResource( 1389): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1389):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1389): , Keyguard show=false, IME shown=false, Panel expanded=false
,D/BarTransitions( 1389): draw background and invalidate : color = f3000000
D/BarTransitions( 1389): draw background and invalidate : color = f3e9e9e9
I/MicrophoneInputStream( 2047): mic_started com.google.android.apps.gsa.speech.audio.u@23eea14
,I/ActivityManager(  985): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4586 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/HotwordWorker( 2047): onReady
D/AndroidRuntime( 4443): Shutting down VM
,W/ResourcesManager( 4564): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 4564): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4564): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 4564): Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
I/Timeline(  985): Timeline: Activity_windows_visible id: ActivityRecord{3047d54c u0 com.lge.launcher2/.Launcher t219} time:60262
,D/BluetoothAdapterApp( 4564): Loading JNI Library
I/ActivityManager(  985): Killing 4071:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
,W/libprocessgroup(  985): failed to open /acct/uid_10054/pid_4071/cgroup.procs: No such file or directory
,E/BluetoothServiceJni( 4564): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
D/BluetoothAdapterApp( 4564): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1f28da6e Instance Count = 1
,D/BluetoothAdapterApp( 4564): onCreate
D/LCardEmulationManager( 1871): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1871): getDefaultRoute
,I/LGBluetoothServiceJni( 4564): classInitNative: succeeds
,D/BtSettings.ProfileConfig( 4564): [BTUI] HeadsetServiceis supported
D/BtSettings.ProfileConfig( 4564): Adding HeadsetService
W/ResourcesManager(  985): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/BtSettings.ProfileConfig( 4564): [BTUI] A2dpServiceis supported
D/BtSettings.ProfileConfig( 4564): Adding A2dpService
D/BtSettings.ProfileConfig( 4564): [BTUI] HidServiceis supported
D/BtSettings.ProfileConfig( 4564): Adding HidService
D/BtSettings.ProfileConfig( 4564): [BTUI] HealthServiceis supported
D/BtSettings.ProfileConfig( 4564): Adding HealthService
,D/LGBluetoothFeatureConfig( 4564): isSupportPan() :  mTargetOp=OPEN
D/LGBluetoothFeatureConfig( 4564): isSupportPan() :  mTargetOp=OPEN
D/BtSettings.ProfileConfig( 4564): [BTUI] PanServiceis supported
D/BtSettings.ProfileConfig( 4564): Adding PanService
D/BtSettings.ProfileConfig( 4564): [BTUI] GattServiceis supported
D/BtSettings.ProfileConfig( 4564): Adding GattService
D/BtSettings.ProfileConfig( 4564): [BTUI] BluetoothMapServiceis supported
D/BtSettings.ProfileConfig( 4564): Adding BluetoothMapService
V/LGBluetoothServiceAdapter( 4564): [BTUI] region:EU country:EU
,D/BtSettings.ProfileConfig( 4564): [BTUI] SapServiceis supported
D/BtSettings.ProfileConfig( 4564): Adding SapService
D/BtSettings.ProfileConfig( 4564): [BTUI] FTPServiceis supported
D/BtSettings.ProfileConfig( 4564): Adding FTPService
E/BtSettings.ProfileConfig( 4564): [BTUI] HeadsetClientServiceis NOT supported
D/BtSettings.ProfileConfig( 4564): [BTUI] OppServiceis supported
D/BtSettings.ProfileConfig( 4564): Adding OppService
D/BtSettings.ProfileConfig( 4564): deviceMode from shared preference   -1
D/BtSettings.ProfileConfig( 4564): checkAndAdjustDeviceModeConfiguration deviceMode1
D/BtSettings.ProfileConfig( 4564): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 4564): Unable to read settings
D/BtSettings.ProfileConfig( 4564): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 4564): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 4564): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 4564): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 4564): 	at com.broadcom.bt.service.ProfileConfig.checkAndAdjustDeviceModeConfiguration(ProfileConfig.java:400)
D/BtSettings.ProfileConfig( 4564): 	at com.broadcom.bt.service.ProfileConfig.init(ProfileConfig.java:550)
D/BtSettings.ProfileConfig( 4564): 	at com.lge.bluetooth.adapter.LGBluetoothProfileConfigAdapter.init(LGBluetoothProfileConfigAdapter.java:30)
D/BtSettings.ProfileConfig( 4564): 	at com.android.bluetooth.btservice.AdapterApp.onCreate(AdapterApp.java:67)
D/BtSettings.ProfileConfig( 4564): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
D/BtSettings.ProfileConfig( 4564): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
D/BtSettings.ProfileConfig( 4564): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
D/BtSettings.ProfileConfig( 4564): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
D/BtSettings.ProfileConfig( 4564): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 4564): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 4564): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
D/BtSettings.ProfileConfig( 4564): 	at java.lang.reflect.Method.invoke(Native Method)
D/BtSettings.ProfileConfig( 4564): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BtSettings.ProfileConfig( 4564): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
D/BtSettings.ProfileConfig( 4564): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/BtSettings.ProfileConfig( 4564): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 4564): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 4564): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 4564): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 4564): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 4564): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 4564): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 4564): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 4564): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/LGBluetoothOppAdapter( 4564): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,D/LGBluetoothUserBindClient( 4451): [BTUI] onServiceConnected
I/FmServiceJni( 4564): classInitNative: succeeds
,D/FmService( 4564): FmReceiverServiceStub createdcom.broadcom.fm.fmreceiver.FmService$FmReceiverServiceStub@f0c2f7aservicecom.broadcom.fm.fmreceiver.FmService@1103932b
D/FmNativehandler( 4564): start
D/BluetoothRadioManager( 4564): [BTUI] getRadioManager()
D/BluetoothRadioManager( 4564): [BTUI] BluetoothRadioManager()
D/BluetoothManagerService(  985): Message: 20
,D/BluetoothManagerService(  985): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24ce2924:true
D/BluetoothRadioManager( 4564): doBind: com.broadcom.bt.service.radiomanager.IBluetoothRadioManager
,V/FmService( 4564): FM Service  onCreate
D/FmService( 4564): Binding service...
D/FMFRW_FmProxy( 1889): Fm proxy onServiceConnected() name = ComponentInfo{com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService}, service = android.os.BinderProxy@2d69d873
D/BluetoothAdapterService( 4564): Set JNI Library before classInit
,D/BluetoothAdapterService(603177012)( 4564): AdapterService() - REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterService(603177012)( 4564): onCreate()
D/BluetoothAdapterState( 4564): make
W/ResourceType(  985): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/bluedroid( 4564): init
I/BluetoothAdapterState( 4564): Entering OffState
I/bte_conf( 4564): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 4564): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 4564): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 4564): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 4564): [BTUI] lge_load_bluetooth_address
I/[LGHome]EVENT( 1965): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ActivityManager(  985): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found

```
