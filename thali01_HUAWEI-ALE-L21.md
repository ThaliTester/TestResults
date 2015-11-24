#### Test 50388019b17f598_thali01_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
I/HwLauncher( 3621): StkAppReceiver StkAppReceiver action:==android.intent.action.BOOT_COMPLETED
I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10007
I/HwSystemManager( 3803): HoldService:uid:10007 pid:3902 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10007,3902
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10007, pid: 3902
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10007, pid: 3902
I/HwLauncher( 3621): PreBootCompletedReceiver PreBootCompletedReceiver action:==android.intent.action.BOOT_COMPLETED
I/HwCust  ( 3621): Constructor found for class com.huawei.android.launcher.HwCustPreBootCompletedReceiverImpl
I/HwLauncher( 3621): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3621): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3621): Model STK reName intent is received.
I/HwLauncher( 3621): Model mAllAppsList.updatePackage com.android.stk
I/HwLauncher( 3621): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
I/HwLauncher( 3621): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
I/HwLauncher( 3621): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
I/HwLauncher( 3621): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3621): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
I/HwLauncher( 3621): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
I/HwLauncher( 3621): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3621): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3621): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3621): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3621): Launcher.Folder childCount: 5
I/HwLauncher( 3621): Launcher.Folder childCount: 5
I/HwLauncher( 3621): Launcher.Folder childCount: 7
I/HwLauncher( 3621): Launcher.Folder childCount: 7
I/HwLauncher( 3621): Launcher.Folder childCount: 6
I/HwLauncher( 3621): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
I/HwLauncher( 3621): Launcher.Folder childCount: 6
I/HwLauncher( 3621): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
I/HwLauncher( 3621): Launcher.Folder childCount: 7
I/HwLauncher( 3621): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3621):  syncPages mCurrentPage = 0
E/HideAppsPagedView( 3621):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3621):  createAddIcon count = 0
I/HwLauncher( 3621):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
W/PGApi_client( 3511): recv actoionId = 10010, action = com.huawei.pgmng.PGAction@3d2481f0 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3511): in handleAction method, action = 10010
W/PGMiddleWare jhh( 3511): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@233849f9, action = com.huawei.pgmng.PGAction@3d2481f0 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3511): jhh handle default mActionId = 10010, action = com.huawei.pgmng.PGAction@3d2481f0 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3511): enter into the safetyguard Scene.
W/AudioEffectLowPowerImpl jhh( 3511): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3511): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3511): return for smartPAOn and mLowAudioEffectEnable both = false
E/Thermal-daemon( 2331): [charger_ic] temp_new :33  temp_old :34
I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10014
I/HwSystemManager( 3803): HoldService:uid:10014 pid:5292 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10014,5292
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10014, pid: 5292
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10014, pid: 5292
E/HwOUC   ( 5645): [main-1]load system config caught FileNotFoundException(/HwOucConfig.java:1298)
I/art     ( 5645): Can not find class: Lcom/huawei/pad/Product;
E/HwOUC   ( 5645): [main-1]method invoke failed(/HwOucUtility.java:471)
I/HwOUC   ( 5645): [main-1]isTablet() = false(/HwOucUtility.java:474)
I/HwOUC   ( 5645): [main-1]baseVersionOfNewVersion is ALE-L21C432B132;isInstallingStatus is false(/HwOucUtility.java:2228)
I/HwOUC   ( 5645): [main-1]HwOucApplication--onCreate, cacheCpuInfo is 8_1.2GHz(hwouc/HwOucApplication.java:48)
I/HwOUC   ( 5645): [main-1]receive ACTION_BOOT_COMPLETED -----for pad customized(hwouc/DownloadReceiver.java:70)
I/HwOUC   ( 5645): [main-1]receive ACTION_BOOT_COMPLETED ----settingNetworkDialogTime is 1456158732723(hwouc/DownloadReceiver.java:76)
I/HwOUC   ( 5645): [Thread-59-59]ProcessResumeWhenExceptionThread run(hwouc/ProcessResumeWhenExceptionThread.java:35)
I/HwOUC   ( 5645): [main-1]receive ACTION_BOOT_COMPLETED ----Show settingNetworkDialogTime is 1456158732723;currentTime is 1448385972814(hwouc/DownloadReceiver.java:83)
I/art     ( 5645): Can not find class: Lcom/huawei/pad/Product;
E/HwOUC   ( 5645): [main-1]method invoke failed(hwouc/HwOucUtility.java:471)
I/HwOUC   ( 5645): [main-1]isTablet() = false(hwouc/HwOucUtility.java:474)
I/HwOUC   ( 5645): [main-1]isCharm is false(hwouc/HwOucUtility.java:425)
I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10060
I/HwSystemManager( 3803): HoldService:uid:10060 pid:4963 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10060,4963
I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10008
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10060, pid: 4963
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10060, pid: 4963
I/HwSystemManager( 3803): HoldService:uid:10008 pid:5325 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10008,5325
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10008, pid: 5325
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10008, pid: 5325
W/asset   ( 5690): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
I/HwSystemManager( 5690): SystemManagerApplication:onCreate
I/HwSystemManager( 3803): MainService:on startCommand,flags:0,startId:5
I/System.out( 5690): [ls, -l, /system/app/HwSystemManager/HwSystemManager.apk]
I/System.out( 5690): null
I/System.out( 5690): null
I/System.out( 5690): Calling by::className:bkk  MethodName:yw
I/HwSystemManager( 3803): LocalService:Received start id 4: Intent { cmp=com.huawei.systemmanager/com.huawei.permission.HoldService }
I/HwSystemManager( 3803): BgPowerManagerService:onStartCommand
I/HwSystemManager( 3803): AppLockService:onStartCommand
I/HwSystemManager( 5690): check push opration, match idx:-1
I/HwSystemManager( 3803): AppCleanUpService:onStartCommand() in!
I/HwSystemManager( 5690): HsmStat_info:feature enable:false
E/Thermal-daemon( 2331): [ap] temp_new :33  temp_old :34
I/HwSystemManager( 5690): ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.example.hello, com.test.thalitest]
I/HwSystemManager( 5690): OverseaCfgHelper:permissionStatus is 0
I/HwSystemManager( 5690): ProcPolicy:begin get procName.
I/HwSystemManager( 5690): ProcPolicy:this proc is:com.huawei.systemmanager
I/HwSystemManager( 5690): ProcPolicy:end get procName.
I/HwSystemManager( 5690): SimCardManager:/onReceive: action =android.intent.action.ACTION_DSDS_SUB1_OPERATOR_CHANGED
I/YhdsEngine( 5690): [EngineIntentService] Received: com.huawei.dianxinos.optimizer.engine.action.APP_START
I/HwSystemManager( 5690): SimCardManager:/getOperatorNameFromService: in spn action airpalne mode on
I/HwSystemManager( 5690): SimCardManager:getOperatorNameFromService mNameServSlot0 = null
I/HwSystemManager( 5690): SimCardManager:/onReceive: action =android.intent.action.ACTION_DSDS_SUB2_OPERATOR_CHANGED
I/HwSystemManager( 5690): SimCardManager:/getOperatorNameFromService: in spn action airpalne mode on
I/HwSystemManager( 5690): SimCardManager:getOperatorNameFromService mNameServSlot1 = null
I/HwSystemManager( 5690): SimCardManager:/onReceive: action =android.provider.Telephony.SPN_STRINGS_UPDATED
I/HwSystemManager( 5690): SimCardManager:action:android.provider.Telephony.SPN_STRINGS_UPDATED
I/HwSystemManager( 5690): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@16f09aa7
I/HwSystemManager( 5690): HsmIntentService:started for intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.BOOT_COMPLETED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
I/HwSystemManager( 5690): ComBroadcastReceiver:ComBroadcastReceiver action = android.intent.action.BOOT_COMPLETED
I/HwSystemManager( 5690): HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
I/HwSystemManager( 5690): OptimizeReceiver:OptimizeReceiver received action:android.intent.action.BOOT_COMPLETED
I/HwSystemManager( 5690): HsmIntentService:task completed for intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.BOOT_COMPLETED
I/HwSystemManager( 5690): HsmIntentService:in thread:Thread[HsmIntentServiceTask #1,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 5690): HsmIntentService:last work complete! lets stop service.
I/YhdsEngine( 5690): [AlarmEventMgr] event scheduled: com.dianxinos.optimizer.action.ALARM_EVENT_THUMBNAIL_CLEAN
I/HwSystemManager( 3803): LocalService:Received start id 5: Intent { cmp=com.huawei.systemmanager/com.huawei.permission.HoldService }
I/HwSystemManager( 5690): ComBroadcastReceiver:Start Hold Service
I/HwSystemManager( 5690): HsmIntentService:started for intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.ComBroadcastReceiver (has extras) }, action:android.intent.action.BOOT_COMPLETED, class:com.huawei.permissionmanager.ui.ComBroadcastReceiver
I/HwSystemManager( 5690): AppCleanUpLackStorageReceiver:AppCleanUpLackStorageReceiver boot completed
I/HwSystemManager( 5690): HsmIntentService:invoked com.huawei.permissionmanager.ui.ComBroadcastReceiver
I/HwSystemManager( 3803): AppCleanUpService:onStartCommand() in!
I/HwSystemManager( 3803): AppCleanUpService:onStartCommand() out!
I/HwSystemManager( 5690): UpdateCheckRecorder:Recorder, add /data/cust/xml/hsm/permission/hsm_permission_white_apps.xml
E/HwSystemManager( 3803): AppCleanUpService:msg is 2
I/HwSystemManager( 5690): xml:Recorded sign:0, current sign:0:/data/cust/xml/hsm/permission/hsm_permission_white_apps.xml
I/YhdsEngine( 5690): [EngineIntentService] Received: com.dianxinos.optimizer.action.ALARM_EVENT_THUMBNAIL_CLEAN
I/HwSystemManager( 5690): UpdateCheckRecorder:Recorder, add /data/cust/xml/hsm/permission/hsm_permission_black_apps.xml
I/HwSystemManager( 5690): xml:Recorded sign:0, current sign:0:/data/cust/xml/hsm/permission/hsm_permission_black_apps.xml
I/HwSystemManager( 5690): HsmIntentService:task completed for intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.ComBroadcastReceiver (has extras) }, action:android.intent.action.BOOT_COMPLETED
I/HwSystemManager( 5690): HsmIntentService:in thread:Thread[HsmIntentServiceTask #2,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 5690): HsmIntentService:last work complete! lets stop service.
I/HwSystemManager( 5690): PreventReceiver:RreventReceiver receive the action :android.intent.action.BOOT_COMPLETED
I/HwSystemManager( 3803): AppCleanUpAndStorageNotifyUtils:isLackSpaceShow is true
I/HwSystemManager( 3803): AppCleanUpAndStorageNotifyUtils:cancel alarmManager !
I/HwSystemManager( 3803): AppCleanUpAndStorageNotifyUtils:set alarmManager !
I/HwSystemManager( 5690): HsmIntentService:started for intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.BOOT_COMPLETED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
I/HwSystemManager( 5690): HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
I/HwSystemManager( 5690): BootBroadcastReceiver:doInBackground handle action: android.intent.action.BOOT_COMPLETED
W/HwSystemManager( 5690): ChangeMode:setAlarmPolicyState, NoSuchMethodException
I/HwCust  ( 5690): Constructor found for class com.huawei.systemmanager.comm.module.HwCustModuleCustomizeImpl
W/HwSystemManager( 5690): TMSApplicationWrapper:try to init service, virus module disabled.
E/HwSystemManager( 5690): SecurityBroadcastReceiver:SecurityBroadcastReceiver the rainbow is not enabled!
I/HwSystemManager( 3803): AppLockService:onStartCommand
I/HwSystemManager( 5690): avl:parsePowerWarningParameter result:{app_show_level=1, dangerous_current_level=30, count_frequency_fg=5, high_level_standard=10, msg_send_interval=240, dangerous_level_standard=25, min_interval_time=3, average_current_fg=350, count_frequency=60}
I/HwSystemManager( 5690): HsmIntentService:task completed for intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.BOOT_COMPLETED
I/HwSystemManager( 5690): HsmIntentService:in thread:Thread[HsmIntentServiceTask #3,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 5690): HsmIntentService:last work complete! lets stop service.
W/MsgPolicyThreshold( 3511): path not found:/sys/devices/system/cpu/cpu0/cpufreq/msg_policy
I/HwSystemManager( 5690): avm: alreadySaved ? false
I/HwSystemManager( 5690): avm:presetRoguePackage rogueList is:[]
I/HwSystemManager( 5690): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@16f09aa7
W/PGManager( 3511): the new power is the same as old. why not.
,I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10004
I/HwSystemManager( 3803): HoldService:uid:10004 pid:4798 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10004,4798
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10004, pid: 4798
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10004, pid: 4798
I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10010
I/HwSystemManager( 3803): HoldService:uid:10010 pid:3861 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10010,3861
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10010, pid: 3861
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10010, pid: 3861
I/appproc ( 5750): CLASSPATH=/system/framework/am.jar
I/appproc ( 5750): Command=app_process /system/bin com.android.commands.am.Am start -n com.example.hello/com.example.hello.MainActivity 
I/appproc ( 5750): app_process:number,5,0
I/HwCust  ( 5752): Constructor found for class com.huawei.omacp.HwCustCheckJobImpl
I/AndroidRuntime( 5750): readDownloadBoosterConfig: 'false'
I/HwCust  ( 5752): Constructor found for class com.huawei.omacp.HwCustReceiverImpl
I/Receiver( 5752): onReceive start...
I/Receiver( 5752): onReceive_boot completed action.
I/Receiver( 5752): onReceive complete.
I/ProvDBHelper( 5752): fetchUnreadProvMessage OK.
I/        ( 5750): power log dlsym ok
I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10017
I/HwSystemManager( 3803): HoldService:uid:10017 pid:5358 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10017,5358
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10017, pid: 5358
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10017, pid: 5358
I/ActivityManager( 2935): filter receiver for action = com.android.providers.calendar.intent.CalendarProvider2
E/android_hardware_fm.cpp( 5750): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 5750): ========64bit long size = 8
E/FM_HAL  ( 5750): [FM_HAL], libname is libhisifm_if
I/fm_hisi ( 5750): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 5750): 
I/fm_hisi ( 5750): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 5750): 
I/fm_hisi ( 5750): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 5750): 
E/android_hardware_fm.cpp( 5750): register_android_hardware_fm_fmradio, ret is 0
I/art     ( 2935): Can not find class: Lcom/android/server/wm/WindowState$2;
I/art     ( 2935): Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
I/art     ( 2935): Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
I/art     ( 2935): Can not find class: Lcom/android/server/wm/StartingData;
I/HwLauncher( 3621): Launcher onPause()
I/HwLauncher( 3621): Launcher.MotionManager stopMotionAppsReco 402
I/art     ( 2935): Can not find class: Landroid/widget/ViewStub;
I/HwLauncher( 3621): Launcher.MotionManager stopMotionAppsReco 403
I/art     ( 2935): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 2935): Can not find class: Landroid/app/ViewStub;
W/HwLauncher( 3621): Launcher.MotionManager stopMotionAppsReco service flg 402 is unavailable
W/HwLauncher( 3621): Launcher.MotionManager stopMotionAppsReco service flg 403 is unavailable
I/art     ( 2935): Can not find class: Lcom/android/server/am/ActivityStack$2;
I/HwCust  ( 3575): Constructor found for class com.android.stk.HwCustStkAppServiceImpl
E/STK App ( 3575): StkAppService refreshCatService fail
I/HwLauncher( 3621): Launcher onStop()
E/STK App ( 3575): StkAppService refreshCatService fail
I/HwLauncher( 3621): Launcher dismissDialog
I/HwLauncher( 3621): Launcher dynamicIconsUnregister
I/HwLauncher( 3621): DynamicUpdater unregisterReceiver
I/HwCust  ( 5813): Constructor found for class org.simalliance.openmobileapi.service.HwCustSmartcardServiceImpl
I/HwSystemManager( 3803): HoldService:uid:1000 pid:5382 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:1000,5382
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
W/MediaProcessHandler( 2935): processOp uid 1000 is not concerned!
I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 1000
I/HwLauncher( 3621): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.calendar
I/HwLauncher( 3621): DynamicUpdater unregisterReceiver
I/HwSystemManager( 3803): AppLockService:applock password not initial or function is closed
I/HwLauncher( 3621): DynamicIcon onPause  isvisible = true   mAttachedToWindow:true    mWindowVisible:truecom.android.deskclock
I/HwLauncher( 3621): DynamicUpdater unregisterReceiver
I/HwLauncher( 3621): DynamicIcon onPause  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
I/HwLauncher( 3621): DynamicIcon onVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3621): DynamicIcon onVisibilityChanged 4 - com.android.deskclock
I/PhoneStatusBar( 3174): shouldTranslucent:true
I/PhoneStatusBar( 3174): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/HwLauncher( 3621): Launcher  onWindowVisibilityChanged visibility = 4
I/HwLauncher( 3621): DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3621): DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
I/HwLauncher( 3621): Launcher  onWindowVisibilityChanged visibility = 8
I/HwLauncher( 3621): DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
I/HwLauncher( 3621): DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
I/SUPL20_Config( 3597):  supl version 2
I/HwCust  ( 5813): Constructor found for class org.simalliance.openmobileapi.service.terminals.HwCustUiccTerminalImpl
I/UiccTerminal( 5813): get the TelephonyAPDU instance is success ,the real class is com.android.telephonyapdu.ITelephonyAPDU$Stub$Proxy
I/UiccTerminal( 5813): get the TelephonyAPDU instance is success ,the real class is com.android.telephonyapdu.ITelephonyAPDU$Stub$Proxy
W/PGApi_client( 3511): recv actoionId = 10000, action = com.huawei.pgmng.PGAction@17c2a369 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3511): in handleAction method, action = 10000
W/PGMiddleWare jhh( 3511): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@233849f9, action = com.huawei.pgmng.PGAction@17c2a369 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3511): jhh handle default mActionId = 10000, action = com.huawei.pgmng.PGAction@17c2a369 actionId =10000 pkg =com.example.hello extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3511): enter into DEFAULT_FRONT Scene.
W/AudioEffectLowPowerImpl jhh( 3511): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3511): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3511): return for smartPAOn and mLowAudioEffectEnable both = false
I/SUPL20_Config( 3597): UDP socket enabled = false
I/SUPL20_Config( 3597): pcm socketpath is /data/gnss/pcm_socthe orginal parsed value is/data/gnss/pcm_soc
I/SUPL20_Config( 3597): scm socketpath is /data/gnss/scm_socthe orginal parsed value is/data/gnss/scm_soc
I/SmartcardService( 5813): Initializing Access Control
I/SmartcardService( 5813): NOT initializing Access Control for SIM SE not present.
I/SmartcardService( 5813): OnPostExecute()
I/HwSystemManager( 3803): AppLockService:applock password not initial or function is closed
I/SUPL20_Config( 3597): UDP socket enabled = false
I/PGSocket( 3511): socket:android.net.LocalSocket@37dfc1ee impl:android.net.LocalSocketImpl@2370468f fd:FileDescriptor[41] bw:java.io.BufferedWriter@2de7cd1c
I/SUPL20_Config( 3597): KeyStore Valid =true
I/SUPL20_Config( 3597): KeyStore Path = /system/etc/security
I/SUPL20_Config( 3597): ConnectionTimeOut :15
I/SUPL20_Config( 3597): ConnectionRetries:5
I/SUPL20_Config( 3597): PCMPort:9001
I/SUPL20_Config( 3597): PCMFQDN:127.0.0.1
I/SUPL20_Config( 3597): SCMPort:9002
I/SUPL20_Config( 3597): SCMFQDN:127.0.0.1
I/SUPL20_Config( 3597): PCMUnixSocPath:/data/gnss/pcm_soc
I/SUPL20_Config( 3597): SCMUnixSocPath:/data/gnss/scm_soc
E/SUPL20_Config( 3597): /system/etc/gnss/config/SuplConfig.spl not found 
E/SUPL20_Config( 3597): java.io.FileNotFoundException: /system/etc/gnss/config/SuplConfig.spl: open failed: ENOENT (No such file or directory)
E/SUPL20_Config( 3597): 	at libcore.io.IoBridge.open(IoBridge.java:463)
E/SUPL20_Config( 3597): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
E/SUPL20_Config( 3597): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
E/SUPL20_Config( 3597): 	at java.io.FileReader.<init>(FileReader.java:66)
E/SUPL20_Config( 3597): 	at com.android.supl.config.ConfigManager.loadKeyStorePath(ConfigManager.java:217)
E/SUPL20_Config( 3597): 	at com.android.supl.config.ConfigManager.<init>(ConfigManager.java:207)
E/SUPL20_Config( 3597): 	at com.android.supl.config.ConfigManager.getInstance(ConfigManager.java:196)
E/SUPL20_Config( 3597): 	at com.android.supl.loc.SUPLPlatformService.onCreate(SUPLPlatformService.java:114)
E/SUPL20_Config( 3597): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2858)
E/SUPL20_Config( 3597): 	at android.app.ActivityThread.access$2200(ActivityThread.java:152)
E/SUPL20_Config( 3597): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SUPL20_Config( 3597): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SUPL20_Config( 3597): 	at android.os.Looper.loop(Looper.java:135)
E/SUPL20_Config( 3597): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
E/SUPL20_Config( 3597): 	at java.lang.reflect.Method.invoke(Native Method)
E/SUPL20_Config( 3597): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SUPL20_Config( 3597): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
E/SUPL20_Config( 3597): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
E/SUPL20_Config( 3597): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
E/SUPL20_Config( 3597): 	at libcore.io.Posix.open(Native Method)
E/SUPL20_Config( 3597): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/SUPL20_Config( 3597): 	at libcore.io.IoBridge.open(IoBridge.java:449)
E/SUPL20_Config( 3597): 	... 17 more
I/SUPL20_Config( 3597): key store path and pd taken from the config xml file
I/SUPL20_Config( 3597): stPd = 123456
I/SUPL20_Config( 3597): Path = /system/etc/security
E/SUPL20_NC( 3597): iConnType = 0
I/SUPL20_SCMService( 3597): Support for MultiBearer
E/SUPL20_NC( 3597): iConnType = 0
I/SUPL20_SCMService( 3597): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3597): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3597): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3597): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3597): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3597): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3597): network type:0 ,UNKNOWN
I/SUPL20_SCMService( 3597): network type:0 ,UNKNOWN
I/WebViewFactory( 5845): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10032
I/HwSystemManager( 3803): HoldService:uid:10032 pid:5403 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10032,5403
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10032, pid: 5403
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10032, pid: 5403
I/LibraryLoader( 5845): Loading: webviewchromium
I/LibraryLoader( 5845): Time to load native libraries: 46 ms (timestamps 36-82)
I/LibraryLoader( 5845): Expected native library version number "",actual native library version number ""
I/LibraryLoader( 5845): Expected native library version number "",actual native library version number ""
I/chromium( 5845): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5845): Initializing chromium process, renderers=0
W/art     ( 5845): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5845): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 5845): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5845): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
I/chromium( 5845): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10030
I/HwSystemManager( 3803): HoldService:uid:10030 pid:5426 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10030,5426
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10030, pid: 5426
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10030, pid: 5426
W/chromium( 5845): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 5845): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 5845): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10004
I/HwSystemManager( 3803): HoldService:uid:10004 pid:3668 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10004,3668
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10004, pid: 3668
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10004, pid: 3668
W/art     ( 5845): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5845): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 5845): Can not find class: Landroid/widget/ViewStub;
I/art     ( 5845): Can not find class: Landroid/webkit/ViewStub;
I/art     ( 5845): Can not find class: Landroid/app/ViewStub;
W/art     ( 5845): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5845): Attempt to remove local handle scope entry from IRT, ignoring
,I/HwSystemManager( 5690): HsmStat_info:service connect
,I/art     ( 5983): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 5983): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5983): Installed default security provider GmsCore_OpenSSL
,I/PG Utils( 5983): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/OpenGLRenderer( 5845): Initialized EGL, version 1.4
,I/ActivityManager( 2935): Displayed com.example.hello/.MainActivity: +1s268ms
,W/System.err( 2935): java.lang.SecurityException: WifiService: Neither user 10087 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2935): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2935): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2935): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2935): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2935): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2935): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2935): 	at android.os.Binder.execTransact(Binder.java:446)
E/WifiManager( 5983): WifiServiceMessenger == null
,I/art     ( 2935): Can not find class: Lcom/android/server/wm/DisplayContentList;
,I/art     ( 2935): Can not find class: Lcom/android/server/statusbar/StatusBarManagerService$4;
,I/chromium( 5845): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 5845): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/dex2oat ( 6032): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=default --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1506981928.jar --oat-fd=34 --oat-location=/data/data/com.google.android.youtube/cache/ads1506981928.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6032): dex2oat took 55.264ms (threads: 8)
,I/art     ( 5983): Can not find class: Lcom/google/android/ads/zxxz/e;
,I/art     ( 5983): Can not find class: Lcom/google/android/ads/zxxz/l;
,I/art     ( 5983): Can not find class: Lcom/google/android/ads/zxxz/i;
,I/art     ( 5983): Can not find class: Lcom/google/android/ads/zxxz/g;
,I/art     ( 5983): Can not find class: Lcom/google/android/ads/zxxz/m;
I/art     ( 5983): Can not find class: Lcom/google/android/ads/zxxz/f;
I/art     ( 5983): Can not find class: Lcom/google/android/ads/zxxz/k;
,I/art     ( 5983): Can not find class: Lcom/google/android/ads/zxxz/j;
,E/YouTube MDX( 5983): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/art     ( 5983): Can not find class: Lcom/google/android/ads/zxxz/d;
,I/art     ( 5983): Can not find class: Lcom/google/android/ads/zxxz/c;
,I/art     ( 5983): Can not find class: Lcom/google/android/ads/zxxz/b;
,I/art     ( 5983): Can not find class: Lcom/google/android/ads/zxxz/h;
,I/art     ( 5983): Can not find class: Lcom/google/android/ads/zxxz/a;
,W/ContextImpl( 5983): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/MultiDex( 6050): VM with version 2.1.0 has multidex support
I/MultiDex( 6050): install
,I/MultiDex( 6050): MultiDexExtractor.load(/data/app/com.google.android.gms-2/base.apk, false)
,I/chromium( 5845): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5845): 
,I/MultiDex( 6050): loading existing secondary dex files
,I/MultiDex( 6050): load found 3 secondary dex files
,I/MultiDex( 6050): install done
,I/System  ( 5983): core_booster, getBoosterConfig = false
,W/jxcore-log( 5845): Initializing JXcore engine
W/jxcore-log( 5845): JXcore engine is ready
,W/jxcore-log( 5845): Starting JXcore engine
,I/PG Utils( 6050): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 6050): Can not find class: Lcom/google/android/gms/org/conscrypt/OpenSSLSocketFactoryImpl;
,W/System  ( 6050): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11b1d580: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6050): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 2935): filter receiver for action = com.google.android.gms.INITIALIZE
,W/ContextImpl( 5983): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,W/ContextImpl( 5983): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,W/ContextImpl( 5983): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 5983): Found 10007
,I/ActivityManager( 2935): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2935): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,W/ContextImpl( 5983): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,W/jxcore-log( 5845): Platform android
W/jxcore-log( 5845): 
W/jxcore-log( 5845): Process ARCH arm
W/jxcore-log( 5845): 
,I/ActivityManager( 2935): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/jxcore-log( 5845): JXcore Cordova bridge is ready!
I/jxcore-log( 5845): 
,W/jxcore-log( 5845): JXcore engine is started
,E/jxcore-log( 5845): >> HUAWEI-ALE-L21
E/jxcore-log( 5845): 
,I/jxcore-log( 5845): Total memory 1949741056
I/jxcore-log( 5845): 
,I/jxcore-log( 5845): Free memory 18980864
I/jxcore-log( 5845): 
,I/jxcore-log( 5845): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5845): 
I/jxcore-log( 5845): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5845): 
,I/jxcore-log( 5845): userPath [ 'www' ]
I/jxcore-log( 5845): 
,I/jxcore-log( 5845): Size 720 1184
I/jxcore-log( 5845): 
,I/jxcore-log( 5845): Screen Brightness 242
I/jxcore-log( 5845): 
,E/jxcore-log( 5845): Dummy Error Log.
E/jxcore-log( 5845): 
,I/SUPL20_PCM( 3597): calling nc.connect for pcm
I/SUPL20_NC( 3597): Calling getLocalSocket for PCM
,I/SUPL20_NC( 3597): deque initialized
I/SUPL20_NC( 3597): WriterThread initialize
,I/SUPL20_NC( 3597): readerThread initialized
,I/SUPL20_PCM( 3597): process icmdID: 0X101
I/SUPL20_PCM( 3597): process hello msg
I/SUPL20_PCM( 3597): init msg success
I/SUPL20_PCM( 3597): sendHelloMessage
I/SUPL20_PCM( 3597): process: process less then zero 0
I/SUPL20_SPIMESLP-SENDING( 3597): m_bPacket.length 12
I/SUPL20_SPIMESLP-SENDING( 3597): bBrokenPipe = false
I/SUPL20_PCM( 3597): process icmdID: 0X103
I/SUPL20_LocMan( 3597): register the Emergency Receiver 
I/SUPL20_SCM( 3597): calling nc.connect for scm
I/SUPL20_NC( 3597): Calling getLocalSocket for SCM
I/SUPL20_NC( 3597): deque initialized
I/SUPL20_NC( 3597): WriterThread initialize
I/SUPL20_NC( 3597): readerThread initialized
I/SUPL20_PCM( 3597):  process MSG_PCM_GET_LOCATION_ID
I/SUPL20_PCM( 3597): process icmdID: 0X11a
I/SUPL20_PCM( 3597):  process MSG_PCM_GET_HIST_KEY
,I/SUPL20_SCM( 3597): buffer size:12writePosition: 12
I/SUPL20_SCM( 3597): process icmdID2: 0X201
I/SUPL20_SCM( 3597): process hello msg
I/SUPL20_SCM( 3597): init msg success
I/SUPL20_SCM( 3597): sendHelloMessage
,I/SUPL20_SPIMESLP-SENDING( 3597): m_bPacket.length 12
I/SUPL20_SPIMESLP-SENDING( 3597): bBrokenPipe = false
,I/SUPL20_LocMan( 3597): SIM state :1
,I/SUPL20_LocMan( 3597): Registered MyPhoneStateListener
,W/PhoneInterfaceManager( 3575): shouldBlockLocation running ...
,I/PhoneInterfaceManager( 3575): shouldBlockLocation  ret:false
,E/SUPL20_LocMan( 3597): tm.getCellLocation() returned null
I/SUPL20_LocMan( 3597):  sim is not enabled on the SET
,I/SUPL20_LocMan( 3597): onServiceStateChanged ServiceState.STATE_POWER_OFF
,E/PhoneInterfaceManager( 3575): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/SUPL20_LocMan( 3597): Phone type:GSM
,I/SUPL20_LocMan( 3597): NULL Value received for network operator
I/SUPL20_LocMan( 3597):  cellInfo NetworkType:UNKNOWN,0
,I/SUPL20_LocMan( 3597): onDataConnectionStateChanged networkType = 0
I/SUPL20_SPIMESLP-SENDING( 3597): m_bPacket.length 40
I/SUPL20_SPIMESLP-SENDING( 3597): bBrokenPipe = false
I/SUPL20_LocMan( 3597): onDataConnectionStateChanged state = -1
,W/PhoneInterfaceManager( 3575): shouldBlockLocation running ...
,I/PhoneInterfaceManager( 3575): shouldBlockLocation  ret:false
,E/SUPL20_LocMan( 3597): tm.getCellLocation() returned null
,I/SUPL20_LocMan( 3597): onDataConnectionStateChanged Unknown: -1
,W/PhoneInterfaceManager( 3575): shouldBlockLocation running ...
,I/PhoneInterfaceManager( 3575): shouldBlockLocation  ret:false
,E/SUPL20_LocMan( 3597): tm.getCellLocation() returned null
,I/SystemBroadcastReceiver( 6131): Boot has been completed
I/SystemBroadcastReceiver( 6131): toggleAppIcon() : FLAG_SYSTEM = true
,I/SUPL20_PCM( 3597): Fetching the historic secret key ...
I/SUPL20_PCM( 3597): process: process less then zero 0
I/SUPL20_SPIMESLP-SENDING( 3597): m_bPacket.length 24
I/SUPL20_SPIMESLP-SENDING( 3597): bBrokenPipe = false
,I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10001
I/HwSystemManager( 3803): HoldService:uid:10001 pid:4747 died
I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10059
I/HwSystemManager( 3803): HoldService:oldVersionKey:10001,4747
I/HwSystemManager( 3803): HoldService:uid:10059 pid:5484 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10059,5484
,E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10001, pid: 4747
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10001, pid: 4747
,E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10059, pid: 5484
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10059, pid: 5484
,I/art     ( 2935): Explicit concurrent mark sweep GC freed 19496(1025KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.572ms total 171.031ms
,I/SystemBroadcastReceiver( 6131): Killing my process: pid=6131
I/Process ( 6131): Sending signal. PID: 6131 SIG: 9
,I/jxcore-log( 5845): getBuffer is called!!!!
I/jxcore-log( 5845): 
,I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10077
I/HwSystemManager( 3803): HoldService:uid:10077 pid:6131 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10077,6131
,E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10077, pid: 6131
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10077, pid: 6131
,I/art     ( 2935): Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,I/AlarmInitReceiver( 5540): handleMessage : AlarmInitReceiver, will exit app. Config.exit_count: 0
,I/art     ( 5540): System.exit called, status: 0
I/AndroidRuntime( 5540): VM exiting with result code 0, cleanup skipped.
,I/PG Utils( 6166): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Babel_SMS( 6166): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6166): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6166): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Android-Mms/2.0, mUaProfUrl=http://www.google.com/oha/rdf/ua-profile-kila.xml
I/Babel_SMS( 6166): MmsConfig.loadFromDatabase
,I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10045
I/HwSystemManager( 3803): HoldService:uid:10045 pid:5540 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10045,5540
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10045, pid: 5540
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10045, pid: 5540
,E/Babel_SMS( 6166): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6166): MmsConfig.loadFromResources
,E/Babel_SMS( 6166): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6166): MmsConfig.loadMmsSettings: mUserAgent=Android-Mms/2.0, mUaProfUrl=http://www.google.com/oha/rdf/ua-profile-kila.xml
,I/CameraHalInterface( 2584): Found a matching camera info for ID 0
,I/CameraHalInterface( 2584): Found a matching camera info for ID 1
,W/Settings( 6166): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/System.err( 2935): java.lang.SecurityException: WifiService: Neither user 10058 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2935): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2935): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2935): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2935): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2935): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2935): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2935): 	at android.os.Binder.execTransact(Binder.java:446)
,E/WifiManager( 6166): WifiServiceMessenger == null
,I/Babel_Crash( 6166): startup - clean
,I/Babel   ( 6166): deleted: false for 0
,W/VideoCapabilities( 6166): Unsupported mime video/mpeg
,W/VideoCapabilities( 6166): Unsupported mime video/mpeg2
,W/VideoCapabilities( 6166): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6166): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6166): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6166): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6166): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6166): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6166): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6166): Unrecognized profile 32768 for video/3gpp
W/VideoCapabilities( 6166): Unrecognized profile/level 0/0 for video/3gpp
W/VideoCapabilities( 6166): Unrecognized profile 0 for video/3gpp
,W/VideoCapabilities( 6166): Unsupported mime video/mp4
,I/VideoCapabilities( 6166): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6166): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6166): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6166): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6166): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6166): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6166): Unsupported profile 8 for video/mp4v-es
I/VideoCapabilities( 6166): Unsupported profile 8 for video/mp4v-es
W/VideoCapabilities( 6166): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 6166): Unrecognized profile 0 for video/mp4v-es
,W/VideoCapabilities( 6166): Unsupported mime video/mpeg4
,W/VideoCapabilities( 6166): Unsupported mime video/x-flv
,W/VideoCapabilities( 6166): Unsupported mime video/vc1
,W/VideoCapabilities( 6166): Unsupported mime video/wvc1
,W/VideoCapabilities( 6166): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6166): Unsupported mime video/x-ms-wmv3
,W/VideoCapabilities( 6166): Unsupported mime video/x-pn-realvideo
,W/VideoCapabilities( 6166): Unsupported mime video/ffmpeg
,W/AudioCapabilities( 6166): Unsupported mime audio/ffmpeg
,I/VideoCapabilities( 6166): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager( 2935): filter receiver for action = com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION
,I/PG Utils( 6050): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG,
,I/vclib   ( 6166): onServiceConnected
,W/Babel   ( 6166): Attempted to change video mute state without an active call.,
,I/iu.UploadsManager( 6050): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,I/PG Utils( 6050): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6050): acquire_providerpkg:[com.android.providers.media] pid:[]  maybe timeout , send to PG
,I/iu.UploadsManager( 6050): End new media; added: 0, uploading: 0, time: 38 ms
,I/PG Utils( 6050): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2935): filter receiver for action = com.android.mail.ACTION_NOTIFY_DATASET_CHANGED
,I/PG Utils( 6201): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2935): filter receiver for action = com.google.android.gm.intent.ACTION_PROVIDER_CREATED
,I/Gmail   ( 6201): getAccountsCursor
,I/art     ( 2935): Can not find class: Lcom/android/server/accounts/AccountManagerService$GetAccountsByTypeAndFeatureSession;
,I/art     ( 2935): Can not find class: Lcom/android/server/accounts/AccountManagerService$Session;
,I/art     ( 6201): Can not find class: Lcom/google/ads/AdRequest;
,W/GAV2    ( 6201): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 6201): Observing account changes for notifications
,E/Gmail   ( 6201): Error finding the version of the Email provider.....
E/Gmail   ( 6201): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6201): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:120)
E/Gmail   ( 6201): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6201): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6201): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6201): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6201): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6201): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6201): getAccountsCursor
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 228us total 32.164ms
,E/SQLiteLog( 6201): (283) recovered 98 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 203us total 28.811ms
,I/art     ( 2324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 205us total 22.442ms
,I/Gmail   ( 6201): notifyAccountChanged
,I/PG Utils( 6201): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Gmail   ( 6201): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6201): getAccountsCursor
,I/PG Utils( 6201): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Gmail   ( 6201): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6201): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6201): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3803): HoldService:uid:1000 pid:5462 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:1000,5462
,E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
W/MediaProcessHandler( 2935): processOp uid 1000 is not concerned!
,E/WearSyncService( 6246): Failed to connect to GoogleApiClient within the timeout
,I/PG Utils( 6201): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6201): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6201): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/Gmail   ( 6201): getAccountsCursor
,I/PG Utils( 6306): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/System.err( 2935): java.lang.SecurityException: WifiService: Neither user 10025 nor current process has android.permission.CHANGE_WIFI_STATE.
W/System.err( 2935): 	at android.app.ContextImpl.enforce(ContextImpl.java:1962)
W/System.err( 2935): 	at android.app.ContextImpl.enforceCallingOrSelfPermission(ContextImpl.java:1991)
W/System.err( 2935): 	at com.android.server.wifi.WifiServiceImpl.enforceChangePermission(WifiServiceImpl.java:784)
W/System.err( 2935): 	at com.android.server.wifi.WifiServiceImpl.getWifiServiceMessenger(WifiServiceImpl.java:1903)
W/System.err( 2935): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:495)
W/System.err( 2935): 	at com.android.server.wifi.HwWifiService.onTransact(HwWifiService.java:61)
W/System.err( 2935): 	at android.os.Binder.execTransact(Binder.java:446)
E/WifiManager( 6306): WifiServiceMessenger == null
,W/Settings( 6306): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6306): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PG Utils( 6306): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6306): acquire_providerpkg:[com.android.providers.downloads] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3449): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 6050): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm64/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,I/PG Utils( 6050): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/InstanceID/Rpc( 6050): Found 10007
,I/ActivityManager( 2935): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/ActivityManager( 2935): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10047
I/HwSystemManager( 3803): HoldService:uid:10047 pid:5517 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10047,5517
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10047, pid: 5517
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10047, pid: 5517
,I/art     ( 2935): Explicit concurrent mark sweep GC freed 14142(673KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.735ms total 182.825ms
,I/PG Utils( 6050): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/CheckinService( 6050): Checkin interval check for package: unspecified last checkin: 1448013111636 min interval config: 0 actual interval: 372867960
,I/CheckinService( 6050): Disabling old GoogleServicesFramework version
,I/GCoreUlr( 6050): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 3449): DispatchingService.onCreate()
,I/CheckinService( 6050): Checking schedule, now: 1448385979665 next: 1448603372250
,I/CheckinService( 6050): active receiver: disabled
,I/SystemUpdateService( 6050): cancelUpdate (empty URL)
,I/SystemUpdateService( 6050): active receiver: disabled
,I/PG Utils( 3449): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/art     ( 6050): Can not find class: Landroid/content/pm/PackageManager$OnPermissionsChangedListener;
,I/art     ( 6050): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 6050): Can not find class: Lcom/google/android/gms/common/h/c;
,I/art     ( 6050): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/PG Utils( 3449): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2935): filter receiver for action = com.google.android.gms.security.snet.BOOT_COMPLETED
,I/ActivityManager( 2935): filter receiver for action = com.google.android.checkin.CHECKIN_COMPLETE
,I/GCoreUlr( 3449): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/ActivityManager( 2935): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,W/BaseAppContext( 6050): Using Auth Proxy for data requests.
,I/art     ( 3449): Explicit concurrent mark sweep GC freed 26521(1627KB) AllocSpace objects, 6(120KB) LOS objects, 40% free, 17MB/29MB, paused 1.590ms total 117.935ms
,I/art     ( 3647): Explicit concurrent mark sweep GC freed 8049(490KB) AllocSpace objects, 3(60KB) LOS objects, 40% free, 17MB/29MB, paused 1.178ms total 100.211ms
,I/art     ( 6050): Explicit concurrent mark sweep GC freed 44199(3MB) AllocSpace objects, 27(540KB) LOS objects, 40% free, 17MB/29MB, paused 2.097ms total 118.806ms
,I/AuthZen ( 6050): Fetching signing key...
,I/AuthZen ( 6050): Signing key fetched successfully!
,W/BaseAppContext( 6050): Using Auth Proxy for data requests.
,I/GCoreUlr( 3449): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/PG Utils( 6050): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6050): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2935): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
,W/Kids    ( 6050): [AbstractKidsOperation] Invalid device state 3
,I/Kids    ( 6050): [KidAccountFixer] No network connection
,W/GCoreFlp( 3449): No location to return for getLastLocation()
,W/FusedLocationProvider( 6050): location=null
I/EventLogService( 6050): Aggregate from 1448383808211 (log), 1448383808211 (data)
,I/GCoreUlr( 3449): Unbound from all location providers
I/PG Utils( 6050): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/ActivityManager( 2935): filter receiver for action = com.google.android.gms.gcm.ACTION_SCHEDULE
I/PG Utils( 6050): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3449): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 3449): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/GCoreUlr( 3449): DispatchingService.onDestroy()
I/GCoreUlr( 3449): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 3449): Unbound from all location providers
,W/Auth    ( 3647): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,W/GCoreFlp( 3449): No location to return for getLastLocation()
W/FusedLocationProvider( 6050): location=null
,I/PG Utils( 6050): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6050): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6050): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6050): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6414): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6414): acquire_providerpkg:[com.google.android.partnersetup] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6444): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 6444): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,W/StubController( 5564): calendar access!
,W/StubController( 5564): calendar access!
,I/CalendarSimpleUiPRovider( 5564): onReceive[intent]Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.simpleui.CalendarSimpleUiPRovider }
I/CalendarSimpleUiPRovider( 5564): onConfigurationChanged
,W/StubController( 5564): calendar access!
,I/CalendarSimpleUiPRovider( 5564): initParams20151124T182620Europe/Warsaw(2,327,3600,0,1448385980)
,W/StubController( 5564): calendar access!
,I/WebViewFactory( 6414): Loading com.android.webview version 37 (eng.jenkinswh-arm64) (code 199992)
,I/LibraryLoader( 6414): Loading: webviewchromium
,I/LibraryLoader( 6414): Time to load native libraries: 4 ms (timestamps 6625-6629)
I/LibraryLoader( 6414): Expected native library version number "",actual native library version number ""
,W/art     ( 6414): Attempt to remove local handle scope entry from IRT, ignoring
,I/PG Utils( 6414): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5564): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5564): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,I/PG Utils( 5564): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
I/PG Utils( 5564): acquire_providerpkg:[com.android.providers.calendar] pid:[]  maybe timeout , send to PG
,W/art     ( 6414): Attempt to remove local handle scope entry from IRT, ignoring
,I/HwLauncher( 3621): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
,I/HwLauncher( 3621): StkAppReceiver StkAppReceiver action:==com.android.stk.status_change
I/HwLauncher( 3621): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3621): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3621): Model STK reName intent is received.
,I/HwLauncher( 3621): Model mAllAppsList.updatePackage com.android.stk
,I/HwLauncher( 3621): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
,E/        ( 2935): open /proc/5517/smaps fail errno 2
,I/BluetoothAdapter( 5845): Start to disable Bluetooth!
,W/StubController( 6480): calendar access!
,W/StubController( 5564): calendar access!
,I/HwLauncher( 3621): Model  onReceive intent=Intent { act=android.intent.action.appname.change.stk flg=0x10 pkg=com.huawei.android.launcher (has extras) }
I/HwLauncher( 3621): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 2 packages = [com.android.stk]
I/HwLauncher( 3621): Model STK reName intent is received.
,I/HwLauncher( 3621): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/ActivityManager( 2935): filter receiver for action = com.android.calendar.APPWIDGET_UPDATE
,I/HwLauncher( 3621): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3621): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
,I/HwCust  ( 6506): Constructor found for class com.android.providers.contacts.HwCustContactsProviderHelperImpl
,I/PG Utils( 6506): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3803): HoldService:checkBeforeShowDialog: uid:10302 pid:5845, permissionType:2097152
I/HwSystemManager( 3803): OverseaCfgHelper:permissionStatus is 0
,I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10050
I/HwLauncher( 3621): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/ConnectPermission( 2935): allowOpenWifi blocked:false
I/HwSystemManager( 3803): HoldService:uid:10050 pid:5597 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10050,5597
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10050, pid: 5597
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10050, pid: 5597
,I/PG Utils( 6506): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/jxcore-log( 5845): ****TEST TOOK:  5259  ms ****
I/jxcore-log( 5845): 
I/jxcore-log( 5845): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5845): 
I/CalendarSimpleUiPRovider( 5564): loadEvent end update UI0
,I/PG Utils( 6506): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/HwLauncher( 3621): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
I/HwLauncher( 3621): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwCust  ( 6506): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
I/HwLauncher( 3621): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3621): Model shortcutInfo.title = SIM Toolkit
I/HwCust  ( 6506): Constructor found for class com.android.providers.contacts.HwCustContactsDatabaseHelperImpl
I/PG Utils( 6506): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
I/HwLauncher( 3621): Model mAllAppsList.updatePackage com.android.stk
I/HwLauncher( 3621): AllIdleAppsList  updatePackage : package[com.android.stk] matched activity's size is 2 and data List size is 61
,I/HwLauncher( 3621): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3621): Launcher.Folder childCount: 5
I/HwLauncher( 3621): Launcher.Folder childCount: 5
,I/HwLauncher( 3621): Launcher.Folder childCount: 7
I/HwLauncher( 3621): Launcher.Folder childCount: 7
I/HwLauncher( 3621): Launcher.Folder childCount: 6
I/HwLauncher( 3621): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3621): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwCust  ( 6537): Constructor found for class com.huawei.mms.util.HwCustHwBackgroundLoaderImpl
I/HwLauncher( 3621): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3621): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
,I/HwLauncher( 3621): Launcher.IconCache changeStkTitleBySim() title from stk db = SIM Toolkit
,I/HwCust  ( 6506): Constructor found for class com.android.providers.contacts.HwCustContactsProvider2Impl
,I/HwLauncher( 3621): Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,I/HwLauncher( 3621): Launcher.IconCache, cacheLocked end Utilities.createIconBitmap entry.title = SIM Toolkit
I/HwLauncher( 3621): Model shortcutInfo.title = SIM Toolkit
I/HwLauncher( 3621): Model shortcutInfo.title = SIM Toolkit
,I/HwLauncher( 3621): Launcher.Folder childCount: 6
I/HwLauncher( 3621): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3621): Launcher.Folder childCount: 7
I/HwLauncher( 3621): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3621):  syncPages mCurrentPage = 0
,E/ContactsProtector( 6506): getHiCloudAccountData query fail
I/PG Utils( 6506): acquire_providerpkg:[com.android.providers.contacts] pid:[]  maybe timeout , send to PG
,E/HideAppsPagedView( 3621):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3621):  createAddIcon count = 0
,I/PG Utils( 3483): acquire_providerpkg:[com.android.providers.userdictionary] pid:[]  maybe timeout , send to PG
I/HwLauncher( 3621):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
I/HwLauncher( 3621): Launcher Deferring update until onResume
I/HwLauncher( 3621): Workspace updateShortcuts apps.size() 2
I/HwLauncher( 3621): Launcher.Folder childCount: 5
I/HwLauncher( 3621): Launcher.Folder childCount: 5
I/HwLauncher( 3621): Launcher.Folder childCount: 7
I/HwLauncher( 3621): Launcher.Folder childCount: 7
I/HwLauncher( 3621): Launcher.Folder childCount: 6
I/HwLauncher( 3621): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
I/HwLauncher( 3621): Launcher.Folder childCount: 6
I/HwLauncher( 3621): Launcher.Folder updateFolderShortcuts shortcutInfo = SIM Toolkit
,I/HwLauncher( 3621): Launcher.Folder childCount: 7
I/HwLauncher( 3621): Launcher.Folder childCount: 7
E/HideAppsPagedView( 3621):  syncPages mCurrentPage = 0
,W/HWContacts( 6537): ProviderFeatureChcker - cootek package not installed
,E/HideAppsPagedView( 3621):  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
E/HideAppsPagedView( 3621):  createAddIcon count = 0
,I/HwLauncher( 3621):  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,I/HwLauncher( 3621): Launcher Deferring update until onResume
,E/TmoMonitor( 6537): Add already observed target for ThreadEx's defualtExecutor TaskStack com.huawei.cspcommon.ex.ThreadEx$SerialExecutor@a9be3c1
,I/HwCust  ( 6506): Constructor found for class com.android.providers.contacts.aggregation.HwCustContactAggregatorImpl
,I/HwCust  ( 6506): Constructor found for class com.android.providers.contacts.HwCustDataRowHandlerForGroupMembershipImpl
,I/art     ( 2935): Explicit concurrent mark sweep GC freed 17871(1144KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.860ms total 180.205ms
,I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 1000
,I/HwSystemManager( 3803): HoldService:uid:1000 pid:5622 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:1000,5622
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
W/MediaProcessHandler( 2935): processOp uid 1000 is not concerned!
,I/HwCust  ( 6537): Constructor found for class com.android.mms.data.HwCustConversationImpl
,I/HwSystemManager( 3803): ContactsObserverHelper:Receive contacts change broadcast
,I/appproc ( 6570): CLASSPATH=/system/framework/pm.jar
I/appproc ( 6570): Command=app_process /system/bin com.android.commands.pm.Pm uninstall -k com.example.hello 
I/appproc ( 6570): app_process:number,5,0
,I/EmuiFeatureManager( 6537): loadEmailAnrSupportFlag:true
,I/Mms_threadcache( 6537): [RecipientIdCache] fill: begin
,I/AndroidRuntime( 6570): readDownloadBoosterConfig: 'false'
,I/SimFactoryManager( 6537): Inside init method of SimFactoryManger the combination is:-1
,I/SimFactoryManager( 6537): Get SIM state from SIM factory manager: 1,For slotId:0
I/SimFactoryManager( 6537): isSIM1CardPresent:1
,I/SimFactoryManager( 6537): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6537): Get SIM state from SIM factory manager: 1,For slotId:1
,I/SimFactoryManager( 6537): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,I/SimFactoryManager( 6537): Get SIM state from SIM factory manager: 1,For slotId:1
E/MmsConfig( 6537): load /system/etc/xml/mms_config.xml MmsSettings caught FileNotFoundException
,I/SimFactoryManager( 6537): isSIM2CardPresent:1
,I/SimFactoryManager( 6537): Get SIM state from SIM factory manager: 1,For slotId:0
,I/SimFactoryManager( 6537): Get SIM state from SIM factory manager: 1,For slotId:1
,I/SimFactoryManager( 6537): updateSimState,sIsSIMCard1Present=false,sIsSIMCard1Enabled=false,sIsSIMCard2Present=false,sIsSIMCard2Enabled=false
,I/HwCust  ( 6537): Constructor found for class com.android.contacts.HwCustContactApplicationHelperImpl
,I/HwCust  ( 6537): Constructor found for class com.android.contacts.hap.HwCustCommonUtilMethodsImpl
,I/art     ( 6537): Can not find class: Lhuawei/android/view/TableLayout;
,I/art     ( 6537): Can not find class: Lhuawei/android/widget/TableLayout;
,I/art     ( 6537): Can not find class: Lhuawei/android/view/View;
,I/art     ( 6537): Can not find class: Lhuawei/android/widget/View;
I/art     ( 6537): Can not find class: Landroid/widget/View;
I/art     ( 6537): Can not find class: Landroid/webkit/View;
,I/art     ( 6537): Can not find class: Landroid/app/View;
,I/art     ( 6537): Can not find class: Lhuawei/android/view/TableRow;
,I/art     ( 6537): Can not find class: Lhuawei/android/widget/TableRow;
,I/art     ( 6537): Can not find class: Lhuawei/android/view/LinearLayout;
,I/art     ( 6537): Can not find class: Lhuawei/android/widget/LinearLayout;
,I/art     ( 6537): Can not find class: Lhuawei/android/view/ImageButton;
I/art     ( 6537): Can not find class: Lhuawei/android/widget/ImageButton;
I/art     ( 6537): Can not find class: Lhuawei/android/view/TextView;
I/art     ( 6537): Can not find class: Lhuawei/android/widget/TextView;
,I/HwCust  ( 6537): Constructor found for class com.android.mms.transaction.HwCustMsgNotificationImpl
,I/HwCust  ( 6537): Constructor found for class com.android.mms.transaction.HwCustMessagingNotificationImpl
,I/art     ( 6537): Can not find class: Lhuawei/android/view/RelativeLayout;
I/art     ( 6537): Can not find class: Lhuawei/android/widget/RelativeLayout;
,I/art     ( 6537): Can not find class: Lhuawei/android/view/ImageView;
,I/art     ( 6537): Can not find class: Lhuawei/android/widget/ImageView;
,I/        ( 6570): power log dlsym ok
,I/art     ( 6537): Can not find class: Lhuawei/android/view/ViewStub;
,I/art     ( 6537): Can not find class: Lhuawei/android/widget/ViewStub;
I/art     ( 6537): Can not find class: Landroid/widget/ViewStub;
I/art     ( 6537): Can not find class: Landroid/webkit/ViewStub;
,I/art     ( 6537): Can not find class: Landroid/app/ViewStub;
,E/android_hardware_fm.cpp( 6570): register_android_hardware_fm_fmradio
I/android_hardware_fm.cpp( 6570): ========64bit long size = 8
E/FM_HAL  ( 6570): [FM_HAL], libname is libhisifm_if
,I/fm_hisi ( 6570): FM::[fm_device_open:4653] fm_device_open
I/fm_hisi ( 6570): 
I/fm_hisi ( 6570): FM::[fm_device_open:4664] find the id:libhisifm_if and begins to open the device
I/fm_hisi ( 6570): 
I/fm_hisi ( 6570): FM::[fm_device_open:4708] device open sucess
I/fm_hisi ( 6570): 
,E/android_hardware_fm.cpp( 6570): register_android_hardware_fm_fmradio, ret is 0
,I/art     ( 2935): Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,I/art     ( 2935): Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,I/art     ( 6537): Can not find class: Lhuawei/android/view/FrameLayout;
I/art     ( 6537): Can not find class: Lhuawei/android/widget/FrameLayout;
,I/art     ( 6537): Can not find class: Lhuawei/android/view/EditText;
,I/art     ( 6537): Can not find class: Lhuawei/android/widget/EditText;
,E/textview( 6537): initAddtionalStyle default
,I/art     ( 6537): Can not find class: Lhuawei/android/view/ProgressBar;
,I/art     ( 6537): Can not find class: Lhuawei/android/widget/ProgressBar;
,I/CommonUtilMethods isFastScrollerIsVisibleToChilds( 6537): fieldValue : protected java.lang.Object android.widget.AbsListView.getScrollerInner()
,I/CalendarProvider2( 6480): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6480): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 2935): filter receiver for action = android.intent.action.PROVIDER_CHANGED
,I/HwLauncher( 3621): Launcher  onWindowVisibilityChanged visibility = 4
I/HwLauncher( 3621): DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
I/HwLauncher( 3621): DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
,I/ActivityManager( 2935): filter receiver for action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 2935): filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10302
I/HwSystemManager( 3803): HoldService:uid:10302 pid:5845 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10302,5845
,I/HwSystemManager( 3803): AppLockService:applock password not initial or function is closed
W/GeofencerStateMachine( 3449): Ignoring removeGeofence because network location is disabled.
,E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10302, pid: 5845
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10302, pid: 5845
,I/InputReader( 2935): Reconfiguring input devices.  changes=0x00000010
,I/HwLauncher( 3621): Launcher onStart()
I/HwLauncher( 3621): Launcher dynamicIconsRegister
I/HwLauncher( 3621): DynamicUpdater registerReceiver
,I/HwSystemManager( 3803): AppManager:getNetAppInfoFromDB cursor lenth = 1
,E/RegisteredServicesCache( 3554): invalidateCache set mNeedToastTableFull
,W/System.err( 2935): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/System.err( 2935): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 2935): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
W/System.err( 2935): 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
W/System.err( 2935): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2935): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2935): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/PGApi_client( 3511): recv actoionId = 10010, action = com.huawei.pgmng.PGAction@2bd90d25 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
W/PGMiddleWare jhh( 3511): in handleAction method, action = 10010
W/PGMiddleWare jhh( 3511): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@233849f9, action = com.huawei.pgmng.PGAction@2bd90d25 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
I/AudioEffectLowPowerImpl jhh( 3511): jhh handle default mActionId = 10010, action = com.huawei.pgmng.PGAction@2bd90d25 actionId =10010 pkg =com.huawei.android.launcher extend1 =0 extend2 = flag =3 type =1
W/AudioEffectLowPowerImpl jhh( 3511): enter into the safetyguard Scene.
W/AudioEffectLowPowerImpl jhh( 3511): m2DGameFront = false, m3DGameFront = false, mMediaPerceptible = false, mMusicPerceptible = false
,W/AudioEffectLowPowerImpl jhh( 3511): mAudioActive = false, mMusicPerceptible = false
W/AudioEffectLowPowerImpl jhh( 3511): return for smartPAOn and mLowAudioEffectEnable both = false
,I/art     ( 3803): Explicit concurrent mark sweep GC freed 88163(5MB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 14MB/23MB, paused 1.220ms total 94.456ms
I/HwSystemManager( 3803): HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwSystemManager( 3803): HsmPackageManager:replacing:false
I/HwSystemManager( 3803): HsmPackageManager:pkgName:com.example.hello
I/HwSystemManager( 3803): HsmPackageManager:doAppRemoved, remove:com.example.hello
,I/HwSystemManager( 3803): ww:deleteLockData:com.example.hello
,I/HwLauncher( 3621): DynamicUpdater call updateFolder
I/HwLauncher( 3621): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
I/HwLauncher( 3621): DynamicUpdater registerReceiver
,W/ResourceType( 2935): ResTable_typeSpec entry count inconsistent: given 1, previously 1445
,I/art     ( 2935): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,I/art     ( 2935): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
,I/art     ( 2935): Can not find class: Lhuawei/com/android/server/util/ReportTool;
,I/art     ( 2935): Can not find class: Lcom/huawei/report/ReporterInterface;
,E/ReportTools( 2935): Can't find sReporterClazz
,I/art     ( 2935): Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,I/art     ( 2935): Can not find class: Lhuawei/com/android/server/util/AppInfo;
,W/System.err( 2935): java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,W/System.err( 2935): 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
W/System.err( 2935): 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
W/System.err( 2935): 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
W/System.err( 2935): 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
W/System.err( 2935): 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9036)
W/System.err( 2935): 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9092)
W/System.err( 2935): 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
W/System.err( 2935): 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
W/System.err( 2935): 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
W/System.err( 2935): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
W/System.err( 2935): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 2935): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2935): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2935): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/System.err( 2935): 	at com.android.server.SystemServer.main(SystemServer.java:212)
W/System.err( 2935): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 2935): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 2935): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 2935): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
E/ReportTools( 2935): This is not beta user build
,I/HwLauncher( 3621): DynamicUpdater call updateFolder
I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10052
I/HwLauncher( 3621): DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
I/HwLauncher( 3621): DynamicUpdater registerReceiver
,I/HwSystemManager( 3803): HoldService:uid:10052 pid:5645 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10052,5645
,I/HwLauncher( 3621): DynamicUpdater call updateFolder
I/HwLauncher( 3621): DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
,I/HwLauncher( 3621): Launcher onResume()
I/HwLauncher( 3621): WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
I/HwLauncher( 3621): Launcher doResumeWork()
,I/HwLauncher( 3621): Launcher.MotionManager startMotionAppsReco 402
,I/HwLauncher( 3621): Launcher  onResume mIsToUninstallApp = false
,E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10052, pid: 5645
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10052, pid: 5645
,W/asset   ( 2935): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwLauncher( 3621): DynamicIcon onVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3621): DynamicIcon onVisibilityChanged 0 - com.android.deskclock
,I/art     ( 2935): Explicit concurrent mark sweep GC freed 13816(1003KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 27MB/41MB, paused 2.682ms total 243.994ms
,I/HwLauncher( 3621): Launcher  onWindowVisibilityChanged visibility = 0
I/HwLauncher( 3621): DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
I/HwLauncher( 3621): DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
I/PhoneStatusBar( 3174): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
I/HwLauncher( 3621): Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/HwLauncher( 3621): Model replacing = false package = com.example.hello
I/HwLauncher( 3621): Model  ACTION_PACKAGE_REMOVED replacing = false
I/HwLauncher( 3621): MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.example.hello]
I/HwLauncher( 3621): SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.example.hello
I/HwLauncher( 3621): SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.example.hello
I/HwLauncher( 3621): Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
I/HwLauncher( 3621): SimpleAllAppsList   add packageName into uninstalledSDApps 
I/HwLauncher( 3621): SimpleLauncherModeuninstalledSDApps size > 0
W/HwLauncher( 3621): SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
I/HwLauncher( 3621): SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
I/art     ( 3621): Can not find class: Lhuawei/android/view/EditText;
I/art     ( 3621): Can not find class: Lhuawei/android/widget/EditText;
E/textview( 3621): initAddtionalStyle default
I/PhoneStatusBar( 3174): shouldTranslucent:true
I/PhoneStatusBar( 3174): hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,I/HwSystemManager( 3803): NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_ADDED
I/HwSystemManager( 3803): NotificationManagerReceiver:onReceive, send action to background
I/PG Utils( 3621): acquire_providerpkg:[com.huawei.motionservice] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3803): ProcPolicy:begin get procName.
,I/HwSystemManager( 3803): ProcPolicy:this proc is:com.huawei.systemmanager:service
I/HwSystemManager( 3803): ProcPolicy:end get procName.
,W/asset   ( 6673): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10056
I/HwSystemManager( 3803): HoldService:uid:10056 pid:5728 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10056,5728
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10056, pid: 5728
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10056, pid: 5728
,I/HwSystemManager( 3803): HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@2d3ea244
,I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 1000
I/HwSystemManager( 3803): HoldService:uid:1000 pid:5690 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:1000,5690
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
W/MediaProcessHandler( 2935): processOp uid 1000 is not concerned!
,I/HwSystemManager( 3803): HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED, class:com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 3803): HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
,I/HwSystemManager( 3803): XmlRuleBase:parseAndCacheList notification_black_list_match :[com.android.contacts, com.android.email, com.android.calendar, com.huawei.android.hwouc, com.huawei.appmarket, com.huawei.gamebox, com.huawei.android.thememanager, com.android.mediacenter, com.huawei.hwvplayer, com.android.browser, com.vmall.client, com.huawei.wallet, com.huawei.android.totemweather, com.huawei.android.FMRadio, com.android.soundrecorder, com.android.providers.downloads.ui, com.android.settings]
,I/HwSystemManager( 3803): XmlRuleBase:parseAndCacheList notification_white_list_match :[]
,I/HwSystemManager( 3803): NmCenterDefValueXmlHelper:mCachedConfigs = null, init.
I/HwSystemManager( 3803): NmCenterDefValueXmlHelper:getConfigs: Starts
,I/HwSystemManager( 3803): NmCenterDefValueXmlHelper:getConfigs: Ends. Count = 33
,I/HwSystemManager( 3803): NotificationDBAdapter:initNewApp: add to db:com.example.hello, default:null
,I/HwSystemManager( 3803): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3803): NotificationDBProvider:query starts, matchCode = 1
W/HwSystemManager( 3803): NotificationDBAdapter:initNewApp: Fail to get uid , skip applying default cfg. pkgname = com.example.hello
I/HwSystemManager( 3803): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 3803): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3803): NotificationDBProvider:query starts, matchCode = 1
,I/HwSystemManager( 3803): NotificationDBProvider:call: method = notification_list_query
I/HwSystemManager( 3803): NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
I/HwSystemManager( 3803): NotificationDBProvider:query starts, matchCode = 1
,I/PhoneStatusBar( 3174): notification pkg =com.android.settings
I/PhoneStatusBar( 3174): notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
I/PhoneStatusBar( 3174): notification pkg =android
I/PhoneStatusBar( 3174): notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
,I/HwSystemManager( 3803): HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_ADDED
,I/HwSystemManager( 3803): HsmIntentService:in thread:Thread[HsmIntentServiceTask #1,5,main], current active tasksize:1, queue size:0
I/HwSystemManager( 3803): HsmIntentService:last work complete! lets stop service.
,I/art     ( 2325): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 442us total 25.950ms
,I/HwCust  ( 6673): Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,I/HwCust  ( 6673): Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,I/GAV2    ( 6201): Thread[GAThread,5,main]: No campaign data found.
,I/art     ( 2325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 376us total 39.775ms
,I/art     ( 2325): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 372us total 20.164ms
,I/PG Utils( 6050): acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
I/PG Utils( 3621): acquire_providerpkg:[com.huawei.motionservice] pid:[]  maybe timeout , send to PG
,I/HwSystemManager( 3803): HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@2d3ea244
,W/asset   ( 6714): Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,I/HwLauncher( 3621): Model mAllAppsList.removePackage com.example.hello
,E/HideAppsPagedView( 3621): removeItems begin 
E/HideAppsPagedView( 3621): ShortcutInfo(title=HelloWorld)
E/HideAppsPagedView( 3621): removeItems end 
I/HwSystemManager( 3803): BgPowerManagerService:onProcessDied uid = 10065
I/HwSystemManager( 3803): HoldService:uid:10065 pid:5752 died
I/HwSystemManager( 3803): HoldService:oldVersionKey:10065,5752
E/HsmCoreServiceImpl( 2935): onTransact in code is: 102
I/MediaProcessHandler( 2935): processOp opType: 1, uid: 10065, pid: 5752
W/MediaProcessHandler( 2935): remove target not exist, maybe the UI process: uid: 10065, pid: 5752
I/HwLauncher( 3621): Workspace removeItems info = ShortcutInfo(title=HelloWorld) isNeedDelete = true
W/System.err( 3621): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
I/GAv4-SVC( 6050): Google Analytics 8.3.01 is starting up.
W/System.err( 3621): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
W/System.err( 3621): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:340)
W/System.err( 3621): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3621): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3621): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3621): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3621): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3621): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3621): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3621): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3621): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
W/System.err( 3621): java.lang.NullPointerException: null receiver
W/System.err( 3621): 	at java.lang.reflect.Field.get(Native Method)
W/System.err( 3621): 	at java.lang.reflect.Field.get(Field.java:279)
W/System.err( 3621): 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:365)
W/System.err( 3621): 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
W/System.err( 3621): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3621): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3621): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3621): 	at android.app.ActivityThread.main(ActivityThread.java:5538)
W/System.err( 3621): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3621): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3621): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
W/System.err( 3621): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
I/HwLauncher( 3621): CellLayout rearrangeAfterRmItem isAutoAlign = false
I/HwLauncher( 3621): WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
,E/HideAppsPagedView( 3621): removeHideApps  begin 
E/HideAppsPagedView( 3621): removeHideApps  end 
E/HideAppsPagedView( 3621):  syncPages mCurrentPage = 0

```
