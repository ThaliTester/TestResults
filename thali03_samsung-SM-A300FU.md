#### Test 82147046d1155fd_thali03_samsung-SM-A300FU Logs


```
--------- beginning of system
,08-22 11:14:51.375  1022  1035 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
08-22 11:14:51.375  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.385  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.385  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.385  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.405  1022  1035 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6643 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
--------- beginning of main
08-22 11:14:51.405  6643  6643 E Zygote  : MountEmulatedStorage()
08-22 11:14:51.405  6643  6643 I libpersona: KNOX_SDCARD checking this for 10090
08-22 11:14:51.405  6643  6643 E Zygote  : v2
08-22 11:14:51.405  6643  6643 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:51.405  1022  1035 I ActivityManager: Killing 6204:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-22 11:14:51.405  6643  6643 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:51.415  6643  6643 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:51.415  6643  6643 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:14:51.445  6643  6643 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:51.445  6643  6643 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:51.475  6643  6643 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
08-22 11:14:51.485  6643  6643 D elm:15121: ELMEngine.ELMEngine( context ).
08-22 11:14:51.485  6643  6643 D elm:15121: MDMBridge.setEnterpriseBridge()
08-22 11:14:51.485  1022  4370 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-22 11:14:51.485  1022  4370 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-22 11:14:51.485  1022  4370 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:51.485  1022  4370 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:51.485  1022  4370 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-22 11:14:51.495  6643  6643 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
08-22 11:14:51.495  6643  6643 D elm:15121: ElmAgentService : onCreate()
08-22 11:14:51.495  6643  6660 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
08-22 11:14:51.505  6643  6660 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
08-22 11:14:51.505  1022  1223 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-22 11:14:51.505  1022  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
08-22 11:14:51.505  6643  6643 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
08-22 11:14:51.505  1022  1223 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:51.505  1022  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:51.505  1022  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
08-22 11:14:51.505  6643  6643 D elm:15121: ModuleBase.ModifySetAlarm()
08-22 11:14:51.505  6643  6643 D elm:15121: MDMBridge.getInstance()
08-22 11:14:51.505  6643  6643 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-22 11:14:51.515  6643  6643 D elm:15121: ElmAgentService : onDestroy().
08-22 11:14:51.525  1022  4369 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-22 11:14:51.525  1022  4369 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
08-22 11:14:51.525  1022  4369 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:51.525  1022  4369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:51.525  1022  4369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
08-22 11:14:51.525  1022  1329 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
08-22 11:14:51.525  1022  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.525  1022  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.525  1022  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.525  1022  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.545  6664  6664 E Zygote  : MountEmulatedStorage()
08-22 11:14:51.545  6664  6664 E Zygote  : v2
08-22 11:14:51.545  6664  6664 I libpersona: KNOX_SDCARD checking this for 10037
08-22 11:14:51.545  6664  6664 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:51.545  6664  6664 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:51.545  1022  1329 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6664 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 11:14:51.545  6664  6664 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:51.545  1022  1486 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-22 11:14:51.545  6664  6664 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-22 11:14:51.545  1022  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.545  1022  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.545  1022  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.545  1022  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.565  6664  6664 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:51.565  6664  6664 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:51.575  6679  6679 E Zygote  : MountEmulatedStorage()
08-22 11:14:51.575  6679  6679 E Zygote  : v2
08-22 11:14:51.575  6679  6679 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:14:51.575  6679  6679 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:51.575  6679  6679 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:51.575  6679  6679 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:51.575  6679  6679 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:14:51.575  1022  1486 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=6679 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 11:14:51.605  6664  6664 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
08-22 11:14:51.605   314   314 I art     : Explicit concurrent mark sweep GC freed 8667(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 22.229ms
08-22 11:14:51.615  6679  6679 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:51.615  6679  6679 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:51.625   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 17.066ms
08-22 11:14:51.635  6664  6664 I CalendarProvider2: CalendarProvider2.onCreate() called
08-22 11:14:51.645   314   314 I art     : Explicit concurrent mark sweep GC freed 3(80B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 636us total 16.671ms
08-22 11:14:51.645  6679  6679 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 11:14:51.645  6679  6679 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 11:14:51.645  6679  6679 D SecurityLogAgent: StateMachine : Current State = 1
08-22 11:14:51.645  1022  4367 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
08-22 11:14:51.645  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.645  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.645  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.645  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.665  6652  6652 D AndroidRuntime: 
08-22 11:14:51.665  6652  6652 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-22 11:14:51.665  6695  6695 E Zygote  : MountEmulatedStorage()
08-22 11:14:51.665  6652  6652 D AndroidRuntime: CheckJNI is OFF
08-22 11:14:51.665  6695  6695 E Zygote  : v2
08-22 11:14:51.665  6695  6695 I libpersona: KNOX_SDCARD checking this for 10153
08-22 11:14:51.665  6695  6695 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:51.665  6652  6652 D AndroidRuntime: readGMSProperty: start
08-22 11:14:51.665  6652  6652 D AndroidRuntime: readGMSProperty: already setted!!
08-22 11:14:51.665  6652  6652 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-22 11:14:51.665  6652  6652 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 11:14:51.665  6652  6652 D AndroidRuntime: readGMSProperty: end
08-22 11:14:51.665  6652  6652 D AndroidRuntime: addProductProperty: start
08-22 11:14:51.665  1022  4367 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6695 uid=10153 gids={50153, 9997} abi=armeabi-v7a
08-22 11:14:51.665  6695  6695 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:51.665  1022  4367 I ActivityManager: Killing 6140:com.google.android.apps.plus/u0a117 (adj 15): empty #21
08-22 11:14:51.665  6695  6695 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:51.675  6695  6695 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:14:51.705  6695  6695 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:51.705  6695  6695 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:51.725  6695  6695 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:51.735  1022  1035 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
08-22 11:14:51.735  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.735  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.735  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.735  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.755  6720  6720 E Zygote  : MountEmulatedStorage()
08-22 11:14:51.755  6720  6720 E Zygote  : v2
08-22 11:14:51.755  6720  6720 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:14:51.755  6720  6720 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:51.755  6720  6720 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:51.755  1022  1035 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6720 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 11:14:51.755  1022  1035 I ActivityManager: Killing 6313:com.sec.android.app.music:service/u0a35 (adj 15): empty #21
08-22 11:14:51.755  6720  6720 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:51.755  6720  6720 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:14:51.765  1022  1034 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
08-22 11:14:51.765  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
08-22 11:14:51.765  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:51.765  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:51.765  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
08-22 11:14:51.795  6720  6720 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:51.795  6720  6720 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:51.795  6652  6652 E AffinityControl: AffinityControl: registerfunction enter
08-22 11:14:51.825  1022  4371 I ActivityManager: Killing 6225:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
08-22 11:14:51.825  6652  6652 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-22 11:14:51.825  6720  6720 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1471857291839
08-22 11:14:51.825  6720  6720 D         : TimeServiceNative: User Time to be set is 1471857291840
08-22 11:14:51.825  6720  6720 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-22 11:14:51.825  6720  6720 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-22 11:14:51.825  6720  6720 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1471857291840
08-22 11:14:51.835  6720  6720 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-22 11:14:51.835   338   430 D QC-time-services: Daemon: Connection accepted:time_genoff
08-22 11:14:51.835   338  6738 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1471857291840
08-22 11:14:51.835   338  6738 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1471857291840, operation = 0
08-22 11:14:51.835   338  6738 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/17/71 2:57:45
08-22 11:14:51.835   338  6738 D QC-time-services: Daemon:Value read from RTC seconds = 35607465000
08-22 11:14:51.835   338  6738 D QC-time-services: Daemon:new time 1471857291840 
08-22 11:14:51.835   338  6738 D QC-time-services: Daemon: delta 1436249826840 genoff 1436249826840 
08-22 11:14:51.835   338  6738 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249826840 to memory
08-22 11:14:51.835   338  6738 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-22 11:14:51.835   338  6738 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-22 11:14:51.855  1022  4368 E PersonaManagerService: inState():  stateMachine is null !!
08-22 11:14:51.855  1022  4368 I PersonaManagerService: PersonaId don't exist
08-22 11:14:51.855  1022  4368 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-22 11:14:51.855  1022  4368 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 11:14:51.875  1022  4368 W ActivityManager: mDVFSHelper.acquire()
08-22 11:14:51.875  1022  4368 D FocusedStackFrame: Set to : 0
08-22 11:14:51.885   338  6738 D QC-time-services: Updating the TOD offset
08-22 11:14:51.885   338  6738 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249826840 to memory
08-22 11:14:51.885   338  6738 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-22 11:14:51.885   338  6738 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-22 11:14:51.895  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.895  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.895  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.895  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:51.895   338  6738 E QC-time-services: Daemon:Update to modem bit set
08-22 11:14:51.895  6720  6720 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-22 11:14:51.895   338  6738 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-22 11:14:51.895   338  6738 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285026840
08-22 11:14:51.895  1022  1052 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-22 11:14:51.895  1022  1052 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-22 11:14:51.905   338   427 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-22 11:14:51.905   338   430 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-22 11:14:51.905  1022  4368 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6740 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-22 11:14:51.905  1022  4368 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-22 11:14:51.905  1022  4368 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 11:14:51.905  1022  4368 D InputDispatcher: Focused application set to: xxxx
08-22 11:14:51.905  1022  4368 D InputDispatcher: Focus left window: 1494
08-22 11:14:51.905  6740  6740 E Zygote  : MountEmulatedStorage()
08-22 11:14:51.905  6740  6740 I libpersona: KNOX_SDCARD checking this for 10170
08-22 11:14:51.905  6740  6740 E Zygote  : v2
08-22 11:14:51.905  6740  6740 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:51.905  6652  6652 D AndroidRuntime: Shutting down VM
08-22 11:14:51.915  6740  6740 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:51.915  1022  1141 I ActivityManager: Killing 6002:com.google.android.gm/u0a99 (adj 15): empty #21
08-22 11:14:51.915  1022  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-22 11:14:51.915  1022  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-22 11:14:51.915  6740  6740 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:51.915   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-22 11:14:51.915  6740  6740 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-22 11:14:51.925  2635  2635 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
08-22 11:14:51.925  2635  2635 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-22 11:14:51.925  2635  2635 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
08-22 11:14:51.935  2635  2635 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
08-22 11:14:51.935  6740  6740 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:51.935  2635  2635 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
08-22 11:14:51.945  6740  6740 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:51.945  1022  4368 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-22 11:14:51.945  2635  2635 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
08-22 11:14:51.945  2635  2635 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-22 11:14:51.945  2635  2635 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
08-22 11:14:51.945  1022  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 11:14:51.945  1022  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 11:14:51.945  2635  2635 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-22 11:14:51.945  2635  2635 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-22 11:14:51.945  2635  2635 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
08-22 11:14:51.945  1022  1022 V ActivityManager: Display changed displayId=0
08-22 11:14:51.945  2635  2635 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
08-22 11:14:51.955  2635  2635 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
08-22 11:14:51.955  1022  1052 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-22 11:14:51.955  1022  1052 W DisplayManagerService: Failed to notify process 6002 that displays changed, assuming it died.
08-22 11:14:51.955  1022  1052 W DisplayManagerService: android.os.TransactionTooLargeException
08-22 11:14:51.955  1022  1052 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-22 11:14:51.955  1022  1052 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-22 11:14:51.955  1022  1052 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
08-22 11:14:51.955  1022  1052 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
08-22 11:14:51.955  1022  1052 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
08-22 11:14:51.955  1022  1052 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
08-22 11:14:51.955  1022  1052 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
08-22 11:14:51.955  1022  1052 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:14:51.955  1022  1052 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:14:51.955  1022  1052 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 11:14:51.955  1022  1052 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-22 11:14:51.955  2635  2635 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
08-22 11:14:51.955  1022  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-22 11:14:51.955  2635  2635 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-22 11:14:51.955  2635  2635 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
08-22 11:14:51.955  2635  2635 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
08-22 11:14:51.965  2635  2635 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
08-22 11:14:51.965  1022  4368 D PersonaManager: isKioskContainerExistOnDevice
08-22 11:14:51.985  1022  1022 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-22 11:14:51.995  2635  2635 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
08-22 11:14:51.995  2635  2635 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
08-22 11:14:51.995   258  6371 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-22 11:14:52.005   258   453 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-22 11:14:52.005  1494  1494 V ActivityThread: updateVisibility : ActivityRecord{45834e8 token=android.os.BinderProxy@36f69d86 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-22 11:14:52.005  1494  1494 D Launcher: onTrimMemory. Level: 20
08-22 11:14:52.025  1439  1439 I HomeSyncInstallReceiver: This pkg do not need BT addr. Do nothing
08-22 11:14:52.025  1022  4367 I splitIntent: Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 2 receivers.size=42
08-22 11:14:52.025  1022  4367 I splitIntent: finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
08-22 11:14:52.035  1022  1047 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
08-22 11:14:52.035  2816  2816 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
08-22 11:14:52.035  2816  2816 I AASAservice-TokenRule: parseToken()
08-22 11:14:52.035  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.035  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.035  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.035  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.035  2816  2816 W System.err: java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
08-22 11:14:52.035  2816  2816 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-22 11:14:52.035  2816  2816 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 11:14:52.035  2816  2816 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
08-22 11:14:52.035  2816  2816 W System.err: 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:86)
08-22 11:14:52.035  2816  2816 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:55)
08-22 11:14:52.035  2816  2816 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-22 11:14:52.035  2816  2816 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-22 11:14:52.035  2816  2816 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-22 11:14:52.035  2816  2816 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:14:52.035  2816  2816 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:14:52.035  2816  2816 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:14:52.035  2816  2816 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:14:52.035  2816  2816 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:14:52.035  2816  2816 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:14:52.035  2816  2816 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:14:52.035  2816  2816 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
08-22 11:14:52.035  2816  2816 W System.err: 	at libcore.io.Posix.open(Native Method)
08-22 11:14:52.035  2816  2816 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 11:14:52.035  2816  2816 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-22 11:14:52.035  2816  2816 W System.err: 	... 14 more
08-22 11:14:52.035  2816  2816 E AASAservice-TokenRule: parseToken() : TokenFile is null
08-22 11:14:52.035  2816  2816 E AASAservice-UpdateReceiver: AASARuleUpdateResult() : Rule file is not exist.
08-22 11:14:52.035  2816  2816 I art     : System.exit called, status: 0
08-22 11:14:52.035  2816  2816 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-22 11:14:52.045  6757  6757 E Zygote  : MountEmulatedStorage()
08-22 11:14:52.045  6757  6757 E Zygote  : v2
08-22 11:14:52.045  6757  6757 I libpersona: KNOX_SDCARD checking this for 10029
08-22 11:14:52.045  6757  6757 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:52.055  6757  6757 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:52.055  1022  1047 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6757 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-22 11:14:52.055  6757  6757 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:52.055  6757  6757 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:14:52.055  1022  1047 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
08-22 11:14:52.055  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.055  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.055  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.055  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.055  1022  1226 I TactileAssist: enable value -1
08-22 11:14:52.055  1022  1226 I TactileAssist: internal enable value -1
08-22 11:14:52.055  1022  1226 I TactileAssist: intensity value -1
08-22 11:14:52.055  1022  1226 I TactileAssist: saveAppList value true
08-22 11:14:52.065  1022  1226 I TactileAssist: List of disabled apps :
08-22 11:14:52.075  6766  6766 E Zygote  : MountEmulatedStorage()
08-22 11:14:52.075  6766  6766 I libpersona: KNOX_SDCARD checking this for 10098
08-22 11:14:52.075  6766  6766 E Zygote  : v2
08-22 11:14:52.075  6766  6766 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:52.075  6766  6766 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:52.075  6766  6766 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:52.075  1022  1047 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6766 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-22 11:14:52.075  6766  6766 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:14:52.085  1022  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
08-22 11:14:52.085  1022  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.085  1022  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.085  1022  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.085  1022  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.085  6757  6757 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:52.085  6757  6757 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:52.095  6781  6781 E Zygote  : MountEmulatedStorage()
08-22 11:14:52.095  6781  6781 E Zygote  : v2
08-22 11:14:52.095  1022  1491 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6781 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
08-22 11:14:52.105  6781  6781 I libpersona: KNOX_SDCARD checking this for 10048
08-22 11:14:52.105  6781  6781 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:52.105  6781  6781 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:52.105  6781  6781 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:52.105  6781  6781 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-22 11:14:52.115  6766  6766 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:52.115  6766  6766 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:52.125  6652  6652 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-22 11:14:52.125  1022  1141 I ActivityManager: Process com.samsung.aasaservice (pid 2816)(adj 0) has died(80,725)
08-22 11:14:52.125  2784  2784 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(79/onServiceDisconnected)] AASA: onServiceDisconnected
08-22 11:14:52.125  1022  1141 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-22 11:14:52.145  1022  4369 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
08-22 11:14:52.145  6781  6781 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:52.145  6781  6781 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:52.155  6757  6802 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
08-22 11:14:52.155  6766  6766 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
08-22 11:14:52.155  6766  6766 D PackageIntentReceiver: Not GearManger package! 
08-22 11:14:52.155  1022  4370 I ActivityManager: Killing 6383:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
08-22 11:14:52.165  6740  6740 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-22 11:14:52.165  1022  1034 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:14:52.165  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
08-22 11:14:52.165  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:52.165  2784  2784 I DBG_POLICYDM: [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
08-22 11:14:52.165  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:52.175  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 11:14:52.175  1022  1141 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
08-22 11:14:52.175  3823  6804 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
08-22 11:14:52.175  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.175  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.175  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.175  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.185  6757  6802 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-22 11:14:52.185  6757  6802 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:14:52.185  6757  6802 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:52.185  6757  6802 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-22 11:14:52.185  6757  6802 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-22 11:14:52.195  6805  6805 E Zygote  : MountEmulatedStorage()
08-22 11:14:52.195  6757  6802 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-22 11:14:52.195  6805  6805 E Zygote  : v2
08-22 11:14:52.195  6757  6802 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-22 11:14:52.195  6757  6802 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 11:14:52.195  6781  6781 D Compatibility: onReceive() it will make start service
08-22 11:14:52.195  6757  6802 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:14:52.195  6757  6802 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:52.195  6757  6802 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-22 11:14:52.195  6805  6805 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:14:52.195  6805  6805 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:52.195  6805  6805 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:52.195  1022  1141 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6805 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 11:14:52.195  1022  1141 I ActivityManager: Killing 5083:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-22 11:14:52.195  6805  6805 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:52.195  1022  1223 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-22 11:14:52.195  1022  1223 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
08-22 11:14:52.195  1022  1223 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:52.195  1022  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:52.195  1022  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
08-22 11:14:52.205  6805  6805 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:14:52.205  1022  1329 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:14:52.205  1022  1329 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
08-22 11:14:52.205  1022  1329 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:52.205  1022  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:52.205  1022  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 11:14:52.205  1022  1141 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-22 11:14:52.205  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.205  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.205  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.205  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.215  6757  6802 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 11:14:52.215  6757  6802 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:14:52.215  6757  6802 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:52.215  6781  6815 D Compatibility: onHandleIntent()
08-22 11:14:52.215  6781  6815 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10170, android.intent.extra.user_handle=0}]
08-22 11:14:52.225  6818  6818 E Zygote  : MountEmulatedStorage()
08-22 11:14:52.225  6818  6818 I libpersona: KNOX_SDCARD checking this for 10032
08-22 11:14:52.225  6818  6818 E Zygote  : v2
08-22 11:14:52.225  6818  6818 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:52.225  6757  6802 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-22 11:14:52.225  6757  6802 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:52.225  6757  6802 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-22 11:14:52.225  6818  6818 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:52.225  6781  6815 D Compatibility: found: 2
08-22 11:14:52.225  1022  1141 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=6818 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 11:14:52.225  6805  6805 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:52.225  6818  6818 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:52.225  6805  6805 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:52.225  6818  6818 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-22 11:14:52.235  1022  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:14:52.235  1022  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
08-22 11:14:52.235  1022  1486 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:52.235  1022  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:52.235  1022  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 11:14:52.235  3823  3823 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-22 11:14:52.235  3823  3823 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
08-22 11:14:52.245  6757  6802 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 11:14:52.245  6757  6802 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:14:52.245  6757  6802 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:52.245  6757  6802 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-22 11:14:52.245  6757  6802 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-22 11:14:52.245  6757  6802 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 11:14:52.245  6740  6740 I cr.library_loader: Time to load native libraries: 23 ms (timestamps 4778-4801)
08-22 11:14:52.245  6757  6802 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-22 11:14:52.245  6740  6740 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-22 11:14:52.245  1022  4370 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
08-22 11:14:52.245  1022  4370 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.245  1022  4370 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.245  1022  4370 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.245  1022  4370 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.255  6757  6802 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:52.255  6757  6802 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 11:14:52.255  6757  6802 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-22 11:14:52.265  6781  6815 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-22 11:14:52.265  6781  6815 D Compatibility: skipping ResolveInfo{38e79617 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-22 11:14:52.265  6781  6815 D Compatibility: considering ResolveInfo{37201a04 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-22 11:14:52.265  6781  6815 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
08-22 11:14:52.265  6781  6815 D Compatibility: enabling receiver ResolveInfo{23b07bed com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-22 11:14:52.265  6757  6802 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-22 11:14:52.265  6757  6802 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 11:14:52.265  6757  6802 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:52.265  6757  6802 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 11:14:52.275  6840  6840 E Zygote  : MountEmulatedStorage()
08-22 11:14:52.275  6840  6840 I libpersona: KNOX_SDCARD checking this for 10052
08-22 11:14:52.275  6840  6840 E Zygote  : v2
08-22 11:14:52.275  6840  6840 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:52.275  6818  6818 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:52.275  6818  6818 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:52.275  6781  6815 D Compatibility: enabling receiver ResolveInfo{3e352a22 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-22 11:14:52.275  1022  4370 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6840 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-22 11:14:52.285  1022  1226 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:14:52.285  1022  1226 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
08-22 11:14:52.285  1022  1226 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:52.285  6757  6802 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-22 11:14:52.285  6781  6815 D Compatibility: enabling receiver ResolveInfo{27c57cb3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-22 11:14:52.285  6757  6802 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:52.285  1022  1226 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:52.285  6757  6802 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 11:14:52.285  1022  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 11:14:52.285  6757  6802 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-22 11:14:52.285  6781  6815 D Compatibility: enabling receiver ResolveInfo{86d270 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-22 11:14:52.295  6840  6840 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:52.295  1022  1035 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.wearable.service.WearableControlService in 10833ms
08-22 11:14:52.295  6840  6840 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:52.295  6840  6840 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-22 11:14:52.295  1022  4369 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:52.295  1022  4369 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:14:52.295  1022  4369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:52.295  1022  4369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-22 11:14:52.295  1022  4369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 11:14:52.305  6781  6815 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
08-22 11:14:52.305  6740  6740 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {25e9e9}
08-22 11:14:52.305  6740  6740 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-22 11:14:52.315  1022  4369 I ActivityManager: Killing 6255:com.google.android.music:main/u0a108 (adj 15): empty #21
08-22 11:14:52.315  6757  6802 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-22 11:14:52.315  6757  6802 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:14:52.315  6757  6802 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:52.315  6757  6802 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-22 11:14:52.325  1022  4368 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
08-22 11:14:52.325  6840  6840 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:52.325  6840  6840 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:52.325  6740  6740 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-22 11:14:52.325  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.325  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.325  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.325  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.335  6757  6802 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-22 11:14:52.345  6855  6855 E Zygote  : MountEmulatedStorage()
08-22 11:14:52.345  6855  6855 E Zygote  : v2
08-22 11:14:52.345  6855  6855 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:14:52.345  6855  6855 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:52.345  6855  6855 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:52.345  6855  6855 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:52.345  1022  4368 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6855 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 11:14:52.345  1022  4368 I ActivityManager: Killing 6074:com.google.android.talk/u0a102 (adj 15): empty #21
08-22 11:14:52.345  6855  6855 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:14:52.365  6757  6802 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-22 11:14:52.365  6757  6802 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
08-22 11:14:52.365  6757  6802 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 11:14:52.365  6757  6802 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:52.365  6757  6802 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 11:14:52.375  6740  6740 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-22 11:14:52.385  6740  6740 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 11:14:52.385  6855  6855 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:52.385  6757  6802 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-22 11:14:52.385  6818  6866 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-22 11:14:52.385  6757  6802 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:52.385  6818  6866 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
08-22 11:14:52.385  6855  6855 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:52.395  6818  6866 D SPPClientService: PushLog.txt file is not deleted.
08-22 11:14:52.395  6818  6866 D SPPClientService: PushLog.txt file is not deleted.
08-22 11:14:52.395  6818  6866 D SPPClientService: ============PushLog. stop!
08-22 11:14:52.395  6757  6802 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
08-22 11:14:52.405   291   291 E SMD     : DCD OFF
08-22 11:14:52.415  1022  1223 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
08-22 11:14:52.415  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.415  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.415  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.415  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.425  6855  6873 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
08-22 11:14:52.425  6740  6740 E SysUtils: ApplicationContext is null in ApplicationStatus
08-22 11:14:52.425  6855  6873 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
08-22 11:14:52.435  6874  6874 E Zygote  : MountEmulatedStorage()
08-22 11:14:52.435  6874  6874 I libpersona: KNOX_SDCARD checking this for 10117
08-22 11:14:52.435  6874  6874 E Zygote  : v2
08-22 11:14:52.435  6874  6874 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:52.435  6874  6874 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:52.435  6874  6874 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:52.435  6874  6874 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-22 11:14:52.455   314   314 I art     : Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 20.014ms
08-22 11:14:52.455  1022  1223 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6874 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-22 11:14:52.455  1022  1223 I ActivityManager: Killing 6088:com.android.vending/u0a26 (adj 15): empty #21
08-22 11:14:52.465  6874  6874 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:52.475  6874  6874 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:52.475  1022  1047 W ActivityManager: Activity pause timeout for ActivityRecord{3ec4517d u0 com.test.thalitest/.MainActivity t163}
08-22 11:14:52.475  1022  1223 I ActivityManager: Killing 6457:com.android.defcontainer/u0a3 (adj 15): empty #21
08-22 11:14:52.475  1022  1034 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-22 11:14:52.475  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:52.475  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
08-22 11:14:52.475  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:52.475  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
08-22 11:14:52.475   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 17.477ms
08-22 11:14:52.485  6855  6855 D AcmsService: Enter Oncreate
08-22 11:14:52.495   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 16.954ms
08-22 11:14:52.505  6855  6855 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 11:14:52.505  6855  6855 D AcmsService: creating AcmsCore
08-22 11:14:52.505  6855  6855 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-22 11:14:52.505  6855  6855 D AcmsCore: AcmsCore
08-22 11:14:52.505  6855  6855 D AcmsCore: init
08-22 11:14:52.505  6855  6855 D AcmsCore: Looper handler is not null
08-22 11:14:52.505  6855  6855 D AcmsCore: Post to AcmsCoreHandler
08-22 11:14:52.505  6855  6855 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 11:14:52.505  6855  6855 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-22 11:14:52.505  6855  6855 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
08-22 11:14:52.505  6855  6855 D AcmsService: onStartCommand
08-22 11:14:52.505  6855  6855 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
08-22 11:14:52.505  6855  6855 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-22 11:14:52.505  6855  6855 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-22 11:14:52.505  6855  6855 D AcmsService: Incremented Counter Value : onStartCommand
08-22 11:14:52.505  1022  1226 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
08-22 11:14:52.515  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.515  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.515  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.515  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.515  6855  6889 D AcmsCertificateMngr: AcmsCertificateMngr
08-22 11:14:52.515  6740  6740 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-22 11:14:52.515  6740  6740 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 11:14:52.515  6740  6740 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 11:14:52.515  6740  6740 I Adreno-EGL: Local Branch: 
08-22 11:14:52.515  6740  6740 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 11:14:52.515  6740  6740 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 11:14:52.515  6740  6740 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-22 11:14:52.535  6874  6874 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:14:52.535  6894  6894 E Zygote  : MountEmulatedStorage()
08-22 11:14:52.535  6894  6894 E Zygote  : v2
08-22 11:14:52.535  6894  6894 I libpersona: KNOX_SDCARD checking this for 10039
08-22 11:14:52.535  6894  6894 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:52.535  1022  1226 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6894 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-22 11:14:52.535  6894  6894 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:52.535  1022  1491 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-22 11:14:52.545  6855  6855 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
08-22 11:14:52.545  6894  6894 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:52.545  6894  6894 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:14:52.555  6855  6889 D AcmsRevocationMngr: AcmsRevocationMngr
08-22 11:14:52.585  6894  6894 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:52.585  6894  6894 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:52.595  1022  4371 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-22 11:14:52.595  1022  4371 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-22 11:14:52.595  1022  4371 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:52.595  1022  4371 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:52.595  1022  4371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-22 11:14:52.605  1022  1141 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-22 11:14:52.605  1022  1141 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-22 11:14:52.605  1022  1141 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:52.605  1022  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:52.605  1022  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-22 11:14:52.615  6855  6855 D AcmsService: Inside handle Intent
08-22 11:14:52.615  6855  6855 D AcmsService: App added - package name: com.test.thalitest
08-22 11:14:52.615  6855  6855 D AcmsCore: Post to AcmsCoreHandler
08-22 11:14:52.615  6855  6855 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 11:14:52.615  6855  6855 D AcmsServiceMonitor: Incrementing - Counter value: 3
08-22 11:14:52.615  6855  6855 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
08-22 11:14:52.615  6855  6855 D AcmsService: Decremented Counter Value : handleStartIntent
08-22 11:14:52.615  6855  6855 D AcmsServiceMonitor: Decrementing - Counter value: 2
08-22 11:14:52.615  6894  6894 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 11:14:52.615  6894  6894 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:14:52.615  6894  6894 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:52.615  6894  6894 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-22 11:14:52.615  6894  6894 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-22 11:14:52.615  6894  6894 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 11:14:52.615  6894  6894 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-22 11:14:52.615  1022  4367 I art     : Explicit concurrent mark sweep GC freed 140886(7MB) AllocSpace objects, 2(1824KB) LOS objects, 33% free, 22MB/34MB, paused 4.313ms total 217.440ms
08-22 11:14:52.665  1022  1035 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
08-22 11:14:52.685  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.685  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.685  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.685  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:52.695  1022  1035 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6922 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 11:14:52.705  6922  6922 E Zygote  : MountEmulatedStorage()
08-22 11:14:52.705  6922  6922 E Zygote  : v2
08-22 11:14:52.705  6922  6922 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:14:52.705  6922  6922 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:52.705  6922  6922 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:52.705  6922  6922 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:52.705  6922  6922 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:14:52.735  6740  6740 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-22 11:14:52.765  6922  6922 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:52.765  6922  6922 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:52.765  6740  6740 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-22 11:14:52.765  6740  6740 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-22 11:14:52.775  6664  6664 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
08-22 11:14:52.785  6740  6740 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-22 11:14:52.785  6740  6740 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-22 11:14:52.785  1022  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
08-22 11:14:52.795  1022  1486 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:52.795  1022  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:52.795  1022  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-22 11:14:52.845  1022  1329 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:14:52.855  1022  1329 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:52.855  1022  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 11:14:52.855  1022  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:14:52.855  3823  3823 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-22 11:14:52.865  1022  1486 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-22 11:14:52.865  1022  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,08-22 11:14:52.865  6922  6922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,08-22 11:14:52.875  1022  1486 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:52.875  1022  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:52.875  1022  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-22 11:14:52.875  1022  1226 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-22 11:14:52.875  1022  1226 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-22 11:14:52.885  1022  1226 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:52.885  1022  1226 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:14:52.885  1022  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-22 11:14:52.885  3823  3823 I ConfigFetchService: launchTask
,08-22 11:14:52.895  1022  1034 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-22 11:14:52.895  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:52.895  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:52.895  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:52.895  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:52.895  6545  6545 I Mms/MmsApp:  start initViewCache mms
,08-22 11:14:52.895  6545  6545 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1934.284218
08-22 11:14:52.905  6545  6545 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-22 11:14:52.915  6949  6949 E Zygote  : MountEmulatedStorage(),
08-22 11:14:52.915  1022  1034 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6949 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
08-22 11:14:52.915  6949  6949 E Zygote  : v2
08-22 11:14:52.915  6949  6949 I libpersona: KNOX_SDCARD checking this for 10087
08-22 11:14:52.915  6949  6949 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:52.915  6949  6949 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:14:52.915  6949  6949 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:14:52.915  6949  6949 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-22 11:14:52.935  1022  4371 I ActivityManager: Killing 6503:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-22 11:14:52.945  6949  6949 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:52.945  6949  6949 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:52.965  1022  1034 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 11:14:52.965  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-22 11:14:52.965  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:52.965  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:52.965  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:14:52.975  3823  3823 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-22 11:14:52.975  3823  3823 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-22 11:14:52.975  6740  6740 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 11:14:52.975  1022  1226 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-22 11:14:52.985  1022  1226 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:52.985  1022  1226 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:52.985  1022  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:14:53.005  6894  6894 D NearbySource: Nearby Source Create!
,08-22 11:14:53.005  6894  6894 D NearbyContext: Nearby Context Create!
,08-22 11:14:53.015  3823  3823 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
,08-22 11:14:53.025  3823  6943 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XMW_ZbNRfm4d4CVMYXJD9vET-qIBARGJ_8dsGVX82kCisGrLrgDhnlePbEzKHfC-Bm_zs3Jiv32CrbFDkHKLh9sRWMSCml9Pcwj9s91zrKw3DA0vXg5ss4EZDPeO_vu5w6pD5cuFN8b6yYi6aef1Sw8vD2dP2FN1jzo39sv2QJhLXxJLVUaoL480yali9Ux2UnfqJoT5MHk6ohNSBeGjWD-Jicj7JO_qG_NfCtp9qM9f7NxCY
,08-22 11:14:53.035  3823  6943 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-22 11:14:53.075   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-22 11:14:53.075   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:14:53.075  6894  6894 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-22 11:14:53.085  6894  6894 D SLinkSource: Samsung link source created
,08-22 11:14:53.095  1022  1035 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-22 11:14:53.095  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-22 11:14:53.095  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:53.095  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:53.095  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:14:53.105  1022  4369 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-22 11:14:53.105  1022  1226 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-22 11:14:53.105  1022  1226 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,08-22 11:14:53.105  1022  1226 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:53.105  1022  1226 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:53.105  1022  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,08-22 11:14:53.115  6740  6740 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-22 11:14:53.125  1022  4369 D LocationManagerService: getProviders()=[passive, gps]
,08-22 11:14:53.125  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.125  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.125  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.125  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:53.135  6980  6980 E Zygote  : MountEmulatedStorage()
08-22 11:14:53.135  6980  6980 E Zygote  : v2
08-22 11:14:53.135  6980  6980 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:14:53.135  6980  6980 I libpersona: KNOX_SDCARD not a persona
,08-22 11:14:53.145  6980  6980 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:14:53.145  6980  6980 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:53.145  1022  1047 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=6980 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 11:14:53.145  6980  6980 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:14:53.145  6740  6740 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-22 11:14:53.145  6740  6740 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-22 11:14:53.165  1022  1492 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,08-22 11:14:53.165  1022  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,08-22 11:14:53.165  6545  6545 D AbsListView: Get MotionRecognitionManager
,08-22 11:14:53.165  1022  4371 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-22 11:14:53.165  1022  1034 D MotionRecognitionService:  ssp status : false
,08-22 11:14:53.175  6740  6740 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-22 11:14:53.175  1022  1492 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:53.175  1022  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:53.175  1022  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
08-22 11:14:53.175  6980  6980 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:53.175  6980  6980 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:53.175  3823  6944 I PeopleContactsSync: CP2 sync disabled
,08-22 11:14:53.185  6545  6545 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 284.624427
,08-22 11:14:53.195  6740  6740 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 11:14:53.195  6740  6740 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 11:14:53.215  1022  1034 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,08-22 11:14:53.225  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:53.225  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.225  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:53.235  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:53.245  7002  7002 E Zygote  : MountEmulatedStorage(),
08-22 11:14:53.245  7002  7002 E Zygote  : v2,
08-22 11:14:53.255  7002  7002 I libpersona: KNOX_SDCARD checking this for 10014
08-22 11:14:53.255  7002  7002 I libpersona: KNOX_SDCARD not a persona
,08-22 11:14:53.255  7002  7002 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:14:53.255  7002  7002 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:14:53.255  1022  1034 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7002 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,08-22 11:14:53.255  7002  7002 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 11:14:53.265  1022  1223 D ActivityManager: startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
,08-22 11:14:53.265  6894  6997 D ContactProvider: getAllContactInfoList Start
,08-22 11:14:53.275  1022  1492 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 11:14:53.275  7002  7002 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:53.275  7002  7002 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:53.305  6980  6980 D AASAservice: onCreate()
,08-22 11:14:53.315  6980  6980 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
,08-22 11:14:53.315  2784  2784 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
,08-22 11:14:53.325  1022  1329 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-22 11:14:53.335  1022  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.335  1022  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.335  1022  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.335  1022  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:53.345  1022  4370 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 11:14:53.345  6545  6545 D Mms/BubbleViewCache: fillCache bubble = 1
,08-22 11:14:53.345  1022  4370 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4191, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-22 11:14:53.345  1022  4370 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-22 11:14:53.345  1022  4370 D BatteryService: stay LED for charging
08-22 11:14:53.345  1022  1022 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 11:14:53.355  1022  4368 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 11:14:53.355  7021  7021 E Zygote  : MountEmulatedStorage()
08-22 11:14:53.355  7021  7021 I libpersona: KNOX_SDCARD checking this for 10148
08-22 11:14:53.355  7021  7021 E Zygote  : v2
08-22 11:14:53.355  7021  7021 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:53.355  7021  7021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:53.355  1022  1329 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7021 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-22 11:14:53.355  7021  7021 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:14:53.355  7021  7021 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:14:53.365  6894  6894 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-22 11:14:53.365  1022  1329 I ActivityManager: Killing 6526:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-22 11:14:53.365  1022  1022 I MotionRecognitionService: Plugged
08-22 11:14:53.365  1022  1022 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 11:14:53.375  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-22 11:14:53.375  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 11:14:53.375  1184  1184 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 11:14:53.375  1184  1184 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 11:14:53.375  6840  6911 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-22 11:14:53.385  7021  7021 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:53.385  7021  7021 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:53.385  3222  3222 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-22 11:14:53.385  3222  3360 D HeadsetStateMachine: Disconnected process message: 10
,08-22 11:14:53.395  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-22 11:14:53.395  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-22 11:14:53.395  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 11:14:53.425  6894  6997 D ContactProvider: getAllContactInfoList End
,08-22 11:14:53.425  6894  6997 I syncContacts: thread: 1278, sync time = 229
,08-22 11:14:53.445  7021  7021 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-22 11:14:53.455  1022  1223 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,08-22 11:14:53.455  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:53.455  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.455  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.455  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:53.475  6740  7039 D OpenGLRenderer: Render dirty regions requested: true
,08-22 11:14:53.475  7040  7040 E Zygote  : MountEmulatedStorage()
08-22 11:14:53.475  7040  7040 E Zygote  : v2
08-22 11:14:53.475  7040  7040 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:14:53.475  7040  7040 I libpersona: KNOX_SDCARD not a persona
,08-22 11:14:53.475  1022  1223 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7040 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 11:14:53.475  1022  1223 I ActivityManager: Killing 6545:com.android.mms/u0a41 (adj 15): empty #21
,08-22 11:14:53.475  1022  4368 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,08-22 11:14:53.485  1022  4368 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,08-22 11:14:53.485  1022  4368 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:53.485  1022  4368 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 11:14:53.485  1022  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,08-22 11:14:53.485  1022  1226 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-22 11:14:53.485  1022  1226 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-22 11:14:53.485  1022  1226 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-22 11:14:53.495  1022  1022 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-22 11:14:53.495  1022  1022 D PersonaManagerService: getPersonasForUser(): returning null!
,08-22 11:14:53.495  6740  6740 V ActivityThread: updateVisibility : ActivityRecord{10ac48d0 token=android.os.BinderProxy@2c5c6182 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-22 11:14:53.495  6740  6917 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-22 11:14:53.505  6740  6740 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-22 11:14:53.505  6740  6740 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-22 11:14:53.525  1022  4367 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,08-22 11:14:53.525  1022  4367 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,08-22 11:14:53.525   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-22 11:14:53.525  1022  4367 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:53.525  1022  4367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:53.525  1022  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,08-22 11:14:53.535  1022  4368 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-22 11:14:53.535  1022  1329 D InputDispatcher: Focus entered window: 6740
,08-22 11:14:53.545  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.545  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.545  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.545  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:53.545  1022  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-22 11:14:53.545  1022  1052 D PointerIcon: setMouseCustomIcon IconType is same.101,
,08-22 11:14:53.545  6740  6740 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
08-22 11:14:53.545  6740  7039 I OpenGLRenderer: Initialized EGL, version 1.4,
,08-22 11:14:53.565  7050  7050 E Zygote  : MountEmulatedStorage()
08-22 11:14:53.565  7050  7050 E Zygote  : v2
08-22 11:14:53.565  7050  7050 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:14:53.565  7050  7050 I libpersona: KNOX_SDCARD not a persona
,08-22 11:14:53.565  1022  4368 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7050 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 11:14:53.565  6740  7039 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-22 11:14:53.565  6740  7039 D OpenGLRenderer: Enabling debug mode 0
,08-22 11:14:53.585  1022  4370 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-22 11:14:53.585  1022  7058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-22 11:14:53.585  1184  1184 D PanelView: There is/are notification(s) 
,08-22 11:14:53.605  1022  1052 I ActivityManager: Displayed Component not be shown by security: +1s635ms (total +1s715ms)
08-22 11:14:53.605  1022  1052 W ActivityManager: mDVFSHelper.release()
08-22 11:14:53.605  1022  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3ec4517d u0 com.test.thalitest/.MainActivity t163} time:96165
,08-22 11:14:53.615  1022  1035 I ActivityManager: Killing 6576:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-22 11:14:53.625  1022  1141 D CountryDetector: No listener is left
,08-22 11:14:53.625  6740  6740 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-22 11:14:53.625   258  6371 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-22 11:14:53.625  6740  6740 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2c5c6182 time:96186
,08-22 11:14:53.625   258  1062 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-22 11:14:53.665  3823  6971 W BaseAppContext: Using Auth Proxy for data requests.
,08-22 11:14:53.665  3823  6971 W BaseAppContext: Using Auth Proxy for data requests.
,08-22 11:14:53.675  7040  7040 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:14:53.675  7050  7050 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:14:53.675  7040  7040 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:14:53.675  7040  7040 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:14:53.675  7050  7050 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:14:53.675  7050  7050 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:14:53.705  7050  7050 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:53.705  7050  7050 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:53.705  7040  7040 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:53.705  7040  7040 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:53.715  3823  6943 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-22 11:14:53.735  3823  6943 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 11:14:53.735  7040  7040 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,08-22 11:14:53.745  3823  6943 I System.out: (HTTPLog)-Static: isShipBuild true
,08-22 11:14:53.745  3823  6943 I System.out: (HTTPLog)-Thread-643-625306162: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-22 11:14:53.745  3823  6943 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 11:14:53.755  1022  4367 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,08-22 11:14:53.755  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:53.755  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:53.755  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:53.755  7050  7050 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-22 11:14:53.755  7050  7050 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-22 11:14:53.755  7050  7050 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-22 11:14:53.755  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:53.765   278   975 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-22 11:14:53.765   278   975 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-22 11:14:53.775  7087  7087 E Zygote  : MountEmulatedStorage(),
08-22 11:14:53.775  7087  7087 E Zygote  : v2
,08-22 11:14:53.775  7087  7087 I libpersona: KNOX_SDCARD checking this for 10041
08-22 11:14:53.775  7087  7087 I libpersona: KNOX_SDCARD not a persona,
,08-22 11:14:53.775  7087  7087 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:14:53.775  1022  1047 W ProcessCpuTracker: Skipping unknown process pid 6576,
,08-22 11:14:53.785  1884  1884 I SamsungIME: getCurrentCandidateView
,08-22 11:14:53.785  7087  7087 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-22 11:14:53.785  7087  7087 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-22 11:14:53.785  1022  4367 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=7087 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,08-22 11:14:53.795  1022  4369 I ActivityManager: Killing 6592:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-22 11:14:53.795  6740  6740 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6740
,08-22 11:14:53.805  7087  7087 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:53.805  7087  7087 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:53.815  1022  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:14:53.815  1022  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:53.825  1022  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:53.825  1022  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,08-22 11:14:53.825  7050  7050 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-22 11:14:53.825  7050  7050 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-22 11:14:53.825  7050  7050 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-22 11:14:53.825  7050  7050 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
,08-22 11:14:53.825  1022  4368 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:53.825  1022  4368 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:14:53.825  1022  4368 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:53.825  1022  4368 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-22 11:14:53.825  1022  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 11:14:53.825  7087  7087 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-22 11:14:53.835  3823  6943 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-22 11:14:53.835  3823  6943 I qtaguid : Tagging socket 99 with tag 1000040b00000000{268436491,0} for uid -1, pid: 3823, getuid(): 10011
,08-22 11:14:53.835  1022  4370 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-22 11:14:53.835  1022  4370 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:53.835  1022  4370 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:53.835  1022  4370 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:14:53.845  1022  1035 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,08-22 11:14:53.845  7087  7087 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 11:14:53.845  7087  7087 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:53.845  7087  7087 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-22 11:14:53.845  7087  7087 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-22 11:14:53.845  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.845  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.845  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.845  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:53.875  7103  7103 E Zygote  : MountEmulatedStorage()
08-22 11:14:53.875  7103  7103 I libpersona: KNOX_SDCARD checking this for 10026
08-22 11:14:53.875  7103  7103 E Zygote  : v2
08-22 11:14:53.875  7103  7103 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:53.885  7103  7103 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:14:53.885  7103  7103 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:14:53.885  1022  1035 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7103 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 11:14:53.885  7103  7103 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 11:14:53.885  1022  1035 I ActivityManager: Killing 6609:com.wsomacp/u0a23 (adj 15): empty #21
,08-22 11:14:53.895  1022  4371 I ActivityManager: Killing 6618:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-22 11:14:53.895  1022  1035 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-22 11:14:53.895  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.895  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.895  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.895  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:53.905  3823  6971 W BaseAppContext: Using Auth Proxy for data requests.
,08-22 11:14:53.905  7103  7103 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:53.905  7103  7103 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:53.925  3823  6943 I qtaguid : Tagging socket 103 with tag 1000040b00000000{268436491,0} for uid -1, pid: 3823, getuid(): 10011
,08-22 11:14:53.925  7087  7087 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-22 11:14:53.935  7120  7120 E Zygote  : MountEmulatedStorage(),
,08-22 11:14:53.935  7120  7120 E Zygote  : v2
,08-22 11:14:53.945  7120  7120 I libpersona: KNOX_SDCARD checking this for 10152
08-22 11:14:53.945  7120  7120 I libpersona: KNOX_SDCARD not a persona,
,08-22 11:14:53.945  7120  7120 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:14:53.945  1022  1035 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7120 uid=10152 gids={50152, 9997} abi=armeabi-v7a,
,08-22 11:14:53.945  7120  7120 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-22 11:14:53.955  1022  1034 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:14:53.955  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-22 11:14:53.955  7120  7120 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-22 11:14:53.965  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:53.965  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:53.965  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:14:53.965   314   314 I art     : Explicit concurrent mark sweep GC freed 8711(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 836us total 23.660ms
,08-22 11:14:53.985  7120  7120 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:53.985   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.037ms total 19.535ms
08-22 11:14:53.985  7120  7120 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:54.005   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 19.698ms
08-22 11:14:54.005  1022  1329 D PowerManagerService: [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10081, pid=6618, ws=null) (elapsedTime=2847)
,08-22 11:14:54.015  1022  1226 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:14:54.015  1022  1226 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:54.015  1022  1226 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:54.015  1022  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:14:54.025  6740  6740 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 11:14:54.075  1022  1490 E EdmStorageProvider: Admin not in database, something went wrong
,08-22 11:14:54.085  2652  2721 I art     : Explicit concurrent mark sweep GC freed 16890(780KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 1.019ms total 46.951ms
,08-22 11:14:54.105  3823  6943 I qtaguid : Untagging socket 99
,08-22 11:14:54.105  1022  1141 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:14:54.105  3823  6971 W BaseAppContext: Using Auth Proxy for data requests.
,08-22 11:14:54.105  1022  1141 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:54.105  1022  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:54.105  1022  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:14:54.105  3823  3823 I ConfigFetchService: fetch service done; releasing wakelock
,08-22 11:14:54.105  7120  7120 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,08-22 11:14:54.115  7120  7120 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,08-22 11:14:54.115  3823  3823 I ConfigFetchService: stopping self
,08-22 11:14:54.115  3823  6971 W BaseAppContext: Using Auth Proxy for data requests.
,08-22 11:14:54.155  3823  3847 W art     : Suspending all threads took: 5.007ms
,08-22 11:14:54.155  7120  7120 I TapandpayWidget:Utils: Clear T&P info.
,08-22 11:14:54.165  3823  6971 W BaseAppContext: Using Auth Proxy for data requests.
,08-22 11:14:54.175  7120  7120 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,08-22 11:14:54.175  1022  4369 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-22 11:14:54.175  1022  4369 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:54.175  1022  4369 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:54.175  1022  4369 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:54.175  1022  4369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:54.195  7138  7138 E Zygote  : MountEmulatedStorage(),
08-22 11:14:54.195  7138  7138 E Zygote  : v2,
08-22 11:14:54.195  1022  4369 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7138 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,08-22 11:14:54.195  7138  7138 I libpersona: KNOX_SDCARD checking this for 10009,
08-22 11:14:54.205  7138  7138 I libpersona: KNOX_SDCARD not a persona,
08-22 11:14:54.205  6840  6911 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 822 ms] updated apps [took 822 ms] ,
,08-22 11:14:54.205  1022  4369 I ActivityManager: Killing 6643:com.sec.esdk.elm/u0a90 (adj 15): empty #21,
,08-22 11:14:54.215  7138  7138 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:14:54.215  7138  7138 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:14:54.215  7138  7138 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-22 11:14:54.225  1884  1884 D SamsungIME: Dismiss ExpandCandiate
,08-22 11:14:54.225  1022  1491 I ActivityManager: Killing 6334:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-22 11:14:54.245  7138  7138 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:54.255  7138  7138 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:54.275  6740  7063 D jxcore_app_log: JniHelper::setJavaVM(0xb7f702b0), pthread_self() = -1202725656
,08-22 11:14:54.285  6740  7063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 11:14:54.285  6740  7063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 11:14:54.285  6740  7063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 11:14:54.285  6740  7063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 11:14:54.285  6740  7063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-22 11:14:54.285  6740  7063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3007c0e7 added. We now have 1 listener(s)
,08-22 11:14:54.295  6740  7063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-22 11:14:54.295  6740  7063 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-22 11:14:54.295  6740  7063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 11:14:54.295  6740  7063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-22 11:14:54.305  6740  7063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ef42f32 added. We now have 1 listener(s)
,08-22 11:14:54.305  6740  7063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:14:54.305  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.315  6740  7063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:14:54.315  6740  7063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-22 11:14:54.315  6740  7063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-22 11:14:54.315  6740  7063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-22 11:14:54.315  6740  7063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-22 11:14:54.325  6740  7063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:14:54.325  6740  7063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-22 11:14:54.335  6740  7063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-22 11:14:54.335  6740  7063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:14:54.335  6740  7063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:14:54.335  6740  7063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:14:54.335  6740  7063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:14:54.335  6740  7063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:14:54.335  6740  7063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:14:54.335  6740  7063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:14:54.335  6740  7063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:14:54.335  6740  7063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-22 11:14:54.335  6740  7063 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:14:54.335  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:14:54.345  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.345  6740  7063 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 11:14:54.345  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:14:54.385  6740  6740 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 11:14:54.385  7087  7087 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 309.117ms
,08-22 11:14:54.395  7103  7103 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-22 11:14:54.425  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.445  1022  1101 V AlarmManager: waitForAlarm result :4
,08-22 11:14:54.455  1022  4369 I ActivityManager: Killing 6353:com.android.calendar/u0a131 (adj 15): empty #21
,08-22 11:14:54.525  1022  4367 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-22 11:14:54.645   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8cb27c8
08-22 11:14:54.645   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,08-22 11:14:54.645   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-22 11:14:54.645   273   326 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1194645368)
,08-22 11:14:54.675  7087  7087 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 290.589ms
,08-22 11:14:54.685  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.685  7087  7169 D Mms/ArtClassLoader: init before art
,08-22 11:14:54.695  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.695   273   326 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-22 11:14:54.695   273   326 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-22 11:14:54.695   273   326 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1194645368) wakelock released: 1, error no: 0
08-22 11:14:54.695   273   326 I rmt_storage: 
,08-22 11:14:54.695   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8cb27c8
,08-22 11:14:54.705  7087  7087 D Mms/TelephonyPermission: start operation mode monitor
,08-22 11:14:54.705  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-22 11:14:54.705  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.715  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.725  7087  7087 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-22 11:14:54.745  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.755  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.755  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.755  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.755  7087  7087 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-22 11:14:54.755  7087  7087 D Mms/TelephonyPermission: isDefault true
,08-22 11:14:54.755  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-22 11:14:54.755  7087  7087 D Mms/MmsApp: onCreate() com.android.mms
,08-22 11:14:54.765  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.765  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.775  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.775  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.775  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.785  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-22 11:14:54.785  7103  7103 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-22 11:14:54.805  1884  1884 I SamsungIME: getDebugLevel  : 0x4f4c
,08-22 11:14:54.815  7103  7103 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-22 11:14:54.815  7103  7103 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-22 11:14:54.885  7087  7087 D Mms/MmsApp: [start]    initCountryIso consume time = 962.753958
,08-22 11:14:54.885  1022  1034 D CountryDetector: The first listener is added
,08-22 11:14:54.895  7087  7087 D Mms/MmsApp: [end]    initCountryIso consume time = 6.116146
,08-22 11:14:54.895  7087  7087 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.608333
,08-22 11:14:54.905  1884  1884 I SamsungIME: getDebugLevel  : 0x4f4c
,08-22 11:14:54.915  7087  7087 D Mms/MmsConfig: before partial update
,08-22 11:14:54.925  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.925  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:54.925  7103  7103 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-22 11:14:54.935  1884  1884 I SamsungIME: KeybaordView init() : load resources
,08-22 11:14:54.945  1022  1486 I art     : Explicit concurrent mark sweep GC freed 21668(1230KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 22MB/34MB, paused 6.935ms total 212.877ms
08-22 11:14:54.945  1022  1032 I art     : WaitForGcToComplete blocked for 109.773ms for cause HeapTrim
,08-22 11:14:54.965  7087  7087 D Mms/MmsConfig: Load Resize quality : 80
,08-22 11:14:54.965  7087  7087 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,08-22 11:14:54.985  7087  7087 D EasySignUpManager_1.0.1: isAuth is false
,08-22 11:14:54.985  7087  7087 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,08-22 11:14:54.995  1022  4367 I ActivityManager: Killing 6679:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-22 11:14:54.995  1455  1474 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7087
,08-22 11:14:55.005  1455  1474 D TP/MmsSmsProvider: match 2117:Elapsed time : 2.900 ms
,08-22 11:14:55.005  7087  7087 D EasySignUpManager_1.0.1: isAuth is false
,08-22 11:14:55.015  7087  7087 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,08-22 11:14:55.015  7087  7087 E CscParser: mps_code.dat does not exist
,08-22 11:14:55.015  7087  7087 E CscParser: customer_path =/system/csc/customer.xml
08-22 11:14:55.015  7087  7087 E CscParser: fileName + /system/csc/customer.xml
,08-22 11:14:55.035  7087  7087 E CscParser: mps_code.dat does not exist
,08-22 11:14:55.035  7087  7087 E CscParser: customer_path =/system/csc/customer.xml
08-22 11:14:55.045  7087  7087 E CscParser: fileName + /system/csc/customer.xml
,08-22 11:14:55.045  7087  7087 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-22 11:14:55.055  7087  7087 D Mms/MmsConfig:  enable multiwindow = false
,08-22 11:14:55.055  1884  1884 I SamsungIME: getCurrentKeyboard
08-22 11:14:55.055  1884  1884 I SamsungIME: getTextKeyboard
,08-22 11:14:55.065  7087  7087 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-22 11:14:55.065  7087  7087 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-22 11:14:55.075  7087  7087 D Mms/MmsConfig: [end]    init() consume time = 182.433385
,08-22 11:14:55.075  7087  7087 D Mms/Contact: [start]    init() consume time = 1.540938
,08-22 11:14:55.095  1884  1884 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-22 11:14:55.145  6949  6998 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-22 11:14:55.145  6949  6998 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-22 11:14:55.145  6949  6998 I GAv4    :   adb logcat -s GAv4
,08-22 11:14:55.145  6740  7157 W jxcore-log: Initializing JXcore engine
,08-22 11:14:55.155  6740  7157 W jxcore-log: JXcore engine is ready
08-22 11:14:55.155  7087  7087 D Mms/Contact: [end]    init consume time = 74.871979
,08-22 11:14:55.155  1455  1474 D TP/MmsSmsProvider: query,matched:13, calling pid = 7087
,08-22 11:14:55.155  1455  1474 D TP/MmsSmsProvider: match 13:Elapsed time : 1.989 ms
,08-22 11:14:55.175  7087  7187 D Mms/DraftCache: [start]    rebuildCache consume time = 20.322188
,08-22 11:14:55.175  1455  1465 D TP/MmsSmsProvider: query,matched:12, calling pid = 7087
,08-22 11:14:55.175  1455  1465 D TP/MmsSmsProvider: match 12:Elapsed time : 2.437 ms
,08-22 11:14:55.175  7087  7087 D Mms/MethodReflector: getSubId is called
,08-22 11:14:55.175  7087  7087 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,08-22 11:14:55.185  7087  7087 D Mms/MethodReflector: getTelephonyProperty is called
,08-22 11:14:55.185  7087  7087 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-22 11:14:55.185  7087  7087 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-22 11:14:55.185  7087  7087 D Mms/DownloadManager: auto download without roaming -> true
08-22 11:14:55.185  7087  7087 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-22 11:14:55.185  7087  7087 D Mms/MethodReflector: getSubId is called
,08-22 11:14:55.185  7087  7187 D Mms/DraftCache: [end]    rebuildCache consume time = 13.240312
,08-22 11:14:55.185  7087  7087 D Mms/MethodReflector: getDefaultSmsSubId is called
,08-22 11:14:55.185  7087  7087 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-22 11:14:55.185  7087  7087 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
,08-22 11:14:55.185  7087  7087 D Mms/MethodReflector: getTelephonyProperty is called
08-22 11:14:55.185  7087  7087 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-22 11:14:55.185  7087  7087 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-22 11:14:55.185  7087  7087 D Mms/DownloadManager: auto download without roaming -> true
08-22 11:14:55.185  7087  7087 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-22 11:14:55.185  7087  7087 D Mms/DownloadManager: auto download during roaming secondary -> false
,08-22 11:14:55.185  7087  7087 D Mms/DownloadManager: mAutoDownload ------> true
,08-22 11:14:55.225  1976  1976 E audit   : type=1400 msg=audit(1471857295.225:205): avc:  denied  { ioctl } for  pid=7157 comm="Thread-1255" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-22 11:14:55.225  1976  1976 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:55.225  1976  1976 E audit   : type=1300 msg=audit(1471857295.225:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9e7008f8 items=0 ppid=314 ppcomm=main pid=7157 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1255" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-22 11:14:55.225  1976  1976 E audit   : type=1320 msg=audit(1471857295.225:205): 
,08-22 11:14:55.235  7087  7087 D ComposerPerformance: 1471857295247 ms / [DONE] Composer constructor
,08-22 11:14:55.235  7087  7087 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,08-22 11:14:55.235  7087  7087 I Mms/ReservationManager: ReservationManager()
,08-22 11:14:55.235  7087  7087 I Mms/ReservationManager: resetAfterConnected()
,08-22 11:14:55.245  6740  7157 W jxcore-log: Starting JXcore engine
,08-22 11:14:55.245  1455  1465 D TP/MmsSmsProvider: query,matched:7, calling pid = 7087
,08-22 11:14:55.245  1455  1465 D TP/MmsSmsProvider: match 7:Elapsed time : 1.901 ms
,08-22 11:14:55.265  6949  6998 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-22 11:14:55.265  7087  7087 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-22 11:14:55.265  1022  1491 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-22 11:14:55.265  7087  7188 D Mms/Conversation: [start]    init() consume time = 82.449323
08-22 11:14:55.265  7087  7087 D Mms/MmsApp: [end]    onCreate() consume time = 0.086458
,08-22 11:14:55.265  1455  1703 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,08-22 11:14:55.265  1455  1703 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-22 11:14:55.265  1455  1703 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-22 11:14:55.275  1455  1703 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,08-22 11:14:55.275  7087  7087 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
,08-22 11:14:55.275  7087  7087 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,08-22 11:14:55.285  7087  7087 D Mms/MethodReflector: getSubId is called
08-22 11:14:55.285  7087  7087 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,08-22 11:14:55.285  7087  7087 D Mms/MethodReflector: getTelephonyProperty is called
08-22 11:14:55.285  7087  7087 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-22 11:14:55.285  7087  7087 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-22 11:14:55.285  7087  7087 D Mms/DownloadManager: auto download without roaming -> true
08-22 11:14:55.285  7087  7087 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-22 11:14:55.285  7087  7087 D Mms/DownloadManager: mAutoDownload ------> true
,08-22 11:14:55.285  1455  1703 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
,08-22 11:14:55.285  7087  7087 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
,08-22 11:14:55.285  1022  1035 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-22 11:14:55.285  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,08-22 11:14:55.285  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:55.285  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:55.285  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,08-22 11:14:55.285  1455  1703 D TP/MmsSmsProvider: need read changed broadcast:false
,08-22 11:14:55.295  1022  1226 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,08-22 11:14:55.295  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:55.295  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:55.295  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:55.295  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.305  1022  1226 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7191 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,08-22 11:14:55.305  7191  7191 E Zygote  : MountEmulatedStorage()
08-22 11:14:55.305  7191  7191 E Zygote  : v2
08-22 11:14:55.305  7191  7191 I libpersona: KNOX_SDCARD checking this for 10042
08-22 11:14:55.305  7191  7191 I libpersona: KNOX_SDCARD not a persona
,08-22 11:14:55.305  7191  7191 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:14:55.315  7191  7191 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:14:55.315  7191  7191 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL,
,08-22 11:14:55.315  7087  7188 D Mms/Conversation: [end]    init consume time = 50.714219
,08-22 11:14:55.325  7087  7189 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-22 11:14:55.325  7087  7189 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
,08-22 11:14:55.335  1022  4368 I ActivityManager: Killing 6695:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-22 11:14:55.335  7191  7191 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:55.335  7191  7191 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:55.345  7087  7188 D Mms/MessagingNotification: [start]    init() consume time = 25.343438
,08-22 11:14:55.345  7087  7188 D Mms/MessagingNotification: [end]    init consume time = 4.430312
,08-22 11:14:55.345  3823  6971 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 252.154ms
,08-22 11:14:55.375  7103  7103 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-22 11:14:55.375  1022  4371 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
08-22 11:14:55.375  1022  4371 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,08-22 11:14:55.375  1022  4371 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:55.375  1022  4371 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:55.375  1022  4371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-22 11:14:55.375  1455  1474 D TP/MmsSmsProvider: query,matched:0, calling pid = 7087
,08-22 11:14:55.375  1455  1474 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-22 11:14:55.375  1455  1474 D TP/MmsSmsProvider: match 0:Elapsed time : 4.084 ms
,08-22 11:14:55.385  6740  7157 W jxcore-log: Platform android
08-22 11:14:55.385  6740  7157 W jxcore-log: 
,08-22 11:14:55.385  6740  7157 W jxcore-log: Process ARCH arm
08-22 11:14:55.385  6740  7157 W jxcore-log: 
,08-22 11:14:55.395  1022  1034 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,08-22 11:14:55.395  7191  7191 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:55.395  7191  7191 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-22 11:14:55.395  7191  7191 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-22 11:14:55.405  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.405  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.405  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-22 11:14:55.405   291   291 E SMD     : DCD OFF
,08-22 11:14:55.405  1022  3416 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-22 11:14:55.405  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.405  7087  7207 D Mms/Synchronizer: [start]    doSync consume time = 62.747083,
08-22 11:14:55.415  7087  7206 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 0.9925
,08-22 11:14:55.425  6949  6998 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-22 11:14:55.425  7211  7211 E Zygote  : MountEmulatedStorage()
08-22 11:14:55.425  7211  7211 I libpersona: KNOX_SDCARD checking this for 10068
08-22 11:14:55.425  7211  7211 E Zygote  : v2
08-22 11:14:55.425  7211  7211 I libpersona: KNOX_SDCARD not a persona
,08-22 11:14:55.435  3823  4381 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-22 11:14:55.435  1022  1034 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7211 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-22 11:14:55.435  7211  7211 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:55.435  7211  7211 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:55.435  7211  7211 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-22 11:14:55.445  1455  1465 D TP/MmsSmsProvider: update, matched:300, calling pid = 7087
08-22 11:14:55.445  1455  1465 V TP/MmsSmsProvider: syncDBData start
08-22 11:14:55.445  1455  1465 V TP/MmsSmsProvider: syncDBData sms end
08-22 11:14:55.445  1455  1465 V TP/MmsSmsProvider: syncDBData mms end
08-22 11:14:55.445  1455  1465 V TP/MmsSmsProvider: syncDBData end
08-22 11:14:55.445  7087  7207 D Mms/Synchronizer: [end]    doSync consume time = 37.25474
,08-22 11:14:55.455  1455  1703 D TP/MmsSmsProvider: query,matched:400, calling pid = 7087
,08-22 11:14:55.455  7087  7206 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 9.344687
,08-22 11:14:55.475  7103  7103 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-22 11:14:55.475  6949  6998 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
,08-22 11:14:55.485  6949  7210 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-22 11:14:55.485  7211  7211 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:55.485  7211  7211 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:55.505  1022  1141 I ActivityManager: Killing 6664:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-22 11:14:55.535  7191  7191 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,08-22 11:14:55.545  1022  1063 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
,08-22 11:14:55.545  1022  1063 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-22 11:14:55.545  1022  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.545  1022  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.545  1022  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.555  7103  7226 D Ads     : Skipping gmscore version check
,08-22 11:14:55.555  7211  7211 D BadgeProvider: onCreate,
,08-22 11:14:55.555  7211  7211 D BadgeProvider: DatabaseHelper,
,08-22 11:14:55.555  1022  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.575  7228  7228 E Zygote  : MountEmulatedStorage()
08-22 11:14:55.575  7228  7228 E Zygote  : v2
08-22 11:14:55.575  7228  7228 I libpersona: KNOX_SDCARD checking this for 10003
08-22 11:14:55.575  7228  7228 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:55.585  1022  1063 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7228 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-22 11:14:55.585  7228  7228 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:14:55.585  7228  7228 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:14:55.585  1022  4371 I ActivityManager: Killing 6720:com.qualcomm.timeservice/1000 (adj 15): empty #21,
,08-22 11:14:55.585  7228  7228 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:14:55.615  7228  7228 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:55.615  7228  7228 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:55.625  6740  7157 I jxcore-log: JXcore Cordova bridge is ready!
08-22 11:14:55.625  6740  7157 I jxcore-log: 
,08-22 11:14:55.625  6740  7157 W jxcore-log: JXcore engine is started
,08-22 11:14:55.635  6740  7063 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-22 11:14:55.635  6740  6740 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-22 11:14:55.645  1022  1492 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,08-22 11:14:55.645  1022  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:55.645  1022  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:55.645  1022  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:55.645  1022  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.665  7245  7245 E Zygote  : MountEmulatedStorage()
08-22 11:14:55.665  7245  7245 E Zygote  : v2
08-22 11:14:55.665  7245  7245 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:14:55.665  7245  7245 I libpersona: KNOX_SDCARD not a persona
,08-22 11:14:55.665  7245  7245 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:14:55.665  7245  7245 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:14:55.665  7245  7245 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:14:55.665  1022  1492 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7245 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 11:14:55.675  7087  7169 D Mms/ArtClassLoader: init [DONE] art
,08-22 11:14:55.675   284   284 E installd: system dir 0 : /system/app/,
08-22 11:14:55.675   284   284 E installd: system dir 1 : /system/priv-app/
08-22 11:14:55.675   284   284 E installd: system dir 2 : /vendor/app/,
08-22 11:14:55.675   284   284 E installd: system dir 3 : /oem/app/
,08-22 11:14:55.685  1022  1329 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-22 11:14:55.685  1022  1329 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:55.685  1022  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:55.685  1022  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-22 11:14:55.685  7087  7188 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-22 11:14:55.695  1455  1705 D TP/SmsProvider: query,matched:26, calling pid = 7087
,08-22 11:14:55.695  1455  1705 D TP/SmsProvider: match 26:Elapsed time : 1.377 ms
,08-22 11:14:55.715  7245  7245 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:55.715  7245  7245 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:55.735  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-22 11:14:55.735  1455  1703 D TP/MmsSmsProvider: query,matched:6, calling pid = 7087
,08-22 11:14:55.735  1455  1703 D TP/MmsSmsProvider: match 6:Elapsed time : 1.152 ms
,08-22 11:14:55.765  7245  7245 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,08-22 11:14:55.765  7245  7245 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,08-22 11:14:55.765  1022  1063 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,08-22 11:14:55.765  1022  4367 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-22 11:14:55.765  1022  4367 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,08-22 11:14:55.775  1022  4367 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:55.775  1022  4367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:14:55.775  1022  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,08-22 11:14:55.775  1022  4371 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,08-22 11:14:55.785  1022  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.785  1022  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:55.785  1022  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.785  1022  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.805  7264  7264 E Zygote  : MountEmulatedStorage(),
08-22 11:14:55.805  7264  7264 E Zygote  : v2
,08-22 11:14:55.805  7264  7264 I libpersona: KNOX_SDCARD checking this for 10023
08-22 11:14:55.805  7264  7264 I libpersona: KNOX_SDCARD not a persona
,08-22 11:14:55.805  7264  7264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:14:55.805  7264  7264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:14:55.815  7264  7264 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:14:55.815  1022  4371 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7264 uid=10023 gids={50023, 9997} abi=armeabi-v7a,
08-22 11:14:55.815  1022  1223 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-22 11:14:55.825  7245  7245 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,08-22 11:14:55.825  1022  1047 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-22 11:14:55.825  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.825  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:55.825  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.825  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.845  1022  1047 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7280 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,08-22 11:14:55.855  7280  7280 E Zygote  : MountEmulatedStorage(),
08-22 11:14:55.855  7280  7280 E Zygote  : v2
,08-22 11:14:55.855  7280  7280 I libpersona: KNOX_SDCARD checking this for 10130
08-22 11:14:55.855  7280  7280 I libpersona: KNOX_SDCARD not a persona
,08-22 11:14:55.855  7280  7280 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:14:55.865  7280  7280 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:14:55.865  7280  7280 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,08-22 11:14:55.875  7264  7264 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:55.875  7264  7264 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:55.885  1022  4368 I ActivityManager: Killing 6757:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,08-22 11:14:55.895  7245  7263 E FilterInstaller: installFilters
,08-22 11:14:55.895  7245  7263 E FilterInstaller: There is no requred permission
,08-22 11:14:55.905  7280  7280 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:55.905  7280  7280 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:55.905  1022  1226 I ActivityManager: Killing 6766:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,08-22 11:14:55.905  3823  3847 W art     : Suspending all threads took: 8.995ms
,08-22 11:14:55.925  7280  7280 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 11:14:55.925  7280  7280 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-22 11:14:55.945  1022  4370 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-22 11:14:55.945  1022  4370 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.945  1022  4370 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:55.945  1022  4370 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:55.945  1022  4370 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:55.945  3823  4381 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-22 11:14:55.955  7295  7295 E Zygote  : MountEmulatedStorage()
,08-22 11:14:55.955  7295  7295 E Zygote  : v2
,08-22 11:14:55.955  7295  7295 I libpersona: KNOX_SDCARD checking this for 10131
,08-22 11:14:55.965  7295  7295 I libpersona: KNOX_SDCARD not a persona,
,08-22 11:14:55.965  7295  7295 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:14:55.965  1022  4370 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7295 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-22 11:14:55.965  7295  7295 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:14:55.965  1022  4370 I ActivityManager: Killing 6781:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
08-22 11:14:55.965  7295  7295 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:14:55.995  7295  7295 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:55.995  7295  7295 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:56.005  7264  7264 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,08-22 11:14:56.025  7295  7295 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-22 11:14:56.025  7295  7295 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:14:56.025  7295  7295 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 11:14:56.045  7087  7188 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-22 11:14:56.065  7264  7264 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-22 11:14:56.075  7264  7264 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-22 11:14:56.075  7264  7264 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-22 11:14:56.075  7264  7264 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-22 11:14:56.075  7264  7264 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-22 11:14:56.075  7264  7264 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-22 11:14:56.085  7264  7264 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-22 11:14:56.085  7264  7264 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-22 11:14:56.085  2635  2649 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-22 11:14:56.085  7264  7264 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-22 11:14:56.085  1022  4367 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-22 11:14:56.085  1022  4367 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-22 11:14:56.085  1022  4367 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:56.085  1022  4367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:56.085  1022  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-22 11:14:56.095  7264  7264 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-22 11:14:56.095  7264  7264 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-22 11:14:56.095  7264  7264 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-22 11:14:56.095  1022  1034 I ActivityManager: Killing 6805:com.samsung.helphub/1000 (adj 15): empty #21
,08-22 11:14:56.095  7264  7264 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-22 11:14:56.115  1022  1329 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-22 11:14:56.115  1022  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-22 11:14:56.115  1022  1329 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:56.115  1022  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:56.115  1022  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-22 11:14:56.125  1022  4368 D ActivityManager: startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,08-22 11:14:56.125  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:56.125  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:56.125  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:56.125  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:14:56.125  6949  7243 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-22 11:14:56.125  6949  7243 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-22 11:14:56.135  7316  7316 E Zygote  : MountEmulatedStorage()
08-22 11:14:56.135  7316  7316 E Zygote  : v2
08-22 11:14:56.135  7316  7316 I libpersona: KNOX_SDCARD checking this for 10037
08-22 11:14:56.135  7316  7316 I libpersona: KNOX_SDCARD not a persona
,08-22 11:14:56.145  7316  7316 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:14:56.145  7316  7316 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:14:56.145  7316  7316 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-22 11:14:56.145  1022  4368 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7316 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 11:14:56.165  7316  7316 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:14:56.165  7316  7316 D ActivityThread: Added TimaKeyStore provider
,08-22 11:14:56.165  3823  4381 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,08-22 11:14:56.165  1022  4371 I ActivityManager: Killing 6818:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-22 11:14:56.185  7316  7316 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-22 11:14:56.185  1022  4370 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-22 11:14:56.195  1022  4370 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:56.195  1022  4370 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:14:56.195  1022  4370 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:14:56.215  7316  7316 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-22 11:14:56.225  6949  7243 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-22 11:14:56.285  6949  7243 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-22 11:14:56.285  6949  7243 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@315c2ca7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-22 11:14:56.285  6949  7243 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-22 11:14:56.315  1022  1141 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,08-22 11:14:56.315  1022  1141 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,08-22 11:14:56.315  1022  1141 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:14:56.315  1022  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:56.315  1022  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-22 11:14:56.325  1022  4371 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,08-22 11:14:56.325  1022  4371 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-22 11:14:56.325  1022  4371 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:56.325  1022  4371 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:14:56.325  1022  4371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-22 11:14:56.335  7316  7334 E SQLiteLog: (284) automatic index on view_events(_id)
,08-22 11:14:56.355  7316  7334 D CalendarAlarmManager: sys current time:1471857296340
,08-22 11:14:56.355  7316  7334 D CalendarAlarmManager: reminder amount:0
,08-22 11:14:56.515  1022  1223 I ActivityManager: Killing 6894:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-22 11:14:57.265  7087  7087 I Mms/MmsApp:  start initViewCache mms
,08-22 11:14:57.265  7087  7087 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1811.274948
,08-22 11:14:57.265  7087  7087 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-22 11:14:57.335  7316  7316 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-22 11:14:57.335  1022  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:57.335  1022  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:57.335  1022  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,08-22 11:14:57.335  1022  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-22 11:14:57.335  1022  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:57.335  1022  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:57.335  1022  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-22 11:14:57.345  1022  4370 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:57.345  1022  4370 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:57.345  1022  4370 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-22 11:14:57.355  1022  1141 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-22 11:14:57.355  1022  1141 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-22 11:14:57.355  1022  1141 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:57.355  1022  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:57.355  1022  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-22 11:14:57.355  1022  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:57.355  1022  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:57.355  1022  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-22 11:14:57.365  7087  7087 D AbsListView: Get MotionRecognitionManager
,08-22 11:14:57.365  1022  1226 D MotionRecognitionService:  ssp status : false
,08-22 11:14:57.365  1022  1035 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-22 11:14:57.365  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-22 11:14:57.365  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:57.365  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:14:57.365  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-22 11:14:57.375  7087  7087 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 105.907395
,08-22 11:14:57.385  1022  1486 I ActivityManager: Killing 6407:com.samsung.android.sm/1000 (adj 15): empty #21
,08-22 11:14:57.495  7087  7087 D Mms/BubbleViewCache: fillCache bubble = 1
,08-22 11:14:58.405   291   291 E SMD     : DCD OFF
,08-22 11:14:58.465  6855  6889 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter,
,08-22 11:14:58.485  6855  6889 I AcmsKeyStoreHelper: Key Store exist
,08-22 11:14:58.485  6855  6889 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-22 11:14:58.535  6855  6889 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit,
08-22 11:14:58.535  6855  6889 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-22 11:14:58.535  6855  6889 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-22 11:14:58.535  6855  6889 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter,
08-22 11:14:58.535  6855  6889 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-22 11:14:58.535  6855  6889 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-22 11:14:58.535  6855  6889 D AcmsCore: This is NOT a valid MirrorLink app
,08-22 11:14:58.535  6855  6889 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-22 11:14:58.535  6855  6889 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 11:14:58.535  6855  6889 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-22 11:14:58.535  6855  6889 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-22 11:14:58.545  6855  6855 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,08-22 11:14:58.545  6855  6855 D AcmsService: Enter onDestroy
08-22 11:14:58.545  6855  6855 I AcmsService: cleanUp(): inside service clean up
,08-22 11:14:58.545  6855  6855 D AcmsCore: AcmsCore: inside DeInit
08-22 11:14:58.545  6855  6855 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
,08-22 11:14:58.545  6855  6855 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
,08-22 11:14:58.545  6855  6855 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-22 11:14:58.545  6855  6855 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-22 11:14:58.545  6855  6855 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-22 11:14:58.545  6855  6855 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,08-22 11:14:58.545  6855  6855 D AcmsService: killing acms process
,08-22 11:14:58.545  6855  6855 I Process : Sending signal. PID: 6855 SIG: 9
,08-22 11:14:58.715  1022  1492 I ActivityManager: Process ACMS.Process (pid 6855)(adj 0) has died(26,753)
,08-22 11:14:59.115  2652  2652 I ConfigService: onDestroy
,08-22 11:14:59.315  1022  3388 D SSRM:n  : SIOP:: AP = 410
,08-22 11:14:59.995  1022  1101 V AlarmManager: waitForAlarm result :8,
,08-22 11:15:00.435  1022  3416 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-22 11:15:01.405   291   291 E SMD     : DCD OFF,
,08-22 11:15:01.925  1022  1063 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-22 11:15:03.135  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:03.135  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:03.135  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:03.135  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:03.145  1022  1047 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7340 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-22 11:15:03.145  7340  7340 E Zygote  : MountEmulatedStorage()
08-22 11:15:03.145  7340  7340 E Zygote  : v2
08-22 11:15:03.145  7340  7340 I libpersona: KNOX_SDCARD checking this for 10011
08-22 11:15:03.145  7340  7340 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:03.145  7340  7340 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:15:03.155  7340  7340 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:03.155  7340  7340 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 11:15:03.175  7340  7340 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:03.175  7340  7340 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:03.195  7340  7340 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-22 11:15:03.195  7340  7340 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-22 11:15:03.225  7340  7340 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-22 11:15:03.225  7340  7340 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-22 11:15:03.235  7340  7340 I MultiDex: VM with version 2.1.0 has multidex support
08-22 11:15:03.235  7340  7340 I MultiDex: install
08-22 11:15:03.235  7340  7340 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-22 11:15:03.255  7340  7340 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-22 11:15:03.315  7340  7340 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-22 11:15:03.315  7340  7340 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@301984f5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-22 11:15:03.315  7340  7340 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-22 11:15:03.325  1022  1047 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.325  1022  1047 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.325  1022  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.325  1022  1329 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:03.325  1022  1329 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.325  1022  1329 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.325  1022  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.325  1022  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.325  1022  4367 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
08-22 11:15:03.325  1022  4367 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-22 11:15:03.325  1022  4367 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-22 11:15:03.325  1022  4367 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-22 11:15:03.325  1022  4367 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.325  1022  4367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.325  1022  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.335  2652  2678 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-22 11:15:03.335  1022  4370 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.335  1022  4370 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.335  1022  4370 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.335  2652  2652 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-22 11:15:03.365  7340  7357 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-22 11:15:03.365  1022  1223 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.365  1022  1223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 11:15:03.365  1022  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.375  1022  4368 I ActivityManager: Killing 6922:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-22 11:15:03.375  1022  4367 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 11:15:03.375  1022  4367 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.375  1022  4367 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.375  1022  4367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.375  1022  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.385  1022  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.385  1022  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.385  1022  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.385  2652  2652 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 11:15:03.385  2652  2652 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 11:15:03.395  1022  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.395  1022  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 11:15:03.395  1022  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-22 11:15:03.395  1022  4368 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 11:15:03.395  1022  4368 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4251, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-22 11:15:03.395  1022  4368 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-22 11:15:03.395  1022  4368 D BatteryService: stay LED for charging
,08-22 11:15:03.395  1022  1022 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 11:15:03.405  3823  3823 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-22 11:15:03.405  1022  1022 I MotionRecognitionService: Plugged
,08-22 11:15:03.405  1022  1022 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 11:15:03.405  1184  1184 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 11:15:03.415  1184  1184 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 11:15:03.415  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-22 11:15:03.415  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 11:15:03.425  3222  3222 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-22 11:15:03.425  3222  3360 D HeadsetStateMachine: Disconnected process message: 10
,08-22 11:15:03.425  1022  1141 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 11:15:03.425  1022  1141 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.435  1022  1141 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.435  1022  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.435  1022  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.435  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.435  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.435  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.435  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 11:15:03.435  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 11:15:03.445  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 11:15:03.445  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.445  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.445  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.455  1022  1491 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.455  1022  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.455  1022  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.455  1022  1226 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.455  1022  1226 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.455  1022  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.465  1022  1141 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:03.465  1022  1141 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.465  1022  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 11:15:03.465  1022  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.475  7340  7340 D WearableService: callingUid 10011, callindPid: 7340
,08-22 11:15:03.475  1022  1226 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.475  1022  1226 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 11:15:03.475  1022  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.505  1022  4367 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.505  1022  4367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.505  1022  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.505  1022  4367 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.505  1022  4367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 11:15:03.505  1022  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.515  1022  1226 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:03.515  1022  1226 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.515  1022  1226 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 11:15:03.515  1022  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.525  1022  1491 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.525  1022  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.525  1022  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.525  1776  5162 E MDM     : [187] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-22 11:15:03.525  1022  1329 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 11:15:03.525  1022  1329 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-22 11:15:03.535  1022  1329 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.535  1022  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.535  1022  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.535  3823  7360 D LocationInitializer: Restart initialization of location
,08-22 11:15:03.535  1022  4368 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 11:15:03.535  1022  4368 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.535  1022  4368 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.535  1022  4368 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.535  1022  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.545  1022  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:03.545  1022  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.545  1022  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.555  1022  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:04.405   291   291 E SMD     : DCD OFF,
,08-22 11:15:05.445  1022  1332 E Watchdog: !@Sync 3
,08-22 11:15:05.785  1022  1063 D PackageManager: [MSG] MCS_UNBIND
,08-22 11:15:06.415   336   336 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-22 11:15:06.415   336   336 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-22 11:15:07.405   291   291 E SMD     : DCD OFF
,08-22 11:15:08.365  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-22 11:15:08.365  6740  7157 I jxcore-log: 
,08-22 11:15:08.365  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-22 11:15:08.365  6740  7157 I jxcore-log: 
,08-22 11:15:08.375  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:08.375  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:08.375  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:08.375  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:08.375  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:08.375  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:08.375  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:08.375  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:08.375  6740  7157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:08.375  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-22 11:15:08.375  6740  7157 I jxcore-log: 
,08-22 11:15:08.375  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-22 11:15:08.375  6740  7157 I jxcore-log: 
,08-22 11:15:08.575  1022  4368 I ActivityManager: Killing 6949:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-22 11:15:09.045  6740  7157 D ExecuteNativeTests: Running unit tests
,08-22 11:15:09.055  1022  1054 I PowerManagerService: [PWL] Off : 50s ago
,08-22 11:15:09.135  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:09.135  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 added. We now have 2 listener(s)
,08-22 11:15:09.135  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-22 11:15:09.135  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:09.135  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:09.135  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:09.135  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 added. We now have 2 listener(s)
08-22 11:15:09.135  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:09.135  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:15:09.135  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:09.135  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:09.135  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:09.135  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:09.135  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:09.135  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:09.135  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:09.135  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:09.135  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:09.145  6740  7157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:09.145  6740  7157 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:09.145  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-22 11:15:09.145  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-22 11:15:09.145  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 11:15:09.145  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-22 11:15:09.145  6740  7157 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-22 11:15:09.145  6740  7157 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 11:15:09.145  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 11:15:09.145  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 11:15:09.145  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
08-22 11:15:09.145  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:09.145  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.145  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.145  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 11:15:09.145  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.145  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:09.145  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:09.145  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 removed from the list
08-22 11:15:09.145  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:09.145  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 removed from the list
08-22 11:15:09.155  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:09.155  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.155  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:09.155  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.155  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:09.155  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 11:15:09.155  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.155  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.155  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
,08-22 11:15:09.155  6740  7157 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-22 11:15:09.155  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:09.155  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.155  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.155  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.155  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.155  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.155  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.155  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.155  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.155  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.155  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.155  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.155  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.155  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:09.155  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.155  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.155  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.155  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
,08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 11:15:09.165  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:09.165  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.165  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.165  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.165  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.165  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.165  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.165  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.165  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.165  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.165  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.165  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.165  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.165  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.165  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.165  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.165  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.165  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.165  6740  7157 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-22 11:15:09.165  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:09.175  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:09.175  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:09.175  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:09.175  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:09.175  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:09.175  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:09.175  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:09.175  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 11:15:09.175  6740  7157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:09.175  6740  7157 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 11:15:09.175  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:09.175  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 11:15:09.175  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:09.175  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:09.175  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 11:15:09.175  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:09.185  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:09.185  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 11:15:09.185  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 11:15:09.195  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 11:15:09.195  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-22 11:15:09.195  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-22 11:15:09.195  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 11:15:09.195  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 11:15:09.195  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-22 11:15:09.205  3222  3245 D BtGatt.GattService: registerClient() - UUID=fd2f34dc-4c12-4351-bdce-075eb547cdb5
,08-22 11:15:09.245  3222  3297 D BtGatt.GattService: onClientRegistered() - UUID=fd2f34dc-4c12-4351-bdce-075eb547cdb5, clientIf=6
,08-22 11:15:09.245  6740  6752 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 11:15:09.245  3222  3355 D BtGatt.GattService: start scan with filters
,08-22 11:15:09.255  3222  3358 D BtGatt.ScanManager: handling starting scan
,08-22 11:15:09.255  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 11:15:09.255  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 11:15:09.255  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 11:15:09.255  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:09.255  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:09.255  3222  3358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:09.255  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 11:15:09.255  6740  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:09.265  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:09.265  3222  3297 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-22 11:15:09.265  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.265  3222  3358 D BtGatt.ScanManager: allow scan with filters
08-22 11:15:09.265  6740  7157 I io.jxcore.node.ConnectionHelper: start: OK
08-22 11:15:09.265  3222  3358 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-22 11:15:09.265  3222  3358 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-22 11:15:09.265  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:09.265  6740  7157 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 11:15:09.265  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.265  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 11:15:09.265  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:09.265  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 11:15:09.265  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 11:15:09.265  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:09.265  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:09.265  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 11:15:09.275  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 11:15:09.275  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 11:15:09.275  3222  3297 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-22 11:15:09.275  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.275  3222  3231 D BtGatt.GattService: stopScan() - queue size =1
08-22 11:15:09.275  3222  3358 D BtGatt.ScanManager: Starting BLE batch scan
08-22 11:15:09.275  3222  3358 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 11:15:09.275  3222  3245 D BtGatt.GattService: unregisterClient() - clientIf=6
08-22 11:15:09.275  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 11:15:09.275  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:09.275  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 11:15:09.275  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 11:15:09.275  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 11:15:09.275  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:09.285  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 11:15:09.285  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-22 11:15:09.285  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 11:15:09.285  3222  3297 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-22 11:15:09.285  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.285  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:09.285  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:09.285  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:09.285  6740  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:09.285  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.285  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.285  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:09.285  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.285  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.285  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.285  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.285  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:09.285  3222  3297 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-22 11:15:09.285  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.295  6740  7157 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-22 11:15:09.295  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:09.295  3222  3358 D BtGatt.ScanManager: filter size is 1
,08-22 11:15:09.295  3222  3358 D BtGatt.ScanManager: delete FilterIndex - 3
,08-22 11:15:09.305  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:09.305  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:09.305  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:09.305  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:09.305  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:09.305  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:09.305  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:09.305  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:09.305  3222  3297 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-22 11:15:09.305  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.305  3222  3358 D BtGatt.ScanManager: stopping BLe Batch
,08-22 11:15:09.305  6740  7157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:09.315  6740  7157 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:09.315  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:09.315  3222  3297 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-22 11:15:09.315  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.315  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:09.315  3222  3358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-22 11:15:09.325  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:09.325  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-22 11:15:09.325  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:09.325  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:09.325  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 11:15:09.325  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 11:15:09.325  3222  3297 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 11:15:09.325  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.335  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 11:15:09.335  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 11:15:09.335  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 11:15:09.335  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 11:15:09.335  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:09.335  3222  3355 D BtGatt.GattService: registerClient() - UUID=bda05aad-5c9d-42bc-9174-5b2cd7418757
,08-22 11:15:09.345  1022  3388 D SSRM:n  : SIOP:: AP = 380
,08-22 11:15:09.385  3222  3297 D BtGatt.GattService: onClientRegistered() - UUID=bda05aad-5c9d-42bc-9174-5b2cd7418757, clientIf=6,
08-22 11:15:09.385  6740  6750 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-22 11:15:09.385  3222  3231 D BtGatt.GattService: start scan with filters
,08-22 11:15:09.385  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 11:15:09.385  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 11:15:09.385  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 11:15:09.385  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-22 11:15:09.385  3222  3358 D BtGatt.ScanManager: handling starting scan
,08-22 11:15:09.385  3222  3297 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-22 11:15:09.385  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-22 11:15:09.385  3222  3358 D BtGatt.ScanManager: allow scan with filters
08-22 11:15:09.385  3222  3358 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-22 11:15:09.385  3222  3358 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6,
08-22 11:15:09.385  3222  3297 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-22 11:15:09.385  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:09.395  3222  3358 D BtGatt.ScanManager: Starting BLE batch scan
08-22 11:15:09.395  3222  3358 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 11:15:09.395  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 11:15:09.395  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 11:15:09.395  6740  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:09.395  3222  3297 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-22 11:15:09.395  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.395  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:09.405  3222  3297 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-22 11:15:09.405  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.405  6740  7157 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 11:15:09.415  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:09.415  6740  7157 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 11:15:09.415  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.415  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 11:15:09.415  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.415  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 11:15:09.415  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 11:15:09.415  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:09.415  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:09.415  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 11:15:09.415  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 11:15:09.415  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 11:15:09.415  3222  3245 D BtGatt.GattService: stopScan() - queue size =1
,08-22 11:15:09.415  3222  3358 D BtGatt.ScanManager: filter size is 1
,08-22 11:15:09.415  3222  3358 D BtGatt.ScanManager: delete FilterIndex - 4
08-22 11:15:09.415  3222  3355 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 11:15:09.415  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 11:15:09.415  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:09.415  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 11:15:09.415  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 11:15:09.415  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 11:15:09.415  3222  3297 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-22 11:15:09.415  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:09.415  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:09.415  3222  3358 D BtGatt.ScanManager: stopping BLe Batch
,08-22 11:15:09.425  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-22 11:15:09.425  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-22 11:15:09.425  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 11:15:09.425  3222  3297 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-22 11:15:09.425  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:09.425  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:09.425  3222  3358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-22 11:15:09.425  3222  3297 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-22 11:15:09.425  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.425  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.425  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.425  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:09.425  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.425  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.425  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.425  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.425  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.425  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.425  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:09.425  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.425  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.425  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.425  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
,08-22 11:15:09.435  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:09.435  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:09.435  6740  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:09.435  6740  7157 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-22 11:15:09.435  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:09.435  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:09.435  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:09.435  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:09.435  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:09.435  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:09.435  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:09.435  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:09.435  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:09.445  6740  7157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:09.445  6740  7157 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:09.445  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:09.445  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:09.445  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 11:15:09.445  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-22 11:15:09.445  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:09.445  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:09.445  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 11:15:09.455  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 11:15:09.455  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 11:15:09.455  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 11:15:09.465  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 11:15:09.465  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-22 11:15:09.465  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:09.465  3222  3245 D BtGatt.GattService: registerClient() - UUID=585edb47-ab31-4066-bd42-4a2fe00d4aca
,08-22 11:15:09.515  3222  3297 D BtGatt.GattService: onClientRegistered() - UUID=585edb47-ab31-4066-bd42-4a2fe00d4aca, clientIf=6
,08-22 11:15:09.515  6740  6752 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 11:15:09.515  3222  3355 D BtGatt.GattService: start scan with filters
,08-22 11:15:09.515  3222  3358 D BtGatt.ScanManager: handling starting scan
,08-22 11:15:09.515  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 11:15:09.515  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-22 11:15:09.515  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-22 11:15:09.515  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:09.515  3222  3297 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-22 11:15:09.515  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.515  3222  3358 D BtGatt.ScanManager: allow scan with filters
,08-22 11:15:09.515  3222  3358 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-22 11:15:09.525  3222  3358 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-22 11:15:09.525  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 11:15:09.525  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 11:15:09.525  6740  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:09.525  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:09.525  3222  3297 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-22 11:15:09.525  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.525  3222  3358 D BtGatt.ScanManager: Starting BLE batch scan
,08-22 11:15:09.525  3222  3358 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 11:15:09.535  6740  7157 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 11:15:09.535  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:09.535  6740  7157 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 11:15:09.535  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.535  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 11:15:09.535  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.535  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 11:15:09.535  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 11:15:09.535  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:09.535  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:09.535  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 11:15:09.535  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 11:15:09.535  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 11:15:09.535  3222  3231 D BtGatt.GattService: stopScan() - queue size =1,
08-22 11:15:09.535  3222  3245 D BtGatt.GattService: unregisterClient() - clientIf=6
08-22 11:15:09.535  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-22 11:15:09.535  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:09.535  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 11:15:09.535  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-22 11:15:09.535  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 11:15:09.535  3222  3297 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-22 11:15:09.535  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.545  3222  3297 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-22 11:15:09.545  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.545  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:09.545  3222  3358 D BtGatt.ScanManager: filter size is 1
,08-22 11:15:09.545  3222  3358 D BtGatt.ScanManager: delete FilterIndex - 5
08-22 11:15:09.545  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 11:15:09.545  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 11:15:09.545  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 11:15:09.545  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:09.545  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-22 11:15:09.545  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:09.545  6740  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:09.545  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:09.545  6740  7157 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 11:15:09.545  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 11:15:09.545  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 11:15:09.555  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 11:15:09.555  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:09.555  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:09.555  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.555  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.555  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.555  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.555  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:09.555  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.555  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:09.555  3222  3297 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-22 11:15:09.555  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.555  3222  3358 D BtGatt.ScanManager: stopping BLe Batch
08-22 11:15:09.555  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.555  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.555  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:09.555  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.555  6740  7157 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-22 11:15:09.555  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:09.555  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.555  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.555  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 11:15:09.555  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.555  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.555  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.555  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:09.555  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list,
08-22 11:15:09.555  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.555  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.555  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.555  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:09.555  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.555  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-22 11:15:09.555  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.555  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-22 11:15:09.555  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.555  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 11:15:09.555  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:09.555  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.555  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.555  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.555  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.555  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.555  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.555  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.555  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.555  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.555  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-22 11:15:09.555  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.555  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.555  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.565  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.565  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 11:15:09.565  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.565  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.565  6740  7157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-22 11:15:09.565  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:09.565  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.565  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.565  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.565  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.565  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:09.565  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.565  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.565  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.565  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop,
08-22 11:15:09.565  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.565  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.565  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:09.565  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.565  3222  3297 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 11:15:09.565  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:09.565  3222  3358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-22 11:15:09.565  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.565  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 11:15:09.565  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:09.565  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.565  6740  7157 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-22 11:15:09.565  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:09.565  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.565  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.565  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 11:15:09.565  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.565  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.565  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.565  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.565  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.565  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.565  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.565  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.565  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.565  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.575  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.575  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.575  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.575  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.575  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-22 11:15:09.575  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 11:15:09.575  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 11:15:09.575  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 11:15:09.575  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 11:15:09.575  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 11:15:09.575  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:09.575  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.575  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 11:15:09.575  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.575  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.575  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.575  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.575  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:09.575  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.575  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.575  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.575  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:09.575  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.575  3222  3297 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 11:15:09.575  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:09.575  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.575  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.575  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.575  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.575  6740  7157 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:09.575  6740  7157 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
08-22 11:15:09.575  6740  7157 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:09.575  6740  7157 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810],
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 11:15:09.575  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 11:15:09.575  6740  7157 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-22 11:15:09.575  6740  7157 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 11:15:09.575  6740  7157 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-22 11:15:09.575  6740  7157 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:09.575  6740  7157 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-22 11:15:09.575  6740  7157 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-22 11:15:09.575  6740  7157 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:09.575  6740  7157 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 11:15:09.575  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-22 11:15:09.575  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-22 11:15:09.585  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-22 11:15:09.585  6740  7157 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-22 11:15:09.585  6740  7157 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:09.585  6740  7157 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-22 11:15:09.585  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:09.585  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 11:15:09.585  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.585  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.585  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.585  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-22 11:15:09.585  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
,08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.585  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.585  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.585  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.585  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.585  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:09.585  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.585  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.585  6740  7157 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-22 11:15:09.585  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:09.585  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.585  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.585  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.585  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.585  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.585  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.585  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.585  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.585  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.585  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.585  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.585  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.585  6740  7370 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1319
08-22 11:15:09.585  6740  7157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-22 11:15:09.585  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:09.585  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.585  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.585  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.585  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.585  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Connectio,nManager@15560ff7 not in the list
08-22 11:15:09.585  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.585  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.585  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.585  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.585  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.585  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.585  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.595  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.595  6740  7157 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-22 11:15:09.595  6740  7157 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-22 11:15:09.595  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 11:15:09.595  6740  7157 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-22 11:15:09.595  6740  7157 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 11:15:09.595  6740  7157 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-22 11:15:09.595  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 11:15:09.595  6740  7157 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-22 11:15:09.595  6740  7157 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 11:15:09.595  6740  7157 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 11:15:09.595  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 11:15:09.595  6740  7157 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-22 11:15:09.595  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:09.595  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.595  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.595  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.595  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.595  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:09.595  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.595  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.595  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.595  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.595  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.595  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:09.595  6740  7369 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1319)
08-22 11:15:09.595  6740  7369 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1319)
08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.595  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
,08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.595  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.595  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.595  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.595  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
,08-22 11:15:09.595  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.595  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.595  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.595  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 11:15:09.595  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.595  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.595  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.595  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:09.595  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 11:15:09.595  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.595  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.595  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.595  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
,08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.595  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.595  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.595  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.595  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.595  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:09.595  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.595  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.595  6740  7157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:09.595  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-22 11:15:09.605  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 11:15:09.605  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.605  6740  6740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-22 11:15:09.605  6740  6740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:09.605  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.605  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:09.605  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:09.605  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:09.605  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.605  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.605  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 lis,tener(s) left
08-22 11:15:09.605  6740  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:09.605  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.605  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.605  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.605  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.605  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.605  6740  7371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-22 11:15:09.605  6740  7371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-22 11:15:09.605  6740  6740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.605  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.605  6740  7157 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-22 11:15:09.605  6740  7157 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 11:15:09.605  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 11:15:09.605  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:09.605  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.605  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.605  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.605  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@155,60ff7 not in the list
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.605  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.605  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.605  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.605  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.605  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.605  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:09.605  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.605  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.605  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.605  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.605  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.605  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.605  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.605  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.605  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.605  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.615  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.615  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.615  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.615  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.615  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:09.615  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:09.615  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:09.615  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:09.615  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.615  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.615  6740  7157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15560ff7 not in the list
08-22 11:15:09.615  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.615  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:09.615  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.615  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.615  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:09.615  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:09.615  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:09.615  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:09.615  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:09.615  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8c3e64 not in the list
08-22 11:15:09.615  6740  7157 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 11:15:09.615  6740  7157 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 11:15:09.615  6740  7157 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-22 11:15:09.615  6740  7157 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 11:15:09.615  6740  7157 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 11:15:09.615  6740  7157 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-22 11:15:09.615  6740  7157 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-22 11:15:09.615  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:09.615  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@202502a6 added. We now have 2 listener(s)
08-22 11:15:09.615  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:09.625  6740  7157 D BluetoothAdapter: enable()
08-22 11:15:09.625  6740  7157 D BluetoothAdapter: enable(): BT is already enabled..!
08-22 11:15:09.625  1022  1492 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-22 11:15:09.625  1022  1492 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-22 11:15:09.625  1022  1492 D SecContentProvider2: mCursor = null
08-22 11:15:09.625  1022  1492 D WifiService: setWifiEnabled: true pid=6740, uid=10170
08-22 11:15:09.625  1022  1492 W ActivityManager: Permission Denial: getCurrentUser() from pid=6740, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-22 11:15:09.635  1022  1492 W WifiService: Failed getting userId using ActivityManagerNative
08-22 11:15:09.635  1022  1492 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6740, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-22 11:15:09.635  1022  1492 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 11:15:09.635  1022  1492 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-22 11:15:09.635  1022  1492 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-22 11:15:09.635  1022  1492 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-22 11:15:09.635  1022  1492 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-22 11:15:09.635  1022  1492 D SettingsProvider: name = wifi_on
08-22 11:15:09.635  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:09.635  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28f4e4e7 added. We now have 3 listener(s)
08-22 11:15:09.635  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:09.635  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:09.635  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fae0894 added. We now have 4 listener(s)
08-22 11:15:09.645  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:09.645  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:09.645  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a2eef3d added. We now have 5 listener(s)
08-22 11:15:09.645  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:09.645  1022  4370 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-22 11:15:09.645  1022  4370 D WifiService: setWifiEnabled: false pid=6740, uid=10170
08-22 11:15:09.645  1022  4370 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-22 11:15:09.645  1022  4370 D SecContentProvider2: mCursor = null
08-22 11:15:09.645  1022  4370 D SettingsProvider: name = wifi_on
08-22 11:15:09.655  1022  1131 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-22 11:15:09.655  6740  7157 D BluetoothAdapter: disable()
08-22 11:15:09.655  1387  1387 I wpa_supplicant: reset timer : RESET_TIMER 0
08-22 11:15:09.655  1387  1387 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-22 11:15:09.655  1022  1491 D SettingsProvider: name = bluetooth_on
08-22 11:15:09.655  1387  1387 I wpa_supplicant: P2P: Current p2p state = IDLE
08-22 11:15:09.655  1387  1387 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-22 11:15:09.655  1022  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-22 11:15:09.675  3222  3294 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-22 11:15:09.675  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:09.675  3222  3294 D BluetoothAdapterProperties: Setting state to 13
08-22 11:15:09.675  3222  3294 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-22 11:15:09.675  3222  3294 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 11:15:09.675  3222  3294 D BluetoothAdapterService: updateAdapterState state is 13
,08-22 11:15:09.675  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:09.685  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:09.685  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:09.685  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:09.685  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:09.685  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:09.685  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:09.685  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:09.685  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 11:15:09.685  1022  4368 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:09.685  1022  4368 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 11:15:09.685  1022  4368 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:09.685  1022  1131 E WifiNative-wlan0: do suspend true
08-22 11:15:09.685  1022  4368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:09.685  1022  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:09.685  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:09.685  6740  7157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:09.685  6740  7157 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:09.685  3222  3294 D BluetoothAdapterService: Autoconnection is available 
08-22 11:15:09.685  3222  3294 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-22 11:15:09.685  3222  3294 D BluetoothAdapterService: terminating service from this receiver
,08-22 11:15:09.685  1022  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-22 11:15:09.685  1022  1223 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:09.685  3222  3222 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-22 11:15:09.685  1022  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:09.685  1022  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 11:15:09.685  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@60c6f30, channel: 19, state: LISTENING
08-22 11:15:09.685  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@60c6f30, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12541518, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@c4c27a9mSocket: android.net.LocalSocket@638912e impl:android.net.LocalSocketImpl@19e604cf fd:FileDescriptor[82]
08-22 11:15:09.685  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@638912e impl:android.net.LocalSocketImpl@19e604cf fd:FileDescriptor[82]
08-22 11:15:09.685  3222  3294 D BluetoothAdapterProperties: onBluetoothDisable()
08-22 11:15:09.685  3222  3294 D BluetoothAdapterProperties: mDiscovering is false
,08-22 11:15:09.685  1022  4371 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-22 11:15:09.685  3222  3294 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-22 11:15:09.695  4835  4835 D BluetoothPbap: Proxy object disconnected
,08-22 11:15:09.695  4835  4835 D PbapServerProfile: Bluetooth service disconnected
08-22 11:15:09.695  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:09.695  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:09.705  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:09.705  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:09.705  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:09.705  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:09.705  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:09.705  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:09.705  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:09.705  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:09.705  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:09.705  3222  3297 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 11:15:09.705  3222  3297 D BluetoothAdapterProperties: Scan Mode:20
,08-22 11:15:09.705  3222  3294 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-22 11:15:09.705  3222  3294 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-22 11:15:09.705  3222  3294 E bt-btif : cmd socket is not created
08-22 11:15:09.705  3222  5319 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 11:15:09.705  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:09.705  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:09.705  3222  3294 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-22 11:15:09.705  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:09.705  3222  3298 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-22 11:15:09.715  3222  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-22 11:15:09.715  3222  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 11:15:09.715  3222  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-22 11:15:09.715  3222  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 11:15:09.715  3222  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 11:15:09.715  3222  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-22 11:15:09.725  1022  1022 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:09.725  1022  1022 I InputMethodManagerService: [BT Setting State] State =13
,08-22 11:15:09.735  1184  1184 D BluetoothTile:  onBluetoothStateChange:
,08-22 11:15:09.735  1184  1184 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:09.735  1184  1184 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-22 11:15:09.735  1184  1184 D BluetoothTile:  getBluetoothState : 13
08-22 11:15:09.735  1184  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:09.735  1184  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:09.735  1884  1884 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 11:15:09.735  1184  1754 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-22 11:15:09.735  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b169565, channel: 5, state: LISTENING
08-22 11:15:09.735  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3b169565, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@14ca7b71, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3b40923amSocket: android.net.LocalSocket@39e81eeb impl:android.net.LocalSocketImpl@3602f448 fd:FileDescriptor[80]
08-22 11:15:09.735  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@39e81eeb impl:android.net.LocalSocketImpl@3602f448 fd:FileDescriptor[80]
,08-22 11:15:09.745  1022  4369 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:09.745  1022  1141 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 11:15:09.745  4835  4835 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:09.745  3222  3222 I BtOppRfcommListener: stopping Accept Thread
,08-22 11:15:09.745  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1d6022e1, channel: 12, state: LISTENING,
08-22 11:15:09.745  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1d6022e1, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3209473, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@27959806mSocket: android.net.LocalSocket@9a7bec7 impl:android.net.LocalSocketImpl@d770cf4 fd:FileDescriptor[86]
08-22 11:15:09.745  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@9a7bec7 impl:android.net.LocalSocketImpl@d770cf4 fd:FileDescriptor[86]
08-22 11:15:09.745  3222  5319 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-22 11:15:09.745  1184  1184 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 11:15:09.755  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:09.755  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:09.755  3222  3222 V BluetoothOppManager: cleanUp...
,08-22 11:15:09.755  4835  4835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:09.755  1022  1034 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-22 11:15:09.755  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 11:15:09.755  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:09.755  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:09.755  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 11:15:09.765  2652  2652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:09.765  4835  4835 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:09.765  4835  4835 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:09.775  1184  1184 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:09.775  1184  1184 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-22 11:15:09.775  1022  4368 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-22 11:15:09.775  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:09.775  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:09.775  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:09.775  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:09.795  7377  7377 E Zygote  : MountEmulatedStorage(),
,08-22 11:15:09.795  1022  4368 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7377 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-22 11:15:09.795  7377  7377 E Zygote  : v2
08-22 11:15:09.795  7377  7377 I libpersona: KNOX_SDCARD checking this for 10055
08-22 11:15:09.795  7377  7377 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:09.795  7377  7377 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:09.805  7377  7377 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:09.805  7377  7377 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:09.815  1022  1130 D WifiP2pService: InactiveState{ what=143375 }
,08-22 11:15:09.815   278   979 D CommandListener: Clearing all IP addresses on wlan0
,08-22 11:15:09.815  2652  2689 V NativeCrypto: Read error: ssl=0xb8483fc0: I/O error during system call, Connection timed out
,08-22 11:15:09.825   314   314 I art     : Explicit concurrent mark sweep GC freed 8684(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 681us total 24.085ms
08-22 11:15:09.825  2652  2689 V NativeCrypto: SSL shutdown failed: ssl=0xb8483fc0: I/O error during system call, Broken pipe
08-22 11:15:09.825  1022  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
08-22 11:15:09.825  1184  1184 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:09.825  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 11:15:09.825  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-22 11:15:09.825  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.825  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 11:15:09.825  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:09.825  1022  1035 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-22 11:15:09.835  1022  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:09.835  1022  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:09.835  1022  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-22 11:15:09.835  1022  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-22 11:15:09.835  1022  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
08-22 11:15:09.835  1022  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:09.835  1022  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-22 11:15:09.835  1022  1748 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 11:15:09.835  1022  1748 I qtaguid : Tagging socket 379 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1022, getuid(): 1000
08-22 11:15:09.835  1022  1133 E ConnectivityService: updateNetworkInfo()
08-22 11:15:09.835  1022  1133 E ConnectivityService: updateNetworkInfo()
08-22 11:15:09.835  1022  1022 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-22 11:15:09.835   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.938ms
,08-22 11:15:09.845  1022  1131 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-22 11:15:09.845  1022  1130 D WifiP2pService: InactiveState{ what=131204 }
08-22 11:15:09.845  1022  1130 D WifiP2pService: P2pEnabledState{ what=131204 }
08-22 11:15:09.845  1022  1022 D WifiScanningService: SCAN_AVAILABLE : 1
08-22 11:15:09.845  1022  1130 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-22 11:15:09.845  1022  1156 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:09.845  1022  1022 D RttService: SCAN_AVAILABLE : 1
,08-22 11:15:09.845  1022  1157 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 11:15:09.845  1022  1748 I qtaguid : Untagging socket 379
,08-22 11:15:09.855  1022  1748 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 11:15:09.855  1022  1052 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 11:15:09.855  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 11:15:09.855  1022  1052 D WifiDisplayAdapter: onP2pDisconnected
08-22 11:15:09.855  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:09.855  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:09.855  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.855  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.855  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.855  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:09.855  1022  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-22 11:15:09.855  1022  1130 D WifiP2pService: P2pDisablingState
08-22 11:15:09.855  1022  1130 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-22 11:15:09.855  1022  1130 D WifiP2pService: p2p socket connection lost
08-22 11:15:09.855  1022  1131 E WifiNative-wlan0: do suspend true
08-22 11:15:09.855  1022  1130 D WifiP2pService: P2pDisabledState
,08-22 11:15:09.855  1022  1022 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-22 11:15:09.855  7377  7377 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:15:09.855  1022  1130 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-22 11:15:09.855  7377  7377 D ActivityThread: Added TimaKeyStore provider
08-22 11:15:09.855  1022  1130 D WifiP2pService: DefaultState{ what=143375 }
08-22 11:15:09.855   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 20.027ms
,08-22 11:15:09.865  1022  1052 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 11:15:09.865  1022  1052 D IpRemoteDisplayController: WfdBridgeServer is already null
08-22 11:15:09.865  1022  1052 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-22 11:15:09.865  1022  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 11:15:09.865  1022  1052 D WifiDisplayController: disconnect
08-22 11:15:09.865  1022  1052 D WifiDisplayController: updateConnection
08-22 11:15:09.865  1022  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 11:15:09.865  1022  1052 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-22 11:15:09.865  1022  1052 D WifiDisplayAdapter: onP2pDisconnected
08-22 11:15:09.865  1022  1052 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 11:15:09.865  1022  1052 D IpRemoteDisplayController: WfdBridgeServer is already null
08-22 11:15:09.865  1022  1052 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 11:15:09.875  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 11:15:09.875  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:09.875  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:09.875  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.875  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.875  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.875  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.875  1184  1184 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
,08-22 11:15:09.875  1022  1490 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 11:15:09.875  1184  1184 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 11:15:09.895  7377  7377 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-22 11:15:09.905  3222  3294 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-22 11:15:09.905  3222  3294 D BtConfig.SecureMode: isSecureModeOn:false
08-22 11:15:09.905  3222  3294 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-22 11:15:09.905  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-22 11:15:09.905  3222  3294 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-22 11:15:09.905  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-22 11:15:09.905  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-22 11:15:09.905  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-22 11:15:09.905  1022  1141 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:09.905  1022  1141 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-22 11:15:09.905  1022  1141 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:09.905  1022  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:09.905  1022  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 11:15:09.915  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-22 11:15:09.915  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 11:15:09.915  3222  3222 D HeadsetService: Received stop request...Stopping profile...
,08-22 11:15:09.915  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
08-22 11:15:09.915  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService,
,08-22 11:15:09.915  1022  1223 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:09.915  1022  1223 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:09.915  1022  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0,
08-22 11:15:09.915  1022  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:09.915  1022  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 11:15:09.915  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-22 11:15:09.915  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-22 11:15:09.915  4835  4835 D HeadsetProfile: Bluetooth service disconnected,
08-22 11:15:09.915  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-22 11:15:09.915  1022  4367 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:09.915  1022  4367 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 11:15:09.925  1022  4367 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:09.925  1022  4367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:09.925  1022  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:09.925  1022  1022 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-22 11:15:09.925  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-22 11:15:09.925  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-22 11:15:09.925  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-22 11:15:09.925  1022  1491 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:09.925  1022  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:09.925  1022  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:09.925  1022  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0,
08-22 11:15:09.925  1022  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 11:15:09.925  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-22 11:15:09.925  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-22 11:15:09.925  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-22 11:15:09.925  7377  7377 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-22 11:15:09.925  1022  1141 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:09.925  1022  1141 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:09.925  1022  1141 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-22 11:15:09.925  1022  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:09.925  1022  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 11:15:09.925  7377  7377 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-22 11:15:09.925  7377  7377 D UserAnalysis: Create SecureDbHelper
08-22 11:15:09.925   278   975 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 11:15:09.925   278   975 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-22 11:15:09.925   278   979 D CommandListener: Clearing all IP addresses on wlan0
08-22 11:15:09.925  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-22 11:15:09.925  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:09.925  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-22 11:15:09.935  1022  4368 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-22 11:15:09.935  1022  1133 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:09.935  1022  4368 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-22 11:15:09.935  1022  1133 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null,
08-22 11:15:09.935  1022  1133 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-22 11:15:09.935  1022  1133 V NetworkStats: updateIfacesLocked()
08-22 11:15:09.935  1022  4368 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:09.935  1022  1133 V NetworkStats: performPollLocked(flags=0x1),
,08-22 11:15:09.935  1022  4368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:09.935  1022  1133 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 11:15:09.935  1022  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-22 11:15:09.935  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-22 11:15:09.935  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 11:15:09.935  3222  3294 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-22 11:15:09.935  1022  1022 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-22 11:15:09.935  1387  1387 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-22 11:15:09.935  1022  1133 V NetworkStats: performPollLocked() took 5ms
08-22 11:15:09.935  1022  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:09.935  1022  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-22 11:15:09.935  1022  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-22 11:15:09.945  1022  1223 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:09.945  1022  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 11:15:09.945  1022  1223 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:09.945  1022  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:09.945  1022  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:09.945  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:09.945  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:09.945  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:09.945  1022  1133 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-22 11:15:09.945  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:09.945  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:09.945  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService,
08-22 11:15:09.945  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 11:15:09.945  1022  1133 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 11:15:09.945  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 11:15:09.945  1022  1133 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-22 11:15:09.945  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 11:15:09.945  1022  1133 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-22 11:15:09.945  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-22 11:15:09.945  1022  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-22 11:15:09.945  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 11:15:09.945  1022  1130 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-22 11:15:09.945  1184  1708 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-22 11:15:09.945  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-22 11:15:09.945  3222  3294 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-22 11:15:09.945  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-22 11:15:09.945  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:09.945  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-22 11:15:09.945  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 11:15:09.945  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:09.945  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:09.945  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.945  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.945  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.945  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.945  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:09.945  1022  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:09.945  1022  1131 D SecContentProvider2: mCursor = null
08-22 11:15:09.945  3222  3222 D A2dpService: Received stop request...Stopping profile...
08-22 11:15:09.945  3222  3363 D A2dpStateMachine: Exit Disconnected: -1
,08-22 11:15:09.945  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-22 11:15:09.945  1455  1455 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-22 11:15:09.955  1022  1051 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-22 11:15:09.955  4835  4835 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:09.955  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:09.955  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:09.955  7377  7377 D IntelligenceServiceApplication: onCreate()
,08-22 11:15:09.965  1022  1133 D ConnectivityService: nai.networkMonitor.doQuit()
08-22 11:15:09.965  1022  1133 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-22 11:15:09.965  1022  1133 E ConnectivityService: updateNetworkInfo()
,08-22 11:15:09.965  1022  1133 E ConnectivityService: updateNetworkInfo()
08-22 11:15:09.965  1022  1133 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 11:15:09.965  1022  1101 V AlarmManager: waitForAlarm result :4
08-22 11:15:09.965  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:09.965  1022  1131 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
08-22 11:15:09.965  1022  1022 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-22 11:15:09.965  1022  1136 D Tethering: MasterInitialState.processMessage what=3
08-22 11:15:09.965  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 11:15:09.965  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:09.965  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 11:15:09.965  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.965  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.965  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.965  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.965  1184  1184 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:09.965  1184  1184 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-22 11:15:09.965  1184  1184 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:09.965  1184  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-22 11:15:09.965  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:09.965  1022  1051 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-22 11:15:09.965  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:09.965  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:09.965  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:09.965  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:09.965  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:09.965  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:09.965  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:09.965  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:09.965  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:09.965  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:09.975  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:09.975  1022  1128 V NetworkStats: updateIfacesLocked()
08-22 11:15:09.975  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:09.975  1022  1128 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:09.975  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:09.975  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:09.975  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:09.975  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:09.975  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:09.975  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:09.975  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:09.975  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:09.975  1184  1184 D HotspotTile: onReceive : 0, 0
08-22 11:15:09.975  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:09.975  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:09.975  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 11:15:09.975  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:09.975  1184  1184 D StatusBar.NetworkController: EthernetConnected: false
08-22 11:15:09.975  1022  1128 V NetworkStats: performPollLocked() took 3ms
08-22 11:15:09.975  1184  1184 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-22 11:15:09.975  1022  1129 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-22 11:15:09.975  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:09.975  1184  1184 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-22 11:15:09.975  1184  1184 D StatusBar.NetworkController: updateDataNetType()
08-22 11:15:09.975  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:09.975  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:09.975  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:09.975  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:09.975  7377  7377 D IntelligenceServiceApplication: no applications having user consent for prediction
08-22 11:15:09.975  1022  1022 D BluetoothA2dp: Proxy object disconnected
08-22 11:15:09.975  1022  1022 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-22 11:15:09.975  4835  4835 D BluetoothA2dp: Proxy object disconnected
08-22 11:15:09.975  4835  4835 D A2dpProfile: Bluetooth service disconnected
,08-22 11:15:09.975  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 11:15:09.975  1184  1184 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-22 11:15:09.985  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:09.985  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:09.985  1184  1184 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
08-22 11:15:09.985  1184  1184 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 17 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-22 11:15:09.985  1184  1184 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-22 11:15:09.985  1184  1184 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-22 11:15:09.985  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 11:15:09.985  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:09.985  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 11:15:09.985  1022  1047 I ActivityManager: Killing 6874:com.google.android.apps.plus/u0a117 (adj 15): empty #21
08-22 11:15:09.985  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.985  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.985  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.985  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:09.985  1022  1101 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-22 11:15:09.995  3222  3222 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-22 11:15:09.995  3222  3222 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 11:15:09.995  3222  3222 D HidService: Received stop request...Stopping profile...
08-22 11:15:09.995  3222  3222 D HidService: Stopping Bluetooth HidService
08-22 11:15:09.995  3222  3222 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 11:15:09.995  3222  3222 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-22 11:15:09.995  3222  3222 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 11:15:09.995  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:09.995  1022  1022 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-22 11:15:09.995  1022  1022 V AlarmManagerEXT: <AppSync3 Whitelist>
08-22 11:15:09.995  1022  1022 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-22 11:15:09.995  3222  3222 D HealthService: Received stop request...Stopping profile...
08-22 11:15:09.995  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
08-22 11:15:09.995  1022  4371 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-22 11:15:10.005  1184  1184 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-22 11:15:10.005  1184  1184 D KeyguardUpdateMonitor: handleTimeUpdate
,08-22 11:15:10.005  3222  3222 D PanService: Received stop request...Stopping profile...
08-22 11:15:10.005  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:10.005  4835  4835 D BluetoothInputDevice: Proxy object disconnected
08-22 11:15:10.005  4835  4835 D HidProfile: Bluetooth service disconnected
08-22 11:15:10.005  1022  1022 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-22 11:15:10.005  3222  3222 D BluetoothMapService: Received stop request...Stopping profile...
,08-22 11:15:10.005  7377  7377 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-22 11:15:10.005  4835  4835 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 11:15:10.005  4835  4835 D PanProfile: Bluetooth service disconnected
,08-22 11:15:10.005  1184  1184 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-22 11:15:10.015  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:10.015  1184  1184 D SecKeyguardClockView: HomeTimezone(): 1
,08-22 11:15:10.015  3222  3222 D SapService: Received stop request...Stopping profile...
08-22 11:15:10.015  3222  3222 D SapService: Stopping Bluetooth SapService
08-22 11:15:10.015  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:10.015  4835  4835 D BluetoothMap: Proxy object disconnected
08-22 11:15:10.015  4835  4835 D MapProfile: Bluetooth service disconnected
08-22 11:15:10.015  1387  1387 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 11:15:10.015  7377  7377 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-22 11:15:10.025  4835  4835 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,08-22 11:15:10.025  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-22 11:15:10.025  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:10.025  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-22 11:15:10.025  3222  3222 D BluetoothA2dp: Proxy object disconnected
08-22 11:15:10.025  3222  3222 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-22 11:15:10.025  3222  3364 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-22 11:15:10.025  3222  3222 I GKI_LINUX: GKI_exit_task 2 done
08-22 11:15:10.025  3222  3222 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-22 11:15:10.025  4835  4835 D SapProfile: Bluetooth service disconnected
,08-22 11:15:10.025  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-22 11:15:10.025  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 11:15:10.025  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:10.025  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:10.025  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-22 11:15:10.025  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 11:15:10.025  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:10.025  1184  1184 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-22 11:15:10.025  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:10.025  3222  3222 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-22 11:15:10.025  3222  3222 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-22 11:15:10.025  1184  1184 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-22 11:15:10.025  1184  1184 I KeyguardEffectViewController: *** don't update sliding image ***
08-22 11:15:10.025  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-22 11:15:10.025  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 11:15:10.025  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:10.025  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:10.025  3222  3222 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 11:15:10.025  3222  3222 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-22 11:15:10.025  1022  1490 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-22 11:15:10.035  1387  1387 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-22 11:15:10.035  1022  1049 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 11:15:10.035  1022  1049 D Tethering: interfaceStatusChanged p2p0, false
,08-22 11:15:10.035  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-22 11:15:10.035  1022  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 11:15:10.035  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 11:15:10.035  1022  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:10.035  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 11:15:10.035  1022  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:10.035  3222  3222 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-22 11:15:10.035  1022  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:10.035  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-22 11:15:10.035  1022  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:10.035  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 11:15:10.035  3222  3222 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-22 11:15:10.035  3222  3222 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-22 11:15:10.045  7399  7399 E Zygote  : MountEmulatedStorage()
08-22 11:15:10.045  7399  7399 E Zygote  : v2
08-22 11:15:10.045  7399  7399 I libpersona: KNOX_SDCARD checking this for 10105
08-22 11:15:10.045  7399  7399 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:10.045  7399  7399 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:15:10.055  7399  7399 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:10.055  1022  1490 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7399 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-22 11:15:10.055  7399  7399 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 11:15:10.055  3222  3294 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-22 11:15:10.055  3222  3294 D BluetoothAdapterProperties: Setting state to 10
08-22 11:15:10.055  3222  3294 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-22 11:15:10.055  3222  3294 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 11:15:10.055  3222  3294 D BluetoothAdapterService: updateAdapterState state is 10
08-22 11:15:10.055  3222  3294 D BluetoothAdapterService: Autoconnection is available 
08-22 11:15:10.055  3222  3294 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-22 11:15:10.055  3222  3294 I BluetoothAdapterState: Entering OffState
08-22 11:15:10.055  3222  3231 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 11:15:10.065  1387  1387 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-22 11:15:10.065  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:10.065  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:10.065  1387  1387 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-22 11:15:10.065  1387  1387 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-22 11:15:10.065  1387  1387 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-22 11:15:10.065  1387  1387 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-22 11:15:10.065  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:10.065  1022  1136 D Tethering: InitialState.processMessage what=4
,08-22 11:15:10.065  4835  4846 D Bluetoothsap: onBluetoothStateChange: up=false
08-22 11:15:10.065  4835  4846 D Bluetoothsap: Unbinding service...
,08-22 11:15:10.075  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:10.075  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:10.075  1022  1136 E Tethering: No numeric data
08-22 11:15:10.075  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 11:15:10.075  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:10.075  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:10.075  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 11:15:10.075  1022  1136 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 11:15:10.075  1022  1136 D Tethering: clearTetheredNotification()
08-22 11:15:10.075  1776  5505 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:10.075  1776  5505 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:10.085  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:10.085  1022  1128 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:10.085  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:10.085  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:10.085  7399  7399 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:15:10.085  1022  1128 V NetworkStats: performPollLocked() took 4ms
08-22 11:15:10.085  7399  7399 D ActivityThread: Added TimaKeyStore provider
08-22 11:15:10.085  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:10.095  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:10.095  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:10.095  1022  1051 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:10.095  1022  1051 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:10.095  4835  7374 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 11:15:10.095  1184  1184 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 11:15:10.095  1184  1184 D HotspotTile: updateTetherState():false, false
,08-22 11:15:10.095  4835  4846 D BluetoothPbap: onBluetoothStateChange: up=false
,08-22 11:15:10.105  1439  1463 D BluetoothAdapter: onBluetoothStateChange: up=false,
08-22 11:15:10.105  1439  1463 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 11:15:10.105  6740  6740 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 11:15:10.105  1430  3359 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:10.105  1430  3359 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 11:15:10.105  1184  1184 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 11:15:10.115  1184  1184 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 11:15:10.115  1184  1184 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 11:15:10.125  1455  1705 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:10.125  1455  1705 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:10.125  3222  3245 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:10.125  3222  3245 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 11:15:10.125  4835  4849 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-22 11:15:10.135  4835  7374 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:10.135  4835  7374 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:10.135  1022  1051 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 11:15:10.135  6740  6750 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:10.135  6740  6750 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 11:15:10.135  6740  6750 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-22 11:15:10.135  6740  6750 D BluetoothLeAdvertiser: Exit stop advertising
08-22 11:15:10.135  6740  6750 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-22 11:15:10.135  6740  6750 D BluetoothLeScanner: Exiting stopAllScan
08-22 11:15:10.135  2652  2660 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:10.135  2652  2660 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:10.135  1184  2150 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:10.145  1184  2150 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:10.145  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:10.145  4835  4849 D BluetoothMap: onBluetoothStateChange: up=false
,08-22 11:15:10.145  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:10.145  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:10.155  1022  1022 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:10.155  1022  1022 I InputMethodManagerService: [BT Setting State] State =10
08-22 11:15:10.155  1022  1022 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-22 11:15:10.155  1184  1184 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 11:15:10.155  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:10.155  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-22 11:15:10.165  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:10.165  1184  1184 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-22 11:15:10.165  1884  1884 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 11:15:10.165  1184  1184 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:10.165  1184  1184 D BluetoothTile:  getBluetoothState : 10
,08-22 11:15:10.165  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:10.165  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:10.165  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:10.165  4835  4835 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:10.175  1022  4369 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:10.175  1022  1223 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 11:15:10.175  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:10.175  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:10.175  1184  1184 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 11:15:10.175  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:10.175  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:10.175  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:10.175  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:10.175  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:10.175  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:10.175  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:10.175  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:10.175  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:10.175  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 11:15:10.175  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:10.175  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:10.175  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 11:15:10.175  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:10.185  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:10.185  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:10.185  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:10.185  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:10.185  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:10.185  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:10.195  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:10.195  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:10.195  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:10.195  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:10.195  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:10.195  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:10.195  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:10.195  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:10.195  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:10.235   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-22 11:15:10.235   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:10.235  7399  7433 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-22 11:15:10.235   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-22 11:15:10.235   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:10.235  7399  7433 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-22 11:15:10.265  1387  1387 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 11:15:10.325  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:10.325  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-22 11:15:10.325  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:10.325  1387  1387 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-22 11:15:10.405  7103  7177 D Finsky  : [1339] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-22 11:15:10.405  7103  7103 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-22 11:15:10.415   291   291 E SMD     : DCD OFF
,08-22 11:15:10.415  7399  7399 D StrictMode: StrictMode policy violation; ~duration=173 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-22 11:15:10.415  7399  7399 D StrictMode: StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-22 11:15:10.415  7399  7399 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-22 11:15:10.415  7399  7399 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.q.e.b(PG:170)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-22 11:15:10.415  7399  7399 D StrictMode: StrictMode policy violation; ~duration=167 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.q.k.d(PG:583)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.q.e.b(PG:170)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:10.415  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:10.425  7399  7399 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 11:15:10.425  7399  7399 D, StrictMode: 	at java.io.File.exists(File.java:363)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:10.425  7399  7399 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at a,ndroid.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:10.425  7399  7399 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:10.425  7399  7399 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:10.425  1022  1223 I ActivityManager: Killing 7021:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
08-22 11:15:10.425  1022  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-22 11:15:10.425  1022  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-22 11:15:10.435  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 11:15:10.435  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:10.435  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 11:15:10.435  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:10.435  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:10.435  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:10.435  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:10.435  1184  1184 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:10.435  1184  1184 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-22 11:15:10.435  1184  1184 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:10.435  4835  4835 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:10.435  1184  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 11:15:10.435  1776  2209 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 11:15:10.445  1184  1184 D HotspotTile: onReceive : 1, 0
08-22 11:15:10.445  1022  1490 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:10.445  1022  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 11:15:10.445  1022  1490 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:10.445  1022  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:10.445  1022  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 11:15:10.445  1640  1640 I Hs20UtilService: Starting #8
08-22 11:15:10.445  1640  1714 I Hs20UtilService: Message received 5007
08-22 11:15:10.445  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:10.445  4835  4835 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 11:15:10.455  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:10.455  4835  4835 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-22 11:15:10.455  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 11:15:10.455  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 11:15:10.455  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:10.455  4835  4835 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 11:15:10.455  4835  4903 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-22 11:15:10.465  1022  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-22 11:15:10.465  4835  4835 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-22 11:15:10.465  4835  4835 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-22 11:15:10.475  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-22 11:15:10.475  1022  1022 I ApplicationPolicy: updateDataUsageMap
08-22 11:15:10.485  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 11:15:10.485  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:10.485  4835  4835 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 11:15:10.485  4835  4903 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-22 11:15:10.485  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:10.485  1022  1490 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-22 11:15:10.495  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:10.495  7399  7439 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.,
,08-22 11:15:10.495  1022  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:10.495  1022  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:10.495  1022  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:10.495  1022  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:10.515  7444  7444 E Zygote  : MountEmulatedStorage(),
08-22 11:15:10.515  1022  1490 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7444 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-22 11:15:10.515  7444  7444 E Zygote  : v2
08-22 11:15:10.515  7444  7444 I libpersona: KNOX_SDCARD checking this for 10064
08-22 11:15:10.515  7444  7444 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:10.515  7444  7444 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:10.525  7444  7444 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:15:10.525  7444  7444 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:10.535  1022  1226 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:10.535  1022  1226 W ActivityManager: userId = 0, bbcId = -10000,
08-22 11:15:10.535  1022  1226 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:10.535  1022  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-22 11:15:10.545  7444  7444 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:10.545  7444  7444 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:10.555  1022  1046 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:10.555  7444  7444 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-22 11:15:10.565  7444  7444 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:10.575  7444  7444 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected,
,08-22 11:15:10.605  7444  7444 D FileShare-Client: Outbound.stopDelayTimer - ,
08-22 11:15:10.605  1022  4368 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-22 11:15:10.605  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:10.605  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:10.605  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:10.605  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:10.615  7461  7461 E Zygote  : MountEmulatedStorage(),
08-22 11:15:10.615  1022  4368 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7461 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 11:15:10.615  7461  7461 E Zygote  : v2
,08-22 11:15:10.615  7461  7461 I libpersona: KNOX_SDCARD checking this for 10065
08-22 11:15:10.615  7461  7461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:10.615  7461  7461 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:10.625  1022  4368 I ActivityManager: Killing 7002:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-22 11:15:10.625  7461  7461 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:10.625  7461  7461 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:10.645  7461  7461 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:10.645  7461  7461 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:10.665  7461  7461 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:10.665  1022  1226 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:10.665  1022  1226 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:10.665  1022  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-22 11:15:10.665  1022  1226 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-22 11:15:10.675  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:10.675  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:10.675  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:10.675  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:10.695  7477  7477 E Zygote  : MountEmulatedStorage(),
08-22 11:15:10.695  7477  7477 E Zygote  : v2
08-22 11:15:10.695  7477  7477 I libpersona: KNOX_SDCARD checking this for 10102
08-22 11:15:10.695  7477  7477 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:10.695  7477  7477 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:10.695  7477  7477 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-22 11:15:10.695  1022  1226 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7477 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-22 11:15:10.695  7477  7477 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 11:15:10.705  1022  1226 I ActivityManager: Killing 7050:com.sec.pcw.device/1000 (adj 15): empty #21,
,08-22 11:15:10.725  7477  7477 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:10.725  7477  7477 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:10.735  7477  7477 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-22 11:15:10.925  7477  7497 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-22 11:15:10.925  7477  7497 I Babel_SMS: MmsConfig.loadMmsSettings
08-22 11:15:10.925  7477  7497 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-22 11:15:10.925  7477  7497 I Babel_SMS: MmsConfig.loadFromDatabase
,08-22 11:15:10.955  7477  7497 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-22 11:15:10.955  7477  7497 I Babel_SMS: MmsConfig.loadFromResources
,08-22 11:15:10.955  7477  7497 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-22 11:15:10.955  7477  7497 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-22 11:15:10.975  1022  4369 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-22 11:15:10.975  1022  4369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-22 11:15:10.975  1022  4369 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:10.975  1022  4369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:10.975  1022  4369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-22 11:15:10.995  7477  7477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 11:15:10.995  7477  7477 I Babel_Crash: startup - clean
,08-22 11:15:11.015  1022  1049 D Tethering: interfaceRemoved wlan0
,08-22 11:15:11.015  1022  1049 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-22 11:15:11.035  1022  4368 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 11:15:11.035  1022  4368 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:11.035  1022  4368 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:11.035  1022  4368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.035  1022  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:11.045  1640  1640 I Hs20UtilService: Starting #9
08-22 11:15:11.045  4835  4835 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 11:15:11.045  4835  4835 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:11.045  1640  1714 I Hs20UtilService: Message received 5007
08-22 11:15:11.045  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 11:15:11.045  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 11:15:11.045  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:11.045  4835  4835 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 11:15:11.045  7477  7477 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 11:15:11.045  4835  4903 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 11:15:11.055  7477  7477 W AudioCapabilities: Unsupported mime audio/evrc
,08-22 11:15:11.055  1022  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:11.055  1022  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:11.055  1022  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:11.055  1022  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.055  1022  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:11.055  7477  7477 W AudioCapabilities: Unsupported mime audio/qcelp
,08-22 11:15:11.055  1022  4367 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-22 11:15:11.055  1640  1640 I Hs20UtilService: Starting #10
,08-22 11:15:11.055  1640  1714 I Hs20UtilService: Message received 5011
,08-22 11:15:11.055  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.055  7477  7477 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-22 11:15:11.055  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.055  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.055  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:11.055  7477  7477 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-22 11:15:11.065  7477  7477 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-22 11:15:11.065  7477  7477 W AudioCapabilities: Unsupported mime audio/x-ima
,08-22 11:15:11.065  7477  7477 W AudioCapabilities: Unsupported mime audio/qcelp,
,08-22 11:15:11.065  7500  7500 E Zygote  : MountEmulatedStorage()
,08-22 11:15:11.065  7500  7500 E Zygote  : v2
08-22 11:15:11.065  7500  7500 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:15:11.065  7500  7500 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:11.065  1022  4367 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7500 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 11:15:11.075  7477  7477 W AudioCapabilities: Unsupported mime audio/evrc
,08-22 11:15:11.085  7500  7500 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:11.085  7500  7500 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:15:11.085  7500  7500 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:11.095  7477  7477 W VideoCapabilities: Unsupported mime video/wvc1
,08-22 11:15:11.095  7477  7477 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-22 11:15:11.115  7500  7500 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:11.115  7500  7500 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:11.125  7477  7477 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-22 11:15:11.125  7477  7477 W VideoCapabilities: Unsupported mime video/wvc1
,08-22 11:15:11.125  7477  7477 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-22 11:15:11.135  7477  7477 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-22 11:15:11.135  7477  7477 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-22 11:15:11.135  7477  7477 W VideoCapabilities: Unsupported mime video/mp43
,08-22 11:15:11.135  7477  7477 W VideoCapabilities: Unsupported mime video/sorenson,
,08-22 11:15:11.145  7477  7477 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-22 11:15:11.155  1022  1049 D Tethering: interfaceRemoved p2p0
08-22 11:15:11.155  1022  1049 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-22 11:15:11.155  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 11:15:11.155  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-22 11:15:11.155  7500  7500 D SecurityLogAgent: StateMachine : Current State = 1
,08-22 11:15:11.165  7500  7500 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 11:15:11.165  1022  1490 I ActivityManager: Killing 7040:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-22 11:15:11.165  1022  1329 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:11.165  1022  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.165  1022  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.175  7477  7477 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-22 11:15:11.175  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:11.175  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.175  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.175  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:11.175  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.175  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.175  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:11.175  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.175  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.185  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:11.185  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.185  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.185  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:11.185  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.185  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.185  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:11.185  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.185  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.195  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:11.195  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.195  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.195  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:11.195  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.195  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.195  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:11.195  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:11.195  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.195  7477  7477 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 11:15:11.205  7477  7477 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 11:15:11.205  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:11.205  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.205  7477  7477 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 11:15:11.205  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.205  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:11.205  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.205  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.205  7477  7477 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 11:15:11.205  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:11.205  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.205  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.215  1022  1223 I ActivityManager: Killing 7120:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-22 11:15:11.215  7477  7477 I vclib   : onServiceConnected
,08-22 11:15:11.215  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:11.215  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.215  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.215  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:11.215  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.215  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:11.225  4835  4835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:11.225  1022  1141 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-22 11:15:11.225  1022  1141 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 11:15:11.225  1022  1141 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:11.225  1022  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.225  1022  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 11:15:11.235  2652  2652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:11.235  4835  4835 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:11.235  4835  4835 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:11.245  1184  1184 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
08-22 11:15:11.245  1184  1184 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-22 11:15:11.265  1022  4369 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 11:15:11.265  1022  4369 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:11.265  1022  4369 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:11.265  1022  4369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.265  1022  4369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:11.265  1640  1640 I Hs20UtilService: Starting #11
,08-22 11:15:11.265  1640  1714 I Hs20UtilService: Message received 5011
,08-22 11:15:11.265  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 11:15:11.265  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 11:15:11.265  7500  7500 D SecurityLogAgent: StateMachine : Current State = 1
08-22 11:15:11.265  7500  7500 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 11:15:11.275  1022  4369 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-22 11:15:11.275  1022  4369 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.275  1022  4369 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.275  1022  4369 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.275  1022  4369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:11.285  7518  7518 E Zygote  : MountEmulatedStorage()
08-22 11:15:11.285  7518  7518 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:15:11.285  7518  7518 E Zygote  : v2
08-22 11:15:11.285  7518  7518 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:11.285  7518  7518 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:11.285  1022  4369 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7518 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 11:15:11.285  7518  7518 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:11.285  7518  7518 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:11.305  7518  7518 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:11.305  7518  7518 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:11.325  7518  7518 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-22 11:15:11.325  7518  7518 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-22 11:15:11.325  7518  7518 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-22 11:15:11.335  7518  7518 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-22 11:15:11.335  7518  7518 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-22 11:15:11.335  7518  7518 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-22 11:15:11.335  7518  7518 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:11.345  1022  1141 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-22 11:15:11.345  1022  1141 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-22 11:15:11.345  1022  1141 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-22 11:15:11.345  1022  1141 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-22 11:15:11.345  1022  1141 I ActivityManager: Killing 7138:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-22 11:15:11.345  7518  7533 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-22 11:15:11.355  1022  1022 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-22 11:15:11.355  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:11.355  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.355  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.355  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:11.375  7535  7535 E Zygote  : MountEmulatedStorage(),
08-22 11:15:11.375  1022  1022 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7535 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 11:15:11.375  7535  7535 E Zygote  : v2
08-22 11:15:11.375  7535  7535 I libpersona: KNOX_SDCARD checking this for 10001
08-22 11:15:11.375  7535  7535 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:11.375  7535  7535 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:11.375  7535  7535 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:11.375  7535  7535 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:11.405  7535  7535 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:11.405  7535  7535 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:11.425   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:15:11.495  1022  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-22 11:15:11.495  1022  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:11.495  1022  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.495  1022  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.505  1022  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:11.515  1022  1491 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7553 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 11:15:11.515  7553  7553 E Zygote  : MountEmulatedStorage()
08-22 11:15:11.515  7553  7553 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:15:11.515  7553  7553 E Zygote  : v2
08-22 11:15:11.515  7553  7553 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:11.515  7553  7553 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:11.515  1022  1491 I ActivityManager: Killing 7087:com.android.mms/u0a41 (adj 15): empty #21
,08-22 11:15:11.515  7553  7553 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:11.525  7553  7553 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:11.545  7553  7553 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:11.545  7553  7553 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:11.595  7553  7553 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-22 11:15:11.635  1022  4367 D CountryDetector: No listener is left
,08-22 11:15:11.725  7553  7553 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-22 11:15:11.735  7553  7553 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-22 11:15:11.745  7553  7553 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:11.745  7553  7553 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-22 11:15:11.745  7553  7553 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-22 11:15:11.745  7553  7553 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-22 11:15:11.745  1022  1226 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-22 11:15:11.745  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:11.745  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.745  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.745  1022  1226 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:11.765  1022  1226 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7569 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-22 11:15:11.765  7569  7569 E Zygote  : MountEmulatedStorage()
08-22 11:15:11.765  7569  7569 I libpersona: KNOX_SDCARD checking this for 10008
08-22 11:15:11.765  7569  7569 E Zygote  : v2
08-22 11:15:11.765  7569  7569 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:11.765  7569  7569 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:11.765  1022  1226 I ActivityManager: Killing 7191:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-22 11:15:11.765  7569  7569 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:11.765  7569  7569 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-22 11:15:11.785  7569  7569 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:11.785  7569  7569 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:11.875  1022  1486 I ActivityManager: Killing 7211:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-22 11:15:11.875  1022  4369 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:11.875  1022  4369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-22 11:15:11.875  1022  4369 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:11.875  1022  4369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:11.875  1022  4369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:11.915  3823  7584 I iu.SyncManager: SYNC; picasa accounts
,08-22 11:15:11.915  3823  3823 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-22 11:15:11.925  1022  1223 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 11:15:11.935  1022  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
08-22 11:15:11.935  1022  1223 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-22 11:15:11.935  1022  1223 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:11.935  1022  1223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 11:15:11.935  1022  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:11.945  3823  3823 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 11:15:11.945  3823  3823 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-22 11:15:11.965  2846  2846 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 22 11:15:11 GMT+02:00 2016
,08-22 11:15:11.975  1022  4370 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-22 11:15:11.975  1022  4370 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-22 11:15:11.975  1022  4370 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:11.975  1022  4370 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:11.975  1022  4370 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-22 11:15:11.985  2846  2846 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-22 11:15:11.985  2846  2846 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-22 11:15:11.995  2846  2846 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-22 11:15:11.995  1022  4367 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-22 11:15:11.995  2846  2846 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-22 11:15:11.995  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.995  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.995  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:11.995  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.005  2846  7586 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-22 11:15:12.005  2846  7586 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-22 11:15:12.005  2846  7586 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-22 11:15:12.015  7587  7587 E Zygote  : MountEmulatedStorage()
08-22 11:15:12.015  7587  7587 E Zygote  : v2
08-22 11:15:12.015  7587  7587 I libpersona: KNOX_SDCARD checking this for 10031
08-22 11:15:12.015  7587  7587 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:12.015  7587  7587 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:12.015  1022  4367 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7587 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-22 11:15:12.015  7587  7587 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:12.015  7587  7587 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:12.015  2846  7586 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-22 11:15:12.025  2846  2846 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-22 11:15:12.035  7587  7587 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:12.035  7587  7587 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:12.065  7587  7587 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-22 11:15:12.085  1022  4371 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-22 11:15:12.085  1022  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.085  1022  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:12.085  1022  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:12.085  1022  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.085  2784  7602 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-22 11:15:12.095  2784  7602 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-22 11:15:12.095  2784  7602 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-22 11:15:12.095  7603  7603 E Zygote  : MountEmulatedStorage(),
08-22 11:15:12.095  7603  7603 E Zygote  : v2
08-22 11:15:12.095  7603  7603 I libpersona: KNOX_SDCARD checking this for 10032
,08-22 11:15:12.095  7603  7603 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:12.095  7603  7603 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:12.095  1022  4371 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7603 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-22 11:15:12.095  7603  7603 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:12.105  2784  7602 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0,
,08-22 11:15:12.105  2784  7602 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-22 11:15:12.105  7603  7603 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-22 11:15:12.125   314   314 I art     : Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 621us total 27.377ms,
,08-22 11:15:12.135  7603  7603 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:15:12.135  1022  1486 I art     : Explicit concurrent mark sweep GC freed 55732(3MB) AllocSpace objects, 11(224KB) LOS objects, 33% free, 22MB/34MB, paused 2.461ms total 181.038ms
,08-22 11:15:12.135  7603  7603 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:12.145   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 627us total 16.757ms
,08-22 11:15:12.155  1022  4367 I ActivityManager: Killing 6840:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-22 11:15:12.155   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 16.842ms
,08-22 11:15:12.195  7603  7618 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-22 11:15:12.195  7603  7618 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-22 11:15:12.205  7603  7603 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-22 11:15:12.205  7603  7618 D SPPClientService: PushLog.txt file is not deleted.
,08-22 11:15:12.205  7603  7618 D SPPClientService: PushLog.txt file is not deleted.
08-22 11:15:12.205  7603  7618 D SPPClientService: ============PushLog. stop!
,08-22 11:15:12.205  1022  4368 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-22 11:15:12.205  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.205  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:12.205  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:12.205  1022  4368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.225  7620  7620 E Zygote  : MountEmulatedStorage(),
08-22 11:15:12.225  7620  7620 E Zygote  : v2
08-22 11:15:12.225  7620  7620 I libpersona: KNOX_SDCARD checking this for 10036,
08-22 11:15:12.225  7620  7620 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:12.225  7620  7620 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:15:12.225  7620  7620 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:12.225  1022  4368 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7620 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 11:15:12.225  1022  4368 I ActivityManager: Killing 7245:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-22 11:15:12.225  7620  7620 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-22 11:15:12.235  1022  1491 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-22 11:15:12.235  1022  1491 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:12.235  1022  1491 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-22 11:15:12.235  1022  1491 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-22 11:15:12.235  1022  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-22 11:15:12.255  7620  7620 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:12.255  7620  7620 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:12.265  7603  7628 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-22 11:15:12.295  7620  7620 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@288f35b1
,08-22 11:15:12.305  7620  7620 I SA      : [SSP] onCreated
,08-22 11:15:12.315  7620  7620 I SA      : [TPM] There is no property file
,08-22 11:15:12.315  7620  7620 I SA      : [SCU] isHaveSA() - false
,08-22 11:15:12.315  7620  7620 I SA      : [TPM] getModelProperty : null
,08-22 11:15:12.315  7620  7620 I SA      : [TPM] getCSCProperty : null
,08-22 11:15:12.315  7620  7620 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-22 11:15:12.315  7620  7620 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-22 11:15:12.315  7620  7620 I SA      : [DM] TFT FEATURE: false
,08-22 11:15:12.325  7620  7620 I SA      : [DM] init START
,08-22 11:15:12.325  7620  7620 I SA      : [DM] This device is not a Vodafone
,08-22 11:15:12.325  7620  7620 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-22 11:15:12.325  7620  7620 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-22 11:15:12.325  7620  7620 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-22 11:15:12.335  7620  7620 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-22 11:15:12.335  7620  7620 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-22 11:15:12.335  7620  7620 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-22 11:15:12.335  7620  7620 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-22 11:15:12.335  7620  7620 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-22 11:15:12.335  7620  7620 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-22 11:15:12.335  7620  7620 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-22 11:15:12.335  7620  7620 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-22 11:15:12.335  7620  7620 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-22 11:15:12.335  7620  7620 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-22 11:15:12.345  7620  7620 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-22 11:15:12.355  7620  7620 I SA      : [SCU] isHaveSA() - false
08-22 11:15:12.355  7620  7620 I SA      : support phone number id : false
08-22 11:15:12.355  7620  7620 I SA      : [DM] Supports Ref Jpn : true
,08-22 11:15:12.355  7620  7620 I SA      : [DM] init END
,08-22 11:15:12.355  7620  7620 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-22 11:15:12.355  7620  7620 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-22 11:15:12.355  7620  7620 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-22 11:15:12.365  7620  7620 I SA      : [SLFUCHKMGR] constructor called
,08-22 11:15:12.365  7620  7620 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-22 11:15:12.365  7620  7620 I SA      : [OR] == isSIMCardReady false ==
,08-22 11:15:12.375  7620  7620 I SA      : [SCU] == networkStateCheck == false
,08-22 11:15:12.375  7620  7620 I SA      : [OR] onReceive END
,08-22 11:15:12.375  1022  1226 I ActivityManager: Killing 7264:com.wsomacp/u0a23 (adj 15): empty #21
,08-22 11:15:12.375  1236  1236 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:12.385  1789  1789 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-22 11:15:12.395  2635  2649 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-22 11:15:12.395  1789  1789 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-22 11:15:12.395  1789  1789 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-22 11:15:12.395  1789  1789 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-22 11:15:12.395  1789  1789 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-22 11:15:12.405  1789  1789 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-22 11:15:12.405  1789  1789 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-22 11:15:12.405  1022  1223 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-22 11:15:12.405  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.405  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:12.405  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.405  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.415  7642  7642 E Zygote  : MountEmulatedStorage()
08-22 11:15:12.415  1022  1223 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7642 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 11:15:12.415  7642  7642 E Zygote  : v2
08-22 11:15:12.415  7642  7642 I libpersona: KNOX_SDCARD checking this for 10077
08-22 11:15:12.415  7642  7642 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:12.415  7642  7642 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:12.425   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 11:15:12.425  7642  7642 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:15:12.425  7642  7642 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-22 11:15:12.435  7642  7642 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:12.445  7642  7642 D ActivityThread: Added TimaKeyStore provider,
,08-22 11:15:12.615  1022  1035 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-22 11:15:12.615  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-22 11:15:12.625  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:12.625  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:12.625  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-22 11:15:12.625  1022  1141 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-22 11:15:12.625  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.625  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:12.625  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:12.625  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.635  7660  7660 E Zygote  : MountEmulatedStorage(),
08-22 11:15:12.635  7660  7660 E Zygote  : v2
08-22 11:15:12.635  7660  7660 I libpersona: KNOX_SDCARD checking this for 10110
08-22 11:15:12.635  7660  7660 I libpersona: KNOX_SDCARD not a persona,
08-22 11:15:12.645  7660  7660 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:12.645  1022  1141 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7660 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 11:15:12.645  1022  1486 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-22 11:15:12.645  1022  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-22 11:15:12.645  7660  7660 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:12.645  1022  1486 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:12.645  1022  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:12.645  1022  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-22 11:15:12.645  7660  7660 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-22 11:15:12.645  7477  7659 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-22 11:15:12.655  1022  1490 I ActivityManager: Killing 7316:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-22 11:15:12.675  7660  7660 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:12.675  7660  7660 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:12.685  1022  4369 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 11:15:12.685  1022  4369 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-22 11:15:12.685  1022  4369 D SecContentProvider2: mCursor = null
,08-22 11:15:12.685  1022  4369 D WifiService: setWifiEnabled: true pid=6740, uid=10170
,08-22 11:15:12.685  1022  4369 W ActivityManager: Permission Denial: getCurrentUser() from pid=6740, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-22 11:15:12.685  1022  4369 W WifiService: Failed getting userId using ActivityManagerNative
08-22 11:15:12.685  1022  4369 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6740, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-22 11:15:12.685  1022  4369 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 11:15:12.685  1022  4369 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-22 11:15:12.685  1022  4369 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-22 11:15:12.685  1022  4369 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-22 11:15:12.685  1022  4369 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 11:15:12.685  1022  4369 D SettingsProvider: name = wifi_on,
,08-22 11:15:12.695  1022  1131 E WifiHW  : ##################### set firmware type 0 #####################,
,08-22 11:15:12.845  1022  1035 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 11:15:12.975   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-22 11:15:12.975   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
08-22 11:15:12.975  7660  7679 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-22 11:15:12.985   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-22 11:15:12.985   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:12.985  7660  7679 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-22 11:15:12.985  7660  7660 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-22 11:15:12.985  7660  7660 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-22 11:15:12.985  7660  7660 I GAv4    :   adb logcat -s GAv4
,08-22 11:15:12.995   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-22 11:15:12.995   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:12.995  7660  7686 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-22 11:15:12.995   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-22 11:15:12.995   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:12.995  7660  7686 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-22 11:15:13.005  7660  7660 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-22 11:15:13.015  1022  4370 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 11:15:13.025  7660  7660 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-22 11:15:13.025  7660  7688 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-22 11:15:13.125  1022  1049 D Tethering: interfaceAdded wlan0
,08-22 11:15:13.135  1022  1136 E Tethering: No numeric data
08-22 11:15:13.135  1022  1136 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 11:15:13.135  1022  1136 D Tethering: clearTetheredNotification()
,08-22 11:15:13.135  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false,
08-22 11:15:13.135  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:13.135  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:13.135  1022  1136 D Tethering: InitialState.processMessage what=4,
,08-22 11:15:13.135  1022  1136 E Tethering: No numeric data
08-22 11:15:13.135  1022  1136 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 11:15:13.135  1022  1136 D Tethering: clearTetheredNotification()
,08-22 11:15:13.145  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:13.145  1022  1128 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:13.145  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:13.145  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 11:15:13.145  1184  1184 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 11:15:13.145  1184  1184 D HotspotTile: updateTetherState():false, false
08-22 11:15:13.145  1022  1049 D Tethering: interfaceAdded p2p0
08-22 11:15:13.145  1022  1049 D Tethering: p2p0 is not a tetherable iface, ignoring
08-22 11:15:13.145   278   979 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-22 11:15:13.145   278   979 D SoftapController: Softap fwReload - Ok
,08-22 11:15:13.145  1022  1049 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 11:15:13.145  1022  1049 D Tethering: interfaceStatusChanged p2p0, false
,08-22 11:15:13.145  1022  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 11:15:13.145  1022  1128 V NetworkStats: performPollLocked() took 7ms
,08-22 11:15:13.145  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:13.145   278   979 D CommandListener: Setting iface cfg
08-22 11:15:13.145   278   979 D CommandListener: Trying to bring down wlan0
,08-22 11:15:13.145   278   979 D CommandListener: Clearing all IP addresses on wlan0
08-22 11:15:13.155  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:13.155  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:13.155  1022  1131 E WifiHW  : supplicant_name : p2p_supplicant,
,08-22 11:15:13.205  7691  7691 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-22 11:15:13.205  7691  7691 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-22 11:15:13.205  7691  7691 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-22 11:15:13.235  7691  7691 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-22 11:15:13.245   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7691
08-22 11:15:13.245   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,08-22 11:15:13.245  7691  7691 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-22 11:15:13.245  7691  7691 I wpa_supplicant: ssSupport state is = 1
08-22 11:15:13.245  7691  7691 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-22 11:15:13.245  7691  7691 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-22 11:15:13.245   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7691
08-22 11:15:13.245   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-22 11:15:13.255  1022  1131 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-22 11:15:13.275  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 11:15:13.275  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:13.275  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 11:15:13.275  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:13.275  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:13.275  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:13.275  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:13.275  1184  1184 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:13.275  1184  1184 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:13.275  1184  1184 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-22 11:15:13.275  1184  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 11:15:13.275  4835  4835 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:13.275  1184  1184 D HotspotTile: onReceive : 2, 0
,08-22 11:15:13.275  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:13.285  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-22 11:15:13.325  1022  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:13.325  1022  1490 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.325  1022  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:13.325  1022  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-22 11:15:13.365  7660  7660 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-22 11:15:13.385  7660  7660 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 5944-5946)
,08-22 11:15:13.385  7660  7660 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-22 11:15:13.405  7660  7660 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {60c6f30}
,08-22 11:15:13.405  7660  7660 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-22 11:15:13.405  7660  7660 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-22 11:15:13.415   291   291 E SMD     : DCD OFF,
,08-22 11:15:13.425  7660  7660 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-22 11:15:13.425  7660  7660 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 11:15:13.425   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:15:13.425  7660  7660 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-22 11:15:13.435   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-22 11:15:13.435  7691  7691 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-22 11:15:13.445  7660  7660 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-22 11:15:13.445  7660  7660 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 11:15:13.445  7660  7660 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 11:15:13.445  7660  7660 I Adreno-EGL: Local Branch: 
08-22 11:15:13.445  7660  7660 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 11:15:13.445  7660  7660 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 11:15:13.445  7660  7660 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-22 11:15:13.455  1022  4367 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-22 11:15:13.455  1022  4367 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4246, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-22 11:15:13.455  1022  4367 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-22 11:15:13.455  1022  4367 D BatteryService: stay LED for charging
,08-22 11:15:13.455  1022  1022 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 11:15:13.455  1022  1022 I MotionRecognitionService: Plugged
08-22 11:15:13.455  1022  1022 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 11:15:13.465  1184  1184 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 11:15:13.465  1184  1184 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 11:15:13.465  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-22 11:15:13.465  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 11:15:13.485  7691  7691 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-22 11:15:13.485  7691  7691 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-22 11:15:13.485  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-22 11:15:13.485  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-22 11:15:13.485  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 11:15:13.495  7691  7691 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-22 11:15:13.495   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7691
08-22 11:15:13.495   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-22 11:15:13.495  7691  7691 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-22 11:15:13.495  7691  7691 I wpa_supplicant: ssSupport state is = 1
,08-22 11:15:13.495  7691  7691 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-22 11:15:13.495  7691  7691 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 11:15:13.495  7691  7691 E wpa_supplicant: SIM READ ERROR,
08-22 11:15:13.495  7691  7691 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:13.495  7691  7691 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 11:15:13.495  7691  7691 E wpa_supplicant: SIM READ ERROR
08-22 11:15:13.495  7691  7691 I wpa_supplicant: Blacklist: Clear (all) 
08-22 11:15:13.495  7691  7691 I wpa_supplicant: wpa_default_ap_write_once,
08-22 11:15:13.495  7691  7691 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-22 11:15:13.495  7691  7691 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:13.495  7691  7691 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-22 11:15:13.495  7691  7691 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:13.495  7691  7691 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,08-22 11:15:13.505  7691  7691 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-22 11:15:13.505  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:13.505  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:13.505  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:13.515  7660  7660 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 11:15:13.525  7660  7660 I NSApplication: Starting up...
,08-22 11:15:13.525  1022  4369 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 11:15:13.535  1022  1226 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 11:15:13.535  7660  7720 W cr.media: Requires BLUETOOTH permission,
,08-22 11:15:13.545  1022  1486 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-22 11:15:13.545  1022  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:13.545  1022  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:13.545  1022  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:13.545  1022  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:13.555  7725  7725 E Zygote  : MountEmulatedStorage()
,08-22 11:15:13.555  7725  7725 E Zygote  : v2
08-22 11:15:13.555  7725  7725 I libpersona: KNOX_SDCARD checking this for 10117
08-22 11:15:13.555  7725  7725 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:13.555  7725  7725 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:15:13.565  7691  7691 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-22 11:15:13.565  1022  1486 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7725 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-22 11:15:13.565  1022  1486 I ActivityManager: Killing 7280:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
08-22 11:15:13.565  7725  7725 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:13.565  7725  7725 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-22 11:15:13.595  7725  7725 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:15:13.595  7725  7725 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:13.605  7725  7725 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 11:15:13.835  7691  7691 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-22 11:15:13.835  7691  7691 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-22 11:15:13.855  7691  7691 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-22 11:15:13.855   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7691
08-22 11:15:13.855   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-22 11:15:13.855  7691  7691 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-22 11:15:13.855  7691  7691 I wpa_supplicant: ssSupport state is = 1
,08-22 11:15:13.855  7691  7691 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-22 11:15:13.855  7691  7691 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-22 11:15:13.865  7691  7691 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-22 11:15:13.865   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7691
08-22 11:15:13.865   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-22 11:15:13.865  7691  7691 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-22 11:15:13.865  7691  7691 I wpa_supplicant: ssSupport state is = 1
08-22 11:15:13.865  7691  7691 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:13.865  7691  7691 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 11:15:13.865  7691  7691 E wpa_supplicant: SIM READ ERROR
08-22 11:15:13.865  7691  7691 I wpa_supplicant: wpa_default_ap_write_once
08-22 11:15:13.865  7691  7691 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-22 11:15:13.865  7691  7691 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-22 11:15:13.875  1022  1049 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 11:15:13.875  1022  1049 D Tethering: interfaceStatusChanged p2p0, false
,08-22 11:15:13.875  1022  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-22 11:15:13.875  1022  1049 D Tethering: interfaceLinkStateChanged p2p0, false
,08-22 11:15:13.875  1022  1049 D Tethering: interfaceStatusChanged p2p0, false
08-22 11:15:13.875  1022  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-22 11:15:13.945  7691  7691 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-22 11:15:13.945  7691  7691 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-22 11:15:13.955  1022  1141 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-22 11:15:13.955  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:13.955  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:13.955  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:13.955  1022  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:13.965  7748  7748 E Zygote  : MountEmulatedStorage(),
08-22 11:15:13.965  7748  7748 E Zygote  : v2
08-22 11:15:13.965  7748  7748 I libpersona: KNOX_SDCARD checking this for 10121
08-22 11:15:13.965  7748  7748 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:13.965  7748  7748 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:15:13.975  1022  1141 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7748 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-22 11:15:13.975  1022  1141 I ActivityManager: Killing 7295:com.android.calendar/u0a131 (adj 15): empty #21
08-22 11:15:13.975  7748  7748 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:15:13.975  7748  7748 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:13.995  7748  7748 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:13.995  7748  7748 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:14.005  7748  7748 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:15:14.005  7748  7748 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 11:15:14.005  7748  7748 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 11:15:14.015  7748  7748 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:14.025  7748  7748 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-22 11:15:14.025  7748  7748 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-22 11:15:14.025  1022  1223 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-22 11:15:14.025  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:14.025  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:14.025  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:14.025  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:14.045  7765  7765 E Zygote  : MountEmulatedStorage(),
08-22 11:15:14.045  7765  7765 I libpersona: KNOX_SDCARD checking this for 10141
08-22 11:15:14.045  7765  7765 E Zygote  : v2
08-22 11:15:14.045  7765  7765 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:14.045  7765  7765 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:14.045  1022  1223 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7765 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-22 11:15:14.045  7691  7691 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-22 11:15:14.045  1022  1223 I ActivityManager: Killing 7228:com.android.defcontainer/u0a3 (adj 15): empty #21
08-22 11:15:14.045  7691  7691 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-22 11:15:14.045  7691  7691 I wpa_supplicant: Skip scan - bUseNetwork false
08-22 11:15:14.045  7765  7765 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:14.045  7765  7765 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:15:14.045  1022  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-22 11:15:14.045  1022  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-22 11:15:14.055  7691  7691 I wpa_supplicant: HOTSPOT20_ENABLE called
08-22 11:15:14.055  7691  7691 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-22 11:15:14.055  7691  7691 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 11:15:14.055  7691  7691 E wpa_supplicant: SIM READ ERROR
08-22 11:15:14.055  7691  7691 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 11:15:14.065  7765  7765 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:14.065  7765  7765 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:14.075  7691  7691 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-22 11:15:14.085  7691  7691 I wpa_supplicant: Skip scan - bUseNetwork false
,08-22 11:15:14.085  1022  1131 D WifiConfigStore: Loading config and enabling all networks 
,08-22 11:15:14.085  7765  7765 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-22 11:15:14.085  7765  7765 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:15:14.085  7765  7765 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:15:14.085  7765  7765 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-22 11:15:14.095  4835  4835 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:14.095  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 11:15:14.095  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:14.095  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:14.095  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:14.095  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:14.095  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:14.095  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:14.095  1184  1184 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:14.095  1184  1184 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-22 11:15:14.105  1184  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 11:15:14.105  1184  1184 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:14.105  1184  1184 D HotspotTile: onReceive : 3, 0
,08-22 11:15:14.105  1022  1131 E WifiConfigStore: Not a HS20
,08-22 11:15:14.105  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:14.105  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:14.105  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:14.105  1022  1131 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-22 11:15:14.105  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:14.105  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:14.115  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:14.115  1022  1131 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-22 11:15:14.115  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 11:15:14.115  7691  7691 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-22 11:15:14.115  7691  7691 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-22 11:15:14.115  7691  7691 I wpa_supplicant: reset timer : RESET_TIMER 0
,08-22 11:15:14.115  7691  7691 I wpa_supplicant: P2P: Current p2p state = IDLE
08-22 11:15:14.115  7691  7691 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-22 11:15:14.115  7691  7691 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,08-22 11:15:14.115  7691  7691 I wpa_supplicant: First Scan Start
08-22 11:15:14.115  7691  7691 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-22 11:15:14.115  1022  1131 D WifiNative-wlan0: Setting external_sim to 1
08-22 11:15:14.115  1022  1131 D WifiStateMachine: Setting OUI to DA-A1-19
08-22 11:15:14.115  1022  1131 I WifiNative-HAL: startHal,
08-22 11:15:14.115  1022  1131 E wifi    : getStaticLongField sWifiHalHandle 0x9ef3e88c
08-22 11:15:14.115  1022  1131 I WifiNative-HAL: Could not start hal
,08-22 11:15:14.115  7477  7477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 11:15:14.115  1022  1131 E WifiNative-wlan0: do suspend true
,08-22 11:15:14.115  1022  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-22 11:15:14.115  1022  1130 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-22 11:15:14.115   278   979 D CommandListener: Setting iface cfg
08-22 11:15:14.115   278   979 D CommandListener: Trying to bring up p2p0
,08-22 11:15:14.125  1022  1130 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-22 11:15:14.125  1022  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-22 11:15:14.125  1022  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 11:15:14.125  1022  1131 E WifiNative-wlan0: invaild command id : 215
,08-22 11:15:14.125  1022  1022 D WifiScanningService: SCAN_AVAILABLE : 3
08-22 11:15:14.125  1022  1156 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:14.125  1022  1156 I WifiNative-HAL: startHal
,08-22 11:15:14.125  1022  1156 E wifi    : getStaticLongField sWifiHalHandle 0x9de009bc
08-22 11:15:14.125  1022  1156 I WifiNative-HAL: Could not start hal
08-22 11:15:14.125  1022  1022 D RttService: SCAN_AVAILABLE : 3
,08-22 11:15:14.125  1022  1157 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:14.125  1022  1156 E WifiScanningService: could not start HAL
,08-22 11:15:14.125  7691  7691 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 11:15:14.125  1022  1130 D WifiP2pService: P2pEnablingState
08-22 11:15:14.125  7691  7691 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-22 11:15:14.125  1022  1130 D WifiP2pService: P2pEnablingState{ what=147457 }
08-22 11:15:14.125  1022  1130 D WifiP2pService: P2p socket connection successful
08-22 11:15:14.125  1022  1130 D WifiP2pService: P2pEnabledState
,08-22 11:15:14.125  1022  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-22 11:15:14.125  7691  7691 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-22 11:15:14.125  1022  1131 E WifiStateMachine: Failed to set frequency band 0
08-22 11:15:14.125  1022  1133 E ConnectivityService: updateNetworkInfo()
,08-22 11:15:14.125  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:14.125  1022  1131 D SecContentProvider2: mCursor = null
,08-22 11:15:14.125  1022  1022 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-22 11:15:14.125  1022  1052 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-22 11:15:14.125  1022  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 11:15:14.125  1022  1052 D WifiDisplayController: disconnect
08-22 11:15:14.125  1022  1052 D WifiDisplayController: updateConnection
08-22 11:15:14.125  1022  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 11:15:14.125  1022  1052 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 11:15:14.135  1022  1049 D Tethering: interfaceLinkStateChanged p2p0, false
,08-22 11:15:14.135  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:14.135  1022  1131 D SecContentProvider2: mCursor = null
08-22 11:15:14.135  1022  1049 D Tethering: interfaceStatusChanged p2p0, false
,08-22 11:15:14.135  1022  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-22 11:15:14.135  1022  1130 D WifiNative-p2p0: p2pGetDeviceAddress
,08-22 11:15:14.135  1022  1130 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-22 11:15:14.135  1022  1052 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-22 11:15:14.135  1022  1052 D WifiDisplayAdapter: onP2pDisconnected
08-22 11:15:14.135  1022  1052 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 11:15:14.135  1022  1052 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-22 11:15:14.145  1022  1141 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:14.145  1184  1184 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-22 11:15:14.145  1022  1329 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 11:15:14.145  1184  1184 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 11:15:14.145  1022  1052 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-22 11:15:14.145  1022  1052 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-22 11:15:14.145  1022  1052 D WifiDisplayController:  primary type: 10-0050F204-5
08-22 11:15:14.145  1022  1052 D WifiDisplayController:  secondary type: null
08-22 11:15:14.145  1022  1052 D WifiDisplayController:  wps: 0
08-22 11:15:14.145  1022  1052 D WifiDisplayController:  grpcapab: 0
08-22 11:15:14.145  1022  1052 D WifiDisplayController:  devcapab: 0
08-22 11:15:14.145  1022  1052 D WifiDisplayController:  status: 3
08-22 11:15:14.145  1022  1052 D WifiDisplayController:  wfdInfo: null
08-22 11:15:14.145  1022  1052 D WifiDisplayController:  groupownerAddress: null
08-22 11:15:14.145  1022  1052 D WifiDisplayController:  GOdeviceName: null
08-22 11:15:14.145  1022  1052 D WifiDisplayController:  interfaceAddress: 
08-22 11:15:14.145  1022  1052 D WifiDisplayController:  SConnectInfo : null
08-22 11:15:14.145  1022  1130 D WifiP2pService: DeviceAddress: 0a:75:42
,08-22 11:15:14.155  1022  1486 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:14.185  1022  4367 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:14.185  1022  1130 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-22 11:15:14.185  1022  1130 D WifiP2pService: InactiveState
08-22 11:15:14.185  1022  1130 D WifiP2pService: InactiveState{ what=143376 }
08-22 11:15:14.185  1022  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
08-22 11:15:14.185  7691  7691 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 11:15:14.195  1022  1130 D WifiP2pService: InactiveState{ what=143376 }
,08-22 11:15:14.195  1022  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-22 11:15:14.195  1022  1492 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:14.235  1022  1491 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-22 11:15:14.235  1022  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:14.235  1022  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:14.235  1022  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:14.235  1022  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:14.245  1022  1226 D RCPManagerService: exchangeData() failure , invalid userId,
,08-22 11:15:14.245  7792  7792 E Zygote  : MountEmulatedStorage()
08-22 11:15:14.245  7792  7792 E Zygote  : v2
08-22 11:15:14.245  7792  7792 I libpersona: KNOX_SDCARD checking this for 10068
08-22 11:15:14.245  7792  7792 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:14.255  7792  7792 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:14.255  1022  1329 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:14.255  7792  7792 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:14.255  7792  7792 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-22 11:15:14.255  1022  1491 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7792 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-22 11:15:14.275  1022  1226 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:14.285  7792  7792 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:15:14.285  7792  7792 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:14.305  1022  4371 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-22 11:15:14.305  1022  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:14.305  1022  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:14.305  1022  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:14.305  1022  4371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:14.305  7792  7792 D BadgeProvider: onCreate
,08-22 11:15:14.305  7792  7792 D BadgeProvider: DatabaseHelper
,08-22 11:15:14.325  7808  7808 E Zygote  : MountEmulatedStorage(),
,08-22 11:15:14.325  7808  7808 E Zygote  : v2,
08-22 11:15:14.325  7808  7808 I libpersona: KNOX_SDCARD checking this for 10009
08-22 11:15:14.325  7808  7808 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:14.325  7808  7808 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:14.325  1022  4371 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7808 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-22 11:15:14.325  7808  7808 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:14.325  1022  4370 I ActivityManager: Killing 7103:com.android.vending/u0a26 (adj 15): empty #21
,08-22 11:15:14.325  1022  4370 I ActivityManager: Killing 7340:com.google.android.gms.wearable/u0a11 (adj 15): empty #22
08-22 11:15:14.335  7808  7808 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-22 11:15:14.355  7792  7805 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-22 11:15:14.365  7808  7808 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:14.365  7808  7808 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:14.365  7792  7805 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-22 11:15:14.365  7792  7805 D BadgeProvider: sendNotify, [notify] : null
08-22 11:15:14.365  7792  7805 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-22 11:15:14.365  7792  7805 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-22 11:15:14.365  7792  7805 D BadgeProvider: update, [UpdateCount] : 1
08-22 11:15:14.375  1494  1494 D Launcher.Model: reloadBadges entered.
,08-22 11:15:14.425   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 11:15:14.435  1022  4370 I ActivityManager: Killing 7444:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-22 11:15:14.445  1022  4369 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:14.445  1022  4369 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:14.445  1022  4369 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:14.445  1022  4369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:14.445  1022  4369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:14.445  1640  1640 I Hs20UtilService: Starting #12,
08-22 11:15:14.445  1640  1714 I Hs20UtilService: Message received 5011
,08-22 11:15:14.455  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 11:15:14.455  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-22 11:15:14.455  7500  7500 D SecurityLogAgent: StateMachine : Current State = 1
,08-22 11:15:14.455  7500  7500 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 11:15:14.465  1022  1223 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 11:15:14.465  1022  1223 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 11:15:14.465  1022  1223 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:14.465  1022  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:14.465  1022  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:14.465  1640  1640 I Hs20UtilService: Starting #13
,08-22 11:15:14.465  1640  1714 I Hs20UtilService: Message received 5011
,08-22 11:15:14.475  1022  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-22 11:15:14.475  1022  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 11:15:14.475  1022  1131 E WifiNative-wlan0: invaild command id : 215
,08-22 11:15:14.475  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 11:15:14.475  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 11:15:14.475  7500  7500 D SecurityLogAgent: StateMachine : Current State = 1
08-22 11:15:14.475  7500  7500 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 11:15:14.485  4835  4835 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-22 11:15:14.485  4835  4835 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:14.485  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 11:15:14.485  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-22 11:15:14.485  1022  1034 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
08-22 11:15:14.485  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 11:15:14.485  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:14.485  4835  4835 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 11:15:14.485  4835  4903 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 11:15:14.485  1022  4370 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-22 11:15:14.495  1022  4370 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.FileShareClient/com.samsung.android.app.FileShareClient.ClientBroadcastReceiver}
08-22 11:15:14.495  1022  4370 W BroadcastQueue: android.os.TransactionTooLargeException
08-22 11:15:14.495  1022  4370 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-22 11:15:14.495  1022  4370 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-22 11:15:14.495  1022  4370 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-22 11:15:14.495  1022  4370 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-22 11:15:14.495  1022  4370 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-22 11:15:14.495  1022  4370 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-22 11:15:14.495  1022  4370 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-22 11:15:14.495  1022  4370 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-22 11:15:14.495  1022  4370 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-22 11:15:14.495  1022  4370 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-22 11:15:14.495  1022  4370 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:14.495  1022  4370 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:14.495  1022  4370 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:14.495  1022  4370 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:14.515  1022  4370 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7826 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 11:15:14.515  7826  7826 E Zygote  : MountEmulatedStorage()
08-22 11:15:14.515  7826  7826 E Zygote  : v2
08-22 11:15:14.515  7826  7826 I libpersona: KNOX_SDCARD checking this for 10064
08-22 11:15:14.515  7826  7826 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:14.515  7826  7826 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:14.515  1022  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-22 11:15:14.515  1022  4367 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-22 11:15:14.525  7826  7826 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:15:14.525  7826  7826 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-22 11:15:14.525  1022  1046 W libprocessgroup: failed to open /acct/uid_10064/pid_7444/cgroup.procs: No such file or directory
,08-22 11:15:14.545  7826  7826 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:14.545  7826  7826 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:14.555  7826  7826 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-22 11:15:14.565  7826  7826 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:14.565  7826  7826 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-22 11:15:14.595  7826  7826 D FileShare-Client: Outbound.stopDelayTimer - 
,08-22 11:15:14.605  7461  7461 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:14.605  1022  1223 I ActivityManager: Killing 7377:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-22 11:15:15.295  7691  7691 I wpa_supplicant: nl80211: Received scan results (32 BSSes),
08-22 11:15:15.295  7691  7691 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-22 11:15:15.295  7691  7691 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-22 11:15:15.295  7691  7691 I wpa_supplicant: Trying to associate with  'G700'
08-22 11:15:15.295  7691  7691 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-22 11:15:15.295  7691  7691 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-22 11:15:15.305  1022  7772 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-22 11:15:15.325  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:15.325  1022  1131 D SecContentProvider2: mCursor = null
,08-22 11:15:15.415  7691  7691 E wpa_supplicant: Cmd 35605 not handled
,08-22 11:15:15.415  7691  7691 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-22 11:15:15.415  7691  7691 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-22 11:15:15.415  7691  7691 I wpa_supplicant: Associated with F4.99.3E
08-22 11:15:15.415  7691  7691 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-22 11:15:15.415  7691  7691 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-22 11:15:15.415  7691  7691 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-22 11:15:15.415  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:15.415  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:15.415  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-22 11:15:15.425  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:15.425  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:15.425  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 11:15:15.425  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
,08-22 11:15:15.425  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:15.425   336   336 I ServiceManager: Waiting for service AtCmdFwd...
08-22 11:15:15.425  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:15.425  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, true
08-22 11:15:15.425  1022  1049 D Tethering: interfaceStatusChanged wlan0, true
,08-22 11:15:15.425  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-22 11:15:15.425  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:15.425  1022  1131 D SecContentProvider2: mCursor = null
,08-22 11:15:15.435  7691  7691 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-22 11:15:15.435  7691  7691 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-22 11:15:15.435  1022  1136 E Tethering: No numeric data
08-22 11:15:15.435  1022  1136 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 11:15:15.435  1022  1136 D Tethering: clearTetheredNotification()
08-22 11:15:15.435  7691  7691 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-22 11:15:15.435  7691  7691 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-22 11:15:15.435  7691  7691 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-22 11:15:15.435  7691  7691 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-22 11:15:15.435  7691  7691 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-22 11:15:15.435  7691  7691 I wpa_supplicant: Blacklist: Clear (temp) 
08-22 11:15:15.435  7691  7691 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030,
08-22 11:15:15.435  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, true
08-22 11:15:15.435  1022  1128 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:15.435  1022  1049 D Tethering: interfaceStatusChanged wlan0, true
08-22 11:15:15.435  1184  1184 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-22 11:15:15.435  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:15.435  1184  1184 D HotspotTile: updateTetherState():false, false
08-22 11:15:15.445  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-22 11:15:15.445  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-22 11:15:15.445  1022  1131 D SecContentProvider2: mCursor = null
,08-22 11:15:15.445  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:15.445  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:15.445  1022  1128 V NetworkStats: performPollLocked() took 9ms
08-22 11:15:15.445  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:15.455  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:15.455  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:15.455  1022  1131 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-22 11:15:15.465  1022  1131 E WifiConfigStore: setLastSelectedConfiguration -1
,08-22 11:15:15.465  1022  1131 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-22 11:15:15.465  1022  1133 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-22 11:15:15.465  1022  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 11:15:15.465  1022  1133 E ConnectivityService: updateNetworkInfo()
,08-22 11:15:15.475  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 11:15:15.475  1022  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:15.475  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:15.475  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:15.475  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.475  1022  1486 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:15.475  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:15.475  1022  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 11:15:15.475  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 11:15:15.475  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 11:15:15.475  1022  1486 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:15.475  1022  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:15.475  1022  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 11:15:15.485  1640  1640 I Hs20UtilService: Starting #14
,08-22 11:15:15.485  1640  1714 I Hs20UtilService: Message received 5007
,08-22 11:15:15.485  4835  4835 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 11:15:15.485  1022  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:15.485  4835  4835 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:15.485  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 11:15:15.485  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-22 11:15:15.485  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:15.485  5962  5962 D FactoryTest: Not factory mode
08-22 11:15:15.485  5962  5962 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-22 11:15:15.495  4835  4835 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 11:15:15.495  4835  4903 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 11:15:15.495  5962  5962 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-22 11:15:15.495  5962  5962 D MTPRx   : still no open session command from host, so toast
,08-22 11:15:15.495  5962  5962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
08-22 11:15:15.495  5962  5962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-22 11:15:15.505  5962  5962 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118061
,08-22 11:15:15.505  1022  1490 E PersonaManagerService: inState():  stateMachine is null !!
,08-22 11:15:15.505  1022  1490 I PersonaManagerService: PersonaId don't exist
,08-22 11:15:15.505  1022  1490 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-22 11:15:15.505  1022  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-22 11:15:15.505  1022  1490 W ActivityManager: userId = 0, bbcId = -10000,
08-22 11:15:15.505  1022  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:15.505  1022  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-22 11:15:15.515  1022  1490 W ActivityManager: mDVFSHelper.acquire()
,08-22 11:15:15.525   278   979 D CommandListener: Setting iface cfg,
,08-22 11:15:15.535  1022  1490 D PersonaManager: isKioskContainerExistOnDevice
,08-22 11:15:15.555  1022  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 11:15:15.555  1022  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-22 11:15:15.555  1022  1490 D InputDispatcher: Focused application set to: xxxx
,08-22 11:15:15.555  1022  1490 D InputDispatcher: Focus left window: 6740
,08-22 11:15:15.555  5962  5962 E MTPRx   : started activity for popup
,08-22 11:15:15.555  1022  1131 E WifiStateMachine: Start Dhcp Watchdog 2
,08-22 11:15:15.555  1022  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-22 11:15:15.565  1022  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 11:15:15.565  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 11:15:15.565  1022  1131 D SecContentProvider2: mCursor = null
,08-22 11:15:15.575  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-22 11:15:15.575  1022  1131 E WifiNative-wlan0: do suspend false
,08-22 11:15:15.575  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:15.575  1022  1130 D WifiP2pService: InactiveState{ what=143375 }
08-22 11:15:15.575  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-22 11:15:15.575  1022  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
08-22 11:15:15.575  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.575  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:15.575  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.575  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.575  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:15.575  1022  1131 D SecContentProvider2: mCursor = null
,08-22 11:15:15.585  5962  5962 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-22 11:15:15.585  5962  5962 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-22 11:15:15.585  5962  5962 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-22 11:15:15.585  5962  5962 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:15:15.585  5962  5962 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:15:15.585  5962  5962 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 11:15:15.605  5962  5962 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-22 11:15:15.605  1022  4368 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-22 11:15:15.605  1022  4368 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-22 11:15:15.605  1022  4368 D InputDispatcher: Focused application set to: xxxx
,08-22 11:15:15.605  1022  4368 D InputDispatcher: Focus entered window: 6740
,08-22 11:15:15.615  1022  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-22 11:15:15.615  1022  4371 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-22 11:15:15.615  1022  4371 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@288208cc attribute=null, token = android.os.BinderProxy@2021371
,08-22 11:15:15.615  1022  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 11:15:15.645  5962  5962 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-22 11:15:15.655  5962  5962 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-22 11:15:15.655  5962  5962 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-22 11:15:15.675  6740  6740 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-22 11:15:15.675  6740  6740 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-22 11:15:15.675  6740  6740 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-22 11:15:15.675  6740  6740 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-22 11:15:15.675  1022  4370 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-22 11:15:15.675  1022  4370 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-22 11:15:15.675  1022  4370 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-22 11:15:15.675  1022  1022 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-22 11:15:15.675  1022  1022 D PersonaManagerService: getPersonasForUser(): returning null!
,08-22 11:15:15.695  1022  1226 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 11:15:15.695  1022  1226 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-22 11:15:15.695  1022  1226 D SecContentProvider2: mCursor = null
,08-22 11:15:15.695  1022  1226 D WifiService: setWifiEnabled: false pid=6740, uid=10170
,08-22 11:15:15.705  1022  1226 D SettingsProvider: name = wifi_on
,08-22 11:15:15.705  6740  6740 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-22 11:15:15.705  6740  6740 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-22 11:15:15.705  6740  6740 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1c40a71e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2ba0e883, 16908290=android.view.AbsSavedState$1@2ba0e883}, android:focusedViewId=100}]}]
,08-22 11:15:15.705  6740  6740 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-22 11:15:15.705  6740  6740 V ActivityThread: updateVisibility : ActivityRecord{10ac48d0 token=android.os.BinderProxy@2c5c6182 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-22 11:15:15.705  6740  6740 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-22 11:15:15.705  6740  6740 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-22 11:15:15.705  6740  6740 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2c5c6182 time:118266
,08-22 11:15:15.715  1022  1492 D PersonaManager: isKioskContainerExistOnDevice
,08-22 11:15:15.715  1022  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:15.725  1022  1131 E WifiNative-wlan0: do suspend true
,08-22 11:15:15.745  1022  1130 D WifiP2pService: InactiveState{ what=143375 }
,08-22 11:15:15.745  1022  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 11:15:15.755   278   979 D CommandListener: Clearing all IP addresses on wlan0
,08-22 11:15:15.755  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 11:15:15.755  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:15.755  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-22 11:15:15.755  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:15.755  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:15.755  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:15.755  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:15.755  1022  1133 E ConnectivityService: updateNetworkInfo()
08-22 11:15:15.755  1022  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 11:15:15.755  1022  1133 E ConnectivityService: updateNetworkInfo()
08-22 11:15:15.755  1022  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-22 11:15:15.755   278   979 E Netd    : no such netId 503
08-22 11:15:15.755  1022  1131 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-22 11:15:15.765  1022  1130 D WifiP2pService: InactiveState{ what=131204 }
,08-22 11:15:15.765  1022  1130 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-22 11:15:15.765  1022  1133 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
,08-22 11:15:15.765  1022  1133 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-22 11:15:15.765  1022  1022 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-22 11:15:15.765  1022  1130 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-22 11:15:15.765  1022  1133 V NetworkStats: updateIfacesLocked()
08-22 11:15:15.765  1022  1133 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:15.765  1022  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:15.765  1022  1133 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:15.765  1022  1133 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:15.775  1022  1133 V NetworkStats: performPollLocked() took 5ms
08-22 11:15:15.775  1022  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:15.775  1022  1022 D WifiScanningService: SCAN_AVAILABLE : 1
,08-22 11:15:15.775  1022  1156 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 11:15:15.775  1022  1022 D RttService: SCAN_AVAILABLE : 1
,08-22 11:15:15.775  1022  1157 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 11:15:15.775  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 11:15:15.775  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:15.775  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:15.775  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.775  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.775  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.775  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:15.785  1022  1052 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 11:15:15.785  1022  1052 D WifiDisplayAdapter: onP2pDisconnected
08-22 11:15:15.785  1022  1052 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 11:15:15.785  1022  1052 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-22 11:15:15.785  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:15.785  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:15.785  1022  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-22 11:15:15.785  1022  1133 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-22 11:15:15.785  1022  7841 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:15.785  1022  1133 D ConnectivityService: nai.networkMonitor.doQuit()
08-22 11:15:15.785  1022  1133 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-22 11:15:15.785  1022  1133 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-22 11:15:15.785  1022  1133 E ConnectivityService: updateNetworkInfo()
08-22 11:15:15.785  1022  1133 E ConnectivityService: updateNetworkInfo()
,08-22 11:15:15.785  1022  7841 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-22 11:15:15.785  1022  1490 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:15.785  1022  1052 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-22 11:15:15.785  1022  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 11:15:15.785  1022  1052 D WifiDisplayController: disconnect
08-22 11:15:15.785  1022  1052 D WifiDisplayController: updateConnection
08-22 11:15:15.785  1022  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 11:15:15.785  1022  1052 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 11:15:15.785  1022  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 11:15:15.785  7846  7846 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-22 11:15:15.785  1022  1022 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-22 11:15:15.785  1022  1490 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:15.785  1022  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:15.785  1022  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:15.795  1640  1640 I Hs20UtilService: Starting #15
,08-22 11:15:15.795  1022  1130 D WifiP2pService: P2pDisablingState
08-22 11:15:15.795  7846  7846 I dhcpcd  : version 5.5.6 starting
08-22 11:15:15.795  1022  1130 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-22 11:15:15.795  1640  1714 I Hs20UtilService: Message received 5007
08-22 11:15:15.795  1022  1130 D WifiP2pService: p2p socket connection lost
08-22 11:15:15.795  1022  1130 D WifiP2pService: P2pDisabledState
,08-22 11:15:15.795  1022  1131 E WifiNative-wlan0: do suspend true
08-22 11:15:15.795  1022  1052 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-22 11:15:15.795  1022  1052 D WifiDisplayAdapter: onP2pDisconnected
08-22 11:15:15.795  1022  1052 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 11:15:15.795  1022  1052 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-22 11:15:15.795  1184  1184 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-22 11:15:15.795  1022  4369 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 11:15:15.795  1184  1184 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 11:15:15.805  4835  4835 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-22 11:15:15.805  4835  4835 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:15.805  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 11:15:15.805  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-22 11:15:15.805  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:15.805  4835  4835 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 11:15:15.805  4835  4903 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 11:15:15.815  4835  4835 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-22 11:15:15.815  4835  4835 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:15.815  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-22 11:15:15.815  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-22 11:15:15.815  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:15.815  4835  4835 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 11:15:15.815  7826  7826 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:15.815  7826  7826 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-22 11:15:15.815  7826  7826 D FileShare-Client: Outbound.stopDelayTimer - 
08-22 11:15:15.815  4835  4903 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 11:15:15.825  7846  7846 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-22 11:15:15.825  1022  1130 D WifiP2pService: P2pDisabledState{ what=143375 }
08-22 11:15:15.825  1022  1130 D WifiP2pService: DefaultState{ what=143375 }
08-22 11:15:15.825   278   979 D CommandListener: Clearing all IP addresses on wlan0
,08-22 11:15:15.835  7461  7461 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:15.835  7691  7691 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-22 11:15:15.835  1022  1022 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-22 11:15:15.855  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-22 11:15:15.855  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-22 11:15:15.855  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:15.855  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 11:15:15.855  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.855  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:15.855  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.855  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-22 11:15:15.855  1022  1131 D SecContentProvider2: mCursor = null
,08-22 11:15:15.855  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 11:15:15.855  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:15.855  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:15.855  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.855  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.855  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.855  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:15.865  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 11:15:15.865  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:15.865  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 11:15:15.865  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.865  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.865  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:15.865  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:15.865  1184  1184 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:15.865  1184  1184 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:15.865  1184  1184 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-22 11:15:15.865  1184  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 11:15:15.865  1184  1184 D HotspotTile: onReceive : 0, 0,
,08-22 11:15:15.865  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:15.865  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:15.865  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:15.865  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:15.865  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:15.865  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:15.865  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:15.865  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:15.865  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:15.875  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:15.875  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 11:15:15.875  4835  4835 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:15.875  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-22 11:15:15.875  1022  4369 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:15.875  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-22 11:15:15.875  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:15.875  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:15.875  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:15.875  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:15.875  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:15.875  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:15.875  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:15.875  1022  4369 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 11:15:15.875  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:15.875  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 11:15:15.875  1022  4369 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:15.875  1022  4369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:15.875  1022  4369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 11:15:15.885  7846  7846 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-22 11:15:15.885  7846  7846 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-22 11:15:15.885  7846  7846 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-22 11:15:15.885  7846  7846 I dhcpcd  : bssid match
,08-22 11:15:15.885  7846  7846 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
08-22 11:15:15.885  1640  1640 I Hs20UtilService: Starting #16
08-22 11:15:15.885  1640  1714 I Hs20UtilService: Message received 5007
,08-22 11:15:15.885  4835  4835 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-22 11:15:15.885  4835  4835 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:15.885  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 11:15:15.885  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-22 11:15:15.885  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:15.885  4835  4835 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 11:15:15.885  4835  4903 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 11:15:15.895  1022  1492 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 11:15:15.895  1022  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:15.895  1022  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:15.895  1022  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:15.895  1022  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:15.905  1640  1640 I Hs20UtilService: Starting #17
,08-22 11:15:15.905  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 11:15:15.905  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 11:15:15.905  7500  7500 D SecurityLogAgent: StateMachine : Current State = 1
,08-22 11:15:15.905  1640  1714 I Hs20UtilService: Message received 5011
08-22 11:15:15.905  7500  7500 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 11:15:15.915  7691  7691 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 11:15:16.005  7846  7846 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-22 11:15:16.075  7691  7691 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,08-22 11:15:16.075  1022  1049 D Tethering: interfaceLinkStateChanged p2p0, false,
08-22 11:15:16.075  1022  1049 D Tethering: interfaceStatusChanged p2p0, false
,08-22 11:15:16.075  1022  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-22 11:15:16.095  7691  7691 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-22 11:15:16.095  7691  7691 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-22 11:15:16.095  7691  7691 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-22 11:15:16.095  7691  7691 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-22 11:15:16.095  7691  7691 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-22 11:15:16.095  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:16.095  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:16.095  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:16.105  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:16.095  1022  1136 D Tethering: InitialState.processMessage what=4
08-22 11:15:16.095  1022  1136 E Tethering: No numeric data
08-22 11:15:16.095  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:16.095  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:16.095  1022  1136 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 11:15:16.095  1022  1136 D Tethering: clearTetheredNotification()
,08-22 11:15:16.105  1022  1128 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:16.105  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:16.105  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:16.105  1184  1184 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 11:15:16.105  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 11:15:16.105  1184  1184 D HotspotTile: updateTetherState():false, false
,08-22 11:15:16.105  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:16.105  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:16.105  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:16.105  1022  1128 V NetworkStats: performPollLocked() took 4ms
,08-22 11:15:16.105  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:16.105  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:16.105  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:16.155  7846  7846 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,08-22 11:15:16.415  7691  7691 I wpa_supplicant: Blacklist: Clear (all) ,
08-22 11:15:16.415  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:16.415  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:16.415  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:16.415   291   291 E SMD     : DCD OFF,
,08-22 11:15:16.425   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-22 11:15:16.585  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false,
08-22 11:15:16.585  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:16.585  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:16.585  7691  7691 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-22 11:15:16.685  1022  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-22 11:15:16.685  1022  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-22 11:15:16.685  7477  7477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 11:15:16.695  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 11:15:16.695  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:16.695  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-22 11:15:16.695  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:16.695  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:16.695  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:16.695  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:16.705  1184  1184 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:16.705  1184  1184 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-22 11:15:16.705  1184  1184 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:16.705  1184  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 11:15:16.705  1776  2209 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 11:15:16.705  1184  1184 D HotspotTile: onReceive : 1, 0
,08-22 11:15:16.705  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:16.705  4835  4835 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:16.705  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:16.715  1022  4367 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:16.715  1022  4367 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:16.715  1022  4367 W ActivityManager: userId = 0, bbcId = -10000,
08-22 11:15:16.715  1022  4367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:16.715  1022  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:16.715  1640  1640 I Hs20UtilService: Starting #18
08-22 11:15:16.715  1640  1714 I Hs20UtilService: Message received 5011,
08-22 11:15:16.715  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 11:15:16.715  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-22 11:15:16.715  7500  7500 D SecurityLogAgent: StateMachine : Current State = 1
08-22 11:15:16.715  7500  7500 D SecurityLogAgent: StateMachine : Changed Current State = 1,
,08-22 11:15:17.435   278   972 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-22 11:15:17.435  1022  1049 D Tethering: interfaceRemoved wlan0
,08-22 11:15:17.435  1022  1049 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-22 11:15:17.635  1022  1049 D Tethering: interfaceRemoved p2p0,
08-22 11:15:17.635  1022  1049 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-22 11:15:17.935  1022  1101 V AlarmManager: waitForAlarm result :4
,08-22 11:15:17.935   278   975 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 11:15:17.935   278   975 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-22 11:15:17.955  1022  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:17.955  1022  1047 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 11:15:17.955  1022  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-22 11:15:18.505  1022  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-22 11:15:18.515  1022  1047 W ActivityManager: mDVFSHelper.release()
,08-22 11:15:18.715  6740  7157 D BluetoothAdapter: enable()
,08-22 11:15:18.715  1022  4369 W ActivityManager: Permission Denial: getCurrentUser() from pid=6740, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-22 11:15:18.725  1022  4369 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-22 11:15:18.725  1022  4369 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6740, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-22 11:15:18.725  1022  4369 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 11:15:18.725  1022  4369 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-22 11:15:18.725  1022  4369 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-22 11:15:18.725  1022  4369 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-22 11:15:18.725  1022  4369 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 11:15:18.725  1022  4369 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 11:15:18.725  1022  4369 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 11:15:18.735  1022  4369 D SettingsProvider: name = bluetooth_on
,08-22 11:15:18.745  1022  1051 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-22 11:15:18.745  1022  1051 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 11:15:18.745  1022  1051 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-22 11:15:18.745  3222  3294 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-22 11:15:18.745  3222  3294 D BluetoothAdapterProperties: Setting state to 11
,08-22 11:15:18.745  3222  3294 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-22 11:15:18.745  3222  3294 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-22 11:15:18.745  3222  3294 D BluetoothAdapterService: updateAdapterState state is 11
,08-22 11:15:18.745  3222  3294 D BluetoothAdapterService: Autoconnection is available 
,08-22 11:15:18.745  3222  3294 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-22 11:15:18.745  3222  3294 D BtConfig.SecureMode: isSecureModeOn:false
,08-22 11:15:18.745  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-22 11:15:18.755  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-22 11:15:18.755  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
,08-22 11:15:18.755  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-22 11:15:18.755  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-22 11:15:18.755  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-22 11:15:18.755  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-22 11:15:18.755  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-22 11:15:18.755  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:18.755  1022  1022 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:18.755  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:18.755  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-22 11:15:18.755  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-22 11:15:18.755  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 11:15:18.755  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-22 11:15:18.755  1022  1022 I InputMethodManagerService: [BT Setting State] State =11
,08-22 11:15:18.765  1184  1184 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 11:15:18.765  1184  1184 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:18.765  1184  1184 D BluetoothTile:  getBluetoothState : 11
,08-22 11:15:18.765  1884  1884 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 11:15:18.775  1022  1486 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:18.775  1184  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:18.775  1184  1754 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-22 11:15:18.775  1022  4369 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 11:15:18.775  1184  1184 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:18.775  1184  1184 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 11:15:18.785  4835  4835 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:18.785  1022  1226 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:18.785  1022  1226 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-22 11:15:18.785  1022  1226 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:18.785  1022  1226 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:18.785  1022  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:18.785  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:18.795  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-22 11:15:18.795  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 11:15:18.795  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-22 11:15:18.795  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:18.795  3222  3222 D HeadsetService: Received start request. Starting profile...
08-22 11:15:18.795  3222  3222 D HeadsetService: start()
08-22 11:15:18.795  3222  3222 D HeadsetStateMachine: make
,08-22 11:15:18.795  3222  3222 E HeadsetStateMachine: # of Max HF connection is 2
,08-22 11:15:18.805  2652  2652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:18.805  1022  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-22 11:15:18.805  1022  1492 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:18.805  1022  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 11:15:18.805  1022  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:18.805  1022  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:18.805  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-22 11:15:18.805  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:18.805  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-22 11:15:18.815  1022  1035 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:18.815  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 11:15:18.815  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:18.815  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,08-22 11:15:18.815  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:18.815  1022  4368 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-22 11:15:18.815  1022  4368 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-22 11:15:18.815  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-22 11:15:18.815  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 11:15:18.815  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-22 11:15:18.815  1022  4368 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:18.815  1022  4368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:18.815  1022  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-22 11:15:18.825  1022  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:18.825  1022  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-22 11:15:18.825  1022  1486 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:18.825  1022  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:18.825  1022  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:18.825  1022  1141 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-22 11:15:18.825  1022  1141 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-22 11:15:18.825  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-22 11:15:18.825  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 11:15:18.825  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-22 11:15:18.825  4835  4835 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:18.825  1022  1141 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:18.825  1022  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:18.825  1022  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-22 11:15:18.835  3222  3222 I bluedroid: get_profile_interface handsfree
,08-22 11:15:18.835  1022  1329 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:18.835  1022  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 11:15:18.835  1022  1329 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:18.835  1022  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:18.835  1022  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:18.835  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-22 11:15:18.835  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:18.835  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-22 11:15:18.845  1184  1184 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:18.845  1184  1184 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-22 11:15:18.845  1022  4370 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:18.845  1022  4370 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 11:15:18.845  3222  3222 E DualScoManager: Dual Sco Manager already instantiated
08-22 11:15:18.845  3222  3222 I DualScoManager: Set HeadsetServiceHelper
08-22 11:15:18.845  3222  3222 D BluetoothAtMessage: createCMTIContentObservers
08-22 11:15:18.845  1022  4370 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:18.845  1022  4370 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:18.845  1022  4370 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 11:15:18.845  1022  1035 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-22 11:15:18.845  1022  1035 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:18.845  1022  1035 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:18.845  1022  1035 D SettingsProvider: selectionArgs: false
08-22 11:15:18.845  1022  1035 D SettingsProvider: selectionArgs: 1002
08-22 11:15:18.845  1022  1035 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:18.845  1022  1035 D SettingsProvider: ret = -1
08-22 11:15:18.855  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-22 11:15:18.855  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 11:15:18.855  1022  4367 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-22 11:15:18.855  3222  3294 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-22 11:15:18.855  3222  7879 D HeadsetStateMachine: Enter Disconnected: -2
,08-22 11:15:18.855  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:18.855  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:18.855  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:18.855  1022  4367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:18.865  1022  4367 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7880 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-22 11:15:18.865  1022  1226 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:18.865  1022  1226 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-22 11:15:18.865  7880  7880 E Zygote  : MountEmulatedStorage()
08-22 11:15:18.865  7880  7880 I libpersona: KNOX_SDCARD checking this for 10055
08-22 11:15:18.865  7880  7880 E Zygote  : v2
,08-22 11:15:18.865  7880  7880 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:18.865  1022  1226 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:18.865  1022  1226 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:18.865  1022  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 11:15:18.865  7880  7880 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:18.865  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:18.865  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService,
08-22 11:15:18.865  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:18.865  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:18.865  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:18.865  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:18.865  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 11:15:18.865  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 11:15:18.865  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 11:15:18.865  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-22 11:15:18.865  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 11:15:18.865  7880  7880 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:18.865  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-22 11:15:18.865  3222  3294 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-22 11:15:18.875  3222  3222 D HeadsetService: mStartError = false
08-22 11:15:18.875  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
08-22 11:15:18.875  7880  7880 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:18.875  3222  3222 D A2dpService: Received start request. Starting profile...
08-22 11:15:18.875  3222  3222 D A2dpService: start()
08-22 11:15:18.875  3222  3222 I bluedroid: get_profile_interface avrcp
,08-22 11:15:18.875  3222  7879 D HeadsetStateMachine: Clear mHeadsetBrsf
08-22 11:15:18.875  3222  7879 D HeadsetStateMachine: map size, before remove : 0
08-22 11:15:18.875  3222  7879 D HeadsetStateMachine: map size, after remove: 0
,08-22 11:15:18.875  3222  3222 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-22 11:15:18.875  3222  3222 D Avrcp   : Initialize Media Controller
08-22 11:15:18.875  3222  3222 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-22 11:15:18.885  3222  3222 E Avrcp   : getActiveSessions
,08-22 11:15:18.885  3222  3222 D Avrcp   : pick active media Controller
08-22 11:15:18.885  3222  3222 D Avrcp   : Get the active Media Controller 
,08-22 11:15:18.885  3222  3222 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-22 11:15:18.885  3222  7886 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-22 11:15:18.885  3222  3222 D A2dpStateMachine: make
,08-22 11:15:18.885  3222  3222 I bluedroid: get_profile_interface a2dp
,08-22 11:15:18.895  3222  7891 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-22 11:15:18.895  3222  3222 E bt-btif : warning : media task started media_task_refcnt 1 
,08-22 11:15:18.895  3222  3222 D A2dpService: mStartError = false
08-22 11:15:18.895  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
08-22 11:15:18.895  3222  7890 D A2dpStateMachine: Enter Disconnected: -2
,08-22 11:15:18.895  3222  3222 D HidService: Received start request. Starting profile...
08-22 11:15:18.895  7880  7880 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:15:18.895  3222  3222 D HidService: start()
08-22 11:15:18.895  3222  3222 I bluedroid: get_profile_interface hidhost
08-22 11:15:18.895  3222  3222 D HidService: setHidService(): set to: null
08-22 11:15:18.895  3222  3222 D HidService: mStartError = false
08-22 11:15:18.895  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
08-22 11:15:18.895  3222  3222 D HeadsetStateMachine: Try to query the phonestate on bind
08-22 11:15:18.895  7880  7880 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:18.895  1430  1445 I Telecom : BluetoothPhoneService: queryPhoneState
,08-22 11:15:18.895  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-22 11:15:18.895  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-22 11:15:18.895  1430  1445 I Telecom : BluetoothPhoneService: Result of Message : true
,08-22 11:15:18.905  3222  3222 D HealthService: Received start request. Starting profile...,
08-22 11:15:18.905  3222  3222 D HealthService: start()
,08-22 11:15:18.905  3222  3222 I bluedroid: get_profile_interface health
08-22 11:15:18.905  3222  3222 D HealthService: mStartError = false
08-22 11:15:18.905  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
08-22 11:15:18.905  3222  3222 D HeadsetStateMachine: Proxy object connected
08-22 11:15:18.905  3222  3222 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-22 11:15:18.905  3222  7879 D HeadsetStateMachine: Disconnected process message: 11
,08-22 11:15:18.905  3222  3222 D PanService: Received start request. Starting profile...
08-22 11:15:18.905  3222  3222 D PanService: start()
08-22 11:15:18.905  3222  3222 D BluetoothPanServiceJni: initializeNative(L110): pan
08-22 11:15:18.905  3222  3222 I bluedroid: get_profile_interface pan
08-22 11:15:18.905  3222  3222 D PanService: mStartError = false
08-22 11:15:18.905  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
08-22 11:15:18.905  3222  3222 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-22 11:15:18.905  3222  3222 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-22 11:15:18.905  3222  7879 D HeadsetStateMachine: Disconnected process message: 18
,08-22 11:15:18.905  3222  3222 D BluetoothMapService: Received start request. Starting profile...
08-22 11:15:18.905  3222  3222 D BluetoothMapService: start()
,08-22 11:15:18.915  3222  7886 D BluetoothMediaBrowser: no now playing list
08-22 11:15:18.915  3222  7886 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-22 11:15:18.915  3222  3222 D BluetoothMapService: mStartError = false
08-22 11:15:18.915  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:18.915  3222  3222 D SapService: Received start request. Starting profile...
08-22 11:15:18.915  3222  3222 D SapService: start()
08-22 11:15:18.915  3222  3222 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-22 11:15:18.915  3222  3222 I bluedroid: get_profile_interface sap
08-22 11:15:18.915  3222  3222 D SapService: mStartError = false
08-22 11:15:18.915  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
08-22 11:15:18.915  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-22 11:15:18.915  3222  3222 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-22 11:15:18.915  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-22 11:15:18.915  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-22 11:15:18.915  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-22 11:15:18.915  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-22 11:15:18.915  3222  7879 D HeadsetStateMachine: Disconnected process message: 10
,08-22 11:15:18.915  3222  7879 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-22 11:15:18.915  3222  7879 D HeadsetStateMachine: Disconnected process message: 11
,08-22 11:15:18.925  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-22 11:15:18.925  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-22 11:15:18.935  3222  3294 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-22 11:15:18.935  3222  3294 I bluedroid: enable
,08-22 11:15:18.935  3222  3297 E bt-btif : BTA got event 0x122c
08-22 11:15:18.935  3222  3297 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-22 11:15:18.935  3222  3297 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-22 11:15:18.935  3222  3297 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-22 11:15:18.935  3222  3297 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-22 11:15:18.935  3222  3297 E BluetoothServiceJni: populateRssiValuesNative
08-22 11:15:18.935  3222  3297 I bluedroid: getModelRssiValues
08-22 11:15:18.935  3222  3297 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-22 11:15:18.935  3222  3297 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-22 11:15:18.935  1022  1022 D SettingsProvider: name = bluetooth_name
,08-22 11:15:18.945  3222  3297 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-22 11:15:18.945  7880  7880 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-22 11:15:18.945  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:18.945  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:18.945  3222  3297 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 11:15:18.945  3222  3297 D BluetoothAdapterProperties: Scan Mode:20
08-22 11:15:18.945  3222  3297 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 11:15:18.945  3222  3297 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-22 11:15:18.945  3222  3297 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-22 11:15:18.945  3222  3297 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
08-22 11:15:18.945  3222  3297 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-22 11:15:18.945  3222  3297 E bt-btif : JVenable fails
,08-22 11:15:18.945  3222  3297 D bte_conf: Device ID record 1 : primary
,08-22 11:15:18.945  3222  3297 D bte_conf:   vendorId            = 0075
,08-22 11:15:18.955  3222  3297 D bte_conf:   vendorIdSource      = 0001
,08-22 11:15:18.955  3222  3297 D bte_conf:   product             = 0100
,08-22 11:15:18.955  3222  3297 D bte_conf:   version             = 0200
08-22 11:15:18.955  3222  3297 D bte_conf:   clientExecutableURL = 
08-22 11:15:18.955  3222  3297 D bte_conf:   serviceDescription  = 
,08-22 11:15:18.955  3222  3297 D bte_conf:   documentationURL    = 
,08-22 11:15:18.955  3222  3297 D bte_conf: bte_load_did_conf no section named DID2.
,08-22 11:15:18.955  3222  3294 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-22 11:15:18.955  3222  3294 D BluetoothAdapterProperties: ScanMode =  20
08-22 11:15:18.955  3222  3297 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-22 11:15:18.955  3222  3294 D BluetoothAdapterProperties: State =  11
08-22 11:15:18.955  3222  3297 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-22 11:15:18.955  1022  4370 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-22 11:15:18.955  3222  3294 D BluetoothAdapterProperties: Setting state to 12
,08-22 11:15:18.955  3222  3294 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-22 11:15:18.965  3222  3297 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 11:15:18.965  3222  3297 D BluetoothAdapterProperties: Scan Mode:21
08-22 11:15:18.965  3222  3297 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 11:15:18.965  1022  4371 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-22 11:15:18.965  1022  4371 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:18.965  1022  4371 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 11:15:18.965  1022  4371 D SettingsProvider: selectionArgs: false
,08-22 11:15:18.965  1022  4371 D SettingsProvider: selectionArgs: 1002
,08-22 11:15:18.965  1022  4371 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 11:15:18.965  1022  4371 D SettingsProvider: ret = -1
,08-22 11:15:18.965  3222  3294 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 11:15:18.965  3222  3294 D BluetoothAdapterService: updateAdapterState state is 12
,08-22 11:15:18.965  1022  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:18.965  1022  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 11:15:18.965  1022  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:18.965  1022  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:18.975  1022  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:18.975  7880  7880 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-22 11:15:18.975  7880  7880 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-22 11:15:18.975  7880  7880 D UserAnalysis: Create SecureDbHelper
,08-22 11:15:18.975  3222  3294 D BluetoothAdapterService: Autoconnection is available 
08-22 11:15:18.975  3222  3294 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-22 11:15:18.975  3222  3294 D BluetoothAdapterService: starting service from this receiver
,08-22 11:15:18.975  1022  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:18.975  3222  3231 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 11:15:18.975  1022  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-22 11:15:18.975  1022  1491 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:18.975  1022  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:18.975  1022  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 11:15:18.975  3222  3231 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:18.975  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:18.975  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:18.975  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:18.975  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:18.975  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:18.975  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:18.975  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:18.975  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:18.975  1022  1051 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 11:15:18.975  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 11:15:18.975  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:18.975  3222  3222 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-22 11:15:18.975  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:18.975  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 11:15:18.985  3222  3294 I BluetoothAdapterState: Entering On State from state = 11
,08-22 11:15:18.985  4835  7374 D Bluetoothsap: onBluetoothStateChange: up=true
08-22 11:15:18.985  4835  7374 D Bluetoothsap: Binding service...
,08-22 11:15:18.985  7880  7880 D IntelligenceServiceApplication: onCreate()
,08-22 11:15:18.985  1022  4371 I ActivityManager: Killing 7399:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-22 11:15:18.985  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:18.995  4835  7374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-22 11:15:18.995  1022  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-22 11:15:18.995  3222  3222 I BluetoothPbapService: Handler(): got msg=1
08-22 11:15:18.995  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 11:15:18.995  1022  1486 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-22 11:15:18.995  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:18.995  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:18.995  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:18.995  7880  7880 D IntelligenceServiceApplication: no applications having user consent for prediction
08-22 11:15:18.995  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:18.995  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:18.995  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:18.995  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:18.995  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:18.995  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:18.995  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:18.995  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:18.995  4835  7374 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-22 11:15:18.995  1776  5505 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:18.995  1776  5505 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:18.995  1022  1226 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-22 11:15:18.995  4835  4849 D BluetoothPan: Binding service...
,08-22 11:15:19.005  7880  7880 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-22 11:15:19.005  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:19.005  3222  7903 V BluetoothPbapService: PBAP Service initSocket try: 0
08-22 11:15:19.005  1022  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-22 11:15:19.005  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 11:15:19.005  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:19.005  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:19.005  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:19.005  1022  1051 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:19.005  1022  1051 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:19.005  4835  4846 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 11:15:19.005  4835  4846 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-22 11:15:19.005  3222  3222 D BluetoothA2dp: Proxy object connected
08-22 11:15:19.005  1022  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 11:15:19.005  3222  3222 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-22 11:15:19.005  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 11:15:19.005  3222  7903 D BluetoothSocket: bindListen(): myUserId = 0
08-22 11:15:19.005  3222  7903 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 11:15:19.005  4835  4835 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-22 11:15:19.005  4835  4835 D SapProfile: Bluetooth service connected
08-22 11:15:19.005  4835  4835 D Bluetoothsap: getConnectedDevices()
,08-22 11:15:19.015  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:19.015  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:19.015  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:19.015  7880  7880 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-22 11:15:19.015  4835  4849 D BluetoothPbap: onBluetoothStateChange: up=true
08-22 11:15:19.015  3222  7903 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-22 11:15:19.015  3222  7903 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 11:15:19.015  3222  7903 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 11:15:19.015  3222  7903 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ed7aeb5
,08-22 11:15:19.015  3222  7903 D BluetoothSocket: channel: 19
08-22 11:15:19.015  3222  7903 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-22 11:15:19.015  4835  4835 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 11:15:19.015  1022  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-22 11:15:19.015  4835  4835 D PanProfile: Bluetooth service connected
08-22 11:15:19.015  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 11:15:19.015  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:19.015  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:19.015  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:19.015  1439  1463 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:19.015  1439  1463 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:19.025  4835  4835 D BluetoothA2dp: Proxy object connected
08-22 11:15:19.025  4835  4835 D A2dpProfile: Bluetooth service connected
,08-22 11:15:19.025  1430  1438 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:19.025  1022  1051 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 11:15:19.025  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:19.025  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:19.025  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:19.025  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:19.025  1430  1438 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:19.025  1430  1445 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:19.025  1430  1445 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:19.025  1430  3359 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:19.025  4835  4835 D BluetoothPbap: Proxy object connected
08-22 11:15:19.025  1022  1051 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 11:15:19.025  4835  4835 D PbapServerProfile: Bluetooth service connected
08-22 11:15:19.025  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 11:15:19.025  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:19.025  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:19.025  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:19.025  1430  3359 E BluetoothHeadset: BluetoothHeadset service is binded,
,08-22 11:15:19.035  1455  1474 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
,08-22 11:15:19.035  1022  1051 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 11:15:19.035  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:19.035  1022  1051 W ActivityManager: userId = 0, bbcId = -10000,
08-22 11:15:19.035  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:19.035  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:19.035  1455  1474 E BluetoothHeadset: BluetoothHeadset service is binded
08-22 11:15:19.035  1455  1705 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:19.035  1455  1705 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:19.035  1022  1051 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-22 11:15:19.035  1022  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 11:15:19.035  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:19.035  1022  1051 E BluetoothHeadset: BluetoothHeadset service is binded
08-22 11:15:19.035  3222  3231 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:19.035  3222  3231 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:19.035  4835  7374 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 11:15:19.045  1022  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-22 11:15:19.045  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 11:15:19.045  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:19.045  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:19.045  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:19.045  4835  4849 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:19.045  4835  4849 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:19.045  1022  1051 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 11:15:19.045  1022  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 11:15:19.045  1022  1051 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-22 11:15:19.045  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 11:15:19.045  4835  4835 D BluetoothInputDevice: Proxy object connected
08-22 11:15:19.045  4835  4835 D HidProfile: Bluetooth service connected
08-22 11:15:19.045  1022  1051 D BluetoothPan: Binding service...
08-22 11:15:19.045  1022  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-22 11:15:19.045  1022  1022 D BluetoothA2dp: Proxy object connected
08-22 11:15:19.045  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 11:15:19.045  6740  6750 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 11:15:19.045  6740  6750 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:19.045  1022  1022 D BluetoothPan: BluetoothPAN Proxy object connected,
08-22 11:15:19.045  1022  1051 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-22 11:15:19.055  1022  1051 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #20
08-22 11:15:19.055  1022  1051 E BluetoothManagerService: android.os.TransactionTooLargeException
08-22 11:15:19.055  1022  1051 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-22 11:15:19.055  1022  1051 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-22 11:15:19.055  1022  1051 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
08-22 11:15:19.055  1022  1051 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
08-22 11:15:19.055  1022  1051 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
08-22 11:15:19.055  1022  1051 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
08-22 11:15:19.055  1022  1051 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
08-22 11:15:19.055  1022  1051 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.055  1022  1051 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:19.055  1022  1051 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 11:15:19.055  1022  1051 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-22 11:15:19.055  2652  2660 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:19.055  2652  2660 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:19.055  1184  1206 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:19.055  1184  1206 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:19.055  4835  4849 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:19.055  1022  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 11:15:19.055  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:19.055  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:19.055  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:19.055  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:19.055  4835  4849 E BluetoothHeadset: BluetoothHeadset service is binded
08-22 11:15:19.055  4835  4835 D HeadsetProfile: Bluetooth service connected
,08-22 11:15:19.055  1430  1438 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:19.055  1022  1051 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 11:15:19.055  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:19.055  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 11:15:19.055  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:19.055  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:19.065  1430  1438 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:19.065  4835  4846 D BluetoothMap: onBluetoothStateChange: up=true
,08-22 11:15:19.065  1022  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-22 11:15:19.065  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 11:15:19.065  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:19.065  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:19.065  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:19.065  1022  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-22 11:15:19.065  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-22 11:15:19.065  1022  1022 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:19.065  1022  1022 I InputMethodManagerService: [BT Setting State] State =12
08-22 11:15:19.065  1022  1022 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-22 11:15:19.065  4835  4835 D BluetoothMap: Proxy object connected
08-22 11:15:19.065  4835  4835 D MapProfile: Bluetooth service connected
08-22 11:15:19.065  4835  4835 D BluetoothMap: getConnectedDevices()
,08-22 11:15:19.075  1184  1184 D BluetoothTile:  onBluetoothStateChange:,
08-22 11:15:19.075  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3007c0e7, true
08-22 11:15:19.075  1184  1184 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 11:15:19.075  1184  1184 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:19.075  1184  1184 D BluetoothTile:  getBluetoothState : 12
,08-22 11:15:19.075  1430  1430 D BluetoothHeadset: registerMessageListener
,08-22 11:15:19.075  1184  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:19.085  1884  1884 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 11:15:19.085  1184  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:19.085  3222  3231 D HeadsetService: registerMessageListener
,08-22 11:15:19.085  3222  3231 D HeadsetService: registerMessageListener
,08-22 11:15:19.085  3222  7879 D HeadsetStateMachine: Disconnected process message: 70
,08-22 11:15:19.085  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-22 11:15:19.085  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-22 11:15:19.085  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:19.085  4835  4835 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:19.085  1184  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:19.085  3222  7879 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3e0eb94a
,08-22 11:15:19.085  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:19.085  4835  4835 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-22 11:15:19.085  4835  4835 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-22 11:15:19.085  4835  4835 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-22 11:15:19.095  4835  4835 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-22 11:15:19.095  1022  1226 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:19.095  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-22 11:15:19.095  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-22 11:15:19.095  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-22 11:15:19.095  1022  1486 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-22 11:15:19.095  1184  1184 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:19.095  3222  7907 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-22 11:15:19.095  3222  7879 D HeadsetStateMachine: Disconnected process message: 9
08-22 11:15:19.095  3222  7879 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-22 11:15:19.095   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-22 11:15:19.095  3222  7907 D BluetoothSocket: bindListen(): myUserId = 0
08-22 11:15:19.095  3222  7907 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:19.105   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,08-22 11:15:19.105  3222  7907 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-22 11:15:19.105  3222  7907 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 11:15:19.105  3222  7907 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 11:15:19.105  3222  7907 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f5a0bb
08-22 11:15:19.105  3222  7907 D BluetoothSocket: channel: 5
,08-22 11:15:19.105   283   283 V voice   : voice_set_parameters: exit with code(-2)
08-22 11:15:19.105   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-22 11:15:19.105   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-22 11:15:19.105   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-22 11:15:19.105   283   283 V audio_hw_primary: adev_set_parameters: exit
08-22 11:15:19.105  3222  7879 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-22 11:15:19.105  4835  4835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:19.105  1022  1329 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-22 11:15:19.105  1022  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 11:15:19.115  1022  1329 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:19.115  1022  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:19.115  1022  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 11:15:19.115  2652  2652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:19.115  4835  4835 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:19.125  4835  4835 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:19.125  1184  1184 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:19.125  1184  1184 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-22 11:15:19.135  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:19.135  3222  3222 D BtConfig.SecureMode: isSecureModeOn:false
,08-22 11:15:19.135  1022  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:19.135  1022  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-22 11:15:19.135  1022  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:19.135  1022  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:19.135  1022  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:19.145  1022  1035 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast,
,08-22 11:15:19.145  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:19.145  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:19.145  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:19.145  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:19.155  7910  7910 E Zygote  : MountEmulatedStorage(),
08-22 11:15:19.155  7910  7910 I libpersona: KNOX_SDCARD checking this for 10105
08-22 11:15:19.155  7910  7910 E Zygote  : v2
08-22 11:15:19.155  7910  7910 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:19.155  7910  7910 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:19.155  7910  7910 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:19.155  7910  7910 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 11:15:19.165  1022  1035 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7910 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,08-22 11:15:19.165  1022  1329 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-22 11:15:19.175  3222  7924 D BluetoothSocket: bindListen(): myUserId = 0,
,08-22 11:15:19.175  3222  7924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 11:15:19.185  3222  7924 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
08-22 11:15:19.185  3222  7924 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 11:15:19.185  3222  7924 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 11:15:19.185  3222  7924 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@30d38d97
,08-22 11:15:19.185  3222  7924 D BluetoothSocket: channel: 12
08-22 11:15:19.185  3222  7924 I BtOppRfcommListener: Accept thread started.
,08-22 11:15:19.185  7910  7910 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:15:19.185   314   314 I art     : Explicit concurrent mark sweep GC freed 8688(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 21.205ms
08-22 11:15:19.185  7910  7910 D ActivityThread: Added TimaKeyStore provider,
,08-22 11:15:19.205   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 16.740ms
,08-22 11:15:19.215   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 16.530ms,
,08-22 11:15:19.315   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-22 11:15:19.315   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:19.315  7910  7931 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-22 11:15:19.325   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-22 11:15:19.325   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:19.325  7910  7931 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-22 11:15:19.365  1022  3388 D SSRM:n  : SIOP:: AP = 350
,08-22 11:15:19.415   291   291 E SMD     : DCD OFF
,08-22 11:15:19.465  7910  7910 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-22 11:15:19.465  7910  7910 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:19.465  7910  7910 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:19.465  7910  7910 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.q.e.b(PG:170)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:19.465  7910  7910 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.q.k.d(PG:583)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.q.e.b(PG:170)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:19.465  7910  7910 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:19.465  7910  7910 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:19.475  1022  1035 I ActivityManager: Killing 7518:com.sec.pcw.device/1000 (adj 15): empty #21
08-22 11:15:19.465  7910  7910 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:19.465  7910  7910 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-22 11:15:19.545  7910  7937 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-22 11:15:19.715  1022  1491 I art     : Explicit concurrent mark sweep GC freed 70026(3MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 22MB/34MB, paused 2.298ms total 159.169ms
,08-22 11:15:19.715  1022  4370 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:19.715  1022  4370 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:19.715  1022  4370 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:19.715  1022  4370 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-22 11:15:20.435  1022  3416 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-22 11:15:21.435   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 11:15:21.745  6740  7157 D BluetoothAdapter: disable()
,08-22 11:15:21.745  1022  4368 D SettingsProvider: name = bluetooth_on
,08-22 11:15:21.755  3222  3294 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-22 11:15:21.755  3222  3294 D BluetoothAdapterProperties: Setting state to 13
,08-22 11:15:21.755  3222  3294 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-22 11:15:21.755  3222  3294 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-22 11:15:21.755  3222  3294 D BluetoothAdapterService: updateAdapterState state is 13
,08-22 11:15:21.755  1022  4370 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:21.755  1022  4370 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.765  1022  4370 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:21.765  1022  4370 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:21.765  1022  4370 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:21.765  3222  3222 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-22 11:15:21.765  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@19017b84, channel: 19, state: LISTENING
08-22 11:15:21.765  3222  3294 D BluetoothAdapterService: Autoconnection is available 
08-22 11:15:21.765  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@19017b84, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ed7aeb5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@255bff6dmSocket: android.net.LocalSocket@2b4d27a2 impl:android.net.LocalSocketImpl@3b396c33 fd:FileDescriptor[80]
08-22 11:15:21.765  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2b4d27a2 impl:android.net.LocalSocketImpl@3b396c33 fd:FileDescriptor[80]
,08-22 11:15:21.765  1022  1022 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:21.765  1022  1022 I InputMethodManagerService: [BT Setting State] State =13
08-22 11:15:21.765  3222  3294 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-22 11:15:21.765  3222  3294 D BluetoothAdapterService: terminating service from this receiver
,08-22 11:15:21.775  1184  1184 D BluetoothTile:  onBluetoothStateChange:,
08-22 11:15:21.775  1184  1184 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 11:15:21.775  1184  1184 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:21.775  1184  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:21.775  1184  1184 D BluetoothTile:  getBluetoothState : 13
,08-22 11:15:21.775  1184  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:21.785  1884  1884 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 11:15:21.785  1184  1754 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-22 11:15:21.785  1022  1492 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:21.785  4835  4835 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:21.785  1022  1223 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 11:15:21.785  1184  1184 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 11:15:21.795  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:21.795  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:21.795  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:21.795  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:21.795  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:21.795  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:21.795  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:21.795  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:21.795  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:21.795  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:21.795  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:21.795  1022  4367 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.805  1022  4367 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:21.805  1022  4367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-22 11:15:21.805  1022  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:21.805  4835  4835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:21.805  3222  3294 D BluetoothAdapterProperties: onBluetoothDisable()
08-22 11:15:21.805  1022  4371 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-22 11:15:21.805  3222  3294 D BluetoothAdapterProperties: mDiscovering is false
08-22 11:15:21.805  1022  4371 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.805  1022  1486 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-22 11:15:21.815  3222  3294 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-22 11:15:21.815  1022  4371 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:21.815  1022  4371 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:21.815  1022  4371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-22 11:15:21.815  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:21.815  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:21.815  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:21.815  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:21.815  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:21.815  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:21.815  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:21.815  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:21.815  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:21.815  6740  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:21.815  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:21.825  4835  4835 D BluetoothPbap: Proxy object disconnected
08-22 11:15:21.825  4835  4835 D PbapServerProfile: Bluetooth service disconnected
,08-22 11:15:21.825  3222  3297 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 11:15:21.825  3222  3297 D BluetoothAdapterProperties: Scan Mode:20
,08-22 11:15:21.825  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:21.835  2652  2652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:21.835  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:21.835  3222  3294 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-22 11:15:21.835  3222  3294 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-22 11:15:21.835  3222  3294 E bt-btif : cmd socket is not created
08-22 11:15:21.835  3222  7924 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-22 11:15:21.835  3222  3298 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-22 11:15:21.835  3222  3294 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-22 11:15:21.835  4835  4835 D DockEventReceiver: finishStartingService: stopping service,
,08-22 11:15:21.845  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@18dccbf0, channel: 5, state: LISTENING
08-22 11:15:21.845  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@18dccbf0, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f5a0bb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7c62569mSocket: android.net.LocalSocket@6fa1bee impl:android.net.LocalSocketImpl@3514988f fd:FileDescriptor[82]
08-22 11:15:21.845  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@6fa1bee impl:android.net.LocalSocketImpl@3514988f fd:FileDescriptor[82]
08-22 11:15:21.845  3222  3222 I BtOppRfcommListener: stopping Accept Thread
08-22 11:15:21.845  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2ddab71c, channel: 12, state: LISTENING
08-22 11:15:21.845  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2ddab71c, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@30d38d97, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2592af25mSocket: android.net.LocalSocket@c7008fa impl:android.net.LocalSocketImpl@19cc2eab fd:FileDescriptor[85]
08-22 11:15:21.845  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@c7008fa impl:android.net.LocalSocketImpl@19cc2eab fd:FileDescriptor[85]
,08-22 11:15:21.845  3222  7924 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-22 11:15:21.845  4835  4835 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:21.855  3222  3222 V BluetoothOppManager: cleanUp...
,08-22 11:15:21.855  3222  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-22 11:15:21.855  3222  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-22 11:15:21.855  3222  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 11:15:21.855  3222  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-22 11:15:21.855  3222  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 11:15:21.855  3222  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-22 11:15:21.865  1184  1184 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:21.865  1184  1184 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-22 11:15:22.045  3222  3294 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-22 11:15:22.045  3222  3294 D BtConfig.SecureMode: isSecureModeOn:false
08-22 11:15:22.045  3222  3294 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-22 11:15:22.045  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-22 11:15:22.045  3222  3294 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-22 11:15:22.045  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-22 11:15:22.045  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 11:15:22.045  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-22 11:15:22.045  1022  1034 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:22.045  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.045  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.045  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:22.045  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.045  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-22 11:15:22.045  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-22 11:15:22.045  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-22 11:15:22.045  1022  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:22.045  1022  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.045  1022  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.045  1022  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:22.055  1022  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.055  3222  3222 D HeadsetService: Received stop request...Stopping profile...
,08-22 11:15:22.055  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-22 11:15:22.055  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:22.055  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-22 11:15:22.055  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
08-22 11:15:22.055  1022  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:22.055  1022  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.055  1022  1486 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:22.055  1022  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.055  1022  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.055  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-22 11:15:22.055  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 11:15:22.055  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-22 11:15:22.055  1022  1022 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-22 11:15:22.065  1022  1035 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-22 11:15:22.065  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.065  4835  4835 D HeadsetProfile: Bluetooth service disconnected
08-22 11:15:22.065  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.065  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:22.065  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.065  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-22 11:15:22.065  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-22 11:15:22.065  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-22 11:15:22.065  1022  1141 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:22.065  1022  1141 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.065  1022  1141 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.065  1022  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:22.065  1022  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.075  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-22 11:15:22.075  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-22 11:15:22.075  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-22 11:15:22.075  1022  4370 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:22.075  1022  4370 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.075  1022  4370 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.075  1022  4370 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.075  1022  4370 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.075  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-22 11:15:22.075  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-22 11:15:22.075  3222  3294 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-22 11:15:22.085  1022  1034 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:22.085  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.085  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.085  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.085  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.085  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:22.085  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:22.085  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:22.085  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-22 11:15:22.085  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:22.085  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-22 11:15:22.085  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 11:15:22.085  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-22 11:15:22.085  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 11:15:22.085  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,08-22 11:15:22.085  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 11:15:22.085  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService,
08-22 11:15:22.085  3222  3294 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-22 11:15:22.085  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-22 11:15:22.085  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:22.085  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-22 11:15:22.095  3222  3222 D A2dpService: Received stop request...Stopping profile...
,08-22 11:15:22.095  3222  7890 D A2dpStateMachine: Exit Disconnected: -1
,08-22 11:15:22.095  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:22.095  1022  1022 D BluetoothA2dp: Proxy object disconnected
08-22 11:15:22.095  1022  1022 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-22 11:15:22.095  4835  4835 D BluetoothA2dp: Proxy object disconnected
,08-22 11:15:22.095  4835  4835 D A2dpProfile: Bluetooth service disconnected
08-22 11:15:22.095  3222  3222 D HidService: Received stop request...Stopping profile...
08-22 11:15:22.095  3222  3222 D HidService: Stopping Bluetooth HidService
08-22 11:15:22.095  3222  3222 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 11:15:22.095  3222  3222 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-22 11:15:22.095  3222  3222 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 11:15:22.095  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:22.095  3222  3222 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-22 11:15:22.095  3222  3222 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-22 11:15:22.095  4835  4835 D BluetoothInputDevice: Proxy object disconnected
08-22 11:15:22.095  4835  4835 D HidProfile: Bluetooth service disconnected
,08-22 11:15:22.105  3222  3222 D HealthService: Received stop request...Stopping profile...
,08-22 11:15:22.105  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:22.105  3222  3222 D PanService: Received stop request...Stopping profile...
,08-22 11:15:22.105  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:22.105  1022  1022 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-22 11:15:22.105  3222  3222 D BluetoothMapService: Received stop request...Stopping profile...
08-22 11:15:22.105  4835  4835 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-22 11:15:22.105  4835  4835 D PanProfile: Bluetooth service disconnected
,08-22 11:15:22.105  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:22.115  4835  4835 D BluetoothMap: Proxy object disconnected
,08-22 11:15:22.115  3222  3222 D SapService: Received stop request...Stopping profile...
08-22 11:15:22.115  4835  4835 D MapProfile: Bluetooth service disconnected
,08-22 11:15:22.115  3222  3222 D SapService: Stopping Bluetooth SapService
08-22 11:15:22.115  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:22.115  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-22 11:15:22.115  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-22 11:15:22.115  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-22 11:15:22.115  3222  3222 D BluetoothA2dp: Proxy object disconnected,
,08-22 11:15:22.115  3222  3222 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-22 11:15:22.115  3222  7891 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-22 11:15:22.115  4835  4835 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-22 11:15:22.115  4835  4835 D SapProfile: Bluetooth service disconnected
08-22 11:15:22.115  3222  3222 I GKI_LINUX: GKI_exit_task 2 done
08-22 11:15:22.115  3222  3222 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-22 11:15:22.115  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-22 11:15:22.115  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 11:15:22.115  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:22.115  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:22.115  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-22 11:15:22.115  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 11:15:22.115  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:22.115  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:22.115  3222  3222 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-22 11:15:22.115  3222  3222 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-22 11:15:22.115  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-22 11:15:22.115  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 11:15:22.115  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:22.115  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:22.115  3222  3222 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 11:15:22.115  3222  3222 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-22 11:15:22.115  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-22 11:15:22.115  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-22 11:15:22.115  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 11:15:22.115  3222  3222 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-22 11:15:22.115  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-22 11:15:22.115  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-22 11:15:22.125  3222  3222 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-22 11:15:22.125  3222  3222 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-22 11:15:22.125  3222  3294 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-22 11:15:22.125  3222  3294 D BluetoothAdapterProperties: Setting state to 10
08-22 11:15:22.125  3222  3294 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-22 11:15:22.125  3222  3294 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 11:15:22.125  3222  3294 D BluetoothAdapterService: updateAdapterState state is 10
,08-22 11:15:22.125  3222  7905 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 11:15:22.125  3222  3294 D BluetoothAdapterService: Autoconnection is available 
08-22 11:15:22.125  3222  3294 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-22 11:15:22.125  3222  3294 I BluetoothAdapterState: Entering OffState
,08-22 11:15:22.125  4835  4846 D Bluetoothsap: onBluetoothStateChange: up=false
08-22 11:15:22.125  4835  4846 D Bluetoothsap: Unbinding service...
,08-22 11:15:22.125  1776  2011 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:22.125  1776  2011 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:22.125  1022  1051 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:22.125  1022  1051 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:22.125  4835  7374 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 11:15:22.125  4835  4846 D BluetoothPbap: onBluetoothStateChange: up=false
,08-22 11:15:22.125  1439  1463 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:22.125  1439  1463 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:22.125  7910  7928 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:22.125  7910  7928 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:22.135  1430  1438 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:22.135  1430  1438 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:22.135  1455  1474 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:22.135  1455  1474 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:22.135  3222  3355 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:22.135  3222  3355 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:22.135  4835  4849 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-22 11:15:22.135  4835  7374 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:22.135  4835  7374 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 11:15:22.135  1022  1051 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 11:15:22.135  6740  6750 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:22.135  6740  6750 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 11:15:22.135  6740  6750 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-22 11:15:22.135  6740  6750 D BluetoothLeAdvertiser: Exit stop advertising
,08-22 11:15:22.135  6740  6750 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-22 11:15:22.135  6740  6750 D BluetoothLeScanner: Exiting stopAllScan
,08-22 11:15:22.135  2652  2721 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:22.135  2652  2721 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:22.135  1184  3568 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:22.135  1184  3568 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:22.145  4835  4849 D BluetoothMap: onBluetoothStateChange: up=false
,08-22 11:15:22.145  1022  1022 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:22.145  1022  1022 I InputMethodManagerService: [BT Setting State] State =10
,08-22 11:15:22.145  1022  1022 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-22 11:15:22.155  1184  1184 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
08-22 11:15:22.155  1184  1184 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:22.155  1184  1184 D BluetoothTile:  getBluetoothState : 10
,08-22 11:15:22.155  1884  1884 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 11:15:22.155  4835  4835 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:22.155  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:22.155  1022  1492 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:22.155  1022  4371 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 11:15:22.155  1184  1184 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 11:15:22.155  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:22.165  4835  4835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:22.165  1022  1035 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-22 11:15:22.165  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.165  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.165  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.165  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 11:15:22.165  2652  2652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:22.175  4835  4835 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:22.175  4835  4835 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:22.175  1184  1184 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:22.175  1184  1184 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-22 11:15:22.425   291   291 E SMD     : DCD OFF
,08-22 11:15:22.425   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:15:23.425   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:15:23.515  1022  1492 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 11:15:23.515  1022  1492 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-22 11:15:23.515  1022  1492 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-22 11:15:23.515  1022  1492 D BatteryService: stay LED for charging
08-22 11:15:23.515  1022  1022 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 11:15:23.515  1184  1184 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 11:15:23.515  1022  1022 I MotionRecognitionService: Plugged
,08-22 11:15:23.515  1184  1184 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-22 11:15:23.515  1022  1022 I MotionRecognitionService: mGripSensorEnabled= false
08-22 11:15:23.525  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-22 11:15:23.525  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 11:15:23.545  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 11:15:23.545  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 11:15:23.545  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 11:15:24.425   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:15:24.765  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 11:15:24.765  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:25.425   291   291 E SMD     : DCD OFF
,08-22 11:15:25.425   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:15:26.425   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-22 11:15:27.765  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 11:15:27.765  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32ad1a00 added. We now have 6 listener(s)
08-22 11:15:27.765  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:27.775  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 11:15:27.775  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2da04239 added. We now have 7 listener(s)
,08-22 11:15:27.775  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:27.775  6740  7157 I System.out: IsBluetoothEnabled
,08-22 11:15:27.775  6740  7157 D BluetoothAdapter: disable()
,08-22 11:15:27.775  1022  1223 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-22 11:15:27.785  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:27.785  6740  7157 D BluetoothAdapter: enable()
,08-22 11:15:27.785  1022  1490 W ActivityManager: Permission Denial: getCurrentUser() from pid=6740, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-22 11:15:27.785  1022  1490 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-22 11:15:27.785  1022  1490 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6740, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-22 11:15:27.785  1022  1490 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 11:15:27.785  1022  1490 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-22 11:15:27.785  1022  1490 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-22 11:15:27.785  1022  1490 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-22 11:15:27.785  1022  1490 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 11:15:27.785  1022  1490 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-22 11:15:27.785  1022  1490 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 11:15:27.795  1022  1490 D SettingsProvider: name = bluetooth_on
,08-22 11:15:27.805  1022  1051 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-22 11:15:27.805  1022  1051 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 11:15:27.805  1022  1051 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-22 11:15:27.805  3222  3294 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-22 11:15:27.815  3222  3294 D BluetoothAdapterProperties: Setting state to 11
08-22 11:15:27.815  3222  3294 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-22 11:15:27.815  3222  3294 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 11:15:27.815  3222  3294 D BluetoothAdapterService: updateAdapterState state is 11
,08-22 11:15:27.815  3222  3294 D BluetoothAdapterService: Autoconnection is available 
08-22 11:15:27.815  3222  3294 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-22 11:15:27.815  3222  3294 D BtConfig.SecureMode: isSecureModeOn:false
08-22 11:15:27.815  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-22 11:15:27.815  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-22 11:15:27.815  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-22 11:15:27.815  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-22 11:15:27.815  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-22 11:15:27.815  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-22 11:15:27.815  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-22 11:15:27.815  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-22 11:15:27.815  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:27.815  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:27.815  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-22 11:15:27.815  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-22 11:15:27.815  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 11:15:27.815  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-22 11:15:27.815  1022  1022 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:27.815  1022  1022 I InputMethodManagerService: [BT Setting State] State =11
,08-22 11:15:27.825  1184  1184 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 11:15:27.825  1184  1184 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:27.825  1184  1184 D BluetoothTile:  getBluetoothState : 11
,08-22 11:15:27.825  1184  1754 D BluetoothTile:  handleUpdatestate:false name:null
08-22 11:15:27.825  1184  1754 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-22 11:15:27.825  1022  4371 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:27.835  1022  1141 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 11:15:27.835  1184  1184 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:27.835  1184  1184 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 11:15:27.835  1884  1884 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-22 11:15:27.835  4835  4835 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:27.845  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:27.845  1022  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:27.845  1022  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-22 11:15:27.845  1022  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:27.845  1022  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:27.845  1022  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:27.845  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-22 11:15:27.845  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 11:15:27.845  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-22 11:15:27.855  3222  3222 D HeadsetService: Received start request. Starting profile...
08-22 11:15:27.855  3222  3222 D HeadsetService: start()
08-22 11:15:27.855  3222  3222 D HeadsetStateMachine: make
,08-22 11:15:27.855  1022  1491 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:27.855  1022  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:27.855  1022  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:27.855  1022  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 11:15:27.855  1022  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 11:15:27.855  1022  4367 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:27.855  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-22 11:15:27.855  1022  4367 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-22 11:15:27.855  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:27.855  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-22 11:15:27.865  1022  4367 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:27.865  1022  4367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:27.865  1022  4367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:27.865  3222  3222 E HeadsetStateMachine: # of Max HF connection is 2
,08-22 11:15:27.865  2652  2652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:27.865  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-22 11:15:27.865  1022  1034 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-22 11:15:27.865  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 11:15:27.865  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-22 11:15:27.865  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-22 11:15:27.865  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:27.865  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:27.865  1022  1035 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:27.865  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-22 11:15:27.865  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-22 11:15:27.875  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:27.875  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:27.875  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:27.875  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-22 11:15:27.875  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-22 11:15:27.875  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-22 11:15:27.885  1022  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:27.885  1022  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 11:15:27.885  1022  1486 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:27.885  1022  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:27.885  1022  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:27.885  4835  4835 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:27.885  1022  1490 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-22 11:15:27.885  1022  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-22 11:15:27.885  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-22 11:15:27.885  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:27.885  3222  3294 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-22 11:15:27.885  1022  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:27.885  1022  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:27.885  1022  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-22 11:15:27.895  1022  1226 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:27.895  1022  1226 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 11:15:27.895  1022  1226 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:27.895  1022  1226 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:27.895  1022  1226 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:27.895  3222  3222 I bluedroid: get_profile_interface handsfree
08-22 11:15:27.895  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-22 11:15:27.895  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 11:15:27.895  3222  3294 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-22 11:15:27.905  1022  1223 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:27.905  1022  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-22 11:15:27.905  1184  1184 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:27.905  1184  1184 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-22 11:15:27.905  1022  1223 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:27.905  1022  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:27.905  1022  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:27.905  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:27.905  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:27.905  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:27.905  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:27.905  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:27.905  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:27.905  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 11:15:27.905  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 11:15:27.905  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 11:15:27.905  3222  3294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-22 11:15:27.905  3222  3294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 11:15:27.905  3222  3294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-22 11:15:27.905  3222  3294 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-22 11:15:27.915  3222  3222 E DualScoManager: Dual Sco Manager already instantiated
08-22 11:15:27.915  3222  3222 I DualScoManager: Set HeadsetServiceHelper
08-22 11:15:27.915  3222  3222 D BluetoothAtMessage: createCMTIContentObservers
,08-22 11:15:27.915  1022  1034 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-22 11:15:27.915  1022  1034 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:27.915  1022  1034 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:27.915  1022  1034 D SettingsProvider: selectionArgs: false
,08-22 11:15:27.915  1022  1034 D SettingsProvider: selectionArgs: 1002
08-22 11:15:27.915  1022  1034 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:27.915  1022  1034 D SettingsProvider: ret = -1
,08-22 11:15:27.915  3222  7955 D HeadsetStateMachine: Enter Disconnected: -2
,08-22 11:15:27.915  3222  3222 D HeadsetService: mStartError = false
,08-22 11:15:27.915  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:27.915  3222  3222 D A2dpService: Received start request. Starting profile...
08-22 11:15:27.915  3222  3222 D A2dpService: start()
08-22 11:15:27.925  3222  3222 I bluedroid: get_profile_interface avrcp
,08-22 11:15:27.925  3222  7955 D HeadsetStateMachine: Clear mHeadsetBrsf
08-22 11:15:27.925  3222  7955 D HeadsetStateMachine: map size, before remove : 0
08-22 11:15:27.925  3222  7955 D HeadsetStateMachine: map size, after remove: 0
,08-22 11:15:27.925  3222  3222 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-22 11:15:27.925  3222  3222 D Avrcp   : Initialize Media Controller
,08-22 11:15:27.925  3222  3222 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-22 11:15:27.935  3222  3222 E Avrcp   : getActiveSessions
08-22 11:15:27.935  3222  3222 D Avrcp   : pick active media Controller
08-22 11:15:27.935  3222  3222 D Avrcp   : Get the active Media Controller 
,08-22 11:15:27.935  3222  3222 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-22 11:15:27.935  3222  7956 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-22 11:15:27.935  3222  3222 D A2dpStateMachine: make
,08-22 11:15:27.945  3222  3222 I bluedroid: get_profile_interface a2dp
,08-22 11:15:27.945  3222  7958 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-22 11:15:27.945  3222  3222 E bt-btif : warning : media task started media_task_refcnt 1 
,08-22 11:15:27.945  3222  3222 D A2dpService: mStartError = false
08-22 11:15:27.945  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:27.945  3222  3222 D HidService: Received start request. Starting profile...
08-22 11:15:27.945  3222  7957 D A2dpStateMachine: Enter Disconnected: -2
08-22 11:15:27.945  3222  3222 D HidService: start()
08-22 11:15:27.945  3222  3222 I bluedroid: get_profile_interface hidhost
08-22 11:15:27.945  3222  3222 D HidService: setHidService(): set to: null
08-22 11:15:27.945  3222  3222 D HidService: mStartError = false
08-22 11:15:27.945  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
08-22 11:15:27.945  3222  3222 D HeadsetStateMachine: Try to query the phonestate on bind
,08-22 11:15:27.945  1430  1445 I Telecom : BluetoothPhoneService: queryPhoneState
,08-22 11:15:27.945  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-22 11:15:27.945  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-22 11:15:27.945  1430  1445 I Telecom : BluetoothPhoneService: Result of Message : true
,08-22 11:15:27.945  3222  3222 D HealthService: Received start request. Starting profile...
08-22 11:15:27.945  3222  3222 D HealthService: start()
,08-22 11:15:27.955  3222  7956 D BluetoothMediaBrowser: no now playing list
,08-22 11:15:27.955  3222  7956 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-22 11:15:27.955  3222  3222 I bluedroid: get_profile_interface health
,08-22 11:15:27.955  3222  3222 D HealthService: mStartError = false
,08-22 11:15:27.955  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:27.955  3222  3222 D HeadsetStateMachine: Proxy object connected
,08-22 11:15:27.955  3222  3222 D PanService: Received start request. Starting profile...
,08-22 11:15:27.955  3222  3222 D PanService: start()
08-22 11:15:27.955  3222  3222 D BluetoothPanServiceJni: initializeNative(L110): pan,
08-22 11:15:27.955  3222  3222 I bluedroid: get_profile_interface pan
08-22 11:15:27.955  3222  3222 D PanService: mStartError = false
08-22 11:15:27.955  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
08-22 11:15:27.955  3222  3222 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-22 11:15:27.955  3222  7955 D HeadsetStateMachine: Disconnected process message: 11
,08-22 11:15:27.955  3222  3222 D BluetoothMapService: Received start request. Starting profile...
,08-22 11:15:27.955  3222  3222 D BluetoothMapService: start()
,08-22 11:15:27.965  3222  3222 D BluetoothMapService: mStartError = false
,08-22 11:15:27.965  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:27.965  3222  3222 D SapService: Received start request. Starting profile...
08-22 11:15:27.965  3222  3222 D SapService: start()
08-22 11:15:27.965  3222  3222 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-22 11:15:27.965  3222  3222 I bluedroid: get_profile_interface sap
08-22 11:15:27.965  3222  3222 D SapService: mStartError = false
08-22 11:15:27.965  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
08-22 11:15:27.965  3222  3222 D HeadsetPhoneState: sendDeviceDataStateChanged
08-22 11:15:27.965  3222  3222 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-22 11:15:27.965  3222  3222 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-22 11:15:27.965  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-22 11:15:27.965  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-22 11:15:27.965  3222  7955 D HeadsetStateMachine: Disconnected process message: 18
08-22 11:15:27.965  3222  7955 D HeadsetStateMachine: Disconnected process message: 10
08-22 11:15:27.965  3222  7955 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-22 11:15:27.965  3222  7955 D HeadsetStateMachine: Disconnected process message: 11
,08-22 11:15:27.965  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-22 11:15:27.975  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-22 11:15:27.975  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-22 11:15:27.985  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-22 11:15:27.985  3222  3222 E BluetoothAdapterService(8835696): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-22 11:15:27.985  3222  3294 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-22 11:15:27.985  3222  3294 I bluedroid: enable
,08-22 11:15:27.995  3222  3297 E bt-btif : Calling BTA_HhEnable
,08-22 11:15:27.995  3222  3297 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-22 11:15:27.995  3222  3297 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-22 11:15:27.995  3222  3297 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-22 11:15:27.995  3222  3297 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-22 11:15:27.995  3222  3297 E BluetoothServiceJni: populateRssiValuesNative
08-22 11:15:27.995  3222  3297 I bluedroid: getModelRssiValues
,08-22 11:15:27.995  3222  3297 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-22 11:15:27.995  3222  3297 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-22 11:15:28.005  1022  1022 D SettingsProvider: name = bluetooth_name
,08-22 11:15:28.005  3222  3297 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-22 11:15:28.005  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:28.005  3222  3297 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 11:15:28.005  3222  3297 D BluetoothAdapterProperties: Scan Mode:20
08-22 11:15:28.005  3222  3297 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 11:15:28.005  3222  3297 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-22 11:15:28.005  3222  3297 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-22 11:15:28.005  3222  3297 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
08-22 11:15:28.005  3222  3297 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-22 11:15:28.005  3222  3297 E bt-btif : JVenable fails
,08-22 11:15:28.005  3222  3297 D bte_conf: Device ID record 1 : primary
08-22 11:15:28.005  3222  3297 D bte_conf:   vendorId            = 0075
08-22 11:15:28.005  3222  3297 D bte_conf:   vendorIdSource      = 0001
08-22 11:15:28.005  3222  3297 D bte_conf:   product             = 0100
08-22 11:15:28.005  3222  3297 D bte_conf:   version             = 0200
08-22 11:15:28.005  3222  3297 D bte_conf:   clientExecutableURL = 
08-22 11:15:28.005  3222  3297 D bte_conf:   serviceDescription  = 
08-22 11:15:28.005  3222  3297 D bte_conf:   documentationURL    = 
08-22 11:15:28.005  3222  3297 D bte_conf: bte_load_did_conf no section named DID2.
08-22 11:15:28.005  3222  3297 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-22 11:15:28.005  3222  3297 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-22 11:15:28.015  3222  3294 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-22 11:15:28.015  3222  3294 D BluetoothAdapterProperties: ScanMode =  20
08-22 11:15:28.015  3222  3294 D BluetoothAdapterProperties: State =  11
,08-22 11:15:28.015  1022  4368 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-22 11:15:28.015  3222  3294 D BluetoothAdapterProperties: Setting state to 12
,08-22 11:15:28.015  3222  3294 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-22 11:15:28.015  3222  3297 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 11:15:28.015  3222  3297 D BluetoothAdapterProperties: Scan Mode:21
08-22 11:15:28.015  3222  3297 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 11:15:28.015  1022  1492 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-22 11:15:28.015  1022  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:28.015  1022  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:28.025  1022  1492 D SettingsProvider: selectionArgs: false
08-22 11:15:28.025  1022  1492 D SettingsProvider: selectionArgs: 1002
,08-22 11:15:28.025  1022  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:28.025  1022  1492 D SettingsProvider: ret = -1
08-22 11:15:28.025  3222  3294 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-22 11:15:28.025  3222  3294 D BluetoothAdapterService: updateAdapterState state is 12
08-22 11:15:28.025  1022  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:28.025  1022  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 11:15:28.025  1022  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:28.025  1022  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:28.025  1022  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:28.025  3222  3294 D BluetoothAdapterService: Autoconnection is available 
,08-22 11:15:28.025  3222  3294 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-22 11:15:28.025  3222  3294 D BluetoothAdapterService: starting service from this receiver
,08-22 11:15:28.025  1022  4369 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:28.025  3222  7905 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 11:15:28.025  1022  4369 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-22 11:15:28.025  1022  4369 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:28.025  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:28.025  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:28.025  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:28.025  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:28.025  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:28.025  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:28.025  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:28.025  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:28.025  1022  4369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:28.035  1022  4369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:28.035  3222  3222 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-22 11:15:28.035  3222  3222 I BluetoothPbapService: Handler(): got msg=1
,08-22 11:15:28.035  3222  7905 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:28.035  1022  1490 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-22 11:15:28.035  3222  3294 I BluetoothAdapterState: Entering On State from state = 11
,08-22 11:15:28.035  1022  1051 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 11:15:28.035  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 11:15:28.035  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:28.035  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:28.035  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:28.045  3222  7964 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-22 11:15:28.045  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:28.045  4835  7374 D Bluetoothsap: onBluetoothStateChange: up=true
,08-22 11:15:28.045  4835  7374 D Bluetoothsap: Binding service...
,08-22 11:15:28.045  4835  7374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-22 11:15:28.045  3222  7964 D BluetoothSocket: bindListen(): myUserId = 0
08-22 11:15:28.045  3222  7964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:28.045  3222  3222 D BluetoothA2dp: Proxy object connected
08-22 11:15:28.045  3222  3222 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-22 11:15:28.045  1022  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-22 11:15:28.045  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 11:15:28.045  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:28.045  3222  7964 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-22 11:15:28.045  3222  7964 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 11:15:28.045  3222  7964 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 11:15:28.045  3222  7964 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c3d9f80
,08-22 11:15:28.045  3222  7964 D BluetoothSocket: channel: 19
08-22 11:15:28.045  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:28.045  3222  7964 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-22 11:15:28.045  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:28.045  4835  7374 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-22 11:15:28.055  1776  1785 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 11:15:28.055  1776  1785 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:28.055  4835  4835 D Bluetoothsap: BluetoothSAP Proxy object connected
08-22 11:15:28.055  4835  4835 D SapProfile: Bluetooth service connected
08-22 11:15:28.055  4835  4835 D Bluetoothsap: getConnectedDevices()
,08-22 11:15:28.055  4835  4849 D BluetoothPan: Binding service...
,08-22 11:15:28.055  1022  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-22 11:15:28.055  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 11:15:28.055  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:28.055  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:28.055  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:28.055  1022  1051 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:28.055  1022  1051 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:28.055  4835  4846 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 11:15:28.055  4835  4835 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 11:15:28.055  4835  4835 D PanProfile: Bluetooth service connected
,08-22 11:15:28.055  4835  4846 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:28.065  1022  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 11:15:28.065  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 11:15:28.065  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:28.065  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:28.065  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:28.065  4835  4849 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 11:15:28.065  1022  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-22 11:15:28.065  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 11:15:28.065  1022  1051 W ActivityManager: userId = 0, bbcId = -10000,
08-22 11:15:28.065  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:28.065  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-22 11:15:28.065  4835  4835 D BluetoothA2dp: Proxy object connected
08-22 11:15:28.065  4835  4835 D A2dpProfile: Bluetooth service connected
,08-22 11:15:28.065  1439  1469 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 11:15:28.065  1439  1469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:28.065  4835  4835 D BluetoothPbap: Proxy object connected
08-22 11:15:28.065  4835  4835 D PbapServerProfile: Bluetooth service connected
,08-22 11:15:28.065  1430  1438 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:28.075  1022  1051 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 11:15:28.075  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 11:15:28.075  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:28.075  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:28.075  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-22 11:15:28.075  1430  1438 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:28.075  7910  7927 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 11:15:28.075  7910  7927 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:28.075  1430  1445 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:28.075  1430  1445 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:28.075  1430  3359 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:28.075  1022  1051 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 11:15:28.075  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:28.075  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:28.075  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:28.075  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:28.075  1430  3359 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:28.085  1455  1465 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:28.085  1022  1051 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 11:15:28.085  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:28.085  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:28.085  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:28.085  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:28.085  1455  1465 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:28.085  1455  1474 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 11:15:28.085  1455  1474 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:28.085  1022  1051 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:28.085  1022  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 11:15:28.085  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:28.085  1022  1051 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:28.095  3222  7906 D BluetoothAdapter: onBluetoothStateChange: up=true,
08-22 11:15:28.095  3222  7906 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:28.095  4835  4849 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-22 11:15:28.095  1022  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-22 11:15:28.095  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-22 11:15:28.095  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:28.095  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:28.095  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:28.095  4835  7374 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 11:15:28.095  4835  7374 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:28.095  1022  1051 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 11:15:28.095  4835  4835 D BluetoothInputDevice: Proxy object connected
08-22 11:15:28.095  1022  1051 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-22 11:15:28.095  4835  4835 D HidProfile: Bluetooth service connected
08-22 11:15:28.095  1022  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 11:15:28.095  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 11:15:28.095  1022  1051 D BluetoothPan: Binding service...
08-22 11:15:28.095  1022  1022 D BluetoothA2dp: Proxy object connected
,08-22 11:15:28.095  6740  6752 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:28.095  1022  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-22 11:15:28.095  6740  6752 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:28.095  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-22 11:15:28.095  2652  2660 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 11:15:28.095  2652  2660 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:28.095  1184  1771 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:28.095  1184  1771 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:28.095  1022  1022 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 11:15:28.095  4835  4849 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:28.095  1022  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 11:15:28.095  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:28.095  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:28.095  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:28.095  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:28.105  4835  4849 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:28.105  4835  4835 D HeadsetProfile: Bluetooth service connected
,08-22 11:15:28.105  1430  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:28.105  1022  1051 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 11:15:28.105  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:28.105  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:28.105  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:28.105  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:28.105  1430  1445 E BluetoothHeadset: BluetoothHeadset service is binded
08-22 11:15:28.105  4835  4846 D BluetoothMap: onBluetoothStateChange: up=true
,08-22 11:15:28.105  1022  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-22 11:15:28.105  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 11:15:28.105  1022  1051 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:28.105  1022  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:28.105  1022  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:28.105  1022  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-22 11:15:28.105  1022  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-22 11:15:28.105  4835  4835 D BluetoothMap: Proxy object connected
08-22 11:15:28.105  4835  4835 D MapProfile: Bluetooth service connected
08-22 11:15:28.105  4835  4835 D BluetoothMap: getConnectedDevices()
,08-22 11:15:28.115  1022  1022 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:28.115  1022  1022 I InputMethodManagerService: [BT Setting State] State =12
08-22 11:15:28.115  1022  1022 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-22 11:15:28.115  1184  1184 D BluetoothTile:  onBluetoothStateChange:
,08-22 11:15:28.115  1184  1184 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 11:15:28.115  1184  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:28.125  1184  1184 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:28.125  1184  1184 D BluetoothTile:  getBluetoothState : 12
,08-22 11:15:28.125  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@29bdb494, true
,08-22 11:15:28.125  1184  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:28.125  1184  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:28.125  1430  1430 D BluetoothHeadset: registerMessageListener
,08-22 11:15:28.125  1884  1884 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 11:15:28.125  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:28.135  3222  3231 D HeadsetService: registerMessageListener
,08-22 11:15:28.135  3222  3231 D HeadsetService: registerMessageListener
,08-22 11:15:28.135  3222  7955 D HeadsetStateMachine: Disconnected process message: 70
08-22 11:15:28.135  3222  7955 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@29d619b9
,08-22 11:15:28.135  1022  4370 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:28.135  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-22 11:15:28.135  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-22 11:15:28.135  1022  1492 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-22 11:15:28.135  1184  1184 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-22 11:15:28.135  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-22 11:15:28.135  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-22 11:15:28.135  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-22 11:15:28.135  4835  4835 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:28.145  3222  7965 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-22 11:15:28.145  3222  7955 D HeadsetStateMachine: Disconnected process message: 9
08-22 11:15:28.145  3222  7955 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-22 11:15:28.145   283   699 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-22 11:15:28.145   283   699 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-22 11:15:28.145   283   699 V voice   : voice_set_parameters: exit with code(-2)
08-22 11:15:28.145   283   699 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-22 11:15:28.145   283   699 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-22 11:15:28.145   283   699 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-22 11:15:28.145   283   699 V audio_hw_primary: adev_set_parameters: exit
,08-22 11:15:28.145  3222  7955 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-22 11:15:28.145  4835  4835 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-22 11:15:28.145  4835  4835 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-22 11:15:28.145  4835  4835 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-22 11:15:28.145  4835  4835 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-22 11:15:28.145  3222  7965 D BluetoothSocket: bindListen(): myUserId = 0
,08-22 11:15:28.145  3222  7965 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:28.145  3222  7965 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,08-22 11:15:28.145  3222  7965 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 11:15:28.145  3222  7965 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 11:15:28.145  3222  7965 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a1581fe
08-22 11:15:28.145  3222  7965 D BluetoothSocket: channel: 5
,08-22 11:15:28.155  4835  4835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:28.155  1022  1490 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-22 11:15:28.155  1022  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 11:15:28.155  1022  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:28.155  1022  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:28.155  1022  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 11:15:28.165  2652  2652 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:28.165  4835  4835 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:28.165  4835  4835 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:28.175  1184  1184 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:28.175  1184  1184 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-22 11:15:28.175  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86d270
,08-22 11:15:28.175  3222  3222 D BtConfig.SecureMode: isSecureModeOn:false
,08-22 11:15:28.175  1022  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:28.175  1022  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-22 11:15:28.185  1022  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:28.185  1022  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:28.185  1022  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:28.185  1022  1034 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-22 11:15:28.195  3222  7970 D BluetoothSocket: bindListen(): myUserId = 0
08-22 11:15:28.195  3222  7970 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:28.195  3222  7970 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-22 11:15:28.195  3222  7970 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 11:15:28.195  3222  7970 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 11:15:28.195  3222  7970 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d43c00a
,08-22 11:15:28.195  3222  7970 D BluetoothSocket: channel: 12
,08-22 11:15:28.205  3222  7970 I BtOppRfcommListener: Accept thread started.
,08-22 11:15:28.425   291   291 E SMD     : DCD OFF
,08-22 11:15:28.825  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-22 11:15:28.825  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:28.825  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:28.825  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:28.825  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:28.825  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:28.825  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:28.825  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:28.825  6740  7157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
08-22 11:15:28.825  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:28.825  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@327fc07e added. We now have 8 listener(s)
,08-22 11:15:28.825  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:28.825  1022  1034 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-22 11:15:28.825  1022  1034 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-22 11:15:28.825  1022  1034 D SecContentProvider2: mCursor = null,
,08-22 11:15:28.835  1022  1034 D WifiService: setWifiEnabled: false pid=6740, uid=10170
,08-22 11:15:28.835  1022  1034 D SettingsProvider: name = wifi_on
,08-22 11:15:28.835  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:28.835  1022  4368 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 11:15:28.835  1022  4368 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-22 11:15:28.835  1022  4368 D SecContentProvider2: mCursor = null
,08-22 11:15:28.845  1022  4368 D WifiService: setWifiEnabled: true pid=6740, uid=10170
,08-22 11:15:28.845  1022  4368 W ActivityManager: Permission Denial: getCurrentUser() from pid=6740, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-22 11:15:28.845  1022  4368 W WifiService: Failed getting userId using ActivityManagerNative
08-22 11:15:28.845  1022  4368 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6740, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-22 11:15:28.845  1022  4368 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 11:15:28.845  1022  4368 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-22 11:15:28.845  1022  4368 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-22 11:15:28.845  1022  4368 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-22 11:15:28.845  1022  4368 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 11:15:28.845  1022  4368 D SettingsProvider: name = wifi_on
,08-22 11:15:28.845  1022  1131 E WifiHW  : ##################### set firmware type 0 #####################
,08-22 11:15:29.175  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
,08-22 11:15:29.175  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:29.175  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 11:15:29.175  1022  1049 D Tethering: interfaceAdded wlan0
,08-22 11:15:29.185  1022  1136 E Tethering: No numeric data
,08-22 11:15:29.195  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:29.195  1022  1128 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:29.195  1022  1136 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 11:15:29.195  1022  1136 D Tethering: clearTetheredNotification()
,08-22 11:15:29.195  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:29.195  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:29.195  1184  1184 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 11:15:29.195  1184  1184 D HotspotTile: updateTetherState():false, false
,08-22 11:15:29.195  1022  1049 D Tethering: interfaceAdded p2p0
,08-22 11:15:29.195  1022  1049 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-22 11:15:29.205  1022  1049 D Tethering: interfaceLinkStateChanged p2p0, false,
08-22 11:15:29.205  1022  1049 D Tethering: interfaceStatusChanged p2p0, false,
,08-22 11:15:29.205  1022  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-22 11:15:29.205  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:29.205  1022  1128 V NetworkStats: performPollLocked() took 16ms
,08-22 11:15:29.205  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:29.205  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:29.205   278   979 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-22 11:15:29.215   278   979 D SoftapController: Softap fwReload - Ok,
,08-22 11:15:29.215   278   979 D CommandListener: Setting iface cfg
08-22 11:15:29.215   278   979 D CommandListener: Trying to bring down wlan0
,08-22 11:15:29.215   278   979 D CommandListener: Clearing all IP addresses on wlan0,
,08-22 11:15:29.225  1022  1131 E WifiHW  : supplicant_name : p2p_supplicant
,08-22 11:15:29.235  1022  1131 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-22 11:15:29.245  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 11:15:29.245  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:29.245  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 11:15:29.245  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:29.245  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:29.245  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:29.245  1184  1184 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:29.245  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:29.245  1184  1184 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:29.245  1184  1184 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-22 11:15:29.245  1184  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-22 11:15:29.245  4835  4835 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:29.245  1184  1184 D HotspotTile: onReceive : 2, 0
,08-22 11:15:29.255  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:29.255  1022  4368 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 11:15:29.255  1022  4368 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:29.255  1022  4368 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:29.255  1022  4368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:29.255  1022  4368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:29.255  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 11:15:29.255  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 11:15:29.255  7500  7500 D SecurityLogAgent: StateMachine : Current State = 1
08-22 11:15:29.255  7500  7500 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 11:15:29.265  1640  1640 I Hs20UtilService: Starting #19
,08-22 11:15:29.265  1640  1714 I Hs20UtilService: Message received 5011
,08-22 11:15:29.275  7984  7984 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-22 11:15:29.275  7984  7984 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-22 11:15:29.275  7984  7984 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-22 11:15:29.285  7984  7984 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-22 11:15:29.295   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7984
08-22 11:15:29.295   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-22 11:15:29.295  7984  7984 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-22 11:15:29.295  7984  7984 I wpa_supplicant: ssSupport state is = 1
08-22 11:15:29.295  7984  7984 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-22 11:15:29.295  7984  7984 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
08-22 11:15:29.295   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7984
08-22 11:15:29.295   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-22 11:15:29.375  1022  3388 D SSRM:n  : SIOP:: AP = 330,
,08-22 11:15:29.435   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
08-22 11:15:29.435  7984  7984 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-22 11:15:29.475  7984  7984 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-22 11:15:29.475  7984  7984 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-22 11:15:29.485  7984  7984 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-22 11:15:29.485   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7984,
08-22 11:15:29.485   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-22 11:15:29.485  7984  7984 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-22 11:15:29.485  7984  7984 I wpa_supplicant: ssSupport state is = 1
08-22 11:15:29.485  7984  7984 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:29.485  7984  7984 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 11:15:29.485  7984  7984 E wpa_supplicant: SIM READ ERROR
08-22 11:15:29.485  7984  7984 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:29.485  7984  7984 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 11:15:29.485  7984  7984 E wpa_supplicant: SIM READ ERROR
08-22 11:15:29.485  7984  7984 I wpa_supplicant: Blacklist: Clear (all) 
08-22 11:15:29.485  7984  7984 I wpa_supplicant: wpa_default_ap_write_once
08-22 11:15:29.485  7984  7984 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-22 11:15:29.485  7984  7984 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:29.485  7984  7984 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-22 11:15:29.485  7984  7984 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:29.485  7984  7984 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-22 11:15:29.495  7984  7984 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-22 11:15:29.495  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:29.495  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:29.495  1022  1049 D Tethering: interfaceStatusChanged wlan0, false,
08-22 11:15:29.495  1022  1136 D Tethering: InitialState.processMessage what=4
08-22 11:15:29.495  1022  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-22 11:15:29.495  1022  1136 E Tethering: No numeric data
08-22 11:15:29.495  1184  1184 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 11:15:29.495  1022  1136 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 11:15:29.495  1184  1184 D HotspotTile: updateTetherState():false, false
08-22 11:15:29.495  1022  1136 D Tethering: clearTetheredNotification()
08-22 11:15:29.505  1022  1128 V NetworkStats: performPollLocked() took 3ms
08-22 11:15:29.495  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:29.495  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:29.495  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 11:15:29.505  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:29.505  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:29.505  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:29.535  7984  7984 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-22 11:15:29.725  7984  7984 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-22 11:15:29.725  7984  7984 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-22 11:15:29.735  7984  7984 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-22 11:15:29.735   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7984
,08-22 11:15:29.735   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-22 11:15:29.735  7984  7984 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-22 11:15:29.735  7984  7984 I wpa_supplicant: ssSupport state is = 1
08-22 11:15:29.745  7984  7984 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-22 11:15:29.745  7984  7984 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-22 11:15:29.755  7984  7984 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-22 11:15:29.755   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7984
08-22 11:15:29.755   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-22 11:15:29.755  7984  7984 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-22 11:15:29.755  7984  7984 I wpa_supplicant: ssSupport state is = 1,
08-22 11:15:29.755  7984  7984 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:29.765  1022  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-22 11:15:29.755  7984  7984 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 11:15:29.755  7984  7984 E wpa_supplicant: SIM READ ERROR
08-22 11:15:29.755  7984  7984 I wpa_supplicant: wpa_default_ap_write_once
08-22 11:15:29.755  7984  7984 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-22 11:15:29.755  7984  7984 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-22 11:15:29.765  1022  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 11:15:29.765  1022  1049 D Tethering: interfaceLinkStateChanged p2p0, false,
08-22 11:15:29.765  1022  1049 D Tethering: interfaceStatusChanged p2p0, false
08-22 11:15:29.765  1022  1049 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 11:15:29.765  1022  1049 D Tethering: interfaceStatusChanged p2p0, false
,08-22 11:15:29.875  7984  7984 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-22 11:15:29.875  7984  7984 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-22 11:15:29.935  7984  7984 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-22 11:15:29.935  7984  7984 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
08-22 11:15:29.935  7984  7984 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-22 11:15:29.945  1022  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-22 11:15:29.945  1022  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-22 11:15:29.945  7984  7984 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-22 11:15:29.955  7984  7984 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-22 11:15:29.955  7984  7984 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-22 11:15:29.955  7984  7984 E wpa_supplicant: SIM READ ERROR
,08-22 11:15:29.955  7984  7984 I wpa_supplicant: Blacklist: Clear (all) ,
,08-22 11:15:29.975  7984  7984 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-22 11:15:29.985  7984  7984 I wpa_supplicant: Skip scan - bUseNetwork false
,08-22 11:15:29.985  1022  1131 D WifiConfigStore: Loading config and enabling all networks ,
,08-22 11:15:29.995  4835  4835 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:29.995  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:29.995  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:29.995  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:29.995  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:29.995  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:29.995  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:29.995  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:29.995  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:29.995  1022  1131 E WifiConfigStore: Not a HS20
,08-22 11:15:30.005  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:30.005  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 11:15:30.005  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:30.005  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:30.005  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:30.005  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:30.005  1022  1035 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:30.005  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:30.005  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:30.005  1022  1131 D WifiNative-wlan0: callSECApiInt - ID [65]
08-22 11:15:30.005  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:30.005  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:30.005  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:30.005  1640  1640 I Hs20UtilService: Starting #20
,08-22 11:15:30.005  1640  1714 I Hs20UtilService: Message received 5011
,08-22 11:15:30.005  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:30.005  1184  1184 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:30.005  1184  1184 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-22 11:15:30.005  1184  1184 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:30.005  1022  1131 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-22 11:15:30.005  7984  7984 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-22 11:15:30.005  1184  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 11:15:30.005  7984  7984 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-22 11:15:30.015  7984  7984 I wpa_supplicant: reset timer : RESET_TIMER 0
08-22 11:15:30.015  7984  7984 I wpa_supplicant: P2P: Current p2p state = IDLE
08-22 11:15:30.015  7984  7984 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-22 11:15:30.015  7984  7984 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-22 11:15:30.015  7984  7984 I wpa_supplicant: First Scan Start
,08-22 11:15:30.015  7984  7984 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-22 11:15:30.015  1184  1184 D HotspotTile: onReceive : 3, 0
,08-22 11:15:30.015  1022  1131 D WifiNative-wlan0: Setting external_sim to 1
,08-22 11:15:30.015  1022  1131 D WifiStateMachine: Setting OUI to DA-A1-19
08-22 11:15:30.015  1022  1131 I WifiNative-HAL: startHal
08-22 11:15:30.015  1022  1131 E wifi    : getStaticLongField sWifiHalHandle 0x9ef3e88c
08-22 11:15:30.015  1022  1131 I WifiNative-HAL: Could not start hal
,08-22 11:15:30.015  7477  7477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 11:15:30.015  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 11:15:30.015  7500  7500 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-22 11:15:30.015  1022  1131 E WifiNative-wlan0: do suspend true
,08-22 11:15:30.015  7500  7500 D SecurityLogAgent: StateMachine : Current State = 1
,08-22 11:15:30.015  7500  7500 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-22 11:15:30.015  1022  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-22 11:15:30.025  1022  1022 D WifiScanningService: SCAN_AVAILABLE : 3
08-22 11:15:30.025  1022  1130 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-22 11:15:30.025  1022  1022 D RttService: SCAN_AVAILABLE : 3
,08-22 11:15:30.025  1022  1157 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 11:15:30.025  1022  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-22 11:15:30.025  1022  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 11:15:30.025  1022  1131 E WifiNative-wlan0: invaild command id : 215
,08-22 11:15:30.025  1022  1156 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:30.025  1022  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-22 11:15:30.025  1022  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 11:15:30.025  1022  1131 E WifiNative-wlan0: invaild command id : 215
,08-22 11:15:30.025  1022  1156 I WifiNative-HAL: startHal
08-22 11:15:30.025  1022  1156 E wifi    : getStaticLongField sWifiHalHandle 0x9de009bc
08-22 11:15:30.025  1022  1156 I WifiNative-HAL: Could not start hal
08-22 11:15:30.025  1022  1156 E WifiScanningService: could not start HAL
,08-22 11:15:30.025  7984  7984 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 11:15:30.025   278   979 D CommandListener: Setting iface cfg
08-22 11:15:30.025   278   979 D CommandListener: Trying to bring up p2p0
,08-22 11:15:30.025  1022  1130 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-22 11:15:30.025  7984  7984 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 11:15:30.025  1022  1130 D WifiP2pService: P2pEnablingState
08-22 11:15:30.025  1022  1130 D WifiP2pService: P2pEnablingState{ what=147457 }
08-22 11:15:30.025  1022  1130 D WifiP2pService: P2p socket connection successful
,08-22 11:15:30.025  7984  7984 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-22 11:15:30.025  1022  1130 D WifiP2pService: P2pEnabledState
08-22 11:15:30.025  1022  1131 E WifiStateMachine: Failed to set frequency band 0
,08-22 11:15:30.025  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:30.025  1022  1131 D SecContentProvider2: mCursor = null
,08-22 11:15:30.035  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:30.035  1022  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-22 11:15:30.035  1022  1131 D SecContentProvider2: mCursor = null
,08-22 11:15:30.035  1022  1133 E ConnectivityService: updateNetworkInfo(),
,08-22 11:15:30.035  1022  1022 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-22 11:15:30.035  1022  1052 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-22 11:15:30.035  1022  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-22 11:15:30.035  1022  1052 D WifiDisplayController: disconnect
08-22 11:15:30.035  1022  1052 D WifiDisplayController: updateConnection
08-22 11:15:30.035  1022  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-22 11:15:30.035  1022  1052 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 11:15:30.045  1022  1130 D WifiNative-p2p0: p2pGetDeviceAddress
,08-22 11:15:30.045  1022  1130 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-22 11:15:30.045  4835  4835 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-22 11:15:30.045  4835  4835 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:30.045  1022  1052 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 11:15:30.045  1022  1052 D WifiDisplayAdapter: onP2pDisconnected
08-22 11:15:30.045  1022  1052 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 11:15:30.045  1022  1052 D IpRemoteDisplayController: WfdBridgeServer is already null
08-22 11:15:30.045  1022  1130 D WifiP2pService: DeviceAddress: 0a:75:42
,08-22 11:15:30.045  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 11:15:30.045  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 11:15:30.045  1184  1184 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-22 11:15:30.045  1022  1492 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 11:15:30.045  1184  1184 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-22 11:15:30.045  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-22 11:15:30.045  4835  4835 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 11:15:30.045  4835  4903 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-22 11:15:30.045  1022  1052 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-22 11:15:30.045  1022  1052 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-22 11:15:30.045  1022  1052 D WifiDisplayController:  primary type: 10-0050F204-5
08-22 11:15:30.045  1022  1052 D WifiDisplayController:  secondary type: null
08-22 11:15:30.045  1022  1052 D WifiDisplayController:  wps: 0
08-22 11:15:30.045  1022  1052 D WifiDisplayController:  grpcapab: 0
08-22 11:15:30.045  1022  1052 D WifiDisplayController:  devcapab: 0
08-22 11:15:30.045  1022  1052 D WifiDisplayController:  status: 3
08-22 11:15:30.045  1022  1052 D WifiDisplayController:  wfdInfo: null
08-22 11:15:30.045  1022  1052 D WifiDisplayController:  groupownerAddress: null
08-22 11:15:30.045  1022  1052 D WifiDisplayController:  GOdeviceName: null
08-22 11:15:30.045  1022  1052 D WifiDisplayController:  interfaceAddress: 
08-22 11:15:30.045  1022  1052 D WifiDisplayController:  SConnectInfo : null
,08-22 11:15:30.055  7826  7826 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:30.055  7826  7826 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-22 11:15:30.055  7826  7826 D FileShare-Client: Outbound.stopDelayTimer - 
,08-22 11:15:30.065  7461  7461 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:30.065  1022  1130 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-22 11:15:30.065  1022  1130 D WifiP2pService: InactiveState
08-22 11:15:30.065  1022  1130 D WifiP2pService: InactiveState{ what=143376 }
08-22 11:15:30.065  1022  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-22 11:15:30.065  7984  7984 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 11:15:30.065  1022  1130 D WifiP2pService: InactiveState{ what=143376 }
08-22 11:15:30.065  1022  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-22 11:15:30.175  1022  1049 D Tethering: interfaceLinkStateChanged p2p0, false
,08-22 11:15:30.175  1022  1049 D Tethering: interfaceStatusChanged p2p0, false
,08-22 11:15:30.175  1022  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-22 11:15:30.865  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:30.865  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:30.865  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:30.865  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:30.865  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:30.865  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:30.865  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:30.865  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:30.865  6740  7157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:30.875  6740  7157 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-22 11:15:30.875  6740  7157 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-22 11:15:30.875  6740  7157 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1c40a71e Bundle[{}]
,08-22 11:15:30.875  6740  7157 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 11:15:30.875  6740  7157 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-22 11:15:30.875  6740  7157 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-22 11:15:30.875  6740  7157 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-22 11:15:30.885  6740  7157 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-22 11:15:30.885  6740  7157 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-22 11:15:30.885  6740  7157 I System.out: Running OutgoingSocketThread
,08-22 11:15:30.885  6740  7992 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1349)
,08-22 11:15:30.895  6740  7992 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42252
,08-22 11:15:30.895  6740  7992 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-22 11:15:31.235  7984  7984 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
08-22 11:15:31.235  7984  7984 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-22 11:15:31.235  7984  7984 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-22 11:15:31.235  7984  7984 I wpa_supplicant: Trying to associate with  'G700'
,08-22 11:15:31.235  7984  7984 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-22 11:15:31.235  7984  7984 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
08-22 11:15:31.235  1022  7989 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-22 11:15:31.255  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:31.255  1022  1131 D SecContentProvider2: mCursor = null
,08-22 11:15:31.345  7984  7984 E wpa_supplicant: Cmd 35605 not handled
,08-22 11:15:31.355  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:31.355  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:31.355  7984  7984 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-22 11:15:31.355  7984  7984 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-22 11:15:31.355  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:31.355  7984  7984 I wpa_supplicant: Associated with F4.99.3E
08-22 11:15:31.355  7984  7984 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-22 11:15:31.355  7984  7984 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-22 11:15:31.355  7984  7984 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-22 11:15:31.355  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:31.355  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:31.355  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:31.355  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, false,
08-22 11:15:31.355  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:31.355  1022  1049 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:31.355  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, true
08-22 11:15:31.355  1022  1049 D Tethering: interfaceStatusChanged wlan0, true
,08-22 11:15:31.365  7984  7984 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-22 11:15:31.365  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-22 11:15:31.365  7984  7984 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-22 11:15:31.365  7984  7984 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-22 11:15:31.365  7984  7984 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-22 11:15:31.365  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:31.365  1022  1131 D SecContentProvider2: mCursor = null
08-22 11:15:31.365  7984  7984 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-22 11:15:31.365  7984  7984 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-22 11:15:31.365  7984  7984 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-22 11:15:31.365  7984  7984 I wpa_supplicant: Blacklist: Clear (temp) 
08-22 11:15:31.365  7984  7984 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-22 11:15:31.365  1022  1136 E Tethering: No numeric data
,08-22 11:15:31.365  1022  1136 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 11:15:31.365  1022  1049 D Tethering: interfaceLinkStateChanged wlan0, true
08-22 11:15:31.365  1022  1136 D Tethering: clearTetheredNotification()
08-22 11:15:31.365  1022  1049 D Tethering: interfaceStatusChanged wlan0, true
,08-22 11:15:31.365  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 11:15:31.365  1022  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-22 11:15:31.365  1022  1131 D SecContentProvider2: mCursor = null
,08-22 11:15:31.375  1022  1128 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:31.375  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:31.375  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:31.375  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:31.375  1184  1184 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 11:15:31.375  1184  1184 D HotspotTile: updateTetherState():false, false
,08-22 11:15:31.375  1022  1128 V NetworkStats: performPollLocked() took 6ms
,08-22 11:15:31.385  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:31.385  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:31.385  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:31.385  1022  1131 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-22 11:15:31.385  1022  1131 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-22 11:15:31.395  1022  1131 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-22 11:15:31.395  1022  1133 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-22 11:15:31.395  1022  1133 E ConnectivityService: updateNetworkInfo()
,08-22 11:15:31.395  1022  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-22 11:15:31.395  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 11:15:31.395  1022  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:31.395  1022  1223 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:31.395  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:31.395  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:31.395  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:31.395  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:31.395  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:31.395  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:31.395  1022  1223 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:31.395  1022  1223 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:31.395  1022  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:31.395  1022  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:31.405  1640  1640 I Hs20UtilService: Starting #21
,08-22 11:15:31.405  1640  1714 I Hs20UtilService: Message received 5007
,08-22 11:15:31.405  4835  4835 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-22 11:15:31.405  4835  4835 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
08-22 11:15:31.405  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 11:15:31.405  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 11:15:31.405  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-22 11:15:31.405  4835  4835 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 11:15:31.415  1022  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:31.415  4835  4903 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 11:15:31.425   291   291 E SMD     : DCD OFF
,08-22 11:15:31.425   278   979 D CommandListener: Setting iface cfg
,08-22 11:15:31.425  1022  1131 E WifiStateMachine: Start Dhcp Watchdog 3
,08-22 11:15:31.425  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 11:15:31.435  1022  1131 D SecContentProvider2: mCursor = null
,08-22 11:15:31.435  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 11:15:31.445  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-22 11:15:31.445  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-22 11:15:31.445  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:31.445  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:31.445  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:31.445  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:31.445  1022  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:31.445  1022  1131 D SecContentProvider2: mCursor = null
,08-22 11:15:31.445  1022  1131 E WifiNative-wlan0: do suspend false
,08-22 11:15:31.455  1022  1130 D WifiP2pService: InactiveState{ what=143375 }
,08-22 11:15:31.455  1022  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 11:15:31.665  7995  7995 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-22 11:15:31.675  7995  7995 I dhcpcd  : version 5.5.6 starting
,08-22 11:15:31.675  7995  7995 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-22 11:15:31.735  7995  7995 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-22 11:15:31.735  7995  7995 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-22 11:15:31.735  7995  7995 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-22 11:15:31.735  7995  7995 I dhcpcd  : bssid match,
08-22 11:15:31.735  7995  7995 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-22 11:15:31.845  7995  7995 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-22 11:15:31.895  6740  7157 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1350)
08-22 11:15:31.895  6740  7157 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1350)
,08-22 11:15:31.895  6740  7157 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1355)
08-22 11:15:31.895  6740  7157 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
08-22 11:15:31.895  6740  7157 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1356)
08-22 11:15:31.895  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 11:15:31.895  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f89df added. We now have 2 listener(s)
,08-22 11:15:31.905  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-22 11:15:31.905  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 11:15:31.905  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 11:15:31.905  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:31.905  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc9d62c added. We now have 9 listener(s),
08-22 11:15:31.905  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:31.905  7995  7995 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,08-22 11:15:31.905  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:15:31.905  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:31.915  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:31.915  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:31.915  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:31.915  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:31.915  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:31.915  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
08-22 11:15:31.915  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:31.915  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:31.915  6740  7157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 11:15:31.915  6740  7157 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-22 11:15:31.915  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:31.915  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3853668a added. We now have 3 listener(s)
,08-22 11:15:31.925  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:31.925  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-22 11:15:31.925  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:31.925  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:31.925  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:31.925  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d7ce4fb added. We now have 10 listener(s)
08-22 11:15:31.925  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:31.925  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:31.925  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:31.925  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:31.925  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:31.925  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:31.925  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:31.925  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:31.925  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-22 11:15:31.925  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f89df removed from the list
08-22 11:15:31.925  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:31.925  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc9d62c removed from the list
08-22 11:15:31.925  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:31.925  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:31.925  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:31.925  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:31.935  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 11:15:31.935  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:31.935  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:31.935  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fc9d62c not in the list
08-22 11:15:31.935  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:31.935  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:31.945  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:31.945  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:31.945  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:31.945  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d7ce4fb removed from the list
08-22 11:15:31.945  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:31.945  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:31.945  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:31.945  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 11:15:31.945  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3853668a removed from the list
08-22 11:15:31.945  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:31.945  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11142918 added. We now have 2 listener(s)
,08-22 11:15:31.945  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-22 11:15:31.945  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:31.945  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:31.945  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:31.945  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aaaff71 added. We now have 9 listener(s)
08-22 11:15:31.945  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:31.945  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:15:31.945  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:31.955  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:31.955  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:31.955  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:31.955  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:31.955  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:31.955  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:31.955  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:31.955  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:31.955  6740  7157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-22 11:15:31.955  6740  7157 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:31.955  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:31.955  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@192ad5d7 added. We now have 3 listener(s)
,08-22 11:15:31.965  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:31.965  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-22 11:15:31.965  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-22 11:15:31.965  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:31.965  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:31.965  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3faebec4 added. We now have 10 listener(s),
08-22 11:15:31.965  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:31.965  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:31.965  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-22 11:15:31.965  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:31.965  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:31.965  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 11:15:31.965  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:31.975  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 11:15:31.975  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 11:15:31.985  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 11:15:31.985  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 11:15:31.985  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 11:15:31.985  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:31.995  3222  3245 D BtGatt.GattService: registerClient() - UUID=919a4fd2-f3c0-4586-a383-56600fb38bfc
,08-22 11:15:32.035  3222  3297 D BtGatt.GattService: onClientRegistered() - UUID=919a4fd2-f3c0-4586-a383-56600fb38bfc, clientIf=6,
,08-22 11:15:32.035  6740  6752 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-22 11:15:32.035  3222  3355 D BtGatt.GattService: start scan with filters
08-22 11:15:32.035  3222  3358 D BtGatt.ScanManager: handling starting scan
,08-22 11:15:32.045  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 11:15:32.045  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 11:15:32.045  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 11:15:32.045  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:32.045  3222  3297 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-22 11:15:32.045  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:32.045  3222  3358 D BtGatt.ScanManager: allow scan with filters
08-22 11:15:32.045  3222  3358 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-22 11:15:32.045  3222  3358 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,08-22 11:15:32.045  3222  3297 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-22 11:15:32.045  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:32.045  3222  3358 D BtGatt.ScanManager: Starting BLE batch scan
08-22 11:15:32.045  3222  3358 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 11:15:32.055  3222  3297 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-22 11:15:32.055  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.055  3222  3297 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-22 11:15:32.055  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.065  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 11:15:32.065  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 11:15:32.065  6740  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:32.065  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:32.065  6740  7157 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 11:15:32.065  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:32.065  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 11:15:32.065  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.065  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 11:15:32.065  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 11:15:32.065  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:32.065  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:32.065  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 11:15:32.065  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 11:15:32.065  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 11:15:32.065  3222  7902 D BtGatt.GattService: stopScan() - queue size =1
,08-22 11:15:32.065  3222  3358 D BtGatt.ScanManager: filter size is 1
,08-22 11:15:32.065  3222  3358 D BtGatt.ScanManager: delete FilterIndex - 6
,08-22 11:15:32.075  3222  3231 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 11:15:32.075  3222  3297 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-22 11:15:32.075  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:32.075  3222  3358 D BtGatt.ScanManager: stopping BLe Batch
08-22 11:15:32.075  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-22 11:15:32.075  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:32.075  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 11:15:32.075  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-22 11:15:32.075  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 11:15:32.075  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:32.075  3222  3297 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 11:15:32.075  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.075  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 11:15:32.075  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 11:15:32.075  3222  3358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-22 11:15:32.075  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 11:15:32.075  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:32.085  3222  3297 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-22 11:15:32.085  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 11:15:32.085  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:32.085  6740  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:32.085  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.095  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:32.095  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:32.095  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:32.095  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:32.095  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:32.095  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:32.095  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:32.095  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11142918 removed from the list
08-22 11:15:32.095  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:32.095  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aaaff71 removed from the list
08-22 11:15:32.095  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 11:15:32.095  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:32.095  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.095  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:32.095  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:32.095  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:32.095  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:32.095  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aaaff71 not in the list
,08-22 11:15:32.095  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.095  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:32.105  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-22 11:15:32.105  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:32.105  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:32.105  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3faebec4 removed from the list
,08-22 11:15:32.105  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:32.105  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.105  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:32.105  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:32.105  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@192ad5d7 removed from the list
08-22 11:15:32.105  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:32.105  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@323b0330 added. We now have 2 listener(s)
,08-22 11:15:32.105  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-22 11:15:32.105  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 11:15:32.105  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:32.105  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:32.105  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5392ba9 added. We now have 9 listener(s)
08-22 11:15:32.105  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:32.105  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:15:32.115  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-22 11:15:32.115  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:32.115  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:32.115  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:32.115  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:32.115  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:32.115  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:32.115  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:32.115  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:32.125  6740  7157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-22 11:15:32.125  6740  7157 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 11:15:32.125  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:32.125  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f84a8cf added. We now have 3 listener(s)
,08-22 11:15:32.125  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-22 11:15:32.125  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:32.125  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:32.125  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:32.125  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2605225c added. We now have 10 listener(s)
08-22 11:15:32.125  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:32.125  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:32.125  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 11:15:32.125  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 11:15:32.125  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:32.125  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:32.125  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 11:15:32.125  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:32.135  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-22 11:15:32.135  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-22 11:15:32.145  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-22 11:15:32.145  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 11:15:32.145  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 11:15:32.145  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 11:15:32.145  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:32.145  3222  3231 D BtGatt.GattService: registerClient() - UUID=72dd8284-e413-4dd1-918a-1628d9d85ff4
,08-22 11:15:32.195  3222  3297 D BtGatt.GattService: onClientRegistered() - UUID=72dd8284-e413-4dd1-918a-1628d9d85ff4, clientIf=6,
08-22 11:15:32.195  6740  6750 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-22 11:15:32.195  3222  7905 D BtGatt.GattService: start scan with filters
08-22 11:15:32.195  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 11:15:32.195  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 11:15:32.195  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-22 11:15:32.195  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-22 11:15:32.195  3222  3358 D BtGatt.ScanManager: handling starting scan,
,08-22 11:15:32.195  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:32.195  6740  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:32.195  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 11:15:32.205  3222  3297 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-22 11:15:32.205  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.205  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:32.205  3222  3358 D BtGatt.ScanManager: allow scan with filters
,08-22 11:15:32.205  3222  3358 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-22 11:15:32.205  3222  3358 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-22 11:15:32.205  3222  3297 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-22 11:15:32.205  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.205  3222  3358 D BtGatt.ScanManager: Starting BLE batch scan
,08-22 11:15:32.205  3222  3358 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 11:15:32.215  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:32.215  6740  7157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-22 11:15:32.215  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:32.215  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:32.215  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:32.215  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:32.215  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.215  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 11:15:32.215  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:32.215  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@323b0330 removed from the list
08-22 11:15:32.215  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:32.215  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5392ba9 removed from the list
08-22 11:15:32.215  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:32.215  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:32.215  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.215  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-22 11:15:32.215  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.215  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:32.215  3222  3297 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-22 11:15:32.215  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.215  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 11:15:32.215  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:32.215  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:32.215  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5392ba9 not in the list
,08-22 11:15:32.215  3222  3297 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-22 11:15:32.225  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-22 11:15:32.225  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:32.225  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 11:15:32.225  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.225  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 11:15:32.225  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 11:15:32.225  3222  3245 D BtGatt.GattService: stopScan() - queue size =1
,08-22 11:15:32.225  3222  3358 D BtGatt.ScanManager: filter size is 1
08-22 11:15:32.225  3222  3358 D BtGatt.ScanManager: delete FilterIndex - 7
,08-22 11:15:32.225  3222  3355 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 11:15:32.225  3222  3297 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-22 11:15:32.225  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.225  3222  3358 D BtGatt.ScanManager: stopping BLe Batch
,08-22 11:15:32.235  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 11:15:32.235  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:32.235  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 11:15:32.235  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 11:15:32.235  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 11:15:32.235  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:32.235  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 11:15:32.235  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 11:15:32.235  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 11:15:32.235  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:32.235  3222  3297 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 11:15:32.235  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.235  3222  3358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-22 11:15:32.235  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:32.235  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:32.235  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:32.235  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2605225c removed from the list
08-22 11:15:32.235  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:32.235  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.235  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:32.235  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:32.235  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f84a8cf removed from the list
,08-22 11:15:32.235  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:32.235  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:32.235  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef00848 added. We now have 2 listener(s)
,08-22 11:15:32.235  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:32.235  6740  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:32.245  3222  3297 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 11:15:32.245  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.245  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-22 11:15:32.245  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 11:15:32.245  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:32.245  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 11:15:32.245  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e69a6e1 added. We now have 9 listener(s)
08-22 11:15:32.245  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:32.245  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:15:32.245  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:32.255  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:32.255  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:32.255  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:32.255  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:32.255  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:32.255  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:32.255  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:32.255  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:32.255  6740  7157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:32.255  6740  7157 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:32.255  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:32.255  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:32.255  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 11:15:32.265  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f6e2c7 added. We now have 3 listener(s)
,08-22 11:15:32.265  1022  1131 E WifiNative-wlan0: do suspend true
,08-22 11:15:32.265  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-22 11:15:32.265  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 11:15:32.265  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:32.265  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 11:15:32.265  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2160f4 added. We now have 10 listener(s)
08-22 11:15:32.265  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:32.265  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:32.265  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-22 11:15:32.265  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:32.265  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:32.265  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 11:15:32.265  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 11:15:32.275  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 11:15:32.275  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 11:15:32.275  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 11:15:32.275  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 11:15:32.275  6740  7157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:32.275  3222  7902 D BtGatt.GattService: registerClient() - UUID=6ebe3734-bede-4a64-91bb-0ef14c457977
,08-22 11:15:32.285  1022  1130 D WifiP2pService: InactiveState{ what=143375 },
,08-22 11:15:32.295  1022  1131 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK,
08-22 11:15:32.285  1022  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
08-22 11:15:32.295  1022  1131 E WifiStateMachine: VerifyingLinkState enter
,08-22 11:15:32.295  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-22 11:15:32.295  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:32.295  1022  1133 E ConnectivityService: updateNetworkInfo()
,08-22 11:15:32.295  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:32.295  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.295  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.295  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.295  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:32.305  1022  1133 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-22 11:15:32.305  1022  1133 D ConnectivityService: Adding iface wlan0 to network 504
,08-22 11:15:32.305  1022  1150 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-22 11:15:32.305  1022  1150 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-22 11:15:32.305  1022  1150 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-22 11:15:32.305  1022  1150 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-22 11:15:32.305  1022  1150 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-22 11:15:32.315  1022  1034 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 11:15:32.315  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:32.315  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 11:15:32.315  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:32.315  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:32.315  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.315  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.315  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:32.315  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.315  1022  1131 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-22 11:15:32.325  3222  3297 D BtGatt.GattService: onClientRegistered() - UUID=6ebe3734-bede-4a64-91bb-0ef14c457977, clientIf=6
08-22 11:15:32.325  6740  6750 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 11:15:32.325  3222  3231 D BtGatt.GattService: start scan with filters
,08-22 11:15:32.325  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 11:15:32.325  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 11:15:32.325  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 11:15:32.325  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:32.325  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:32.325  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:32.325  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 11:15:32.325  3222  3358 D BtGatt.ScanManager: handling starting scan
,08-22 11:15:32.325  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:32.325  6740  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 11:15:32.325  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 11:15:32.325  1640  1640 I Hs20UtilService: Starting #22
08-22 11:15:32.325  1022  1133 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-22 11:15:32.325  1640  1714 I Hs20UtilService: Message received 5007
08-22 11:15:32.325  1022  1133 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-22 11:15:32.325  4835  4835 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-22 11:15:32.335  1022  1133 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-22 11:15:32.335  3222  3297 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-22 11:15:32.335  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:32.335  3222  3358 D BtGatt.ScanManager: allow scan with filters
08-22 11:15:32.335  3222  3358 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-22 11:15:32.335  3222  3358 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
08-22 11:15:32.335  1022  1133 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-22 11:15:32.335  1022  1133 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-22 11:15:32.335  1022  1133 D ConnectivityService: LTETest block dns file not exists
08-22 11:15:32.335  3222  3297 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-22 11:15:32.335  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:32.335  3222  3358 D BtGatt.ScanManager: Starting BLE batch scan
08-22 11:15:32.335  3222  3358 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 11:15:32.335  4835  4835 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-22 11:15:32.335  1022  1022 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-22 11:15:32.335  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:32.335  3222  3297 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-22 11:15:32.335  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.345  3222  3297 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-22 11:15:32.345  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.345  1022  1131 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-22 11:15:32.345  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-22 11:15:32.345  1184  1184 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:32.345  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:32.345  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.345  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.345  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.345  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:32.355  1022  1022 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-22 11:15:32.355  1022  1022 I WifiTrafficPoller: mBoosterFLAG : 0
08-22 11:15:32.355  1022  1022 I WifiTrafficPoller: current booster mode : FullMode
08-22 11:15:32.355  1022  1131 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-22 11:15:32.355  1022  1133 V NetworkStats: updateIfacesLocked()
08-22 11:15:32.355  1184  1184 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:32.355  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-22 11:15:32.355  1022  1133 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:32.355  1022  1133 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:32.355  1022  1133 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:32.355  1022  1133 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 11:15:32.355  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.365  1022  1133 V NetworkStats: performPollLocked() took 3ms
08-22 11:15:32.365  1022  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:32.365  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:32.365  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.365  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:32.375  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:32.375  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:32.375  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 11:15:32.375  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:32.375  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.375  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 11:15:32.375  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:32.375  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef00848 removed from the list
08-22 11:15:32.375  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:32.375  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e69a6e1 removed from the list
08-22 11:15:32.375  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:32.375  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:32.375  1022  1133 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-22 11:15:32.375  1022  1133 E ConnectivityService: updateNetworkInfo()
08-22 11:15:32.375  1022  1133 E ConnectivityService: updateNetworkInfo()
08-22 11:15:32.375  1022  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-22 11:15:32.375  1022  1133 V NetworkStats: updateIfacesLocked()
08-22 11:15:32.385  1022  1133 V NetworkStats: performPollLocked(flags=0x1)
,08-22 11:15:32.385  1022  1133 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:32.385  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:32.385  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:32.385  1022  1492 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:32.385  1022  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:32.385  1022  1492 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:32.385  1022  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:32.385  1022  1133 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:32.385  1022  1133 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:32.385  1022  1133 V NetworkStats: performPollLocked() took 4ms
08-22 11:15:32.385  1022  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:32.385  1022  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:32.385  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.385  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-22 11:15:32.385  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.385  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:32.385  1640  1640 I Hs20UtilService: Starting #23
,08-22 11:15:32.385  1640  1714 I Hs20UtilService: Message received 5007
08-22 11:15:32.385  1022  1133 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-22 11:15:32.385  1022  1133 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-22 11:15:32.385  1022  7993 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:32.385  1022  7993 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-22 11:15:32.385  1022  7993 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:32.385  1022  7993 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-22 11:15:32.385  1022  7993 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 11:15:32.385  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:32.385  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:32.385  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:32.385  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:32.385  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:32.385  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e69a6e1 not in the list
08-22 11:15:32.385  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:32.385  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:32.385  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 11:15:32.385  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 11:15:32.385  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 11:15:32.395  1022  1133 D ConnectivityService:    accepting network in place of null
08-22 11:15:32.395  1022  1131 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-22 11:15:32.395   278   975 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 11:15:32.395   278   975 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-22 11:15:32.395  1022  1130 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-22 11:15:32.395  3222  3231 D BtGatt.GattService: stopScan() - queue size =1,
08-22 11:15:32.395  1022  1133 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-22 11:15:32.395  1022  1133 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-22 11:15:32.395  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-22 11:15:32.395  1022  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-22 11:15:32.395  1455  1455 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 11:15:32.395  1022  7993 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-22 11:15:32.395  1022  7993 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-22 11:15:32.395  4835  4835 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 11:15:32.395  4835  4835 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:32.395  3222  3358 D BtGatt.ScanManager: filter size is 1,
08-22 11:15:32.395  3222  3358 D BtGatt.ScanManager: delete FilterIndex - 8
08-22 11:15:32.395  1022  1133 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-22 11:15:32.395  3222  3245 D BtGatt.GattService: unregisterClient() - clientIf=6
08-22 11:15:32.395  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-22 11:15:32.395  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 11:15:32.405  1022  1133 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-22 11:15:32.395  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:32.395  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 11:15:32.395  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 11:15:32.395  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 11:15:32.395  1022  1022 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-22 11:15:32.395  1022  1051 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-22 11:15:32.395  1022  1136 D Tethering: MasterInitialState.processMessage what=3
,08-22 11:15:32.405  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:32.405  1022  1133 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-22 11:15:32.405  1184  1708 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-22 11:15:32.405  1022  1133 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-22 11:15:32.405  1022  1133 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-22 11:15:32.405  1022  1133 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-22 11:15:32.405  1022  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-22 11:15:32.405  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 11:15:32.405  6740  7157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 11:15:32.405  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 11:15:32.405  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 11:15:32.405  4835  4835 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-22 11:15:32.405  4835  4835 I NearbySettings: MountReceiver.onReceive - Keep current state
08-22 11:15:32.405  1184  1708 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-22 11:15:32.405  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:32.405  1022  1128 V NetworkStats: updateIfacesLocked()
08-22 11:15:32.405  3222  3297 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-22 11:15:32.405  1022  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-22 11:15:32.405  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:32.405  3222  3358 D BtGatt.ScanManager: stopping BLe Batch
08-22 11:15:32.405  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:32.405  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:32.405  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:32.405  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:32.405  1022  1129 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-22 11:15:32.405  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:32.405  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:32.405  1184  1184 D StatusBar.NetworkController: EthernetConnected: false
08-22 11:15:32.405  1184  1184 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-22 11:15:32.405  1184  1184 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-22 11:15:32.405  1184  1184 D StatusBar.NetworkController: updateDataNetType()
08-22 11:15:32.415  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:32.415  3222  3297 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 11:15:32.415  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.415  3222  3358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-22 11:15:32.415  1022  1128 V NetworkStats: performPollLocked() took 7ms
08-22 11:15:32.415  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:32.415  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:32.415  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:32.415  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:32.415  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2160f4 removed from the list
08-22 11:15:32.415  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:32.415  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.415  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:32.415  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-22 11:15:32.415  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:32.415  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f6e2c7 removed from the list
08-22 11:15:32.415  6740  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:32.415  6740  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:32.415  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 11:15:32.415  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 11:15:32.415  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f6d9860 added. We now have 2 listener(s)
08-22 11:15:32.415  1184  1184 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-22 11:15:32.415  3222  3297 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 11:15:32.415  3222  3297 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:32.415  1184  1184 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-22 11:15:32.415  1184  1184 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 17 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-22 11:15:32.415  1184  1184 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-22 11:15:32.415  1184  1184 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-22 11:15:32.415  1184  1184 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:32.415  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 11:15:32.415  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.415  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.415  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.415  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:32.415  1184  1184 D StatusBar.NetworkController: EthernetConnected: false
,08-22 11:15:32.415  1184  1184 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-22 11:15:32.425  1184  1184 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-22 11:15:32.425  1184  1184 D StatusBar.NetworkController: updateDataNetType()
,08-22 11:15:32.425  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-22 11:15:32.425  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:32.425  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:32.425  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:32.425  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@575119 added. We now have 9 listener(s)
08-22 11:15:32.425  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:32.425  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:32.425  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:32.425  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 11:15:32.425  1022  4370 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:32.425  1022  4370 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:32.425  1022  4370 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:32.425  1022  4370 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:32.425  1022  4370 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
08-22 11:15:32.425  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:32.425  1184  1184 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-22 11:15:32.425  1184  1184 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-22 11:15:32.425  1640  1640 I Hs20UtilService: Starting #24
,08-22 11:15:32.435  1640  1714 I Hs20UtilService: Message received 5007
,08-22 11:15:32.435  1184  1184 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-22 11:15:32.435  1184  1184 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 17 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-22 11:15:32.435  1184  1184 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-22 11:15:32.435  1184  1184 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-22 11:15:32.435  1184  1184 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:32.435  1184  1184 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 11:15:32.435  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.435  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:32.435  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:32.435  1184  1184 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:32.435  4835  4835 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-22 11:15:32.435  4835  4835 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-22 11:15:32.435  6740  7157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:32.435  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:32.435  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:32.435  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:32.435  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:32.435  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:32.435  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:32.435  6740  7157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:32.435  6740  7157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:32.435  6740  7157 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 11:15:32.435  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:32.435  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24763bf added. We now have 3 listener(s)
,08-22 11:15:32.445  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:32.445  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:32.445  1022  1141 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-22 11:15:32.445  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-22 11:15:32.445  1022  1034 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-22 11:15:32.455  1022  1034 D SecContentProvider2: mCursor = null
,08-22 11:15:32.455  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-22 11:15:32.455  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:32.455  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:32.455  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d83da8c added. We now have 10 listener(s)
08-22 11:15:32.455  6740  7157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:32.455  6740  7157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:32.455  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:32.455  6740  7157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 11:15:32.455  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:32.455  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.455  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:32.455  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:32.455  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f6d9860 removed from the list
08-22 11:15:32.455  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-22 11:15:32.455  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@575119 removed from the list
,08-22 11:15:32.455  6740  7157 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:32.455  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:32.455  1022  1329 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-22 11:15:32.455  1022  1329 D SecContentProvider2: mCursor = null
,08-22 11:15:32.455  1022  4370 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-22 11:15:32.455  1022  4370 D SecContentProvider2: mCursor = null
08-22 11:15:32.455  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.455  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:32.455  1022  1492 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-22 11:15:32.455  1022  1492 D SecContentProvider2: mCursor = null
08-22 11:15:32.455  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:32.455  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:32.455  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:32.455  6740  7157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@575119 not in the list
08-22 11:15:32.455  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.455  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:32.455  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:32.455  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:32.455  6740  7157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:32.455  6740  7157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d83da8c removed from the list
08-22 11:15:32.455  6740  7157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:32.455  6740  7157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:32.455  6740  7157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:32.455  6740  7157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:32.455  6740  7157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24763bf removed from the list
08-22 11:15:32.455  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-22 11:15:32.455  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-22 11:15:32.455  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-22 11:15:32.455  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:32.455  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-22 11:15:32.455  6740  7157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:32.455  1022  1490 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-22 11:15:32.455  1022  1490 D SecContentProvider2: mCursor = null
08-22 11:15:32.465  1022  4369 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-22 11:15:32.465  1022  4369 D SecContentProvider2: mCursor = null
,08-22 11:15:32.465  6740  8031 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1363, name: My test thread name)
,08-22 11:15:32.465  6740  8031 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1363, thread name: My test thread name)
,08-22 11:15:32.465  6740  8031 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1363, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-22 11:15:32.475  6740  8032 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1365, name: My test thread name)
,08-22 11:15:32.475  6740  8032 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1365, thread name: My test thread name)
08-22 11:15:32.475  6740  8032 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1365, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-22 11:15:32.475  6740  7157 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-22 11:15:32.475  6740  7157 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-22 11:15:32.475  6740  7157 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-22 11:15:32.475  6740  7157 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-22 11:15:32.475  6740  7157 D com.test.thalitest.ThaliTestRunner: Total duration: 23347 ms
,08-22 11:15:32.475  6740  7157 I jxcore-log: Total number of executed tests:  80
08-22 11:15:32.475  6740  7157 I jxcore-log: 
08-22 11:15:32.475  6740  7157 I jxcore-log: Number of passed tests:  80
08-22 11:15:32.475  6740  7157 I jxcore-log: 
,08-22 11:15:32.475  6740  7157 I jxcore-log: Number of failed tests:  0
08-22 11:15:32.475  6740  7157 I jxcore-log: 
08-22 11:15:32.475  6740  7157 I jxcore-log: Number of ignored tests:  0
08-22 11:15:32.475  6740  7157 I jxcore-log: 
08-22 11:15:32.475  6740  7157 I jxcore-log: Total duration:  23347
,08-22 11:15:32.475  6740  7157 I jxcore-log: 
08-22 11:15:32.475  6740  7157 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-22 11:15:32.475  6740  7157 I jxcore-log: 
,08-22 11:15:32.485  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:32.485  6740  7157 I jxcore-log: 
08-22 11:15:32.485  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:32.485  6740  7157 I jxcore-log: 
08-22 11:15:32.485  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:32.485  6740  7157 I jxcore-log: 
08-22 11:15:32.485  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:32.485  6740  7157 I jxcore-log: 
08-22 11:15:32.485  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:32.485  6740  7157 I jxcore-log: 
08-22 11:15:32.485   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
08-22 11:15:32.485  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:32.485  6740  7157 I jxcore-log: 
,08-22 11:15:32.495  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:32.495  6740  7157 I jxcore-log: 
,08-22 11:15:32.495  6740  6740 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-22 11:15:32.495  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:32.495  6740  7157 I jxcore-log: 
08-22 11:15:32.495  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:32.495  6740  7157 I jxcore-log: 
08-22 11:15:32.495  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 11:15:32.495  6740  7157 I jxcore-log: 
08-22 11:15:32.495  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 11:15:32.495  6740  7157 I jxcore-log: 
08-22 11:15:32.495  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 11:15:32.495  6740  7157 I jxcore-log: 
,08-22 11:15:32.495  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:32.495  6740  7157 I jxcore-log: 
08-22 11:15:32.495  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:32.495  6740  7157 I jxcore-log: 
,08-22 11:15:32.495  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 11:15:32.495  6740  7157 I jxcore-log: 
08-22 11:15:32.495  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 11:15:32.495  6740  7157 I jxcore-log: 
,08-22 11:15:32.495  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:32.495  6740  7157 I jxcore-log: 
,08-22 11:15:32.505  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:32.505  6740  7157 I jxcore-log: 
,08-22 11:15:32.505  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 11:15:32.505  6740  7157 I jxcore-log: 
08-22 11:15:32.505  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 11:15:32.505  6740  7157 I jxcore-log: 
,08-22 11:15:32.505  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 11:15:32.505  6740  7157 I jxcore-log: 
,08-22 11:15:32.505  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 11:15:32.505  6740  7157 I jxcore-log: 
08-22 11:15:32.505  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 11:15:32.505  6740  7157 I jxcore-log: ,
,08-22 11:15:32.505  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 11:15:32.505  6740  7157 I jxcore-log: 
08-22 11:15:32.505  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 11:15:32.505  6740  7157 I jxcore-log: 
08-22 11:15:32.505  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 11:15:32.505  6740  7157 I jxcore-log: 
08-22 11:15:32.505  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-22 11:15:32.505  6740  7157 I jxcore-log: 
08-22 11:15:32.505  1022  4367 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1022
,08-22 11:15:32.515  1184  1184 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-22 11:15:32.585  6740  6740 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 11:15:32.585  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 11:15:32.585  6740  7157 I jxcore-log: 
,08-22 11:15:32.735  6740  6740 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 11:15:32.745  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 11:15:32.745  6740  7157 I jxcore-log: 
,08-22 11:15:32.775  8034  8034 D AndroidRuntime: ,
08-22 11:15:32.775  8034  8034 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-22 11:15:32.775  8034  8034 D AndroidRuntime: CheckJNI is OFF,
08-22 11:15:32.775  8034  8034 D AndroidRuntime: readGMSProperty: start
,08-22 11:15:32.775  8034  8034 D AndroidRuntime: readGMSProperty: already setted!!
08-22 11:15:32.775  8034  8034 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-22 11:15:32.775  8034  8034 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 11:15:32.775  8034  8034 D AndroidRuntime: readGMSProperty: end
08-22 11:15:32.775  8034  8034 D AndroidRuntime: addProductProperty: start
,08-22 11:15:32.895  1022  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:32.895  8034  8034 E AffinityControl: AffinityControl: registerfunction enter
,08-22 11:15:32.905  1022  1046 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:32.915  6740  6740 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 11:15:32.915  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 11:15:32.915  6740  7157 I jxcore-log: 
,08-22 11:15:32.915  1022  1047 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-22 11:15:32.915  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:32.915  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:32.915  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:32.915  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:32.925  8034  8034 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
08-22 11:15:32.925  6740  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:32.925  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:32.925  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:32.925  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:32.925  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:32.925  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:32.925  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:32.925  6740  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 11:15:32.925  6740  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:32.935  6740  7157 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:32.935  6740  7157 I jxcore-log: 
,08-22 11:15:32.935  8043  8043 E Zygote  : MountEmulatedStorage()
08-22 11:15:32.935  8043  8043 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:15:32.935  8043  8043 E Zygote  : v2
08-22 11:15:32.935  8043  8043 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:32.935  8043  8043 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:15:32.945  1022  1047 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8043 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 11:15:32.945  8043  8043 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:32.945  8043  8043 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-22 11:15:32.945  1022  1226 D PackageManager: START PACKAGE DELETE: observer{563738427}
08-22 11:15:32.945  1022  1226 D PackageManager: pkg{<packageName>}
08-22 11:15:32.945  1022  1226 D PackageManager: user{0}
08-22 11:15:32.945  1022  1226 D PackageManager: caller{2000}
08-22 11:15:32.945  1022  1226 D PackageManager: flags{2}
08-22 11:15:32.945  1022  1226 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-22 11:15:32.945  1022  1226 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
08-22 11:15:32.945  1022  1226 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-22 11:15:32.945  1022  1226 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-22 11:15:32.945  1022  1226 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-22 11:15:32.955  1022  1063 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
08-22 11:15:32.955  1022  1063 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-22 11:15:32.955  1022  1063 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-22 11:15:32.955  1022  1063 D ApplicationPolicy: getApplicationUninstallationEnabled
08-22 11:15:32.955  1022  1063 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-22 11:15:32.965  1022  1063 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-22 11:15:32.965  8043  8043 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:32.965  8043  8043 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:32.975  1022  1047 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-22 11:15:32.985  1022  1047 I ActivityManager: Killing 6740:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-22 11:15:33.075  1022  1492 I WindowState: WIN DEATH: Window{3734e556 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-22 11:15:33.085   258   447 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
08-22 11:15:33.085   258   453 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
08-22 11:15:33.085  1022  1047 I ActivityManager:   Force finishing activity ActivityRecord{3ec4517d u0 com.test.thalitest/.MainActivity t163}
08-22 11:15:33.085  1022  1492 D InputDispatcher: Focus left window: 6740
,08-22 11:15:33.115  1022  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-22 11:15:33.115  1022  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 11:15:33.125  1022  1047 D InputDispatcher: Focused application released
,08-22 11:15:33.135  1022  1490 W ActivityManager: Spurious death for ProcessRecord{2a846e58 6740:com.test.thalitest/u0a170}, curProc for 6740: null
,08-22 11:15:33.135  1022  1063 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-22 11:15:33.145  1022  1063 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-22 11:15:33.185  2862  2862 I art     : Explicit concurrent mark sweep GC freed 18143(1056KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 826us total 35.252ms
,08-22 11:15:33.185  1022  1104 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-22 11:15:33.195  1884  1884 E SamsungIME: mOCRHelper is null
,08-22 11:15:33.195  1776  2082 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 11:15:33.205  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,08-22 11:15:33.215  1439  1439 D RegisteredServicesCache: empty dynamic service
,08-22 11:15:33.225  8043  8043 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-22 11:15:33.225  1022  1128 V NetworkStats: removeUidsLocked() for UIDs [10170]
,08-22 11:15:33.225  1022  1128 V NetworkStats: performPollLocked(flags=0x3)
,08-22 11:15:33.225  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:33.235  8043  8043 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-22 11:15:33.235  8043  8043 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-22 11:15:33.235  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-22 11:15:33.235  1022  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:33.235  1022  1128 V NetworkStats: performPollLocked() took 11ms
,08-22 11:15:33.245  1022  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:33.245  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:33.245  1022  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:33.265  8043  8043 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-22 11:15:33.265  8043  8043 I PCWCLIENTTRACE_PushUtil: sales region : global
08-22 11:15:33.265  8043  8043 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-22 11:15:33.265  8043  8043 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:33.275  1022  4367 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-22 11:15:33.275  1022  4367 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-22 11:15:33.275  1022  4367 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-22 11:15:33.275  1022  4367 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-22 11:15:33.275  1022  4367 I ActivityManager: Killing 7535:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-22 11:15:33.275  1022  1046 D EnterpriseDeviceManagerService: Package has changed for user 0
08-22 11:15:33.275  1022  1046 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-22 11:15:33.275  1022  1046 W TextServicesManagerService: no available spell checker services found
,08-22 11:15:33.275  1439  1439 D RegisteredComponentCache: Collect Tech packages for Knox
,08-22 11:15:33.285  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,08-22 11:15:33.295  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:33.295  1022  1141 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-22 11:15:33.295  1022  1141 D SecContentProvider2: mCursor = null
,08-22 11:15:33.295  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:33.335  1022  1022 I art     : Explicit concurrent mark sweep GC freed 74593(4MB) AllocSpace objects, 12(193KB) LOS objects, 33% free, 22MB/34MB, paused 2.863ms total 181.025ms
,08-22 11:15:33.335  1022  1063 I art     : WaitForGcToComplete blocked for 112.780ms for cause Explicit
,08-22 11:15:33.345  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:33.355  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:33.375  1022  1022 D RCPManagerService: PackageReceiver onReceive()
,08-22 11:15:33.385  1022  1022 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-22 11:15:33.385  1022  1022 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-22 11:15:33.385  1022  1022 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-22 11:15:33.385  1022  1022 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-22 11:15:33.395  1022  1022 I OTPFW   : ProvisionData::getAllEntries Enter
,08-22 11:15:33.395  1022  1022 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-22 11:15:33.395  1022  1133 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-22 11:15:33.455  1022  1046 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-22 11:15:33.455  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:33.455  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:33.475  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:33.495  1022  1063 I art     : Explicit concurrent mark sweep GC freed 10285(476KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 4.922ms total 161.438ms
,08-22 11:15:33.515  1022  1046 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 11:15:33.515  1022  1046 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:15:33.515  1022  1046 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 11:15:33.525  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:33.545  1022  1063 D PackageManager: delete codoeFile: 
,08-22 11:15:33.545  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:33.545  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 11:15:33.545  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 11:15:33.555  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 11:15:33.555  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:33.555  1022  1063 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-22 11:15:33.555  1022  1063 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-22 11:15:33.555  1022  1063 D PackageManager: result of delete: 1{563738427}
,08-22 11:15:33.555  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 11:15:33.555  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 11:15:33.555  8034  8034 D AndroidRuntime: Shutting down VM
,08-22 11:15:33.565  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 11:15:33.565  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 11:15:33.565  1022  1022 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-22 11:15:33.565  1022  1022 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-22 11:15:33.565  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:33.565  1022  1046 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-22 11:15:33.565  1022  1034 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-22 11:15:33.565  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-22 11:15:33.565  1022  1022 V EnterpriseBillingPolicy: uID is 10170
08-22 11:15:33.565  1022  1022 V EnterpriseBillingPolicy: Removed Packageuid is0
08-22 11:15:33.565  1022  1022 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-22 11:15:33.565  1022  1022 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-22 11:15:33.565  1022  1034 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-22 11:15:33.565  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-22 11:15:33.565  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-22 11:15:33.565  1022  1022 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-22 11:15:33.565  1022  1022 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-22 11:15:33.565  1022  1034 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-22 11:15:33.565  1022  1034 D BatteryService: stay LED for charging
,08-22 11:15:33.575  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 11:15:33.575  1022  1046 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-22 11:15:33.575  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-22 11:15:33.575  1022  1022 V EnterpriseBillingPolicy: uID is 10170
08-22 11:15:33.575  1022  1022 V EnterpriseBillingPolicy: Removed Packageuid is0
08-22 11:15:33.575  1022  1022 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-22 11:15:33.575  1022  3388 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-22 11:15:33.575  1022  1022 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-22 11:15:33.575  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-22 11:15:33.575  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-22 11:15:33.575  1022  1022 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-22 11:15:33.575  1022  1167 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-22 11:15:33.575  1022  1022 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-22 11:15:33.575  1022  1022 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-22 11:15:33.635  1022  1022 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 11:15:33.645  1184  1184 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 11:15:33.645  1184  1184 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 11:15:33.645  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-22 11:15:33.645  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 11:15:33.655  3222  3222 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-22 11:15:33.655  3222  7955 D HeadsetStateMachine: Disconnected process message: 10
,08-22 11:15:33.655  1022  1022 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-22 11:15:33.655  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:33.655  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:33.655  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:33.655  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:33.665  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-22 11:15:33.665  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 11:15:33.665  1184  1184 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 11:15:33.675  8061  8061 E Zygote  : MountEmulatedStorage()
,08-22 11:15:33.675  8061  8061 E Zygote  : v2
08-22 11:15:33.675  8061  8061 I libpersona: KNOX_SDCARD checking this for 10001
08-22 11:15:33.675  8061  8061 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:33.675  8061  8061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-22 11:15:33.675  1022  1022 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=8061 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 11:15:33.675  1022  1022 I MotionRecognitionService: Plugged
,08-22 11:15:33.675  1022  1022 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 11:15:33.675  8061  8061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:15:33.675  8061  8061 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:33.695  8061  8061 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:33.695  8061  8061 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:33.745  7553  7553 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:33.745  7553  7553 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-22 11:15:33.745  7553  7553 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-22 11:15:33.755  7553  7553 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-22 11:15:33.775  8034  8034 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-22 11:15:33.785  1022  1063 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-22 11:15:33.785  1022  1063 D PackageManager: userId{-1}
08-22 11:15:33.785  1022  1063 D PackageManager: andCode{true}
,08-22 11:15:33.785  1022  1063 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-22 11:15:33.795  1022  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:33.795  1022  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:33.795  1022  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:33.795  1022  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:33.805  8080  8080 E Zygote  : MountEmulatedStorage()
,08-22 11:15:33.805  8080  8080 E Zygote  : v2
08-22 11:15:33.805  8080  8080 I libpersona: KNOX_SDCARD checking this for 10003
08-22 11:15:33.805  8080  8080 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:33.805  8080  8080 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:33.815  8080  8080 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:33.815  8080  8080 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:33.815  1022  1063 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8080 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-22 11:15:33.845  8080  8080 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:33.845  8080  8080 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:33.885  1022  4368 I ActivityManager: Killing 7569:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-22 11:15:33.885  1022  1223 W ActivityManager: ProcessRecord{234ba39a 7569:com.sec.android.fotaclient/u0a8} is already killed
08-22 11:15:33.885   255   255 E lowmemorykiller: Error writing /proc/7569/oom_score_adj; errno=22
,08-22 11:15:33.885  1022  1223 I ActivityManager: Existing provider com.sec.android.fotaclient/.log.MasterLogProvider is crashing; detaching ProcessRecord{3629c4cb 7553:com.sec.android.diagmonagent/1000}
,08-22 11:15:33.895  1022  1223 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,08-22 11:15:33.895  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:33.895  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:33.895  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:33.895  1022  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:33.915  8097  8097 E Zygote  : MountEmulatedStorage()
,08-22 11:15:33.915  8097  8097 E Zygote  : v2
08-22 11:15:33.915  8097  8097 I libpersona: KNOX_SDCARD checking this for 10008
08-22 11:15:33.915  8097  8097 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:33.915  1022  1223 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=8097 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-22 11:15:33.915  8097  8097 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:15:33.925  8097  8097 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:33.925  8097  8097 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-22 11:15:33.945  8097  8097 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:33.945  8097  8097 D ActivityThread: Added TimaKeyStore provider

```
