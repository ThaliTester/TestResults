#### Test 55634150e857e16_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
W/ResourcesManager( 3690): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,--------- beginning of main
I/RlzPingService( 3659): Setting next ping for 1453133389419
I/art     ( 2079): Explicit concurrent mark sweep GC freed 2944(115KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 899us total 28.721ms
I/ActivityManager(  953): Killing 3373:com.lge.hiddenmenu/1000 (adj 15): empty #11
D/CalendarProvider2( 3690): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1f56360d
W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_3373/cgroup.procs: No such file or directory
D/CalendarProvider2( 3690): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 3690): Created com.android.providers.calendar.CalendarAlarmManager@3196200e(com.android.providers.calendar.CalendarProvider2@1f56360d)
D/CalendarReceiver( 3690): [onReceive] intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.calendar/.CalendarReceiver (has extras) }
D/CalendarReceiver( 3690): [onReceive] WakeLock new : CalendarReceiver_Provider, ReferenceCounted = true
D/CalendarReceiver( 3690): [onReceive] WakeLock acquire : CalendarReceiver_Provider
D/CalendarReceiver( 3690): [onReceive] android.intent.action.BOOT_COMPLETED
D/CalendarProvider2( 3690): Scheduling check of next Alarm
D/CalendarProvider2( 3690): SCHEDULE_ALARM_REMOVE
D/CalendarReceiver( 3690): [onReceive] WakeLock release : CalendarReceiver_Provider
I/ActivityManager(  953): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.receiver.DmReceiver: pid=3719 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/LAlarm  (  953): Service started flags 0 startId 3
W/ContextImpl( 3719): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmNotiService.bootCompleted:575 com.lge.lgdmsclient.receiver.DmReceiver.onReceive:94 
E/LGDMClient( 3719): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 3719): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 3719): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_BOOTUP_COMPLETE
D/LGDMClient( 3719): [DmUtil.java] [removeSilenceBootFile()] : [894] : Try to remove a Silence file
D/LGDMClient( 3719): [DmNotiService.java] [actionSystemBootComplete()] : [459] : CHECK_AUTO_UPDATE_PROCESS : 0 Call removeSilenceBootFile() 
I/LGDMClient( 3719): [DmNotiService.java] [actionSystemBootComplete()] : [467] : DM Service on boot completed
D/LGDMClient( 3719): [DmClientController.java] [startService()] : [400] : startService(), DownloadService will be started in order to follow the start of DmClientController
W/ContextImpl( 3719): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.controller.DmClientController.startService:404 com.lge.lgdmsclient.dmclient.controller.DmClientController.getInstance:345 com.lge.lgdmsclient.service.DmNotiService.actionSystemBootComplete:474 
I/ActivityManager(  953): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=3738 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
D/LGDMClient( 3719): [DmAgent.java] [<init>()] : [164] : DmAgent is started -> DmConstants.DMAgentState.mDmaState = 0
I/LGDMClient( 3719): [DmCAConfigParser.java] [getInstance()] : [73] : DmsCAConfigParser sInstance null
I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 22.341ms
D/LGDMClient( 3719): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [204] : Current MultiSimEnabled is false
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 23.451ms
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/AndroidRuntime( 3715): 
D/AndroidRuntime( 3715): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/LGDMClient( 3719): [DmClientController.java] [run()] : [178] : LooperSTART
D/LGDMClient( 3719): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [239] : getPhoneSpecificInfo: sim mccmnc(),spn(),gid(null),imsi(null)
I/LGDMClient( 3719): [DmCAConfigParser.java] [parse()] : [108] : parse
D/AndroidRuntime( 3715): CheckJNI is OFF
D/LGDMClient( 3719): [DmCAConfigParser.java] [setDefaultProfile()] : [490] : setDefaultProfile
D/LGDMClient( 3719): [DmCAConfigParser.java] [setDefaultProfile()] : [493] : filename : fota_dm_settings.xml
D/LGDMClient( 3719): [DmCAConfigParser.java] [setDefaultProfile()] : [506] : [UI4.1] Search [fota_dm_settings.xml]
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 26.727ms
D/LGDMClient( 3719): [DmCAConfigParser.java] [parse()] : [134] : [UI4.1] Search [fota_dm_settings.xml]
D/LGDMClient( 3719): [DmAgentUtil.java] [setAutoAgentSchedule()] : [117] : IN setAutoAgentSchedule()
D/LGDMClient( 3719): [DmAgentUtil.java] [setAutoAgentSchedule()] : [126] :  cursor != null setAutoAgentSchedule()
D/LGDMClient( 3719): [DmAgentUtil.java] [setAutoAgentSchedule()] : [167] : SET ALARM setAutoAgentSchedule() = 20160114T212428
D/LGDMClient( 3719): [DmAgentUtil.java] [setAutoAgentSchedule()] : [185] : OUT setAutoAgentSchedule()
D/LGDMClient( 3719): [DmAgent.java] [checkPostponed()] : [2062] : DMAGentState is: DmConstants.DMAgentState.mDmaState = 0
V/LGDMClient( 3719): [DmClientController.java] [handleMessage()] : [181] : DmClientController: run() - msg.what=31
D/LGDMClient( 3719): [DmAgent.java] [processRestartHandler()] : [1241] : DMAGentState is: DmConstants.DMAgentState.mDmaState = 0
E/LGDMClient( 3719): [DmDownloadService.java] [onCreate()] : [56] : DmDownloadService.onCreate()
D/LGDMClient( 3719): [DmDownloadService.java] [onStartCommand()] : [92] : DmDownloadService.onStartCommand()
D/LGDMClient( 3719): [DmDownloadService.java] [handleStart()] : [103] : DmDownloadService  intend : Intent { cmp=com.lge.lgdmsclient/.service.DmDownloadService }
E/[LGE_FOTA] ( 3719): FOTA JNI_OnLoad
E/[LGE_FOTA] ( 3719):  FOTAJNI_GetUAResult in
E/[LGE_FOTA] ( 3719): FOTAFS_Open /cache/fota/usd.dat, 0, handle : 1c
E/[LGE_FOTA] ( 3719): enUpdateState                : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.enState             : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[0]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[0]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[1]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[1]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[2]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[2]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[3]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[3]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[4]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[4]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[5]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[5]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[6]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[6]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[7]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[7]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[8]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[8]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[9]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[9]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[10]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[10]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[11]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[11]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[12]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[12]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[13]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[13]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[14]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[14]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgOffset[15]     : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiPkgSize[15]       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiCurrSection       : 0x00000000
E/[LGE_FOTA] ( 3719): stFWInfo.uiResult            : 0x00000000
E/[LGE_FOTA] ( 3719): stFSInfo.enState             : 0x00000000
E/[LGE_FOTA] ( 3719): stFSInfo.uiFilePackageOffset : 0xa09397d4
E/[LGE_FOTA] ( 3719): stFSInfo.uiFilePackageSize   : 0xa09397f4
E/[LGE_FOTA] ( 3719): stFSInfo.uiResult            : 0x00000000
E/[LGE_FOTA] ( 3719): stPkgInfo.enPackageType      : 0x00000000
E/[LGE_FOTA] ( 3719): stPkgInfo.uiSize             : 0x00000000
E/[LGE_FOTA] ( 3719): stPkgInfo.uiWrittenAddr      : 0x00000000
E/[LGE_FOTA] ( 3719): stPkgInfo.uiWrittenSize      : 0x00000000
E/[LGE_FOTA] ( 3719): stPkgInfo.szPackagePath      : 
E/[LGE_FOTA] ( 3719): stCommand.enCommand	 		: 0x00000000
E/[LGE_FOTA] ( 3719): uiBackupBufferAddr			: 0x00000000
E/[LGE_FOTA] ( 3719): uiLanguage					: 0x00000000
E/[LGE_FOTA] ( 3719): stDebug.uiResetCount			: 0x00000000
E/[LGE_FOTA] ( 3719): stDebug.uiRetryCount			: 0x00000000
E/[LGE_FOTA] ( 3719): FOTAFS_Close 1c
E/[LGE_FOTA] ( 3719): FOTAJNI_GetConvertedUAResult : 450
E/[LGE_FOTA] ( 3719): FOTAJNI_GetUAResult : 450
D/LGDMClient( 3719): [SwUpdate.java] [getSwUpdateStatus()] : [244] : Software update result:450
D/LGDMClient( 3719): [DmAgent.java] [restartIdleSession()] : [1084] : skymymy is: iSwUpdateStatus = 450, isUpgradedByLGUP() = false
D/LGDMClient( 3719): [DmAgent.java] [clearContext()] : [1774] : [Enter] clearContext
I/LGDMClient( 3719): [DmAgent.java] [setState()] : [1875] : Setting Agent State and State is : DmConstants.DMAgentState.mDmaState = 0
D/LGDMClient( 3719): [DmAgent.java] [clearContext()] : [1791] : [Exit] clearContext
V/LGDMClient( 3719): [DmClientController.java] [handleMessage()] : [181] : DmClientController: run() - msg.what=33
D/LGDMClient( 3719): [DmClientController.java] [stopService()] : [408] : stopDownloadService(), DownloadService will be stopped in order to follow the end of DmClientController
W/ContextImpl( 3719): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 com.lge.lgdmsclient.dmclient.controller.DmClientController.stopService:412 com.lge.lgdmsclient.dmclient.controller.DmClientController.clearController:383 com.lge.lgdmsclient.dmclient.controller.DmClientController.access$200:68 
D/LGDMClient( 3719): [DmDownloadService.java] [onDestroy()] : [117] : DmDownloadService.onDestroy()
I/ActivityManager(  953): Killing 3445:com.android.gallery3d/u0a23 (adj 15): empty #11
D/ALBootInit( 3738): ====action==>android.intent.action.BOOT_COMPLETED
D/ALBootInit( 3738): Alarm ALBootInit: BOOT_COMPLETED
I/ALProvider( 3738): delete where======= time <= 1452528589918  and  aindex > 0
D/Alarms  ( 3738):  --- disableExpiredAlarms!!! isBooting : true
W/libprocessgroup(  953): failed to open /acct/uid_10023/pid_3445/cgroup.procs: No such file or directory
D/AndroidRuntime( 3715): Calling main entry com.android.commands.am.Am
I/ActivityManager(  953): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/art     (  953): Explicit concurrent mark sweep GC freed 13792(618KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 3.968ms total 140.282ms
D/Alarms  ( 3738): count ===>0
D/Alarms  ( 3738): snoozeActivating scount==>0
D/Alarms  ( 3738): [setNextAlert] start
D/Alarms  ( 3738): [setNextAlert] (1)
D/Alarms  ( 3738):  minTime  = 0
D/Alarms  ( 3738):  -- OK multi -- 0
D/ActivityManager(  953): setTaskToReturnTo : TaskRecord{3f5bd75b #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  953): setTaskToReturnTo : TaskRecord{3f5bd75b #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
E/jeny.kim( 3738): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 3738): [setNextAlert]setNextAlert temp_AlarmLinkText + 
D/WindowStateEx(  953): AppWindowTokenEx init.. 
D/ContextHelper(  953): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  953): Focus left window: Window{17d73008 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 3715): Shutting down VM
I/[LGHome]EVENT( 1965): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  953): check instance of lgWin Window{2bd7810d u0 Starting com.example.hello}
I/CommonUtil( 3738): BUILD Operator: OPEN
I/ActivityManager(  953): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3771 uid=10317 gids={50317, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1965): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/Alarms  ( 3738): broadcastToWidgetProvider : false
I/HotwordDetector( 2044): Closing mic
I/MicrophoneInputStream( 2044): mic_close com.google.android.apps.gsa.speech.audio.u@baac454
V/AudioRecord( 2044): stop()
D/AudioRecord( 2044): AudioRecord->stop()
V/AudioFlinger(  286): RecordHandle::stop()
V/AudioFlinger(  286): RecordThread::stop
D/Alarms  ( 3738): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/AudioFlinger(  286): Record stopped OK
V/AudioPolicyManager(  286): stopInput() input 17
V/AudioPolicyService(  286): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  286): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  286): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  286): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  286): ThreadBase::setParameters() routing=0
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb3c6e000
D/audio_hw_primary(  286): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/SettingsProvider(  953): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
D/CommonUtil( 3738): Enter deleteUnnecessaryToneItem() enter excepted tone uri value is null, preferparent value is  ALARM
I/[LGHome]EVENT( 1965): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  953): Starting window displayed
I/SystemUI[Framework](  953): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
D/PhoneStatusBar( 1389): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  953): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  953): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  953): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  953): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1891d12f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  953): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1389): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1389):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1389): , Keyguard show=false, IME shown=false, Panel expanded=false
V/audio_hw_primary(  286): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  286): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  286): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  286): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  286): disable_audio_route: exit
E/audio_hw_primary(  286): disable_snd_device: enter 144
D/hardware_info(  286): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  286): disable_snd_device: snd_device(144: lg-vr-handset-mic)
D/BarTransitions( 1389): draw background and invalidate : color = b000000
V/audio_hw_primary(  286): stop_input_stream: exit: status(0)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  286): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  286): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  286): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  286): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  286): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  286): setParameters(): io 17, keyvalue hotword_active=0, calling pid 286
V/AudioFlinger(  286): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  286): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  286): in_set_parameters: exit: status(0)
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb3c6e000
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
D/BarTransitions( 1389): draw background and invalidate : color = 14131313
V/AudioRecord( 2044): stop()
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioRecord( 2044): stop()
V/AudioRecord( 2044): stop()
V/AudioFlinger(  286): RecordHandle::stop()
V/AudioFlinger(  286): RecordThread::stop
V/AudioPolicyManager(  286): releaseInput() 17
V/AudioPolicyManager(  286): closeInput(17)
V/AudioFlinger(  286): closeInput() 17
V/AudioSystem(  286): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2095): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  286): ThreadBase::exit
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioSystem( 3148): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  286): RecordThread 0xb3c6e000 exiting
D/audio_hw_primary(  286): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  286): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioPolicyService(  286): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  286): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): releaseInput() exit
V/AudioFlinger(  286): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  286): removeClient_l() pid 2044, calling pid 286
V/AudioSystem(  953): ioConfigChanged() event 4, ioHandle 17
D/CommonUtil( 3738): deleteUnnecessaryToneItem() -> Alarm Surviv Count is 0
D/CommonUtil( 3738): Exit deleteUnnecessaryToneItem()
V/AudioSystem( 1389): ioConfigChanged() event 4, ioHandle 17
,V/AudioSystem( 1794): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2044): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2120): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  286): releasing 16 from 2044 for -1
V/AudioFlinger(  286):  decremented refcount to 0
V/AudioFlinger(  286): purging stale effects
I/HotwordRecognitionRnr( 2044): Stopping hotword detection.
I/HotwordRecognitionRnr( 2044): Hotword detection finished
I/CommonUtil( 3738): BUILD Country: EU
I/TimerReceiver( 3738): onReceiveIntent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.lge.clock/.timer.TimerReceiver (has extras) }
D/TimerReceiver( 3738): onReceive() : android.intent.action.BOOT_COMPLETED
I/TimerReceiver( 3738): setTimerDone
D/TimerObj( 3738): --------------------- getTimersFromSharedPrefs
D/ContextHelper( 3771): convertTheme. context->name=com.example.hello themeResourceId=16973833
V/TimerObj( 3738): --------------------- timers list is empty
I/ActivityManager(  953): Start proc com.lge.appbox.client:SingleBinaryService for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver: pid=3802 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  953): Killing 3489:com.google.android.onetimeinitializer/u0a8 (adj 15): empty #11
I/WebViewFactory( 3771): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/libprocessgroup(  953): failed to open /acct/uid_10008/pid_3489/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 3802): AppBoxApplication onCreate()
I/LibraryLoader( 3771): Time to load native libraries: 6 ms (timestamps 1064-1070)
I/LibraryLoader( 3771): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3771): Binding Chromium to main looper Looper (main, tid 1) {3196200e}
I/LibraryLoader( 3771): Expected native library version number "",actual native library version number ""
I/chromium( 3771): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/AppUp4:SingleBinary( 3802): /cust/OPEN_EU/config/app-enabled-conf.json is selected!!
D/AppUp4:SingleBinary( 3802):  Starting isFingerChanged 
I/BrowserStartupController( 3771): Initializing chromium process, singleProcess=true
W/art     ( 3771): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3771): ApplicationContext is null in ApplicationStatus
W/chromium( 3771): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/CalendarProvider2( 3690): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3690): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
E/libEGL  ( 3771): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3771): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3771): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3771): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3771): Build Date: 03/02/15 Mon
I/Adreno-EGL( 3771): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 3771): Remote Branch: 
I/Adreno-EGL( 3771): Local Patches: 
I/Adreno-EGL( 3771): Reconstruct Branch: 
I/ActivityManager(  953): Start proc com.lge.appbox.client for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider: pid=3825 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  953): Killing 3523:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10016/pid_3523/cgroup.procs: No such file or directory
V/AudioPolicyService(  286): registerClient() client 0xb4027080, uid 10317
D/BluetoothManagerService(  953): Message: 20
D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12517327:true
D/BluetoothAdapterService(530067226)( 2095): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176f3840
I/AppUp4:AppBoxCP( 3825): onCreate
W/AppUp4:DB( 3825):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 3825):  setFingerPrint start
I/AppUp4:DB( 3825):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 3825):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 3825):  SDK version = 0
I/AppUp4:DB( 3825):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 3825): AppBoxApplication onCreate()
D/AppUp4:SingleBinary( 3802):  The value of isFingerChanged null
D/AppUp4:SingleBinary( 3802): Device : jagnm
D/AppUp4:SingleBinary( 3802): First Boot - ignore boot completed
D/AppUp4:NTCodeSingleBinary( 3802): Starting isFingerChanged 
D/AppUp4:NTCodeSingleBinary( 3802): The value of isFingerChanged lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
D/AppUp4:SingleBinary( 3802): Device : jagnm
D/AppUp4:SingleBinary( 3802): Config file is not exist - nothing
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/AppUp4:SDKReflector( 3825): +myUserId : 0
D/AppUp4:BootUpPollingReceiver( 3825): onReceive on user ID : 0
V/AppUp4:FotaPlusService( 3825):  isFotaPlusTriedOnce : true
D/AppUp4:BootUpPollingReceiver( 3825): Starting getSdkVersion 
D/AppUp4:BootUpPollingReceiver( 3825): SDK version is : 0
D/AppUp4:BootUpPollingReceiver( 3825): currentSdkVersion : 0
D/AppUp4:BootUpPollingReceiver( 3825): isSdkVersionChanged : true
V/AppUp4:FotaPlusService( 3825):  setFotaPlusCompleted : false
D/AppUp4:BootUpPollingReceiver( 3825): isFotaPlusNeeded : true
D/AppUp4:BootUpPollingReceiver( 3825): Fota Plus already tried once, show notification
V/NotificationService(  953): enqueueNotificationInternal: pkg=com.lge.appbox.client id=22319582 notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
D/ZenLog  (  953): intercepted: 0|com.lge.appbox.client|22319582|null|10011,none
D/AppUp4:BootUpPollingReceiver( 3825): isFotaPlusRunning after : true
V/NotificationService(  953): pkg=com.lge.appbox.client canInterrupt=false intercept=true
D/AppUp4:BootUpPollingReceiver( 3825):  installPreloadedValuePackIfNeeded 
I/NotificationServiceEx(  953): LED remove() : mLights=0|com.lge.appbox.client|22319582|null|10011
D/NotificationServiceEx(  953): updateLightListLocked :r=0|com.lge.appbox.client|22319582|null|10011, action=2
D/NotificationServiceEx(  953): notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
D/AppUp4:BootUpPollingReceiver( 3825):  file is : /system/apps/bootup
D/AppUp4:BootUpPollingReceiver( 3825): file false
D/AppUp4:BootUpPollingReceiver( 3825): [BootUpPollingReceiver] No preload installation.
D/AppUp4:dwnld( 3825): [removeAllIncompletedDownload] ... 
V/AppUp4:BootUpPollingReceiver( 3825): [BootUpPollingReceiver] start bootup Polling.
D/SmartCoverUpdateMonitor( 1348): onNotificationPosted() : StatusBarNotification(pkg=com.lge.appbox.client user=UserHandle{0} id=22319582 tag=null score=0 key=0|com.lge.appbox.client|22319582|null|10011: Notification(pri=0 contentView=com.lge.appbox.client/0x1090079 vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE))
D/SmartCoverUpdateMonitor( 1348): onNotificationPosted() !qcn.isEnableToShowNotification()
D/AppUp4  ( 3825): getUpdatePollingPeriod
D/AppUp4  ( 3825): getUpdatePollingPeriod
,D/AppUp4:BackgroundPollingService ( 3825): register polling alarm when : 2016/01/14 21:32:00
D/AppUp4:LightWeightPollingService ( 3825):  [buildRemotePollingIntent]
D/AppUp4:LightWeightPollingService ( 3825): This means remote config is N, so skip it
W/art     ( 3771): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  953): Killing 3573:com.lge.email/u0a21 (adj 15): empty #11
W/AwContents( 3771): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3771): CordovaWebView is running on device made by: LGE
,W/libprocessgroup(  953): failed to open /acct/uid_10021/pid_3573/cgroup.procs: No such file or directory
W/art     ( 3771): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3771): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  953): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3864 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/MmsConfig( 3148): isNotAllowedSms: currentUser:0
D/MmsConfig( 3148): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3148): isUserMode:false
D/SmsReceiverService( 3148): handleMessage isUserMode:false
,I/[SystemUI]PhoneStatusBar( 1389): updateMediaMetaData(false): mMediaMetadata = null
I/Activity( 3771): Activity.onPostResume() called 
W/ResourcesManager( 3148): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/OpenGLRenderer( 3771): Render dirty regions requested: true
I/OpenGLRenderer( 3771): Initialized EGL, version 1.4
D/OpenGLRenderer( 3771): Enabling debug mode 0
,V/SmsReceiverService( 3148): handleMessage action: android.intent.action.BOOT_COMPLETED error: 0
,D/Atlas   ( 3771): Validating map...
D/SplitWindow(  953): check instance of lgWin Window{393d2588 u0 com.example.hello/com.example.hello.MainActivity}
W/chromium( 3771): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  953): Killing 2406:com.android.defcontainer/u0a4 (adj 15): empty #11
W/ResourcesManager( 3864): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/libprocessgroup(  953): failed to open /acct/uid_10004/pid_2406/cgroup.procs: No such file or directory
,D/InputDispatcher(  953): Focus entered window: Window{393d2588 u0 com.example.hello/com.example.hello.MainActivity}
,D/CalendarApplication( 3864): CalendarApplication.onCreate()
D/PreferenceKeysParser( 3864): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 3864): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@18f613d3, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@302eb10, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@a3d2609, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3196200e, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@33841a2f, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1e93a83c, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1c8919c5, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1f982f1a, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1a422a4b, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@18110c28, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3fe68d41, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@357a22e6, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@1f872027, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1d7ec2d4, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@324dbc7d, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@20358772, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3a3b97c3, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@176f3840, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1efea379, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@30d0a8be, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@1d35ed1f, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@232f986c, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@b3cfe35, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@306a92ca, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@28563c3b, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3b3cf58, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@12cc48b1, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@29071196, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@f626117, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@35428904, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@302bbeed, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2f1ab122, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@12a1f7b3, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@fe13170, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@c925ce9, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@37d6bd6e, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@253a5c0f, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@247ff49c, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@13aadea5, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@835427a, lg_preferences_alerts_vibratetype=com.android.calendar,.adaptation.PreferenceKey$KeyData@1d4aaa2b, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@e5be88
D/GeneralPreferenceUtils( 3864): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
W/InputMethodManagerService(  953): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/ActivityManager(  953): Displayed com.example.hello/.MainActivity: +1s35ms
I/Timeline(  953): Timeline: Activity_windows_visible id: ActivityRecord{211a9bf8 u0 com.example.hello/.MainActivity t220} time:51732
D/Config  ( 3864): [init]
I/Config  ( 3864): LGCalendar ver.4.40.17
I/Config  ( 3864): start check model
I/Config  ( 3864): start check native_ca
I/Config  ( 3864): Config Operator=OPEN, Country=EU
,D/Config  ( 3864): [setDefaultValuesToPref]
D/Config  ( 3864): [parseProfiles]
D/ProfilesParser( 3864): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 3864): [debug_displayParseInfos] profile.operator = null
D/Config  ( 3864): [updateProfiletoCountryInfo]
D/GeneralPreference( 3864): [checkAndMigrateOldPreference]
I/Timeline( 3771): Timeline: Activity_idle id: android.os.BinderProxy@b3cfe35 time:51749
,D/AlertReceiver( 3864): onReceive: a=android.intent.action.BOOT_COMPLETED Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.calendar/.alerts.AlertReceiver (has extras) }
,I/InitNotificationRingtoneService( 3864): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 3864): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,D/UsbSettingsReceiver( 3272): [AUTORUN] onReceive() : action = android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3272): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3272): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3272): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3272): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 3272): [AUTORUN] setTetherStatus() : status=false
,D/UsbSettingsReceiver( 3272): [AUTORUN] onReceive() : android.intent.action.BOOT_COMPLETED
,D/UsbSettingsReceiver( 3272): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3272): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3272): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/StoreModeReceiver( 3272): intent.getAction() : android.intent.action.BOOT_COMPLETED
D/StoreModeReceiver( 3272): sim state :null
D/StoreModeReceiver( 3272): Back LED don't supported.
V/SettingsProvider(  953): call_put(system:emotional_led_back_led=0) for 0 calling package = com.android.settings
V/SettingsProvider(  953): call_put(system:emotional_led_back_incoming_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  953): call_put(system:emotional_led_back_alarm=0) for 0 calling package = com.android.settings
V/SettingsProvider(  953): call_put(system:emotional_led_back_missed_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  953): call_put(system:emotional_led_back_missed_messages=0) for 0 calling package = com.android.settings
V/SettingsProvider(  953): call_put(system:emotional_led_back_missed_emails=0) for 0 calling package = com.android.settings
V/SettingsProvider(  953): call_put(system:emotional_led_back_calendar_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  953): call_put(system:emotional_led_back_voice_recording=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  953): call_put(system:emotional_led_back_camera_timer_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  953): call_put(system:emotional_led_back_camera_face_detecting_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  953): call_put(system:notification_light_pulse_back=0) for 0 calling package = com.android.settings
D/StoreModeReceiver( 3272): SystemProperty Default brightness value [0-255] : 143
D/StoreModeReceiver( 3272): Default brightness[0-255] : 143
I/AlertUtils( 3864): [getCalendarNotiSoundURIFromCursor] getCount()= 21
W/ResourcesManager( 3272): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/BindingManager( 3771): Cannot call determinedVisibility() - never saw a connection for the pid: 3771
D/StoreModeReceiver( 3272): Default Screen off timeout value : 30000
D/StoreModeReceiver( 3272): SystemProperty Default brightness Mode value[true/false] : false
D/StoreModeReceiver( 3272): BRIGHTNESS_MODE - 0
D/StoreModeReceiver( 3272): Default brightness Mode [0/1] : 0
D/StoreModeReceiver( 3272): Default NIGHT_MODE : 0
D/StoreModeReceiver( 3272): Set MaxBrightness : 255
,E/PhoneInterfaceManager( 1794): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
D/StoreModeReceiver( 3272): getPhoneNumber is empty
D/StoreModeReceiver( 3272): go to StoreModeCheck()
D/StoreModeReceiver( 3272): isStoremode not null
D/PhoneInterfaceManager( 1794): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
V/SettingsProvider(  953): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,D/StoreModeReceiver( 3272): product_name : jagnm_global_com
D/StoreModeReceiver( 3272): Store mode start!
I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
V/SettingsProvider(  953): call_put(system:shop_mode=1) for 0 calling package = com.android.settings
V/SettingsProvider(  953): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
I/PowerManagerService(  953): ALS enabled for SRE
I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
D/PowerManagerServiceEx(  953): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=120000 (in 68121 ms)
D/StoreModeReceiver( 3272): setBrightness() : NoMultiALC=255
W/ContextImpl( 3272): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.StoreModeReceiver.sendBroadcast:500 com.android.settings.StoreModeReceiver.setMode:473 
I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,V/SettingsProvider(  953): call_put(system:screen_brightness_mode=0) for 0 calling package = com.android.settings
D/SettingsProvider(  953): Set screen_off_timeout in entry value : 120000
V/SettingsProvider(  953): call_put(system:screen_off_timeout=120000) for 0 calling package = com.android.settings
I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
V/SettingsProvider(  953): call_put(system:screen_brightness=255) for 0 calling package = com.android.settings
V/SettingsProvider(  953): call_put(system:check_night_mode=0) for 0 calling package = com.android.settings
I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/chromium( 3771): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/SettingBootReceiver( 3272): onReceive
D/SettingBootReceiver( 3272): Boot Completed intent received, action=android.intent.action.BOOT_COMPLETED
I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/[SystemUI]LGBootReceiver( 1389): onReceive = android.intent.action.BOOT_COMPLETED
D/SettingBootReceiver( 3272): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3272): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3272): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
,D/SettingBootReceiver( 3272): setStyle()
D/SettingBootReceiver( 3272): SettingStyle=1
I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/[SystemUI]LGPowerUI( 1389): onReceive = com.lge.statusbar.bootcompleted
I/[SystemUI]PhoneStatusBar( 1389): got ACTION_STICKY_BOOT_COMPLETED
I/BOOT    ( 1389): got ACTION_STICKY_BOOT_COMPLETED
,I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,D/SettingBootReceiver( 3272): setAccountMenu()
I/AlertUtils( 3864): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3864): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
D/TAG     ( 3272): setKidsMode
D/TAG     ( 3272): mIsOwner, setKidsMode
D/SettingBootReceiver( 3272): setAccountMenu()
I/ActivityManager(  953): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3894 uid=10111 gids={50111, 9997, 1028, 3003} abi=armeabi-v7a
D/YSY     ( 3272): not support Quiet mode notification
I/AlertUtils( 3864): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 3864): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 3864): onHandleIntent
,D/HolidayDataLoader( 3864): readJsonAsset : holiday.json
I/ActivityManager(  953): Waited long enough for: ServiceRecord{59bb0f6 u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
,V/SettingsProvider(  953): call_put(system:gentle_vibration_status=1) for 0 calling package = com.android.settings
,D/AlertService( 3864): 0 Action = android.intent.action.BOOT_COMPLETED
V/SettingsProvider(  953): call_put(system:smart_ringtone=0) for 0 calling package = com.android.settings
D/AlertService( 3864): [Widget]com.android.calendar.widget.CalendarAppWidgetProvider enabled
,D/Feature ( 3864): MemoryLevel - 5:NOT_DEF:Not UI4.2 LOS
D/AlertService( 3864): [Widget]com.android.calendar.widget.MonthWidgetProvider enabled
D/SettingBootReceiver( 3272): timezoneID is null
D/AlertService( 3864): [Widget]com.android.calendar.widget.WeekWidgetProvider enabled
,D/JsMessageQueue( 3771): Set native->JS mode to OnlineEventsBridgeMode
,I/SettingBootReceiver( 3272): disable au
I/TAG     ( 3272): disable WirelessSettingsActivity
I/TAG     ( 3272): disable SKTPhoneMode
D/AlertService( 3864): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,E/AndroidProtocolHandler( 3771): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/HolidayIntentService( 3864): onHandleIntent:holiday data empty
,D/AlarmScheduler( 3864): No events found starting within 1 week.
D/SettingBootReceiver( 3272): [Nightmode] Enter receiver
,D/SettingBootReceiver( 3272): [Nightmode] BOOT_COMPLETED
D/NightModeInfo( 3272): [Nightmode] setNightNodeTabSettings
,D/NightModeInfo( 3272): [Nightmode] getAlreadyNightModeDB() : 0
D/NightModeInfo( 3272): [Nightmode] getUserBrightnessChange() : 0
D/NightModeInfo( 3272): [Nightmode] getUserBrightnessChangeNoNight() : 0
V/SettingsProvider(  953): call_put(system:already_night_mode=0) for 0 calling package = com.android.settings
V/SettingsProvider(  953): call_put(system:user_change_brightness=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  953): call_put(system:user_change_brightness_no_night=0) for 0 calling package = com.android.settings
V/SettingsProvider(  953): call_put(system:night_mode_enabled=0) for 0 calling package = com.android.settings
D/NightModeInfo( 3272): [Nightmode] setTabNightCheck : 0
I/ActivityManager(  953): Killing 2283:com.google.android.gms/u0a6 (adj 15): empty #11
V/SettingsProvider(  953): call_put(system:save_tab_night_check=0) for 0 calling package = com.android.settings
,D/NightModeInfo( 3272): [Nightmode] cancelPendingIntent
D/ConnectivityService(  953): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@b788d59)
,D/ConnectivityService(  953): dumpNetworkRequest
,D/ConnectivityService(  953):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  953):     Requests:
D/ConnectivityService(  953):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953):         NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953):     Lingered:
D/ConnectivityService(  953): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953): sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  953): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/libprocessgroup(  953): failed to open /acct/uid_10006/pid_2283/cgroup.procs: No such file or directory
,D/NightModeInfo( 3272): [Nightmode] requestPendingIntent
D/NightModeInfo( 3272): [Nightmode] setAlarmStart~!!~!!~!!
V/DownloadManager( 3206): Received broadcast intent for android.intent.action.BOOT_COMPLETED
D/NightModeInfo( 3272): [Nightmode] currentHour > 6
D/NightModeInfo( 3272): [Nightmode] currentHour > 6
I/NightModeInfo( 3272): JW getStartTime201601120000
D/NightModeInfo( 3272): [Nightmode] setAlarmEnd~!!~!!~!!
V/DownloadManager( 3206): DownloadService onCreate
D/NightModeInfo( 3272): [Nightmode] currentHour > 6
I/DownloadManager( 3206): in removeSpuriousFiles
,D/NightModeInfo( 3272): [Nightmode] currentHour > 6
I/NightModeInfo( 3272): JW getEndTime201601120600
D/NightModeInfo( 3272): [Nightmode] currentHour > 6
I/NightModeInfo( 3272): getStartTime201601120000
I/NotificationManager( 3206): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/NightModeInfo( 3272): [Nightmode] currentHour > 6
I/NightModeInfo( 3272): getEndTime201601120600
D/jw      ( 3272): Only VZW Supported end return
V/DownloadManager( 3206): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@1d35ed1f on behalf of 3206
V/DownloadManager( 3206): DownloadService onStartCommand
I/DownloadManager( 3206): in trimDatabase
V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3206): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/MediaScannerReceiver( 3206): [MediaScanner] ACTION_BOOT_COMPLETED scan INTERNAL_VOLUME, EXTERNAL_VOLUME
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@28563c3b on behalf of 3206
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@306a92ca on behalf of 3206
D/MediaScannerService( 3206): [MediaScanner] start scanning volume internal: [/system/media, /oem/media, /cust/OPEN_EU/media]
,V/LGMediaProvider( 3206): insertInternal: content://media/none/media_scanner, initValues=volume=internal
D/MediaScannerService( 3206): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///system/media
D/MtpService( 3206): updating state; isCurrentUser=true, mMtpLocked=false
D/WiseScreenService( 1900): [OnBootReceiver.java:24:onReceive()] iKeepScreenOn: 0
,D/WiseScreenService( 1900): [OnBootReceiver.java:28:onReceive()] iSmartVideo: 0
W/ContextImpl( 1900): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.lge.keepscreenon.OnBootReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
D/MtpService( 3206): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 3206): setAccessCapability false
,D/MediaScannerEx( 3206): [MediaScanner] scanDirectories()[0] = /system/media
D/MediaScannerEx( 3206): [MediaScanner] scanDirectories()[1] = /oem/media
D/MediaScannerEx( 3206): [MediaScanner] scanDirectories()[2] = /cust/OPEN_EU/media
I/MusicBrowser( 2120): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 }}
I/MusicBrowser( 2120): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2120): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
,I/ActivityManager(  953): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=3924 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
D/MtpService( 3206): updating state; isCurrentUser=true, mMtpLocked=false
,I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     ( 3206): Thread[1,tid=3206,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
,V/MediaScannerClient( 3206): [MediaScanner]setLocale: = en_US
E/MediaProfilesEx-JNI( 3206): register_com_lge_media_MediaProfilesEx
E/MediaRecorderEx-JNI( 3206): register_com_lge_media_MediaRecorderEx
,D/AudioSystemEx( 3206): register_com_lge_media_LGAudioSystem
E/SurfaceControlEx( 3206): register_com_lge_view_SurfaceControlEx
I/art     ( 3206): Thread[1,tid=3206,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/LGMtpDatabaseJNI( 3206): register_android_mtp_LGMtpDatabase
D/LGMtpServerJNI( 3206): register_android_mtp_LGMtpServer
I/art     ( 3206): Thread[1,tid=3206,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/MediaPlayerEx-jni( 3206): register_com_lge_view_MediaPlayerEx
I/art     ( 3206): Thread[1,tid=3206,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/        ( 3206): register_com_lge_emoji_EmojiUtil
E/MediaFileEx( 3206): Duplicate type = AVI
E/MediaFileEx( 3206): Duplicate type = ASF
E/LGMtpDatabaseJNI( 3206): android_mtp_LGMtpDatabase_setup
,D/MtpService( 3206): starting MTP server in PTP mode
D/LGMtpServer( 3206): LGMtpServer
D/LGMtpServerJNI( 3206): android_mtp_LGMtpServer_setup
D/MtpService( 3206): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 3206): setAccessCapability false
D/MtpServerEx( 3206): ANR FIX - addStorage!
V/DownloadManager( 3206): DownloadService onDestroy
,D/LGMtpServerJNI( 3206): android_mtp_LGMtpServer_run
V/MediaScannerClient( 3206): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3206): Error opening directory '/oem/media/', skipping: No such file or directory.
V/MediaScannerClient( 3206): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3206): Error opening directory '/cust/OPEN_EU/media/', skipping: No such file or directory.
D/LGMediaProvider( 3206): [MediaScanner] delete() uri = content://media/internal/file
D/LGMediaProvider( 3206): [MediaScanner] delete() completed notifyChange, uri = content://media/internal
V/MediaScannerEx( 3206): [MediaScanner] isInternalStorage : true
,V/MediaScannerEx( 3206): [MediaScanner] isInternalStorage : true
V/MediaScannerEx( 3206): [MediaScanner] isInternalStorage : true
D/MediaScanner( 3206): [MediaScanner] prescan time: 82ms
D/MediaScanner( 3206): [MediaScanner] scan time: 65ms
D/MediaScanner( 3206): [MediaScanner] postscan time: 12ms
D/MediaScanner( 3206): [MediaScanner] total time: 159ms
D/LGMediaProvider( 3206): [MediaScanner] delete() uri = content://media/none/media_scanner
I/VRBookmarkProvider( 3924): [BookmarkProvider.java:76:<init>()-[Thread:Other] BookmarkProvider
,I/VRBookmarkProvider( 3924): [BookmarkProvider.java:254:onCreate()-[Thread:Other] onCreate
I/VRBookmarkProvider( 3924): [BookmarkProvider.java:504:registerObservers()-[Thread:Other] registerObservers : content://media/external/audio/media
D/VRBootCompletedReceiver( 3924): [BootCompletedReceiver.java:25:onReceive()-[Thread:Other] Controller has been started on Boot complete
D/VRBootCompletedReceiver( 3924): [BootCompletedReceiver.java:47:onReceive()-[Thread:Other] Voice Recorder launcher enable(1)/disable(2) : 1
,I/ActivityManager(  953): Killing 3555:com.lge.settings.easy/1000 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_3555/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1926): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1926): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 17:09:51.959 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LGBootCompleteReceiver( 1794): onReceive : android.intent.action.BOOT_COMPLETED
D/ConfigUtils( 1794): setUsimOperator() : card operator = 
D/ConfigUtils( 1794): setUsimOperator() : result = null
D/MediaScannerService( 3206): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///system/media
D/ConfigUtils( 1794): setUsimOperator() : simOperator = 
D/ConfigUtils( 1794): setUsimOperator() : usimoperator = 0
D/ConfigUtils( 1794): setSupportedUsimMobilityForVoLTE() : false
I/MusicBrowser( 2120): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 }}
D/LGMediaProvider( 3206): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///system/media, path = /system/media
I/MusicBrowser( 2120): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2120): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
D/MediaScannerService( 3206): [MediaScanner] done scanning volume internal
,D/MediaScannerService( 3206): [MediaScanner] start scanning volume external: [/storage/emulated/0, /storage/external_SD]
D/ConfigUtils( 1794): This Model Voice Clarity Support : false
V/LGMediaProvider( 3206): insertInternal: content://media/none/media_scanner, initValues=volume=external
I/MusicBrowser( 2120): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2120): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2120): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2120): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2120): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2120): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MediaScannerService( 3206): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///storage/emulated/0
D/LGBootCompleteReceiver( 1794): onReceive : updateCallrejectNotify rejectCallOption : 1
V/LGMediaProvider( 3206): insertInternal: content://media/, initValues=name=external
,D/CallRejectInfoToNotify( 1794): update : tPhoneMode : false
I/NotificationManager( 1794): com.android.phone: cancel(2131493582) by com.android.phone
D/MusicBrowser( 2120): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2120): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
I/PhoneApp( 1794): saveDefaultRingtoneUriOfOwner = content://media/internal/audio/media/55
D/MusicBrowser( 2120): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2120): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2120): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2120): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2120): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
I/MusicWidget( 2670): _mediaDataObserver onChange()
D/MediaScannerEx( 3206): [MediaScanner] scanDirectories()[0] = /storage/emulated/0
D/MediaScannerEx( 3206): [MediaScanner] scanDirectories()[1] = /storage/external_SD
D/MusicBrowser( 2120): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
W/VRBookmarkProvider( 3924): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/
D/MusicBrowser( 2120): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2120): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2670): beingMusicWidget_4x2() result::false
,I/ActivityManager(  953): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=3943 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/MusicBrowser( 2120): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2120): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2670): intentReceiver onReceive() action::com.lge.music.queuechanged
,I/MusicWidget( 2670): beingMusicWidget_4x2() result::false
D/MusicBrowser( 2120): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2120): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2120): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/MusicBrowser( 2120): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2120): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
I/MusicWidget( 2670): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2120): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
I/MusicWidget( 2670): beingMusicWidget_4x1() result::true
D/MusicBrowser( 2120): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2120): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2120): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2120): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2120): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
I/MusicWidget( 2670): send mDelayedStopHandler
I/MusicWidget( 2670): performViewUpdater handleMessage() msg.what::3
D/MusicBrowser( 2120): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2120): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2670): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2120): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicWidget( 2670): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicWidget( 2670): beingMusicWidget_4x2() result::false
I/MusicWidget( 2670): beingMusicWidget_Quick() result::false
I/MusicWidget( 2670): beingMusicWidget_4x1() result::true
I/MusicWidget( 2670): send mDelayedStopHandler
I/MusicWidget( 2670): performViewUpdater handleMessage() msg.what::3
,D/jxcore_app_log( 3771): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426135552
D/JX-Cordova( 3771): jxcore cordova android initializing
I/MusicBrowser( 2120): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2120): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2120): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2120): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2120): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicWidget( 2670): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2120): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2120): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2120): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2120): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
I/MusicBrowser( 2120): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
,I/MusicBrowser( 2120): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 2120): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2120): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
,W/MusicBrowser( 2120): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2120): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2120): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2120): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2120): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2120): - End   trace [MusicUtils.query]---------------------------------------------------------------
,V/MediaScannerClient( 3206): [MediaScanner]setLocale: = en_US
,W/jxcore-log( 3771): Initializing JXcore engine
W/jxcore-log( 3771): JXcore engine is ready
,V/DrmBroadcastReceiver( 3943): Receive ACTION_BOOT_COMPLETED
W/jxcore-log( 3771): Starting JXcore engine
V/DrmService( 3943): Service onCreate
D/DrmService( 3943): Received new request = 4
I/art     ( 3206): Explicit concurrent mark sweep GC freed 14783(795KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 8MB/10MB, paused 576us total 58.866ms
,D/DrmServiceHandler( 3943): updateDrmPushNotification() : No notification
D/DrmService( 3943): Completed !! request = 4
,D/DrmService( 3943): Request count = 0
I/ActivityManager(  953): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=3962 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/MusicWidget( 2670): performViewUpdater handleMessage() msg.what::0
,V/DrmService( 3943): Service onDestroy
,I/ActivityManager(  953): Killing 3659:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,I/MusicWidget( 2670): beingMusicWidget_4x1() result::true
I/MusicWidget( 2670): performUpdate()_4x1
I/MusicWidget( 2670): defaultAppWidget()_4x1
W/m.example.hello( 3771): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7353]" dev="sockfs" ino=7353 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
I/MusicWidget( 2670): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2670): 4x1_currentTheme :: null
I/MusicWidget( 2670): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2670): setDefaultViewLayoutId()_4x1
W/m.example.hello( 3771): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3771): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8422]" dev="sockfs" ino=8422 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3771): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3771): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,W/m.example.hello( 3771): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[18190]" dev="sockfs" ino=18190 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/MusicWidget( 2670): appWidgetViewUpdate()_4x1
I/MusicWidget( 2670): linkButtons()_4x1
,D/MediaScannerEx( 3206): [MediaScanner] beginFile() path = /storage/emulated/0/QuicksetLite Setup/data
,V/MediaScannerClient( 3206): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3206): Error opening directory '/storage/external_SD/', skipping: Permission denied.
D/LGMediaProvider( 3206): [MediaScanner] delete() uri = content://media/external/file
W/MusicBrowser( 2120): - Start trace [MusicUtils.query]---------------------------------------------------------------
D/LGMediaProvider( 3206): [MediaScanner] delete() completed notifyChange, uri = content://media/external
W/MusicBrowser( 2120): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2120): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2120): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2120): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2120): - End   trace [MusicUtils.query]---------------------------------------------------------------
W/VRBookmarkProvider( 3924): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/external
W/VRBookmarkProvider( 3924): [BookmarkProvider.java:563:onChange()-[Thread:Other] EXTERNAL Change!!
,V/MediaScanner( 3206): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@12a1f7b3
V/MediaScanner( 3206): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@12a1f7b3
D/MediaScanner( 3206): [MediaScanner] prescan time: 145ms
D/MediaScanner( 3206): [MediaScanner] scan time: 154ms
D/MediaScanner( 3206): [MediaScanner] postscan time: 10ms
D/MediaScanner( 3206): [MediaScanner] total time: 309ms
D/LGMediaProvider( 3206): [MediaScanner] delete() uri = content://media/none/media_scanner
D/MediaScannerService( 3206): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///storage/emulated/0
W/libprocessgroup(  953): failed to open /acct/uid_10009/pid_3659/cgroup.procs: No such file or directory
,D/LGMediaProvider( 3206): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///storage/emulated/0, path = /storage/emulated/0
D/MediaScannerService( 3206): [MediaScanner] done scanning volume external
I/MusicWidget( 2670): pushUpdate()_4x1
I/MusicBrowser( 2120): [MediaPlaybackService.java:1995:onChange()] oooooo 
,V/MusicBrowser( 2120): [MediaPlaybackService.java:5808:getPath()] oooooo {mFileToPlay=null}
I/MusicBrowser( 2120): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 2120): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2120): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
I/MusicWidget( 2670): performViewUpdater handleMessage() msg.what::1
I/MusicBrowser( 2120): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2120): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
,D/MusicBrowser( 2120): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2120): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2120): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2120): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2120): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicWidget( 2670): beingMusicWidget_4x2() result::false
I/MusicWidget( 2670): _mediaDataObserver onChange()
I/MusicBrowser( 2120): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2120): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2120): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2120): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2120): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2120): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2120): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
I/MusicWidget( 2670): beingMusicWidget_4x2() result::false
D/MusicBrowser( 2120): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2120): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2670): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicWidget( 2670): beingMusicWidget_4x2() result::false
I/MusicWidget( 2670): beingMusicWidget_Quick() result::false
I/MusicWidget( 2670): beingMusicWidget_4x1() result::true
I/MusicWidget( 2670): send mDelayedStopHandler
I/MusicWidget( 2670): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2670): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2120): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2120): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2120): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2120): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2120): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
,D/MusicBrowser( 2120): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2120): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2120): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2120): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2120): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2120): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2120): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2120): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2120): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2120): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2670): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicBrowser( 2120): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicWidget( 2670): beingMusicWidget_4x2() result::false
I/MusicWidget( 2670): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2120): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicWidget( 2670): beingMusicWidget_4x1() result::true
I/MusicBrowser( 2120): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2670): send mDelayedStopHandler
I/MusicWidget( 2670): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2670): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2120): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2120): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2120): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2120): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2120): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
E/MusicBrowser( 2120): [GroupingIndexDataProvider.java:381:onCancelled()] oooooo ASYNCTASK is canceled
I/[LgeWidgetLib]LgeAppWidgetHostView( 1965): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/MusicBrowser( 2120): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2120): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
I/MusicBrowser( 2120): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
E/[LgeWidgetLib]LgeAppWidgetHostView( 1965): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,V/CloudHub( 3962): [DATABASE][DBConnection|open] open database
,E/CloudHub( 3962): [DATABASE][DBConnection|getUserId] User id: 0
E/CloudHub( 3962): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
W/jxcore-log( 3771): Platform android
W/jxcore-log( 3771): 
W/jxcore-log( 3771): Process ARCH arm
W/jxcore-log( 3771): 
V/CloudHub( 3962): [SERVICE][CloudHubReceiver|queryUploadCount] # of contents to upload: 0
,V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@fe13170 on behalf of 3962
V/CloudHub( 3962): [SERVICE][CloudHubReceiver|queryDownloadCount] # of contents to download: 0
I/MusicWidget( 2670): performViewUpdater handleMessage() msg.what::0
,I/ActivityManager(  953): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=3981 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  953): Killing 3690:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/jxcore-log( 3771): JXcore Cordova bridge is ready!
I/jxcore-log( 3771): 
W/jxcore-log( 3771): JXcore engine is started
I/MusicWidget( 2670): beingMusicWidget_4x1() result::true
I/MusicWidget( 2670): performUpdate()_4x1
,I/MusicWidget( 2670): defaultAppWidget()_4x1
I/MusicWidget( 2670): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2670): 4x1_currentTheme :: null
I/MusicWidget( 2670): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2670): setDefaultViewLayoutId()_4x1
I/VRBookmarkProvider( 3924): [BookmarkProvider.java:530:handleMessage()-[Thread:Other] -- syncTable() START --
I/MusicWidget( 2670): appWidgetViewUpdate()_4x1
I/MusicWidget( 2670): linkButtons()_4x1
,E/jxcore-log( 3771): >> LGE-LG-D722
E/jxcore-log( 3771): 
,I/jxcore-log( 3771): Total memory 906309632
I/jxcore-log( 3771): 
I/jxcore-log( 3771): Free memory 31748096
I/jxcore-log( 3771): 
I/jxcore-log( 3771): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3771): 
I/jxcore-log( 3771): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3771): 
I/jxcore-log( 3771): userPath [ 'www', 'www' ]
I/jxcore-log( 3771): 
I/jxcore-log( 3771): Size 720 1196
I/jxcore-log( 3771): 
,I/jxcore-log( 3771): Screen Brightness 255
I/jxcore-log( 3771): 
W/libprocessgroup(  953): failed to open /acct/uid_10014/pid_3690/cgroup.procs: No such file or directory
E/jxcore-log( 3771): Dummy Error Log.
E/jxcore-log( 3771): 
,I/MusicWidget( 2670): pushUpdate()_4x1
I/VRBookmarkProvider( 3924): [BookmarkProvider.java:532:handleMessage()-[Thread:Other] -- syncTable() END --
I/MusicWidget( 2670): performViewUpdater handleMessage() msg.what::1
I/MusicWidget( 2670): beingMusicWidget_4x2() result::false
D/AirTest ( 3981): Set airtest_enable to false
I/ActivityManager(  953): Killing 3719:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1965): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1965): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_3719/cgroup.procs: No such file or directory
V/LGSC    ( 2804): [104] 401
,I/ActivityManager(  953): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=3999 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TARGETVALIDLATION_RECEIVER( 3999): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
,D/TARGETVALIDLATION_RECEIVER( 3999): updateFlag = new File(TARGET_FLAG_PATH)
D/TARGETVALIDLATION_RECEIVER( 3999): Do Not display result dialog. it is not used Update Tool!!
I/ActivityManager(  953): Killing 3738:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10010/pid_3738/cgroup.procs: No such file or directory
V/LGSC    ( 1794): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
,W/ContextImpl( 2763): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2663 
,E/AtFwd AutoBoot( 2763): AtFwd Auto Boot Started Successfully
I/GoogleHttpClient( 2079): GMS http client unavailable, use old client
,I/ActivityManager(  953): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=4021 uid=10062 gids={50062, 9997} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 31.409ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.030ms
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.793ms
,I/InsertAccount( 4021): The account already exists
I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  953): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=4039 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 3802:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
,I/jxcore-log( 3771): getBuffer is called!!!!
I/jxcore-log( 3771): 
W/libprocessgroup(  953): failed to open /acct/uid_10011/pid_3802/cgroup.procs: No such file or directory
,I/InsertAccount( 4021): The account info in contact DB already exists
,I/art     (  953): Explicit concurrent mark sweep GC freed 17830(858KB) AllocSpace objects, 3(237KB) LOS objects, 33% free, 23MB/34MB, paused 2.233ms total 177.501ms
,W/ResourcesManager( 4039): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4039): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  953): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4057 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicBrowser( 2120): [MediaPlaybackService.java:2010:handleMessage()] oooooo mGroupIndexHandler msg.what : 0
I/MusicBrowser( 2120): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2120): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2120): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2120): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
,I/MusicBrowser( 2120): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
,I/ActivityManager(  953): Killing 3825:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/[SMS_AD]( 4039): Intent action: android.intent.action.BOOT_COMPLETED
W/libprocessgroup(  953): failed to open /acct/uid_10011/pid_3825/cgroup.procs: No such file or directory
,W/ResourcesManager( 4057): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/[SMS_AD]( 4039): Intent action: android.intent.action.BOOT_COMPLETED
I/ActivityManager(  953): Killing 3272:com.android.settings/1000 (adj 15): empty #11
,D/CalendarProvider2( 4057): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1f56360d
,W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_3272/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2691): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 17:9:53
D/CalendarProvider2( 4057): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 4057): Created com.android.providers.calendar.CalendarAlarmManager@3196200e(com.android.providers.calendar.CalendarProvider2@1f56360d)
D/UpdateThreadPoolManager( 2691): 2 : This is isUpdating : false
,D/Weather_cast( 2691): 2 : set auto-update time : 1/11 20:9
D/WeatherAncestor( 2691): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 17:9:53
D/WeatherService( 2691): 2 : onStartCommand, intent!=null, action: android.intent.action.BOOT_COMPLETED
I/ActivityManager(  953): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=4082 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  953): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2691): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2691): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2691): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/InsertAccount( 4021): The account info in calendar DB already exists
I/Process ( 4021): Sending signal. PID: 4021 SIG: 9
,I/ActivityManager(  953): Process com.lge.defaultaccount (pid 4021) has died
,I/LockScreenSettings( 4082): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 54297083630; DSPS: 1877233; Offset : -3000074099
I/LockScreenSettings( 4082): Received Broadcast : android.intent.action.BOOT_COMPLETED
,I/ActivityManager(  953): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=4104 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BootCompleteReceiver( 4104): hasclipTray = true
,W/ContextImpl( 4104): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
I/ActivityManager(  953): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=4124 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  953): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4141 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 3894:com.android.managedprovisioning/u0a111 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10111/pid_3894/cgroup.procs: No such file or directory
V/AppCleanupService( 4124): registerAlarm
,D/AppCleanupService( 4124): noticeInterval = 2678400000
D/AppCleanupService( 4124): notiDateStr = 2016-01-20 22:41:42
D/AppCleanupService( 4124): noticeStart = 2016-01-20 22:41:42
,D/AppCleanupService( 4124): noticeStart = 1453326102000
D/AppUsageDbAdapter( 4124): initPreloadedAppToTheDB() : row count = 183
,E/UpdateRequestReceiver( 4141): ignoring update request
,E/UpdateRequestReceiver( 4141): ignoring update request
E/UpdateRequestReceiver( 4141): ignoring update request
,E/UpdateRequestReceiver( 4141): ignoring update request
E/UpdateRequestReceiver( 4141): ignoring update request
E/UpdateRequestReceiver( 4141): ignoring update request
,I/ActivityManager(  953): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4171 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  953): Killing 3924:com.lge.voicerecorder/u0a34 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10034/pid_3924/cgroup.procs: No such file or directory
,D/SIMObserver( 4171): action:android.intent.action.BOOT_COMPLETED
,D/SIMObserver( 4171): handle ACTION_BOOT_COMPLETED
I/ActivityManager(  953): Killing 3943:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10051/pid_3943/cgroup.procs: No such file or directory
,E/QcrilMsgTunnelAutoboot( 2322): Received Intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot (has extras) } canStartService = false
,D/PhoneInterfaceManager( 1794): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/PhoneInterfaceManager( 1794): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/LgeGpsLocationProvider(  953): requestTime failed
,I/ActivityManager(  953): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4189 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 4189): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{389bc82c type 2 when 55115 com.android.providers.calendar} when 55115
,I/Babel_SMS( 4189): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4189): MmsConfig.loadMmsSettings
I/Babel_SMS( 4189): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4189): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4189): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4189): MmsConfig.loadFromResources
E/Babel_SMS( 4189): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4189): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 4189): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4189): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4189): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 4189): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4189): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4189): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4189): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4189): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4189): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4189): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4189): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4189): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4189): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4189): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4189): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4189): found sensor: Motion Accel, handle=46
I/art     ( 4189): CheckpointMarkThreadRoots callback created = 0xaaf56440
,W/Settings( 4189): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 4189): CheckpointMarkThreadRoots callback created = 0xaaf56420
I/Babel_Crash( 4189): startup - clean
I/Babel   ( 4189): deleted: false for 0
,W/AudioCapabilities( 4189): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4189): Unsupported mime audio/adpcm
W/AudioCapabilities( 4189): Unsupported mime audio/g726
W/AudioCapabilities( 4189): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4189): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4189): Unsupported mime video/mjpg
W/VideoCapabilities( 4189): Unsupported mime video/theora
W/AudioCapabilities( 4189): Unsupported mime audio/evrc
,W/AudioCapabilities( 4189): Unsupported mime audio/qcelp
W/VideoCapabilities( 4189): Unrecognized profile 2130706433 for video/avc
W/ActivityManager(  953): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  953): RTC_WAKEUP set : Alarm{2377e72e type 0 when 1452528573011 com.android.providers.contacts} when 1452528573011
V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{1e11a2cf type 2 when 55717 com.google.android.talk} when 55717
V/AlarmManager(  953): RTC_WAKEUP set : Alarm{2a066365 type 0 when 1452528595200 com.google.android.googlequicksearchbox} when 1452528595200
W/AudioCapabilities( 4189): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4189): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4189): Unsupported mime audio/evrc
W/VideoCapabilities( 4189): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 4189): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4189): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4189): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4189): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4189): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4189): onServiceConnected
W/Babel   ( 4189): Attempted to change video mute state without an active call.
,I/NotificationManager( 4189): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  953): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4233 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  953): Killing 3962:com.lge.cloudhub/u0a49 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10049/pid_3962/cgroup.procs: No such file or directory
,W/ResourcesManager( 4233): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4233): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 4233): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 4233): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4233): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  953): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=4269 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     ( 4233): CheckpointMarkThreadRoots callback created = 0xb042dd60
E/YouTube MDX( 4233): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd( 4233): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4233): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     ( 4233): CheckpointMarkThreadRoots callback created = 0xb4958de0
W/ResourcesManager( 4269): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4269): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/VoldCmdListener(  249): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  249): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4233): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
W/art     ( 4233): Suspending all threads took: 9.928ms
,I/MultiDex( 4269): VM with version 2.1.0 has multidex support
I/MultiDex( 4269): install
I/MultiDex( 4269): VM has multidex support, MultiDex support library is disabled.
,I/dex2oat ( 4299): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads228868210.jar --oat-fd=22 --oat-location=/data/data/com.google.android.youtube/cache/ads228868210.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,V/JNIHelp ( 4269): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/dex2oat ( 4299): dex2oat took 108.138ms (threads: 4)
I/NotificationManager( 4233): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  249): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  249): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4233): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  249): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  249): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4233): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  249): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  249): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4233): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/ActivityThread( 4269): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4269): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b0025a6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4269): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 4269): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 4269): com.google.android.gms: cancel(39789) by com.google.android.gms
W/InstanceID/Rpc( 4233): Found 10006
E/VoldCmdListener(  249): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  249): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4233): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,D/NativeLibraryUtils( 4269): Install completed successfully. count=14 extracted=0
,D/libc-netbsd( 4233): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4233): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4233): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4233): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  281): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 4233): propertyValue:false
D/libc-netbsd( 4233): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4233): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  953): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4364 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 23.419ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.550ms
,I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 20.923ms
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/NotificationManager( 4233): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,I/ActivityManager(  953): Killing 3999:com.lge.lgfota.permission/1000 (adj 15): empty #11
,I/ActivityManager(  953): Killing 3981:com.lge.gnss.airtest/u0a54 (adj 15): empty #12
,D/libc-netbsd( 4233): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4233): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_3999/cgroup.procs: No such file or directory
,W/libprocessgroup(  953): failed to open /acct/uid_10054/pid_3981/cgroup.procs: No such file or directory
W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4364): getAccountsCursor
,W/GAV2    ( 4364): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1766): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  953): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 4364): Observing account changes for notifications
W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 4364): Error finding the version of the Email provider.....
E/Gmail   ( 4364): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4364): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4364): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4364): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4364): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4364): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4364): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4364): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4364): We do not support migrating this version of the Email provider.
I/Gmail   ( 4364): getAccountsCursor
,V/GLSActivity( 1766): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4364): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@65c3b34 that was originally bound here
E/ActivityThread( 4364): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@65c3b34 that was originally bound here
E/ActivityThread( 4364): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4364): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4364): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4364): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4364): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4364): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4364): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4364): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4364): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4364): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4364): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4364): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4364): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4364): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4364): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4364): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  953): Unbind failed: could not find connection for android.os.BinderProxy@7d83352
I/ActivityManager(  953): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4414 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/Gmail   ( 4364): notifyAccountChanged
,V/GLSActivity( 1766): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1766): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4364): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  953): Killing 4057:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/Gmail   ( 4364): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4364): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4364): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/libprocessgroup(  953): failed to open /acct/uid_10014/pid_4057/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@72fe17f mBinding = false
D/BluetoothManagerService(  953): Message: 2
,D/BluetoothAdapterService(530067226)( 2095): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176f3840
D/BluetoothManagerService(  953): Sending off request.
D/WifiServiceImplEx(  953): setWifiEnabled: false pid=3771, uid=10317, package= com.example.hello, App Lable : HelloWorld
D/WifiService(  953): setWifiEnabled: false pid=3771, uid=10317
D/LocationManagerService(  953): getAllProviders()=[passive, gps, network]
D/BluetoothAdapterService(530067226)( 2095): disable() called...
D/BluetoothAdapterService(530067226)( 2095): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176f3840
D/BluetoothAdapterService(530067226)( 2095): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176f3840
,D/Ulp_jni (  953): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
I/art     (  953): Explicit concurrent mark sweep GC freed 16710(824KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 9.122ms total 157.550ms
D/Ulp_jni (  953): JNI:system_update. Event-4
D/BluetoothAdapterState( 2095): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2095): Setting state to 13
I/BluetoothAdapterState( 2095): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(530067226)( 2095): updateAdapterState() - Broadcasting state to 1 receivers.
D/LocationManagerService(  953): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  953): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  953): JNI:system_update. Event-4
I/jxcore-log( 3771): ****TEST TOOK:  5075  ms ****
I/jxcore-log( 3771): 
I/jxcore-log( 3771): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3771): 
E/WifiStateMachine(  953): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  953): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BluetoothAdapterProperties( 2095): onBluetoothDisable()
I/BluetoothAdapterState( 2095): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 2095): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 2095): Scan Mode:20
D/BluetoothAdapterState( 2095): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 2095): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 2095): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/bt-btif ( 2095): btsock_ctrl_hci_cleanup(L202): poll handle:4
I/bt-btif ( 2095): BTA_JvDeleteRecord
I/bt-btif ( 2095): BTA_JvRfcommStopServer
I/bt-btif ( 2095): BTA_JvDeleteRecord
I/bt-btif ( 2095): BTA_JvRfcommStopServer
W/bt-btif ( 2095): invalid rfc slot id: 1
D/IOP_DB_BT( 2095): db_close: nbr users 0
D/IOP_DB_BT( 2095): db_close: free database
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  953): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  281): Clearing all IP addresses on wlan0
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 7
V/BluetoothPbapService( 2095): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 2095): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/btif_config_util( 2095): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2095): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 2095): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 2095): enum_config(L344): out, value:f8:95:c7:87:85:54
D/btif_config_util( 2095): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:G3s-1
D/btif_config_util( 2095): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2095): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 2095): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2095): enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2095): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
,D/btif_config_util( 2095): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 2095): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2095): enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2095): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2095): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 2095): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2095): enum_config(L344): out, value:��8�\�婓��n�ScanMode
D/btif_config_util( 2095): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 2095): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 2095): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 2095): enum_config(L344): out, value:x
D/btif_config_util( 2095): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2095): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 2095): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2095): enum_config(L344): out, value:s!WE�(E��00:0F:F6
D/btif_config_util( 2095): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2095): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2095): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 2095): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2095): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2095): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 2095): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2095): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2095): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 2095): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2095): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2095): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 2095): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
,D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:�
D/btif_config_util( 2095): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 2095): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2095): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:,Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:$
D/btif_config_util( 2095): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 2095): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
W/bt-btif ( 2095): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:�
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:A5-1
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
E/bt-btif ( 2095): btif_hf_upstreams_evt: wrong handle = 1280 
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2095): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:#
D/btif_config_util( 2095): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 2095): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2095): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:�
D/btif_config_util( 2095): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:XT1072
D/btif_config_util( 2095): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:a
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:S5-1
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
W/bt-obex ( 2095): Ignore event 10 in state 1
W/bt-obex ( 2095): Ignore event 10 in state 1
E/bt-btif ( 2095): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt-btif ( 2095): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 2095): ops_state_cb(L223):  ops_state_cb state:3
D/OppService( 2095): onOpsStateChange() :3
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
,D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:a
D/btif_config_util( 2095): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
D/OppService( 2095): Recieved MESSAGE_OPS_DISABLE
D/btif_config_util( 2095): enum_config(L344): out, value:Thali Test (Galaxy S5)
D/btif_config_util( 2095): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:�
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:Thali Test (Galaxy A5)
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:�
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:Thali Test (Galaxy A3)
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:A
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:Thali Test's G2
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2095): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:	a
D/btif_config_util( 2095): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:Note3-1
D/btif_config_util( 2095): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:�
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:A3-1
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2095): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:�
D/btif_config_util( 2095): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:XT1039
D/btif_config_util( 2095): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:	a
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2095): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:�
D/btif_config_util( 2095): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:HTC One_M8
D/btif_config_util( 2095): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2095): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 7
D/BluetoothAdapterService(530067226)( 2095): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176f3840
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 2095): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 2095): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:A
D/btif_config_util( 2095): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:S5mini-1
D/btif_config_util( 2095): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
,D/btif_config_util( 2095): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2095): enum_config(L300): in, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:T\���K�`�D�`�D�
D/btif_config_util( 2095): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:���
D/btif_config_util( 2095): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:ALE-L21
D/btif_config_util( 2095): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2095): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:#
D/btif_config_util( 2095): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:onem9-1
D/btif_config_util( 2095): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 2095): enum_config(L344): out, value:H
D/btif_config_util( 2095): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:?C
D/btif_config_util( 2095): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:Tab4
D/btif_config_util( 2095): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:Z
D/btif_config_util( 2095): enum_config(L300): in, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:14:b4:84:21:3b:49, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:JustWorks, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:14:b4:84:21:3b:49, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:14:b4:84:21:3b:49, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Service, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Service
D/btif_config_util( 2095): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2095): enum_config(L300): in, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:58:1b:00:00:20:00, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:58:1b:00:00:20:00, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:00:00:00:00:41:0e, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:00:00:00:00:41:0e, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:�h�
D/btif_config_util( 2095): enum_config(L300): in, key:00:00:00:00:41:0e, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:00:00:00:41:0e, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:00:00:00:41:0e, value:DevClass
D/btif_config_util( 2095): enum_config(L300): in, key:00:00:00:00:41:0e, value:DevType
D/btif_config_util( 2095): enum_config(L343): out, key:00:00:00:00:41:0e, value:DevType
D/btif_config_util( 2095): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:J���J�hrD�hrD�
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevClass
D/btif_config_util( 2095): enum_config(L300): in, key:94:06:6b:a0:e3:f1, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:94:06:6b:a0:e3:f1, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevType
D/btif_config_util( 2095): enum_config(L300): in, key:08:00:00:00:67:73, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:00:00:00:67:73, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:08:00:00:00:67:73, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:00:00:00:67:73, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 2095): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpSubVer, value type:int
D/btif_config_util( 2095): enum_config(L344): out, value:�
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L344): out, value:Galaxy S5-2
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 2095): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 2095): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L300): in, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Manufacturer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 2095): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpVer, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 2095): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 2095): enum_config(L344): out, value:�
D/btif_config_util( 2095): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 2095): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 2095): enum_config(L343): out, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:GlobalTrust, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 2095): enum_config(L300): in, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 2095): enum_config(L300): in, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 2095): enum_config(L343): out, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 2095): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 2095): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:���
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:�_
D/btif_config_util( 2095): enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevType
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevType
D/btif_config_util( 2095): enum_config(L300): in, key:00:00:00:00:41:9e, value:Name
D/btif_config_util( 2095): enum_config(L343): out, key:00:00:00:00:41:9e, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:4g�
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevClass, value type:int
D/btif_config_util( 2095): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevClass
D/btif_config_util( 2095): enum_config(L344): out, value:��f
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevType, value type:int
D/btif_config_util( 2095): enum_config(L344): out, value:
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:Name, value type:string
D/btif_config_util( 2095): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:Name
D/btif_config_util( 2095): enum_config(L344): out, value:4g�������v��
D/btif_config_util( 2095): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevClass, value type:int
I/QCNEJ   ( 1926): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1926): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 17:09:57.735 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1926): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1389): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  953): hidePasspointNotification off =false
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGBluetoothAPIService( 1872): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/BluetoothMapService( 2095): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 2095): STATE_TURNING_OFF
V/BluetoothMapService( 2095): Handler(): got msg=4
D/BluetoothMapService( 2095): MAP Service closeService in
D/BluetoothMapMasInstance( 2095): MAP Service shutdown
D/LGBluetoothMapAdapter( 2095): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2095): MAP Service closeService out
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1389): Remote
,D/BluetoothAdapterService(530067226)( 2095): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176f3840
D/BluetoothAdapterService(530067226)( 2095): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176f3840
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1389): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
D/ConnectivityService(  953): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  953): disableDataServiceNotify
,I/ActivityManager(  953): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4444 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/DSQN    (  953): stop dsqn bin
D/ConnectivityService(  953): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  953): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  953): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/WifiHS20(  953): hidePasspointNotification off =false
D/ConnectivityManager.CallbackHandler( 1389): CM callback handler got msg 524292
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1926): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1926): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 17:09:57.879 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1926): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): DefaultState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  953): Disconnected - quitting
D/WifiNetworkAgent(  953): NetworkAgent: NetworkAgent channel lost
D/LGWifiP2pService(  953): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  953): SCAN_AVAILABLE : 1
D/RttService(  953): SCAN_AVAILABLE : 1
D/WifiScanningService(  953): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  953): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  953): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  953): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  953): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  953): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  953): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NetworkPolicy(  953): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1926): |CORE| No family connected
D/Tethering(  953): MasterInitialState.processMessage what=3
D/ConnectivityService(  953): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  953): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  953): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  953): Removing idletimer
D/TelephonyNetworkFactory-1( 1794): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings(  953): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1794):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
V/NetworkPolicy(  953): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1926): |CORE| No family connected
I/QCNEJ   ( 1926): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1926): |CORE| sendDefaultNwMsg: default = -1
I/[SystemUI]StatusBar.NetworkController( 1389): mWifiConnected = false, mWifiLevel = 0
D/LGWifiP2pService(  953): P2pDisablingState
D/LGWifiP2pService(  953): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): p2p socket connection lost
D/LGWifiP2pService(  953): P2pDisabledState
D/Tethering(  953): MasterInitialState.processMessage what=3
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1389): Remote
D/WIFI    (  953): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  953):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WfdsService( 1872): WifiP2pState is changed : false
D/LGWifiP2pService(  953): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  953): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1872): WfdsEnabledState: Receive the WFDS_DISABLE message
D/CommandListener(  281): Clearing all IP addresses on wlan0
D/WifiHS20(  953): hidePasspointNotification off =false
I/QCNEJ   ( 1926): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1926): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 17:09:57.908 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WfdsJNI ( 1872): doCommand: P2P_STOP_FIND
I/QCNEJ   ( 1926): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WfdsService( 1872): Set the WFDS Monitor: false
I/WifiServerServiceExt(  953): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt(  953): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  953): setSupplicantStateDISCONNECTED
,I/QCNEJ   ( 1926): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1926): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 17:09:57.917 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1926): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WfdsMonitor( 1872): WFDS Monitor is stopped
D/CtrlSupplicant( 1872): Received on exit socket, terminate
E/CtrlSupplicant( 1872): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1872): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1872): WfdsMonitorThread is received the interrupt - closing
D/WfdsService( 1872): STATE : WfdsDisabledState - enter
D/WfdsService( 1872): WFDS: Scanner is paused
D/WfdsDiscoveryStore( 1872): Clear Discovery Method Map: ScanAlwaysMode false
W/WfdsSession:Controller( 1872): DefaultState - msg [9441355] is not handled
D/TelephonyIcons( 1389): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1389): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/DhcpStateMachine(  953): StoppedState
D/DhcpStateMachine(  953): StoppedState{ when=-45ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyIcons( 1389): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1389): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.p2p.STATE_CHANGED at null
I/[SystemUI]StatusBar.NetworkController( 1389): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1389): Remote
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.WIFI_STATE_CHANGED at null
I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 4
,I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 5
I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 10
I/wpa_supplicant( 2803): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2803): monitor socket send errors count : 1
I/wpa_supplicant( 2803): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1872-2\x00 that cannot receive messages
I/Netd    (  281): M: Get netlink event, ifname: p2p0 action: 7
V/[BNRBootReceiver]( 4414): boot receiver action = android.intent.action.BOOT_COMPLETED
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/[BNRBootReceiver]( 4414): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4414): End of BootComplted IF
V/[BNRBootReceiver]( 4414): Boot Receiver Return
,I/wpa_supplicant( 2803): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 2803): USIM:  scard_deinit function
W/linker  ( 4461): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
V/[BNRBootCompletedThread]( 4414): run
,W/bnrd    ( 4461): BNRD > wait starting [4461-3058102400] <
E/bnrd    ( 4461): /data/data/.bnr_fifo_req
W/ResourcesManager( 4444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4444): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 4444): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4444): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 4444): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
D/libc-netbsd(  953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  953): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4465 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  953): Killing 4039:com.lge.hiddenmenu/1000 (adj 15): empty #11
,I/ThermalEngine(  299): Sensor:pa_therm0:32000 mC
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
,W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_4039/cgroup.procs: No such file or directory
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 5
I/wpa_supplicant( 2803): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiOffDelayIfNotUsed(  953): stopMonitoring
D/WfdsService( 1872): Supplicant Connection state is changed : false
,D/WfdsService( 1872): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1872): Set the WFDS Monitor: false
D/WfdsMonitor( 1872): WFDS Monitor is stopped
W/Settings( 4189): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Tethering(  953): InitialState.processMessage what=4
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1389): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.net.wifi.WIFI_STATE_CHANGED at null
I/WifiServerServiceExt(  953): WIFI_STATE_CHANGED_ACTION [1]
I/QCNEJ   ( 1926): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1926): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-11 17:09:58.15 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1926): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/Tethering(  953): sendTetherStateChangedBroadcast 0, 0, 0
I/WifiServerServiceExt(  953): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt(  953): batteryPsActivateMsgHandler : this is not treated
,V/[BNRBootCompletedThread]( 4414): End of BNRProcess
W/Settings( 1766): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/[BNRBootCompletedThread]( 4414): End of BNRViaWifiProcess
,D/AndroidRuntime( 4437): 
D/AndroidRuntime( 4437): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4437): CheckJNI is OFF
V/[BNRBootCompletedThread]( 4414): End of SpriteProcess
V/[BNRBootCompletedThread]( 4414): exit
I/IndexDatabaseHelper( 4444): Using schema version: 115
,I/IndexDatabaseHelper( 4444): Index is fine
V/GLSActivity( 1766): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4364): getAccountsCursor
I/Gmail   ( 4364): getAccountsCursor
,V/GLSActivity( 1766): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 4444): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 2095): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2095): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2095): ***********state = 13
V/BluetoothPbapReceiver( 2095): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 2095): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 2095): state: 13
V/BluetoothPbapService( 2095): Pbap Service closeService in
V/BluetoothPbapService( 2095): successfully stopped pbap service
V/BluetoothPbapService( 2095): Pbap Service closeService out
V/BluetoothPbapService( 2095): Pbap Service onDestroy
V/BluetoothPbapService( 2095): Pbap Service closeService in
V/BluetoothPbapService( 2095): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 2095): [BTUI] cleanup
,D/BluetoothManagerService(  953): Message: 20
D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37bf397c:true
D/BluetoothAdapterService(530067226)( 2095): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176f3840
,D/BluetoothManagerService(  953): Message: 30
D/BluetoothManagerService(  953): Message: 30
,D/LocalBluetoothProfileManager( 4444): Adding local MAP profile
D/BluetoothMap( 4444): Create BluetoothMap proxy object
D/BluetoothManagerService(  953): Message: 30
D/BluetoothManagerService(  953): Message: 30
D/LocalBluetoothProfileManager( 4444): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 4444):  get() - isFeatureLoaded : false
,D/LGBluetoothUserBindClient( 4444): [BTUI] initUserBindClient
,D/AndroidRuntime( 4437): Calling main entry com.android.commands.pm.Pm
W/ContextImpl( 4444): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 4444): finishStartingService: stopping service
,D/BluetoothInputDevice( 4444): Proxy object connected
D/HidProfile( 4444): Bluetooth service connected
,D/BluetoothAdapterService(530067226)( 2095): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176f3840
D/BluetoothPan( 4444): BluetoothPAN Proxy object connected
D/PanProfile( 4444): Bluetooth service connected
D/BluetoothAdapterService(530067226)( 2095): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176f3840
D/BluetoothMap( 4444): Proxy object connected
D/MapProfile( 4444): Bluetooth service connected
D/BluetoothMap( 4444): getConnectedDevices()
D/BluetoothAdapterService(530067226)( 2095): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176f3840
D/BluetoothMap( 4444): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 4444): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 4444): [BTUI] cancel All Notification
I/NotificationManager( 4444): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 4444): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 4444): com.android.settings: cancel(-1000011) by com.android.settings
,I/NotificationManager( 4444): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 4444): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 4444): com.android.settings: cancel(-1000041) by com.android.settings
I/ActivityManager(  953): Force stopping com.example.hello appid=10317 user=-1: uninstall pkg
I/ActivityManager(  953): Killing 3771:com.example.hello/u0a317 (adj 0): stop com.example.hello
I/WindowState(  953): WIN DEATH: Window{393d2588 u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  953): Focus left window: Window{393d2588 u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  953): Window went away: Window{393d2588 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  953): Skipping PackageSetting{1a1d4df0 com.test.thalitest/10316} due to missing metadata
,W/ActivityManager(  953): Force removing ActivityRecord{211a9bf8 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,D/BluetoothPermissionRequest( 4444): onReceive
,W/ActivityManager(  953): Spurious death for ProcessRecord{f460757 3771:com.example.hello/u0a317}, curProc for 3771: null
I/ActivityManager(  953): Force stopping com.example.hello appid=10317 user=0: pkg removed
D/LGBluetoothAuthorization( 4444): [BTUI] cancel All Notification
I/NotificationManager( 4444): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 4444): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 4444): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 4444): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 4444): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 4444): com.android.settings: cancel(-1000041) by com.android.settings
I/[LGHome]EVENT( 1965): [Launcher.java:5203:onStart()]onStart
,D/KeyguardModel( 1389): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/bt-l2cap( 2095): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2095): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 2095): ag scb idx 1 not allocated
E/bt-btif ( 2095): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2095): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2095): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 2095): ag scb idx 1 not allocated
E/bt-btif ( 2095): BTA AG is already disabled, ignoring ...
E/bt-btif ( 2095): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 2095): bta_gattc_deregister Deregister Failedm unknown client cif
W/bt_userial( 2095): select_read return size <=0:0, exiting userial_read_thread
D/bt_hwcfg( 2095): hw_epilog_process
I/bt_userial_vendor( 2095): device fd = 70 close
E/bt_vendor( 2095): [BTUI] Proto is enabled. Set Proto disable!!
,I/[LGHome]EVENT( 1965): [Launcher.java:776:onResume()]onResume
W/GeofencerStateMachine( 1766): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  953): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3622): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/System.err( 3622): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,W/System.err( 3622): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3622): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3622): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3622): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3622): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3622): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3622): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3622): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3622): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3622): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/QCNEJ   ( 1926): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
V/BluetoothOppReceiver( 2095): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 2095): [BTUI] cancel opp incoming file confirm notification
I/NotificationManager( 2095): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/BluetoothOppNotification( 2095): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 2095): com.android.bluetooth: cancel(-1) by com.android.bluetooth
,I/[SystemUI]QSlideListController( 1389): onReceive = android.intent.action.PACKAGE_REMOVED
V/BluetoothSapReceiver( 2095): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 2095): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,I/[LGHome]LGActivityUtil( 1965): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,D/administrator(  953): Handling package changes for user 0
,I/GKI_LINUX( 2095): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/ActivityManager(  953): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4513 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/[LGHome]EVENT( 1965): [Launcher.java:929:onResume()]onResume end
I/Activity( 1965): Activity.onPostResume() called 
D/KeyguardModel( 1389): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1389): createShortcutInfo...
,I/GKI_LINUX( 2095): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2095): GKI_destroy_task(): task [BTU] terminated
I/bt-btif ( 2095): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 2095): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2095): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1389): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1389): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/Finsky  ( 4465): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/KeyguardModel( 1389): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1389): createShortcutInfo...
,W/ResourceType( 1389): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1389): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/BtSettings.ProfileConfig( 2095): Unable to read settings
D/BtSettings.ProfileConfig( 2095): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2095): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2095): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2095): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2095): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 2095): 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
D/BtSettings.ProfileConfig( 2095): 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
D/BtSettings.ProfileConfig( 2095): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2095): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2095): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2095): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2095): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 2095): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(530067226)( 2095): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
D/KeyguardModel( 1389): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1389): createShortcutInfo...
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2095): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 2095): Not skipping com.android.bluetooth.a2dp.A2dpService
W/ResourceType( 1389): No package identifier when getting value for resource number 0x00000000
D/BluetoothAdapterService(530067226)( 2095): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
D/HeadsetService( 2095): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2095): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
W/[LGHome]LGWallpaperInfo( 1965): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/WallpaperManager( 1965): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/BluetoothAdapterService( 2095): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(530067226)( 2095): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
I/LGBluetoothHfpAdapter( 2095): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 2095): Cleaning up Bluetooth Handsfree callback object
D/HeadsetStateMachine( 2095): Exit Disconnected: -1
D/BluetoothAdapterService( 2095): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f982f1a
W/PackageManager( 1389): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/BluetoothHeadset( 1794): Proxy object disconnected
D/BluetoothHeadset( 1794): Proxy object disconnected
D/BluetoothHeadset( 1794): Proxy object disconnected
D/KeyguardModel( 1389): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1389): createShortcutInfo...
W/ResourceType( 1389): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1389): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/A2dpService( 2095): Received stop request...Stopping profile...
D/A2dpStateMachine( 2095): Exit Disconnected: -1
,D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
D/KeyguardModel( 1389): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1389): createShortcutInfo...
W/BluetoothAdapterService( 2095): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
I/SystemUI[Framework](  953): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/BluetoothAdapterService( 2095): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(530067226)( 2095): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
D/InputDispatcher(  953): Focus entered window: Window{17d73008 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2095): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/KeyguardModel( 1389): handleShortcutListChanged...
W/BluetoothAdapterService( 2095): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(530067226)( 2095): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
D/LGBluetoothA2dpAdapter( 2095): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 2095): Cleaning up Bluetooth Handsfree callback object
D/LGBluetoothPowerControlManager( 2095): [BTUI] terminate
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2095): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2095): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(530067226)( 2095): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  953): Message: 31
W/PhoneWindowManagerEx(  953): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  953): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  953): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  953): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1891d12f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  953): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/art     ( 1841): CheckpointMarkThreadRoots callback created = 0xaaf21b50
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
,W/BluetoothAdapterService( 2095): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2095): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(530067226)( 2095): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2095): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f982f1a
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - Message: 1
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 2095): isTurningOnRadio()=false
D/BluetoothAdapterState( 2095): isTurningOffRadio()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2095): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/KeyguardModel( 1389): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1389): createShortcutInfo...
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2095): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2095): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/HeadsetStateMachine( 2095): Unbinding service...
W/BluetoothAdapterService( 2095): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(530067226)( 2095): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
D/HeadsetPhoneState( 2095): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2095): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 2095): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2095): [BTUI] listenForMultiSimPhoneState : start = false
D/KeyguardModel( 1389): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1389): createShortcutInfo...
W/BluetoothHeadsetServiceJni( 2095): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2095): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 2095): [BTUI] LGBluetoothHfpAdapter cleanup
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
D/HidService( 2095): Received stop request...Stopping profile...
W/BluetoothAdapterService( 2095): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
D/BluetoothAdapterService( 2095): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f982f1a
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 2095): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(530067226)( 2095): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2095):, check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2095): getQuietmodeRadioCount = 0
D/BluetoothInputDevice( 4444): Proxy object disconnected
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2095): Not skipping com.broadcom.bt.service.opp.OppService
D/HidProfile( 4444): Bluetooth service disconnected
D/BluetoothAdapterService(530067226)( 2095): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
,D/BluetoothAdapterState( 2095): Stopping profile services that were post enabled
D/HealthService( 2095): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2095): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f982f1a
I/[LGHome]EVENT( 1965): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
W/ResourceType( 1389): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1389): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/PanService( 2095): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2095): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f982f1a
I/[LGHome]LGPlusHomeDBManager( 1965): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/BtGatt.DebugUtils( 2095): handleDebugAction() action=null
D/BtGatt.GattService( 2095): Received stop request...Stopping profile...
D/BtGatt.GattService( 2095): stop()
D/KeyguardModel( 1389): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1389): createShortcutInfo...
D/BtGatt.AdvertiseManager( 2095): advertise clients cleared
I/[LGHome]LGPlusHomeDBManager( 1965): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/LGBluetoothGattAdapter( 2095): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 2095): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f982f1a
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - Message: 1
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 2095): isTurningOnRadio()=false
D/BluetoothAdapterState( 2095): isTurningOffRadio()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2095): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2095): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/ResourceType( 1389): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1389): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/BluetoothMapService( 2095): Received stop request...Stopping profile...
D/BluetoothPan( 4444): BluetoothPAN Proxy object disconnected
D/PanProfile( 4444): Bluetooth service disconnected
D/BluetoothMapService( 2095): stop()
D/BluetoothMapEmailAppObserver( 2095): deinitObservers()
D/BluetoothMapEmailAppObserver( 2095): removeReceiver()
,D/BluetoothAdapterService( 2095): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f982f1a
D/KeyguardModel( 1389): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1389): createShortcutInfo...
I/BluetoothA2dpServiceJni( 2095): cleanupNative
I/GKI_LINUX( 2095): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2095): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2095): GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/BluetoothMap( 4444): Proxy object disconnected
D/MapProfile( 4444): Bluetooth service disconnected
D/SapService( 2095): Received stop request...Stopping profile...
D/SapService( 2095): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 2095): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 2095): [BTUI] terminateSapManager
I/[LGHome]EVENT( 1965): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1965): [setNavigationBarColor] color=0x 0
D/BluetoothAdapterService( 2095): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f982f1a
,D/BluetoothAdapterService(530067226)( 2095): handleMessage() - Message: 1
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 2095): isTurningOnRadio()=false
D/BluetoothAdapterState( 2095): isTurningOffRadio()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2095): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2095): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHidServiceJni( 2095): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 2095): Cleaning up Bluetooth GID callback object
W/ResourceType( 1389): No package identifier when getting value for resource number 0x00000000
D/**BluetoothFTPService( 2095): Received stop request...Stopping profile...
D/LgeBluetoothSimManager( 1794): [BTUI] SAP_DISABLE_EVT
D/**BluetoothFTPService( 2095): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 2095): closeFtpServerNative
D/BluetoothAdapterService( 2095): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f982f1a
D/**OppService( 2095): Received stop request...Stopping profile...
D/OppService( 2095): Stopping Bluetooth OppService
D/OppService( 2095): cleanup OPP Service
W/BluetoothOPPServiceJni( 2095): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 2095): Cleaning up Bluetooth OPP callback object
D/OppService( 2095): remove callbacks and handler
D/LGBluetoothOppAdapter( 2095): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 2095): cleanup done
D/BluetoothAdapterService( 2095): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f982f1a
W/PackageManager( 1389): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - Message: 1
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 2095): isTurningOnRadio()=false
D/BluetoothAdapterState( 2095): isTurningOffRadio()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2095): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2095): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHealthServiceJni( 2095): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2095): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 2095): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - Message: 1
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAda,pterState( 2095): isTurningOnRadio()=false
D/BluetoothAdapterState( 2095): isTurningOffRadio()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2095): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2095): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 2095): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2095): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - Message: 1
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 2095): isTurningOnRadio()=false
D/BluetoothAdapterState( 2095): isTurningOffRadio()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2095): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2095): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 2095): Handler(): got msg=4
D/BluetoothMapService( 2095): MAP Service closeService in
D/LGBluetoothMapAdapter( 2095): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2095): MAP Service closeService out
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - Message: 1
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2095): isTurningOnRadio()=false
D/BluetoothAdapterState( 2095): isTurningOffRadio()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2095): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
,D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2095): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 2095): cleanup()
D/BluetoothMapService( 2095): MAP Service closeService in
D/LGBluetoothMapAdapter( 2095): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2095): MAP Service closeService out
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - Message: 1
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2095): isTurningOnRadio()=false
D/BluetoothAdapterState( 2095): isTurningOffRadio()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2095): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2095): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothSAPServiceJni( 2095): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2095): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - Message: 1
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
D/BluetoothAdapterState( 2095): isTurningOnRadio()=false
D/BluetoothAdapterState( 2095): isTurningOffRadio()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2095): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2095): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2095): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothFTPService( 2095): cleanup FTP Service
V/BluetoothFTPServiceJni( 2095): closeFtpServerNative
V/BluetoothFTPServiceJni( 2095): cleanupNative
W/BluetoothFTPServiceJni( 2095): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 2095): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 2095): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 2095): cleanup done
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - Message: 1
D/BluetoothAdapterService(530067226)( 2095): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
D/BluetoothAdapterState( 2095): isTurningOnRadio()=false
D/BluetoothAdapterState( 2095): isTurningOffRadio()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2095): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2095): processProfileServiceStateChanged(): serviceName=com.broa,dcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(530067226)( 2095): onProfileServiceStateChange() - All profile services stopped...
D/BluetoothAdapterState( 2095): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2095): Setting state to 10
I/BluetoothAdapterState( 2095): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(530067226)( 2095): updateAdapterState() - Broadcasting state to 1 receivers.
D/OppService( 2095): cleanup OPP Service
D/OppService( 2095): remove callbacks and handler
D/LGBluetoothOppAdapter( 2095): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 2095): cleanup done
D/BluetoothManagerService(  953): Message: 60
D/BluetoothManagerService(  953): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  953): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 2095): Entering OffState
D/BluetoothHeadset( 1794): onBluetoothStateChange: up=false
D/KeyguardModel( 1389): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1389): createShortcutInfo...
D/BluetoothInputDevice( 4444): onBluetoothStateChange: up=false
D/BluetoothMap( 4444): onBluetoothStateChange: up=false
D/BluetoothHeadset(  953): onBluetoothStateChange: up=false
D/BluetoothA2dp(  953): onBluetoothStateChange: up=false
D/BluetoothPbap( 4444): onBluetoothStateChange: up=false
W/ResourcesManager( 4513): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/art     ( 1841): CheckpointMarkThreadRoots callback created = 0xaaf52570
D/KeyguardModel( 1389): handleShortcutListChanged...
,D/BluetoothHeadset( 1794): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1794): onBluetoothStateChange: up=false
D/BluetoothPan( 4444): onBluetoothStateChange on: false
D/BluetoothAdapterService(530067226)( 2095): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@176f3840
D/BluetoothManagerService(  953): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  953): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService(  953): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService(  953): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService(  953): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@72fe17f mBinding = false
D/BluetoothManagerService(  953): Sending unbind request.
D/BluetoothAdapterService(530067226)( 2095): onUnbind() - calling cleanup
D/BluetoothManagerService(  953): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService(530067226)( 2095): cleanup()
D/BluetoothAdapter( 1389): 57305198: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1389): 57305198: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothAPIService( 1872): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1872): Message: 2
I/[SystemUI]QuickSettingsHandler( 1389): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1389): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
D/LGBluetoothAPIService( 1872): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3d97f391 mBinding = false
D/LGBluetoothAPIService( 1872): Sending unbind request.
D/LGBluetoothFeatureConfig( 4444): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 4444): [BTUI] resetProperty - success
E/LGBluetoothEventManager( 4444): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,D/LGBluetoothEventManager( 4444): [BTUI] clear device connection state
D/BluetoothAdapterService(530067226)( 2095): cleanup() - Cleaning up adapter native
I/bt-btif ( 2095): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 2095): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/bt-btif ( 2095): HAL bt_hal_cbacks->thread_evt_cb
I/GKI_LINUX( 2095): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2095): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 2095): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2095): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2095): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2095): GKI_exit_task 2 done
I/GKI_LINUX( 2095): GKI_exit_task 1 done
I/GKI_LINUX( 2095): GKI_exit_task 0 done
I/BluetoothServiceJni( 2095): cleanupNative: return from cleanup
W/LGBluetoothServiceJni( 2095): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 2095): [BTUI] unregister observer for LG device name DB
D/BluetoothAdapterService(530067226)( 2095): cleanup() - Bluetooth process exited normally.
D/BluetoothAdapterService(530067226)( 2095): cleanup() done
D/BluetoothAdapter( 1766): 652744920: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1766): 652744920: getState() :  mService = null. Returning STATE_OFF
I/art     ( 2095): System.exit called, status: 0
,I/AndroidRuntime( 2095): VM exiting with result code 0, cleanup skipped.
I/ActivityManager(  953): Killing 4104:com.lge.springcleaning/1000 (adj 15): empty #11
,V/AudioFlinger(  286): 2095 died, releasing its sessions
V/AudioFlinger(  286):  pid 1794 @ 0
V/AudioFlinger(  286):  pid 2120 @ 1
V/AudioFlinger(  286):  pid 3148 @ 2
V/AudioFlinger(  286):  pid 3148 @ 3
D/LGBluetoothUserBindClient( 4444): [BTUI] onServiceDisconnected
D/FMFRW_FmProxy( 1872): Fm Proxy object disconnected
,D/AuthorizationBluetoothService( 1766): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/InputMethodManagerService(  953): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/NotificationService(  953): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService(  953): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
W/InputMethodManagerService(  953): Got RemoteException sending setActive(false) notification to pid 3771 uid 10317
D/JobSchedulerService(  953): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  953): Explicit concurrent mark sweep GC freed 33805(1887KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 17.266ms total 473.574ms
,I/ActivityManager(  953): Process com.android.bluetooth (pid 2095) has died
,I/SystemUI[Framework](  953): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
I/Timeline( 1965): Timeline: Activity_idle id: android.os.BinderProxy@9e9912c time:59775
W/PhoneWindowManagerEx(  953): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  953): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  953): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  953): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1891d12f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  953): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ActivityManager(  953): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,W/ActivityManager(  953): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 11000ms
W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_4104/cgroup.procs: No such file or directory
W/ContextImpl( 4444): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,D/PhoneStatusBar( 1389): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1389): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1389):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1389): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  953): removeObsoleteFile: deleting file=220_task.xml
D/BarTransitions( 1389): draw background and invalidate : color = f6000000
D/BarTransitions( 1389): draw background and invalidate : color = f4ebebeb
I/HotwordRecognitionRnr( 2044): Starting hotword detection.
,I/ActivityManager(  953): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=4542 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
D/DockEventReceiver( 4444): finishStartingService: stopping service
I/MicrophoneInputStream( 2044): mic_starting com.google.android.apps.gsa.speech.audio.u@35460452
V/AudioRecord( 2044): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
D/PowerService( 1872): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,V/AudioRecord( 2044): set(): mSessionId 23
D/KeyguardUpdateMonitor( 1389): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
V/AudioPolicyManager(  286): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 23, flags 0
V/AudioPolicyManager(  286): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  286): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  286): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e1a0)
V/audio_hw_primary(  286): adev_open_input_stream: exit
V/AudioFlinger(  286): openInput_l() openInputStream returned input 0xb546e1a0, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  286): openInput_l() created record thread: ID 24 thread 0xb3c6e000
I/AudioFlinger(  286): AudioFlinger's thread 0xb3c6e000 ready to run
,D/audio_hw_primary(  286): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
D/audio_hw_primary(  286): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioSystem(  286): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1389): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1794): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 3148): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem(  953): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 2044): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 2120): ioConfigChanged() event 3, ioHandle 24
V/AudioPolicyService(  286): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  286): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
,D/AndroidRuntime( 4437): Shutting down VM
I/[SystemUI]LGPowerUI( 1389): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1389): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1389): On Skip Timer : true
,V/AudioFlinger(  286): openRecord() lSessionId: 23 input 24
V/AudioFlinger(  286): getOrphanEffectChain_l session 23 index -2
V/AudioFlinger(  286): acquiring 23 from 2044, for -1
V/AudioFlinger(  286):  added new entry for 23
V/AudioRecord( 2044): start, sync event 0 trigger session 0
V/AudioRecord( 2044): mAudioRecord->start()
V/AudioFlinger(  286): RecordHandle::start()
V/AudioFlinger(  286): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  286): startInput() module primary->input primary(24)
V/AudioPolicyManager(  286): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  286): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  286): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  286): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  286): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  286): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  286): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  286): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  286): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  286): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  286): in_set_parameters: exit: status(0)
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb3c6e000
V/AudioFlinger::PatchPanel(  286): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  286): createAudioPatch() added new patch handle 25 halHandle 0
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): setInputDevice() createAudioPatch returned 0 patchHandle 25
V/AudioPolicyManager(  286): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  286): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  286): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() adding set parameter string hotword_active=1, io 24 ,delay 0
V/AudioPolicyService(  286): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  286): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing set parameters string hotword_active=1, io 24
V/AudioFlinger(  286): setParameters(): io 24, keyvalue hotword_active=1, calling pid 286
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioFlinger(  286): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
,D/audio_hw_primary(  286): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  286): in_set_parameters: exit: status(0)
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb3c6e000
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 2044): mic_started com.google.android.apps.gsa.speech.audio.u@35460452
V/msm8974_platform(  286): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  286): start_input_stream: enter: stream(0xb546e1a0)usecase(7: audio-record)
V/voice   (  286): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  286): start_input_stream: usecase(7)
E/audio_hw_primary(  286): select_devices: enter and usecase(7)
V/msm8974_platform(  286): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  286): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  286): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  286): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  286): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  286): enable_snd_device: enter  144
D/hardware_info(  286): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  286): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  286): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  286): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  286): ACDB -> send_adm_topology
D/ACDB-LOADER(  286): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  286): ACDB -> send_asm_topology
D/ACDB-LOADER(  286): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  286): ACDB -> send_audtable
D/ACDB-LOADER(  286): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  286): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  286): ACDB -> send_audvoltable
D/ACDB-LOADER(  286): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  286): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  286): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  286): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  286): ACDB -> AUDIO_SET_AFE_CAL
,V/audio_hw_primary(  286): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  286): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  286): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  286): enable_audio_route: exit
D/audio_hw_primary(  286): select_devices: done
V/audio_hw_primary(  286): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  286): start_input_stream: exit
W/ResourcesManager( 4542): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 4542): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4542): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 4542): Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
,D/Finsky  ( 4465): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/BluetoothAdapterApp( 4542): Loading JNI Library
,I/Timeline(  953): Timeline: Activity_windows_visible id: ActivityRecord{2317be9f u0 com.lge.launcher2/.Launcher t219} time:60031
,W/Settings( 4465): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4465): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/HotwordWorker( 2044): onReady
,D/LCardEmulationManager( 1841): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1841): getDefaultRoute
I/NotificationManager( 4465): com.android.vending: cancel(-1050172287) by com.android.vending
E/BluetoothServiceJni( 4542): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
,D/BluetoothAdapterApp( 4542): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1f56360d Instance Count = 1
W/ResourcesManager(  953): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 4542): onCreate
,I/LGBluetoothServiceJni( 4542): classInitNative: succeeds
D/BtSettings.ProfileConfig( 4542): [BTUI] HeadsetServiceis supported
,D/BtSettings.ProfileConfig( 4542): Adding HeadsetService
D/Volley  ( 4465): [461] DiskBasedCache.clear: Cache cleared.
D/BtSettings.ProfileConfig( 4542): [BTUI] A2dpServiceis supported
D/BtSettings.ProfileConfig( 4542): Adding A2dpService
D/Volley  ( 4465): [468] DiskBasedCache.clear: Cache cleared.
D/BtSettings.ProfileConfig( 4542): [BTUI] HidServiceis supported
D/BtSettings.ProfileConfig( 4542): Adding HidService
D/BtSettings.ProfileConfig( 4542): [BTUI] HealthServiceis supported
D/BtSettings.ProfileConfig( 4542): Adding HealthService
D/LGBluetoothFeatureConfig( 4542): isSupportPan() :  mTargetOp=OPEN
I/ActivityManager(  953): Killing 4141:com.google.android.configupdater/u0a3 (adj 15): empty #11
D/LGBluetoothFeatureConfig( 4542): isSupportPan() :  mTargetOp=OPEN
D/BtSettings.ProfileConfig( 4542): [BTUI] PanServiceis supported
D/BtSettings.ProfileConfig( 4542): Adding PanService
D/BtSettings.ProfileConfig( 4542): [BTUI] GattServiceis supported
D/BtSettings.ProfileConfig( 4542): Adding GattService
D/BtSettings.ProfileConfig( 4542): [BTUI] BluetoothMapServiceis supported
D/BtSettings.ProfileConfig( 4542): Adding BluetoothMapService
V/LGBluetoothServiceAdapter( 4542): [BTUI] region:EU country:EU
D/BtSettings.ProfileConfig( 4542): [BTUI] SapServiceis supported
D/BtSettings.ProfileConfig( 4542): Adding SapService
D/BtSettings.ProfileConfig( 4542): [BTUI] FTPServiceis supported
D/BtSettings.ProfileConfig( 4542): Adding FTPService
E/BtSettings.ProfileConfig( 4542): [BTUI] HeadsetClientServiceis NOT supported
D/BtSettings.ProfileConfig( 4542): [BTUI] OppServiceis supported
D/BtSettings.ProfileConfig( 4542): Adding OppService
,D/Ads     ( 4465): Skipping gmscore version check
W/libprocessgroup(  953): failed to open /acct/uid_10003/pid_4141/cgroup.procs: No such file or directory
,D/BtSettings.ProfileConfig( 4542): deviceMode from shared preference   -1
D/BtSettings.ProfileConfig( 4542): checkAndAdjustDeviceModeConfiguration deviceMode1
D/BtSettings.ProfileConfig( 4542): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 4542): Unable to read settings
D/BtSettings.ProfileConfig( 4542): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 4542): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 4542): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 4542): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 4542): 	at com.broadcom.bt.service.ProfileConfig.checkAndAdjustDeviceModeConfiguration(ProfileConfig.java:400)
D/BtSettings.ProfileConfig( 4542): 	at com.broadcom.bt.service.ProfileConfig.init(ProfileConfig.java:550)
D/BtSettings.ProfileConfig( 4542): 	at com.lge.bluetooth.adapter.LGBluetoothProfileConfigAdapter.init(LGBluetoothProfileConfigAdapter.java:30)
D/BtSettings.ProfileConfig( 4542): 	at com.android.bluetooth.btservice.AdapterApp.onCreate(AdapterApp.java:67)
D/BtSettings.ProfileConfig( 4542): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
D/BtSettings.ProfileConfig( 4542): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
D/BtSettings.ProfileConfig( 4542): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
D/BtSettings.ProfileConfig( 4542): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
D/BtSettings.ProfileConfig( 4542): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 4542): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 4542): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
D/BtSettings.ProfileConfig( 4542): 	at java.lang.reflect.Method.invoke(Native Method)
D/BtSettings.ProfileConfig( 4542): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BtSettings.ProfileConfig( 4542): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
D/BtSettings.ProfileConfig( 4542): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/BtSettings.ProfileConfig( 4542): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/BtSettings.ProfileConfig( 4542): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 4542): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 4542): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 4542): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 4542): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 4542): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BtSettings.Profi,leConfig( 4542): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@c925ce9 on behalf of 4465
D/BtSettings.ProfileConfig( 4542): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
V/BluetoothPbapReceiver( 4542): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 4542): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 4542): ***********state = 10
D/Finsky  ( 4465): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4465): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  953): Waited long enough for: ServiceRecord{18b97c3c u0 com.android.mms/.service.SwitchedService}
V/LGMDMManagerInternal( 4542): Create singleton instance
,D/Finsky  ( 4465): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4465): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourceType(  953): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,D/LGBluetoothUserBindClient( 4444): [BTUI] onServiceConnected
I/[LGHome]EVENT( 1965): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/BluetoothPermissionRequest( 4444): onReceive
,D/LGBluetoothUtils( 4444): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 4444): cancelDiscoverableAlarm(): Enter
I/FmServiceJni( 4542): classInitNative: succeeds

```
