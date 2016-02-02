#### Test 579720943a29850_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 4450): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4450):  
D/Mms/MessagingNotification( 4410): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 4410): isDefault true
--------- beginning of /dev/log/system
I/ActivityManager(  759): Killing 3251:com.google.android.talk/u0a105 (adj 15): empty #43
D/TP/MmsSmsProvider( 1235): match 200:Elapsed time : 1.381 ms
I/SELinux ( 4450): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4450):  
I/SELinux ( 4450):  
I/SELinux ( 4450): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4450): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4450): >>>>> Normal User
E/dalvikvm( 4450): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
E/SELinux ( 4450): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/BadgeProvider( 1351): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/TimaKeyStoreProvider( 4450): in addTimaSignatureService
D/TimaKeyStoreProvider( 4450): Cannot add TimaSignature Service, License check Failed
D/BadgeProvider( 1351): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1351): sendNotify, [notify] : null
D/BadgeProvider( 1351): update, [uri] : content://com.sec.badge/apps/2
D/Launcher.Model( 1254): reloadBadges entered.
D/BadgeProvider( 1351): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1351): update, [UpdateCount] : 1
D/ActivityThread( 4450): Added TimaKesytore provider
D/Mms/MessagingNotification( 4410): setBadgeCount(), count=0
D/MessagingNotification( 4410): remove alarm
,D/Mms/MessagingNotification( 4410): updateAllHistoryAsRead()
D/Mms/MessagingNotification( 4410): [end]    nonBlockingUpdateMessageIndicator()
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=4450, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
D/com.samsung.app( 1444): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidintentactionTIME_SET
D/com.samsung.app( 1444): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/ActivityManager(  759): Killing 3280:com.samsung.helphub/1000 (adj 15): empty #43
I/ Time Manager ( 4450): Time Difference not stored. TIME_DIFFERENCE
I/SELinux ( 4467): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4467):  
I/SELinux ( 4467): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4467):  
I/SELinux ( 4467):  
I/SELinux ( 4467): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4467): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4467): >>>>> Normal User
E/dalvikvm( 4467): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
E/SELinux ( 4467): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4467): in addTimaSignatureService
D/TimaKeyStoreProvider( 4467): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4467): Added TimaKesytore provider
I/ActivityManager(  759): Waited long enough for: ServiceRecord{431ed658 u0 com.samsung.android.sconnect/.periph.PeriphService}
D/dalvikvm( 3579): GC_CONCURRENT freed 6825K, 44% free 10750K/18948K, paused 3ms+17ms, total 70ms
I/SELinux ( 4482): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4482):  
I/ActivityManager(  759): Killing 3313:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #43
I/SELinux ( 4482): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4482):  
I/SELinux ( 4482):  
I/SELinux ( 4482): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4482): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4482): >>>>> Normal User
E/dalvikvm( 4482): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 4482): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4482): in addTimaSignatureService
D/TimaKeyStoreProvider( 4482): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4482): Added TimaKesytore provider
I/SecureStorage(  299): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  299): [INFO]: SPID(0x00000003)PID: 4333, TID: 4333
D/elm:14132( 4482): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
D/elm:14132( 4482): ELMEngine.ELMEngine( context ).
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=4482, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 4482): MDMBridge.setEnterpriseBridge()
D/elm:14132( 4482): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
I/knox    ( 3297): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/elm:14132( 4482): ElmAgentService : onCreate()
W/ContextImpl( 3297): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/elm:14132( 4482): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
D/knox    ( 3297): MainReceiver.listeningToTimeDateChanges( context, intent ).
I/knox    ( 3297): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/knox    ( 3297): KNOXAgentService : onCreate()
D/knox    ( 3297): KNOXAgentService : set alarms for deniallog and usage data upload
D/elm:14132( 4482): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 4482): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14132( 4482): ModuleBase.resetCalllogAPIAlarm()
D/knox    ( 3297): KNOXAgentService. startJobThread() start
D/knox    ( 3297): KNOXAgentService. JobThread()
D/knox    ( 3297): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3297): KNOXAgentService. startJobThread() wait
I/SELinux ( 4497): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4497):  
D/AndroidRuntime( 4471): 
D/AndroidRuntime( 4471): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/knox    ( 3297): KNOXAgentService : onDestroy().
D/knox    ( 3297): ModuleBase.cancelAllAlarmManageModule()
D/elm:14132( 4482): ModuleBase.ModifySetAlarm()
D/elm:14132( 4482): MDMBridge.getInstance()
D/elm:14132( 4482): MDMBridge.getAllLicenseInfoFromSDK()
D/AndroidRuntime( 4471): CheckJNI is OFF
D/elm:14132( 4482): ElmAgentService : onDestroy().
D/AndroidRuntime( 4471): setted country_code = Poland
D/AndroidRuntime( 4471): setted countryiso_code = PL
D/AndroidRuntime( 4471): setted sales_code = XEO
D/AndroidRuntime( 4471): readGMSProperty: start
D/AndroidRuntime( 4471): readGMSProperty: already setted!!
D/AndroidRuntime( 4471): readGMSProperty: end
D/AndroidRuntime( 4471): addProductProperty: start
I/ActivityManager(  759): Killing 3329:com.LocalFota/u0a110 (adj 15): empty #43
D/dalvikvm( 4471): Trying to load lib libjavacore.so 0x0
I/SecureStorage( 4333): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4333): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4333): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4333): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 4333): Open platform.db in secure mode
D/dalvikvm( 4471): Added shared lib libjavacore.so 0x0
I/SELinux ( 4497): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4497):  
I/SELinux ( 4497):  
I/SELinux ( 4497): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4497): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 4497): >>>>> Normal User
E/dalvikvm( 4497): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10143 ]
E/SELinux ( 4497): [DEBUG] seapp_context_lookup: seinfoCategory = shared
D/dalvikvm( 4471): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4471): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4471): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/TimaKeyStoreProvider( 4497): in addTimaSignatureService
D/TimaKeyStoreProvider( 4497): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4497): Added TimaKesytore provider
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=4497, uid=10143 requires android.permission.INTERACT_ACROSS_USERS
I/SQLiteSecureOpenHelper( 4333): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 4333): ...getDatabaseLocked(b,b,pwd)
I/SELinux ( 4517): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4517):  
I/ActivityManager(  759): Killing 3344:com.sec.android.app.mt/1000 (adj 15): empty #43
D/dalvikvm(  247): GC_EXPLICIT freed 42K, 50% free 9506K/18948K, paused 2ms+2ms, total 25ms
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9506K/18948K, paused 2ms+2ms, total 19ms
I/SELinux ( 4517): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4517):  
I/SELinux ( 4517):  
I/SELinux ( 4517): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4517): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4517): >>>>> Normal User
E/dalvikvm( 4517): >>>>> com.qualcomm.timeservice [ userId:0 | appId:10168 ]
E/SELinux ( 4517): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/memtrack( 4471): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4471): failed to load memtrack module: -2
I/ActivityManager(  759): Killing 3387:com.sec.android.app.camera/u0a147 (adj 15): empty #43
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9506K/18948K, paused 2ms+3ms, total 28ms
D/TimaKeyStoreProvider( 4517): in addTimaSignatureService
D/TimaKeyStoreProvider( 4517): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4517): Added TimaKesytore provider
D/dalvikvm( 4471): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=4517, uid=10168 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 4517): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x425dd9a0, skipping init
D/TimeService( 4517): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454414785686
D/        ( 4517): TimeServiceNative: User Time to be set is 1454414785686
D/QC-time-services( 4517): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4517): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4517): Lib:time_genoff_operation: pargs->ts_val = 1454414785686
D/QC-time-services( 4517): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  291): Daemon: Connection accepted:time_genoff
D/QC-time-services(  291): Daemon: genoff_handler: Process name is omm.timeservice
D/QC-time-services(  291): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454414785686
D/QC-time-services(  291): Daemon:genoff_opr: Base = 2, val = 1454414785686, operation = 0
D/QC-time-services(  291): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/9/70 4:3:8
D/QC-time-services(  291): Daemon:Value read from RTC seconds = 5803388000
D/QC-time-services(  291): Daemon:new time 1454414785686 
D/QC-time-services(  291): Daemon: delta 1448611397686 genoff 1448611397686 
D/QC-time-services(  291): Daemon:genoff_persistent_update: Writing genoff = 1448611397686 to memory
D/QC-time-services(  291): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  291): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  291): Updating the TOD offset
D/QC-time-services(  291): Daemon:genoff_persistent_update: Writing genoff = 1448611397686 to memory
D/QC-time-services(  291): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  291): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  291): Daemon:Update to modem bit set
D/QC-time-services(  291): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  291): Daemon: Base = 2, Value being sent to MODEM = 1138449985686
E/QC-time-services( 4517): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  291): Daemon: Time-services: Waiting to acceptconnection
E/QC-time-services(  291): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  759): Killing 3401:com.sec.android.inputmethod/1000 (adj 15): empty #43
D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/AndroidRuntime( 4471): Calling main entry com.android.commands.am.Am
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1463): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1463): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/comdaemonstockapp( 1463): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 1463): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
I/CheckinService( 1758): Checkin interval check for package: unspecified last checkin: 1453985581353 min interval config: 0 actual interval: 429204426
D/AndroidRuntime( 4471): Shutting down VM
D/dalvikvm( 4471): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 0ms+0ms, total 2ms
D/dalvikvm(  759): GC_EXPLICIT freed 681K, 14% free 23392K/26936K, paused 8ms+11ms, total 125ms
D/PackageManager(  759): [MSG] SEND_PENDING_BROADCAST
D/PackageManager(  759): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10011, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@42ffe410, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "sms"
D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "smsto"
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 1463): GC_CONCURRENT freed 7480K, 47% free 10196K/18948K, paused 5ms+7ms, total 59ms
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
W/InputMethodInfo(  759): Duplicated subtype definition found: , voice
D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1463): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1463): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mms"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mmsto"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "sms"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1463): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1463): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "smsto"
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mms"
D/dalvikvm( 3579): GC_CONCURRENT freed 2408K, 46% free 10300K/18948K, paused 2ms+17ms, total 55ms
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mmsto"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/ContextualEventManager( 1065): removeContextualEvent(): requestClass=com.android.mms
D/ContextualEventManager( 1065): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1065): updateContainer()
D/ContextualEventContainer( 1065): update()
D/ContextualEventContainer( 1065): handleUpdate()
D/Mms/MessagesLockscreen( 4410): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
D/ContextualEventManager( 1065): getTopEventView()
D/ContextualEventManager( 1065): getTopContextualEvent()
E/CscFactoryReceiver( 1235): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1235): Media DB Scanner finished.
D/CscFactoryReceiver( 1235): start service to Set Ringtone
D/CscFactoryReceiver( 1235): start service to Set Notification
D/ContextualEventManager( 1065): top view = flightmode
I/KeyguardEffectViewMain( 1065): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1065): getTopEventClass()
D/ContextualEventManager( 1065): getTopContextualEvent()
D/ContextualEventManager( 1065): !isClockTop
D/ContextualEventManager( 1065): getTopEventClass()
D/ContextualEventManager( 1065): getTopContextualEvent()
D/CscFactoryReceiver( 1235): start service to Set Alarmtone
D/ContextualEventManager( 1065): !isClockTop
D/ContextualEventManager( 1065): getTopEventClass()
D/ContextualEventManager( 1065): getTopContextualEvent()
D/CscUpdateService( 1235): onStart
E/CscUpdateService( 1235): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1235): only ringtone update
D/CscUpdateService( 1235): onStart
E/CscUpdateService( 1235): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1235): only notification update
E/SMD     (  240): DCD ON
D/CscUpdateService( 1235): onStart
E/CscUpdateService( 1235): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1235): only alarmtone update
E/CscParser( 1235): update(): xml file exist
D/UsbManager( 1065):  :::: isUsb30Available :: return = false from pid = 1065
E/CscParser( 1235): update(): xml file exist
E/CscParser( 1235): update(): xml file exist
I/SELinux ( 4538): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4538):  
D/SecContextualClockFlightMode( 1065): handleUpdateClock()
D/KeyguardProperties( 1065): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
W/CSCSettings( 1235): Setting Ringtones (type) : 1
D/CscParser( 1235): RingTone: null
W/CSCSettings( 1235): 1. Tag_Str: null
W/CSCSettings( 1235): Setting Ringtones (type) : 4
D/CscParser( 1235): AlarmTone: null
W/CSCSettings( 1235): 1. Tag_Str: null
I/SELinux ( 4538): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4538):  
I/SELinux ( 4538):  
I/SELinux ( 4538): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4538): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4538): >>>>> Normal User
E/dalvikvm( 4538): >>>>> com.samsung.indexservice [ userId:0 | appId:10004 ]
E/SELinux ( 4538): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4538): in addTimaSignatureService
D/TimaKeyStoreProvider( 4538): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4538): Added TimaKesytore provider
W/CSCSettings( 1235): Setting Ringtones (type) : 2
D/CscParser( 1235): MessageTone: null
W/CSCSettings( 1235): 1. Tag_Str: null
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/IndexBroadcastProcessorService( 4538): lucene onHandleIntent-ACTION_MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 3840): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.MEDIA_SCANNER_FINISHED
I/IndexBroadcastProcessorService( 4538): lucene systemReadyToIndex
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/FactoryTestApp( 3840): [XMLDataStorage$parseXML] is Live Demo : false
D/FactoryTestApp( 3840): [XMLDataStorage$parseXML] modelXML=sm-g800h.dat
D/FactoryTestApp( 3840): [XMLDataStorage$parseXML] deviceXML=kmini3g.dat
D/FactoryTestApp( 3840): [XMLDataStorage$parseXML] nameXML=kmini3gxx.dat
I/IndexService( 4538): lucene onCreate ...service
W/ActivityThread( 3840): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/FactoryTestApp( 3840): [XMLDataStorage$parseAsset] Convert dat file: sm-g800h.dat
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 4538): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 4538): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
I/dalvikvm( 4538): Could not find method java.lang.management.ManagementFactory.getPlatformMBeanServer, referenced from method org.apache.lucene.util.RamUsageEstimator.<clinit>
W/dalvikvm( 4538): VFY: unable to resolve static method 5877: Ljava/lang/management/ManagementFactory;.getPlatformMBeanServer ()Ljavax/management/MBeanServer;
D/dalvikvm( 4538): VFY: replacing opcode 0x71 at 0x01ed
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/IndexService( 4538): lucene beginIndexing
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/File    ( 4538): fail readDirectory() errno=13
I/IndexService( 4538): lucene onDestroy start
I/IndexService( 4538): lucene onDestroy end
I/IndexService( 4538): lucene cleanupEverything start
I/IndexService( 4538): ERROR: null
E/ParserThreadsListManager( 4538): Lucene Interrupt in run
I/IndexService( 4538): lucene cleanupEverything end
I/Process ( 4538): Sending signal. PID: 4538 SIG: 9
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/FactoryTestApp( 3840): [XMLDataStorage$parseAsset] Decode base file: factory.dat
I/ActivityManager(  759): Process com.samsung.indexservice (pid 4538) (adj 9) has died.
I/GCoreNlp( 1214): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
W/ContextImpl( 3579): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1659 android.content.ContextWrapper.sendStickyBroadcast:439 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:841 <bottom of call stack> 
I/Process ( 3579): Sending signal. PID: 3579 SIG: 9
D/LocationProviderProxy(  759): applying state to connected service
D/LocationProviderProxy(  759): applying state to connected service
W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/ActivityManager(  759): Process com.sec.android.app.sysscope (pid 3579) (adj 0) has died.
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APP
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_COMMAND
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=MODEL_NAME
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=MODEL_NUMBER
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=MODEL_HARDWARE_REVISION
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=MODEL_COMMUNICATION_MODE
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=CHIPSET_MANUFACTURE
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=CHIPSET_NAME
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=DEVICE_TYPE
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=PANEL_TYPE
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_ACCELEROMETER
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_MAGNETIC
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=REAR_CAMERA_TYPE
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=ISP_FLASH_TEST_SMD
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TORCH_MODE_FLASH_ON_CURRENT
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SPEAKER_COUNT
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=MIC_COUNT
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SVC_LED_TEST_BRIGHTNESS
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_VIBRATOR
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_LTE
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_QWERTY_KEY
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_FRONT_CAMERA
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_RCV
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FACTORY_TEST_APO
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_EPEN
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_SENSORHUB
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_CAM_ISP
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_IRLED_FEEDBACK_IC
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=HW_VER_EFS
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_BOOK_COVER
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=MULTI_TSK_THD
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_SELFTEST_PWC_DISPLAY
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_GLOVE_MODE
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FONT_SIZE
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=RAM_SIZE_IF
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_FONT_SIZE
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_SEMI_FUNCTION_TEST
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SEMI_FUNCTION_TEST_UI_ORIENTATION
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_UP
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=KEY_TEST_VOLUME_DOWN
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=KEY_TEST_POWER
,I/Mms/MmsApp( 4410):  start initViewCache mms
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=KEY_TEST_APP_RECENT
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=KEY_TEST_HOME
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=KEY_TEST_BACK
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=KEY_TEST_SEARCH
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=KEY_TEST_FOCUS
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=KEY_TEST_CAMERA
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=KEY_TEST_F1
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_USER
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_POWER
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SEMI_KEY_TEST_HOME
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=IS_KEY_TEST_THRESHOLD
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=IS_SENSOR_TEST_ACC_REVERSE
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SUPPORT_GEOMAGNETIC_ALPS_CAL
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=GEOMAGNETIC_IC_POINT
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SENSOR_TEST_ACC_BIT
,D/Mms/ComposeMessageFragment( 4410): fillCache, easy = false
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=IS_VIBETONZ_UNSUPPORTED
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=IS_IRLED_TEST_SPLIT_COMMAND
,D/dalvikvm( 3840): GC_CONCURRENT freed 7286K, 46% free 10354K/18948K, paused 3ms+2ms, total 34ms
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=AT_GPSSTEST
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=AT_BATTEST_RESET_WHEN_READ
,D/checkbox( 4410): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=PA0_TEMP_ADC
D/checkbox( 4410): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4410): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4410): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=PA1_TEMP_ADC
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=NEED_ACK_FOR_CAMERA_STOP
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=HALL_IC_TEST
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=HUMITEMP_TEST
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_PEEK_TO_PEEK
,I/GAV2    ( 4179): Thread[GAThread,5,main]: No campaign data found.
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=GESTURE_SENSOR_IR_CURRENT_CHANGE
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SYS_INFO_FONT_SIZE
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SYS_INFO_MEMORY_SIZE
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SYS_INFO_OUT_POSITION
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SYS_INFO_MODEL_NAME
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_WIDTH
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_NODE_COUNT_HEIGHT
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_SPEC_MAX_MINUS_MIN
,W/ApplicationsProvider( 1402): Could not fetch usage stats
W/ApplicationsProvider( 1402): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1402): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1402): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1402): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1402): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1402): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1402): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1402): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1402): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 1402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1402): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1402): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/GAv4-SVC( 1758): Google Analytics 8.4.89 is starting up.
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_ATMEL
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_ATMEL
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_Y_ATMEL
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_Y_ATMEL
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_X_ATMEL
,D/dalvikvm( 1758): GC_CONCURRENT freed 1747K, 40% free 11482K/18948K, paused 10ms+9ms, total 53ms
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_X_ATMEL
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MIN_CYPRESS_PWC
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_MAX_CYPRESS_PWC
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_Y_CYPRESS
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_Y_CYPRESS
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MIN_X_CYPRESS
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_HOVERING_MAX_X_CYPRESS
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MIN
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=TOUCH_KEY_SPEC_MAX
,D/AbsListView( 4410): Get MotionRecognitionManager
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MIN
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MAX
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_START
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_PIXEL_END
D/MotionRecognitionService(  759):  ssp status : false
,I/ActivityManager(  759): Waited long enough for: ServiceRecord{4300e7f0 u0 tv.peel.smartremote/tv.peel.samsung.widget.service.WidgetTimerService}
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_START
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_PIXEL_END
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MIN
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_MAX
I/dalvikvm( 4410): Could not find method android.sec.multiwindow.MultiWindow.createInstance, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 4410): VFY: unable to resolve static method 1402: Landroid/sec/multiwindow/MultiWindow;.createInstance (Landroid/app/Activity;)Landroid/sec/multiwindow/MultiWindow;
D/dalvikvm( 4410): VFY: replacing opcode 0x71 at 0x03bb
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MIN
I/dalvikvm( 4410): Could not find method android.sec.multiwindow.MultiWindow.isMultiWindow, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 4410): VFY: unable to resolve virtual method 1403: Landroid/sec/multiwindow/MultiWindow;.isMultiWindow ()Z
D/dalvikvm( 4410): VFY: replacing opcode 0x74 at 0x0759
I/dalvikvm( 4410): Could not find method android.sec.multiwindow.MultiWindow.isMultiWindow, referenced from method com.android.mms.ui.MessageListItem.bind
W/dalvikvm( 4410): VFY: unable to resolve virtual method 1403: Landroid/sec/multiwindow/MultiWindow;.isMultiWindow ()Z
D/dalvikvm( 4410): VFY: replacing opcode 0x74 at 0x07e8
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_MAX
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_PRIMARY_SPEC_AVG
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_SECONDARY_SPEC_AVG
D/checkbox( 4410): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4410): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4410): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 4410): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_AVG
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_PRIMARY_SPEC_MAX
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_AVG
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECONDARY_SPEC_MAX
V/WebViewChromium( 4410): Binding Chromium to the main looper Looper (main, tid 1) {422b21e0}
I/chromium( 4410): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4410): Initializing chromium process, renderers=0
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_MAX
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION1_SPEC_AVG
W/chromium( 4410): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_MAX
I/Adreno-EGL( 4410): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4410): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4410): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4410): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4410): Remote Branch: 
I/Adreno-EGL( 4410): Local Patches: 
I/Adreno-EGL( 4410): Reconstruct Branch: 
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=FINGERPRINT_STDEV_SECTION2_SPEC_AVG
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_SAMPLE_NO
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_PEAK_IR
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_IR
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=HRM_FREQUENCY_NOISE_IR
,D/dalvikvm( 3840): GC_CONCURRENT freed 2029K, 46% free 10355K/18948K, paused 1ms+1ms, total 23ms
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=HRM_PEAK_TO_PEAK_DC_RED
,D/checkbox( 4410): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4410): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4410): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4410): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=BOOTLOADER_VERSION
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=BATTERY_TEST_MODE
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=BATTERY_VOLT_AVER
,D/checkbox( 4410): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4410): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4410): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4410): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=BATTERY_VF_OCV
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_CELCIUS
D/checkbox( 4410): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=SEC_EXT_THERMISTER_ADC
D/checkbox( 4410): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4410): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4410): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=PA0_THERMISTER_ADC
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=PA1_THERMISTER_ADC
,D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=PATH_HALLIC_STATE
,D/checkbox( 4410): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4410): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4410): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 4410): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,I/ActivityManager(  759): Waited long enough for: ServiceRecord{431aca48 u0 org.simalliance.openmobileapi.service/.SmartcardService}
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=KEY_PRESSED_POWER
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_PAM
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=BATTERY_TEMP_ADC
D/checkbox( 4410): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4410): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4410): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 4410): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_BATT_CELCIUS
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT
D/checkbox( 4410): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4410): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4410): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
D/checkbox( 4410): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
D/FactoryTestApp( 3840): [XMLDataStorage$redefinitionById] id=LPA_MODE_SET
,D/checkbox( 4410): setButtonDrawable(Drawable d) mButtonBgHasBeenSet=false
D/checkbox( 4410): This is not checkbox or checkbox with ADVANCED_VI_EFFECTS disabled
D/checkbox( 4410): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=false
,D/checkbox( 4410): checkMarkDrawable=null, checkRectangleDrawable=null, enabled=false
,D/Mms/BubbleViewCache( 4410): fillCache bubble = 8
,D/Mms/Synchronizer( 4410): [start]    dbSync()
,D/FactoryTestApp( 3840): [XMLDataStorage$parseAsset] SemiFunctionMenu
D/TP/MmsSmsProvider( 1235): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 1235): syncDBData start
,D/TP/MmsSmsProvider( 1235): match 0:Elapsed time : 1.035 ms
,V/TP/MmsSmsProvider( 1235): syncDBData sms end
,V/TP/MmsSmsProvider( 1235): syncDBData mms end
,V/TP/MmsSmsProvider( 1235): syncDBData end
,D/Mms/Synchronizer( 4410): [end]    dbSync()
,D/FactoryTestApp( 3840): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
,D/FactoryTestApp( 3840): [Support$Properties.get] property=ro.factory.factory_binary
D/FactoryTestApp( 3840): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
,D/Mms/MessagingNotification( 4410): checkBadgeCount unreadCount=0 badgeCount=0
,D/FactoryTestApp( 3840): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
D/FactoryTestApp( 3840): [Support$Values.getString] id=CHIPSET_MANUFACTURE, value=Qualcomm
I/FactoryTestApp( 3840): [ModuleCommon$ModuleCommon] Create ModuleCommon
,I/FactoryTestApp( 3840): [ModuleCommon$setMediascanningCounter]  
,I/FactoryTestApp( 3840): [ModuleCommon$getMediaScanningCount] get : 0
,D/FactoryTest( 3840): User mode
,I/FactoryTestApp( 3840): [ModuleCommon$getMediaScanningCount] get : 1
,D/TP/MmsSmsProvider( 1235): match 6:Elapsed time : 1.065 ms
W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:269 android.app.ActivityThread.handleReceiver:2698 
,D/GalleryCacheReady( 2779): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 2779): handleMeidaScanFinish()
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 2779): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 2779): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 2779): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,W/Vold    (  227): Returning OperationFailed - no handler for errno 30
I/SELinux ( 4595): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4595):  
,D/FaceInterface( 2779): requestFaceScan() is called.
,I/FaceInterface( 2779): startFaceScan() : waiting 5 sec
,I/SELinux ( 4595): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4595):  
I/SELinux ( 4595):  
,I/SELinux ( 4595): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4595): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4595): >>>>> Normal User
,E/dalvikvm( 4595): >>>>> com.sec.android.app.music:service [ userId:0 | appId:10150 ]
,E/SELinux ( 4595): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4595): in addTimaSignatureService
,W/LocalSuggestAlbumData( 2779): query fail: 
,W/LocalSuggestAlbumData( 2779): query fail: 
,D/TimaKeyStoreProvider( 4595): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4595): Added TimaKesytore provider
,D/com.samsung.musicplus.bitmapcache.BitmapCache( 4595): Allocated bitmap cache: 13421772
,D/ContextualEventManager( 1065): removeContextualEvent(): requestClass=com.android.mms
D/Mms/MessagesLockscreen( 4410): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
D/ContextualEventManager( 1065): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1065): updateContainer()
,D/ContextualEventContainer( 1065): update()
D/ContextualEventContainer( 1065): handleUpdate()
D/ContextualEventManager( 1065): getTopEventView()
,D/ContextualEventManager( 1065): getTopContextualEvent()
,D/ContextualEventManager( 1065): top view = flightmode
I/KeyguardEffectViewMain( 1065): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1065): getTopEventClass()
,D/ContextualEventManager( 1065): getTopContextualEvent()
,D/ContextualEventManager( 1065): !isClockTop
D/ContextualEventManager( 1065): getTopEventClass()
,D/ContextualEventManager( 1065): getTopContextualEvent()
D/ContextualEventManager( 1065): !isClockTop
D/ContextualEventManager( 1065): getTopEventClass()
,D/ContextualEventManager( 1065): getTopContextualEvent()
I/ActivityManager(  759): Killing 2518:com.android.defcontainer/u0a6 (adj 15): empty #43
D/UsbManager( 1065):  :::: isUsb30Available :: return = false from pid = 1065
,D/SecContextualClockFlightMode( 1065): handleUpdateClock()
,D/KeyguardProperties( 1065): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SettingSearch/SearchIntentReceiver( 1318): action : android.settings.CHANGED_ICC_LOCK_ENABLE
,E/CscFactoryReceiver( 1235): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1235): Media DB Scanner finished.
,D/CscFactoryReceiver( 1235): start service to Set Ringtone
,D/CscFactoryReceiver( 1235): start service to Set Notification
,D/CscFactoryReceiver( 1235): start service to Set Alarmtone
D/CscUpdateService( 1235): onStart
,E/CscUpdateService( 1235): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1235): only ringtone update
D/CscUpdateService( 1235): onStart
E/CscUpdateService( 1235): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1235): only notification update
D/CscUpdateService( 1235): onStart
,E/CscUpdateService( 1235): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1235): only alarmtone update
E/CscParser( 1235): update(): xml file exist
,E/CscParser( 1235): update(): xml file exist
,E/CscParser( 1235): update(): xml file exist
,I/SELinux ( 4612): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4612):  
,D/dalvikvm( 1235): GC_CONCURRENT freed 1634K, 44% free 10729K/18948K, paused 6ms+3ms, total 30ms
,D/dalvikvm( 1235): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 1286): GC_EXPLICIT freed 1197K, 44% free 10751K/18948K, paused 3ms+4ms, total 53ms
,D/dalvikvm( 1235): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 1235): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/CSCSettings( 1235): Setting Ringtones (type) : 4
,D/CscParser( 1235): AlarmTone: null
,W/CSCSettings( 1235): 1. Tag_Str: null
,W/CSCSettings( 1235): Setting Ringtones (type) : 1
,D/CscParser( 1235): RingTone: null
,W/CSCSettings( 1235): 1. Tag_Str: null
I/SELinux ( 4612): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4612):  
I/SELinux ( 4612):  
,I/SELinux ( 4612): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4612): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4612): >>>>> Normal User
,E/dalvikvm( 4612): >>>>> com.samsung.indexservice [ userId:0 | appId:10004 ]
,E/SELinux ( 4612): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/CSCSettings( 1235): Setting Ringtones (type) : 2
,D/CscParser( 1235): MessageTone: null
,W/CSCSettings( 1235): 1. Tag_Str: null
,D/TimaKeyStoreProvider( 4612): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4612): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4612): Added TimaKesytore provider
,D/FactoryTestApp( 3840): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.MEDIA_SCANNER_FINISHED
I/FactoryTestApp( 3840): [XMLDataStorage$parsingXML] FtClient => data parsing was completed.
D/FactoryTestApp( 3840): [FactoryTestBroadcastReceiver$onReceive] ACTION_MEDIA_SCANNER_FINISHED => XML data parsing was failed.
D/FactoryTestApp( 3840): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 3840): [Support$Properties.get] property=ro.factory.factory_binary
I/FactoryTestApp( 3840): [ModuleCommon$setMediascanningCounter]  
,I/FactoryTestApp( 3840): [ModuleCommon$getMediaScanningCount] get : 1
D/FactoryTest( 3840): User mode
I/FactoryTestApp( 3840): [ModuleCommon$getMediaScanningCount] get : 2
,I/FactoryTestApp( 3840): [ModuleCommon$getMediaScanningCount] get : 2
,D/FactoryTestApp( 3840): [Support$Values.getBoolean] id=FACTORY_TEST_APO, value=true
D/FactoryTestApp( 3840): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 3840): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
I/FactoryTestApp( 3840): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false
I/FactoryTestApp( 3840): [FactoryTestBroadcastReceiver$USER MODE] BOOT_COMPLETE
,I/FactoryTestApp( 3840): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted] start DummyFtClient service for APO
,I/IndexBroadcastProcessorService( 4612): lucene onHandleIntent-ACTION_MEDIA_SCANNER_FINISHED
,I/IndexBroadcastProcessorService( 4612): lucene systemReadyToIndex
,D/FactoryTestApp( 3840): [Support$Values.getBoolean] id=SUPPORT_BOOST_MEDIASCAN, value=false
D/FactoryTest( 3840): User mode
,I/FactoryTestApp( 3840): [ModuleCommon$15 Test Ready flag] set
,I/IndexService( 4612): lucene onCreate ...service
W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:577 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:278 
,I/FactoryTestApp( 3840): [ModuleCommon$isFirstBoot] before : false
,D/GalleryCacheReady( 2779): Receive action.ACTION_MEDIA_SCANNER_FINISHED
D/GalleryCacheReady( 2779): handleMeidaScanFinish()
,D/FactoryTestApp( 3840): [DummyFtClient$onCreate] Create DummyFtClient service
I/FactoryTestApp( 3840): [XMLDataStorage$parsingXML] FtClient => data parsing was completed.
D/FactoryTestApp( 3840): [DummyFtClient$onReceive] ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
D/FactoryTestApp( 3840): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 3840): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
,D/FaceInterface( 2779): requestFaceScan() is called.
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/LocalSuggestAlbumData( 2779): query fail: 
,D/FactoryTestApp( 3840): [Support$Values.getBoolean] id=SUPPORT_AUTO_WAKELOCK, value=false
W/ContextImpl( 4612): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,W/LocalSuggestAlbumData( 2779): query fail: 
,I/FaceInterface( 2779): startFaceScan() : waiting 5 sec
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 4612): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/FactoryTestApp( 3840): [DummyFtClient$onStartCommand] ...
D/FactoryTestApp( 3840): [DummyFtClient$sendBootCompletedAndFinish] ...
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,W/Vold    (  227): Returning OperationFailed - no handler for errno 30
D/FactoryTestApp( 3840): [Support$Values.getString] id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 3840): [ModuleCommon$isConnectionModeNone] mConnectionMode = gsm
D/FactoryTestApp( 3840): [IPCWriterToSecPhoneService$ResponseWriter] Create IPCWriterToSecPhoneService
,I/FactoryTestApp( 3840): [IPCWriterToSecPhoneService$connectToSecPhoneService]  
W/ContextImpl( 3840): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:141 
,D/GalaxyFinderApplication( 2436): [Slink platform] The state of Slink geocode service is true
D/LocationTagReadyService( 2436): SLink location service is enable. content://media/external/images/media not register
D/GalaxyFinderApplication( 2436): [Slink platform] The state of Slink geocode service is true
D/LocationTagReadyService( 2436): SLink location service is enable. content://media/external/video/media not register
,D/GalaxyFinderApplication( 2436): [Slink platform] The state of Slink geocode service is true
,I/dalvikvm( 4612): Could not find method java.lang.management.ManagementFactory.getPlatformMBeanServer, referenced from method org.apache.lucene.util.RamUsageEstimator.<clinit>
W/dalvikvm( 4612): VFY: unable to resolve static method 5877: Ljava/lang/management/ManagementFactory;.getPlatformMBeanServer ()Ljavax/management/MBeanServer;
,D/dalvikvm( 4612): VFY: replacing opcode 0x71 at 0x01ed
,I/SELinux ( 4637): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4637):  
,I/LocationTagReadyService( 2436): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2436): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2436): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2436): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 2779): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 4646): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4646):  
,I/SELinux ( 4637): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4637):  
I/SELinux ( 4637):  
,I/SELinux ( 4637): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4637): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4637): >>>>> Normal User
,E/dalvikvm( 4637): >>>>> com.sec.phone [ userId:0 | appId:1001 ]
,E/SELinux ( 4637): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/IndexService( 4612): lucene beginIndexing
,D/TimaKeyStoreProvider( 4637): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4637): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4637): Added TimaKesytore provider
,I/SELinux ( 4646): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4646):  
I/SELinux ( 4646):  
,I/SELinux ( 4646): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4646): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4646): >>>>> Normal User
,E/dalvikvm( 4646): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 4646): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 4669): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4669):  
,D/TimaKeyStoreProvider( 4646): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4646): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4646): Added TimaKesytore provider
,I/SELinux ( 4669): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4669):  
I/SELinux ( 4669):  
,I/SELinux ( 4669): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4669): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4669): >>>>> Normal User
,E/dalvikvm( 4669): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 4669): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 4682): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4682):  
,I/SettingSearchManagerReceiver( 1235): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
,I/SettingSearchManagerReceiver( 1235): addSearchInfoDB
,D/TimaKeyStoreProvider( 4669): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4669): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4669): Added TimaKesytore provider
,I/SELinux ( 4688): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4688):  
,E/File    ( 4612): fail readDirectory() errno=13
,I/IndexService( 4612): lucene onDestroy start
,I/IndexService( 4612): lucene onDestroy end
I/SELinux ( 4682): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4682):  
I/SELinux ( 4682):  
,I/SELinux ( 4682): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4682): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4682): >>>>> Normal User
,E/dalvikvm( 4682): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
,E/SELinux ( 4682): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/IndexService( 4612): lucene cleanupEverything start
,I/IndexService( 4612): ERROR: null
E/ParserThreadsListManager( 4612): Lucene Interrupt in run
,I/IndexService( 4612): lucene cleanupEverything end
,I/Process ( 4612): Sending signal. PID: 4612 SIG: 9
,I/SELinux ( 4688): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4688):  
I/SELinux ( 4688):  
,I/SELinux ( 4688): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4688): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4688): >>>>> Normal User
,E/dalvikvm( 4688): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10160 ]
,E/SELinux ( 4688): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/FactoryTestApp( 3840): [IPCWriterToSecPhoneService$onServiceConnected] connected done
D/FactoryTestApp( 3840): [IPCWriterToSecPhoneService$write] Send Response Message to SecPhone
,D/FactoryTestApp( 3840): [IPCWriterToSecPhoneService$write] Response ��
,D/TimaKeyStoreProvider( 4682): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4682): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4682): Added TimaKesytore provider
,D/AT_Distributor(  286): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/FactoryTestApp( 3840): [IPCWriterToSecPhoneService$handleMessage] Send BOOT COMPLETED done
D/AT_Distributor(  286): SetAtdStatus(), 1_1_0
,D/AT_Distributor(  286): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,I/ActivityManager(  759): Process com.samsung.indexservice (pid 4612) (adj 9) has died.
D/TimaKeyStoreProvider( 4688): in addTimaSignatureService
V/KVNProvider( 4669): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
V/KVNProvider( 4669): getFindoCursor query string : 
D/TimaKeyStoreProvider( 4688): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4688): Added TimaKesytore provider
,V/KVNProvider( 4669): getTagSearchCursor() tagSearchCursor count : 0
,W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=4688, uid=10160 requires android.permission.INTERACT_ACROSS_USERS
,I/MediaStoreImporter( 3994): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SettingSearchManagerReceiver( 1235): endInsert
I/ActivityManager(  759): Killing 3466:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
,I/SELinux ( 4714): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4714):  
,I/SELinux ( 4714): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4714):  
I/SELinux ( 4714):  
,I/SELinux ( 4714): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4714): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4714): >>>>> Normal User
,E/dalvikvm( 4714): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 4714): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4714): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4714): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4714): Added TimaKesytore provider
,D/AssistantMenuSettingSearch( 4714): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
,D/AssistantMenuSettingSearch( 4714): Make Setting DB
,W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=4682, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm(  759): GC_EXPLICIT freed 1725K, 13% free 23609K/26936K, paused 4ms+11ms, total 115ms
,W/ContextImpl( 4714): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:123 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:35 
,I/ActivityManager(  759): Killing 3547:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
,I/ActivityManager(  759): Killing 3493:com.sec.modem.settings/1000 (adj 15): empty #44
,I/SELinux ( 4731): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4731):  
,I/SELinux ( 4731): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4731):  
I/SELinux ( 4731):  
,I/SELinux ( 4731): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4731): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4731): >>>>> Normal User
,E/dalvikvm( 4731): >>>>> com.google.android.talk [ userId:0 | appId:10105 ]
,E/SELinux ( 4731): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4731): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4731): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4731): Added TimaKesytore provider
,W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=4731, uid=10105 requires android.permission.INTERACT_ACROSS_USERS
,I/Babel   ( 4731): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4731): MmsConfig.loadMmsSettings
,I/Babel   ( 4731): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,I/Babel   ( 4731): MmsConfig.loadFromDatabase
,E/Babel   ( 4731): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4731): MmsConfig.loadFromResources
,E/Babel   ( 4731): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4731): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,W/Settings( 4731): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/dalvikvm( 4731): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4731): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4731): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4731): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4731): VFY: unable to resolve instance field 36
,D/dalvikvm( 4731): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4731): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4731): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4731): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4731): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4731): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4731): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42703358
D/dalvikvm( 4731): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42703358
,D/dalvikvm( 4731): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42703358, skipping init
,D/dalvikvm( 4731): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42703358
,D/dalvikvm( 4731): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42703358
,V/JNIHelp ( 4731): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/knox    ( 3297): InnerIntentReceiver.onReceive() : com.sec.knox.seandroid.alarm.LOG_UPLOAD_ALARM_INTENT
,W/ContextImpl( 3297): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.InnerIntentReceiver.onReceive:171 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3297): KNOXAgentService. startJobThread() start
D/knox    ( 3297): KNOXAgentService. JobThread()
D/knox    ( 3297): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3297): KNOXAgentService. startJobThread() wait
D/knox    ( 3297): startFileChecker
D/knox    ( 3297): KNOXAgentService : onCreate()
D/knox    ( 3297): KNOXAgentService : set alarms for deniallog and usage data upload
I/knox    ( 3297): start checking file is exist to uploading
D/knox    ( 3297): notiShow :0 / context pref : 2
I/knox    ( 3297): denial log zip completed
D/knox    ( 3297): KNOXAgentService : onDestroy().
D/knox    ( 3297): ModuleBase.cancelAllAlarmManageModule()
,W/GCoreFlp( 1214): No location to return for getLastLocation()
,W/FusedLocationProvider( 1214): location=null
,D/GCM     ( 1286): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 4731): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42703358
,D/dalvikvm( 4731): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42703358
D/dalvikvm( 4731): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42703358
,D/dalvikvm( 4731): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42703358
,I/ActivityManager(  759): Killing 3621:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/ProviderInstaller( 4731): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 4777): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4777):  
,E/SMD     (  240): DCD ON
,D/dalvikvm(  247): GC_EXPLICIT freed 45K, 50% free 9506K/18948K, paused 2ms+3ms, total 25ms
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9506K/18948K, paused 1ms+2ms, total 18ms
,I/SELinux ( 4777): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4777):  
I/SELinux ( 4777):  
,I/SELinux ( 4777): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4777): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4777): >>>>> Normal User
,E/dalvikvm( 4777): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 4777): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9506K/18948K, paused 1ms+2ms, total 18ms
,D/TimaKeyStoreProvider( 4777): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4777): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4777): Added TimaKesytore provider
,E/MTPRx   ( 4777): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,E/MTPRx   ( 4777): check value of boot_completed is1
,E/MTPRx   ( 4777): check booting is completed_sys.boot_completed
E/MTPRx   ( 4777): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4777): Status for mount/Unmount :removed
,E/MTPRx   ( 4777): SDcard is not available
,W/MTPRx   ( 4777): value of connected istrue
W/MTPRx   ( 4777): value of configured istrue
W/MTPRx   ( 4777): value of mtpEnabled istrue
,W/MTPRx   ( 4777): value of ptpEnabled isfalse
E/MTPRx   ( 4777): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4777): mFirstTime: false
,D/        ( 4777): MTP: reading debug level property
,E/MTPRx   ( 4777):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 4777): Getting CryptionKey from JAVA
,E/MTPRx   ( 4777): currentUserId is 0
,E/MTPRx   ( 4777): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4777): usbMode is 0200
,E/MTPRx   ( 4777): is_secretmode is NOT 1
,W/MTPRx   ( 4777): Phone is lockedtrue
,D/LockPatternUtils( 1065): isPcwEnable = null
,D/MTPRx   ( 4777):  inside checkKnoxStatus
,D/MTPRx   ( 4777):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 4777): sending MTP_ICON_ENABLED to stack
,E/MTPRx   ( 4777): else part ... so first time!!!
,E/MTPPlaObsrvr( 4777): inside setContext()
,E/MTPPlaObsrvr( 4777):  inside createplafiles
E/MTPPlaObsrvr( 4777): playlist count is0
,E/MTPPlaObsrvr( 4777):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4777):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4777): Inside registerContentObserver
E/MtpAdbObserver( 4777): inside setContext()
,E/MtpAdbObserver( 4777): Inside registerContentObserver
,W/Settings( 4777): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,E/MtpService( 4777): onCreate.
,E/MtpService( 4777): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4777): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 4777): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 4777): onStartCommand.
,E/MtpService( 4777): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 4777): calling native method
,E/MTPJNIInterface( 4777): < MTP > Registering BroadCast receiver :::::
,D/MediaScannerReceiver( 1202): action: android.intent.action.MTP_FILE_SCAN
E/MTPJNIInterface( 4777): < MTP > Registering BroadCast receiver :::::::
E/MTPJNIInterface( 4777): noti = 10
E/MtpService( 4777): onStartCommand.
W/MTPRx   ( 4777): calling native method
E/MTPRx   ( 4777): Checking the driver time out
E/MTPJNIInterface( 4777): noti = 2
D/        ( 4777): deleting sockets before message queue initialization
E/MtpService( 4777): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
D/        ( 4777): event handler thread is created, so set the flag
E/MTPRx   ( 4777): called native method
E/MTPJNIInterface( 4777): Getting media scanner status0
E/MTPJNIInterface( 4777): setting Media scanner status0
E/MTPJNIInterface( 4777): After setting Media scanner status0
W/MTPRx   ( 4777): notification from stack 1
,E/MTPJNIInterface( 4777): DeviceName is Galaxy S5-2
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
V/NetworkStats(  759): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,D/NtpTrustedTime(  759): currentTimeMillis() cache hit
,V/NetworkStats(  759): performPollLocked() took 22ms
D/Headlines( 4166): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 4166): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 4166): Breath 7511 latestRequest time : 1454414781904 current time : 1454414789415
,D/Mms/MessagesLockscreen( 4410): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,D/ContextualEventManager( 1065): removeContextualEvent(): requestClass=com.android.mms
D/ContextualEventManager( 1065): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1065): updateContainer()
D/ContextualEventContainer( 1065): update()
D/ContextualEventContainer( 1065): handleUpdate()
D/ContextualEventManager( 1065): getTopEventView()
,D/ContextualEventManager( 1065): getTopContextualEvent()
,W/ContextImpl( 3994): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ContextualEventManager( 1065): top view = flightmode
I/KeyguardEffectViewMain( 1065): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1065): getTopEventClass()
,D/ContextualEventManager( 1065): getTopContextualEvent()
D/ContextualEventManager( 1065): !isClockTop
D/ContextualEventManager( 1065): getTopEventClass()
,D/ContextualEventManager( 1065): getTopContextualEvent()
D/ContextualEventManager( 1065): !isClockTop
D/ContextualEventManager( 1065): getTopEventClass()
,D/ContextualEventManager( 1065): getTopContextualEvent()
D/UsbManager( 1065):  :::: isUsb30Available :: return = false from pid = 1065
I/ActivityManager(  759): Waited long enough for: ServiceRecord{431a56d8 u0 com.qualcomm.atfwd/.AtFwdService}
,D/SecContextualClockFlightMode( 1065): handleUpdateClock()
,D/KeyguardProperties( 1065): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/MediaScannerService( 1202): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,W/ContextImpl( 3994): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/IcingCorporaProvider( 2175): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/FileShare-Server( 3051): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,I/SELinux ( 4810): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4810):  
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter started
,I/SELinux ( 4810): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4810):  
I/SELinux ( 4810):  
,I/SELinux ( 4810): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4810): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4810): >>>>> Normal User
,E/dalvikvm( 4810): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/MediaProvider( 1202): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,E/SELinux ( 4810): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4810): in addTimaSignatureService
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/TimaKeyStoreProvider( 4810): Cannot add TimaSignature Service, License check Failed
,D/MediaProvider( 1202): savePlaylistTableInBulkDeleter finished
,D/ActivityThread( 4810): Added TimaKesytore provider
,D/MediaScanner( 1202): Prescan. DB items number : 20 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,V/MediaScanner( 1202): processDirectory :  /storage/emulated/0
D/MediaScanner( 1202): Skipping:
,D/MediaScanner( 1202): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1202): Skipping:
,D/MediaScanner( 1202): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
V/MediaScanner( 1202): processDirectory :  /storage/extSdCard
W/MediaScanner( 1202): Error opening directory, reason : Permission denied.
,W/MediaScanner( 1202): 7klwibgf7fxlKdCbid7
,E/File    ( 1202): fail readDirectory() errno=2
,V/MediaScanner( 1202): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@4264ad38
,D/BezelQuickConnect( 3370): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 3370): BezelBroadcastReceiver - packageName : com.google.android.gms
,V/MediaScanner( 1202): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@4264ad38
V/MediaScanner( 1202):  prescan time: 19ms (DB items: 20)
V/MediaScanner( 1202):     scan time: 25ms (Caching mode: true), (makeEntry time: 20ms ~80%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1202): postscan time: 24ms (bulkDeleter : 0), (delete DeadThumbnail time : 22ms)
V/MediaScanner( 1202):    total time: 68ms
V/MediaScanner( 1202): checked files: 3  directories : 17  (I: 0, U: 0)
,I/dalvikvm( 3698): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 3698): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 3698): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager(  759): Killing 3825:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,I/MusicLeanback( 3994): Conditions not met for autocaching.
,I/MusicLeanback( 3994): Stop autocaching.
,I/Icing   ( 1758): Storage manager: low false usage 1.69MB avail 11.24GB capacity 11.95GB
,E/MTPJNIInterface( 4777): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
D/MediaScannerService( 1202): !@done scanning volume external
,I/DBG_DIAGMONDM( 4034): [1.140541.0531][Line:24][onReceive] com.sec.intent.action.SYSSCOPESTATUS
,D/PackageBroadcastService( 1758): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/SELinux ( 4833): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4833):  
,I/ActivityManager(  759): Killing 3908:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
I/dalvikvm( 1758): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.b.g.a
W/dalvikvm( 1758): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
D/dalvikvm( 1758): VFY: replacing opcode 0x6e at 0x0029
I/PackageBroadcastService( 1758): Null package name or gms related package.  Ignoreing.
,I/SELinux ( 4833): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4833):  
I/SELinux ( 4833):  
,I/SELinux ( 4833): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4833): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4833): >>>>> Normal User
,E/dalvikvm( 4833): >>>>> com.wssyncmldm [ userId:0 | appId:1000 ]
,E/SELinux ( 4833): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4833): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4833): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4833): Added TimaKesytore provider
,I/DBG_DM  ( 4833): [][Line:95][onCreate] 
,E/DBG_DM  ( 4833): BootingfileStream is null
,E/DBG_DM  ( 4833): xdmCreateBootingFilestream
,I/DBG_DM  ( 4833): [3.19.140541][Line:718][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_DM  ( 4833): [3.19.140541][Line:744][xdmGetCheckDataOnly] Voice : true
,I/DBG_DM  ( 4833): [3.19.140541][Line:745][xdmGetCheckDataOnly] SMS : true
,I/DBG_DM  ( 4833): [3.19.140541][Line:746][xdmGetCheckDataOnly] isDataOnly : false
,D/dalvikvm(  759): GC_EXPLICIT freed 1433K, 13% free 23464K/26936K, paused 5ms+11ms, total 136ms
,I/iu.UploadsManager( 1758): End new media; added: 0, uploading: 0, time: 243 ms
,I/DBG_DM  ( 4833): [3.19.140541][Line:139][xdmCheckFeatureRoamingWifiOnly] get SecProductFeature
,I/DBG_DM  ( 4833): [3.19.140541][Line:154][xdmCheckFeatureRoamingUnableNetworkMsg] get SecProductFeature
,I/DBG_DM  ( 4833): [3.19.140541][Line:36][onCreate] myUserId : 0
,I/DBG_DM  ( 4833): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 0
,I/DBG_DM  ( 4833): [3.19.140541][Line:2702][xdmdbsqlGetDownloadPostponeStatus] xdbsqlGetDownloadPostponeStatus : 0
,I/DBG_DM  ( 4833): [3.19.140541][Line:2586][xdmGetUpdateReport] wssGetUpdateReport : 0
,I/DBG_DM  ( 4833): [3.19.140541][Line:99][onCreate] DMApplication NOT Start !
,I/DBG_DM  ( 4833): [3.19.140541][Line:139][onReceive] com.sec.intent.action.SYSSCOPESTATUS
,I/SettingSearch/SearchIntentReceiver( 1318): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1318): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 1318): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 1318): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1318): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
I/ActivityManager(  759): Killing 3949:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,I/SettingSearch/SettingsSearchManager( 1318): Infomation -> numtitleinfo : 0 numSearchinfo : 312
,I/dalvikvm( 1758): Total arena pages for JIT: 11
,I/dalvikvm( 1758): Total arena pages for JIT: 12
I/dalvikvm( 1758): Total arena pages for JIT: 13
,I/dalvikvm( 1758): Total arena pages for JIT: 14
,I/Icing   ( 1758): updateResources: need to parse f{com.google.android.gms}
,I/SettingSearch/SettingsSearchManager( 1318):  Infomation -> getItem size : 312
,D/dalvikvm( 1202): GC_EXPLICIT freed 489K, 47% free 10048K/18948K, paused 4ms+5ms, total 27ms
,E/CscFactoryReceiver( 1235): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1235): Media DB Scanner finished.
,D/CscFactoryReceiver( 1235): start service to Set Ringtone
,D/CscFactoryReceiver( 1235): start service to Set Notification
,D/CscFactoryReceiver( 1235): start service to Set Alarmtone
D/CscUpdateService( 1235): onStart
,E/CscUpdateService( 1235): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1235): only ringtone update
,E/CscParser( 1235): update(): xml file exist
D/CscUpdateService( 1235): onStart
,E/CscUpdateService( 1235): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1235): only notification update
D/CscUpdateService( 1235): onStart
,E/CscParser( 1235): update(): xml file exist
E/CscUpdateService( 1235): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1235): only alarmtone update
,E/CscParser( 1235): update(): xml file exist
,I/SELinux ( 4866): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4866):  
,E/MTPJNIInterface( 4777): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4777): SDcard is not available
,W/CSCSettings( 1235): Setting Ringtones (type) : 1
D/CscParser( 1235): RingTone: null
,W/CSCSettings( 1235): 1. Tag_Str: null
,W/CSCSettings( 1235): Setting Ringtones (type) : 2
D/CscParser( 1235): MessageTone: null
,W/CSCSettings( 1235): 1. Tag_Str: null
,E/MTPJNIInterface( 4777): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4777): SDcard is not available
E/SQLiteLog( 4777): (21) API call with NULL database connection pointer
,E/SQLiteLog( 4777): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 4777): (21) API call with NULL database connection pointer
E/SQLiteLog( 4777): (21) misuse at line 93298 of [00bb9c9ce4]
,E/SQLiteLog( 4777): (21) API call with NULL database connection pointer
E/SQLiteLog( 4777): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 4777): (21) API call with NULL database connection pointer
,E/SQLiteLog( 4777): (21) misuse at line 96833 of [00bb9c9ce4]
,W/MTPRx   ( 4777): notification from stack 2
,D/        ( 4777): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4777): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 4777): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,D/        ( 4777): *****Starting mtp_io()
D/        ( 4777): [mtp_start_io] source_thread Creation 
,W/MTPRx   ( 4777): notification from stack 3
,D/        ( 4777): [mtp_start_io] sink_thread Creation 
,D/        ( 4777): [mtp_start_io:360] sink thread created so set th_sink
,W/CSCSettings( 1235): Setting Ringtones (type) : 4
D/CscParser( 1235): AlarmTone: null
,W/CSCSettings( 1235): 1. Tag_Str: null
,I/SELinux ( 4866): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4866):  
I/SELinux ( 4866):  
,I/SELinux ( 4866): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4866): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4866): >>>>> Normal User
,E/dalvikvm( 4866): >>>>> com.samsung.indexservice [ userId:0 | appId:10004 ]
,E/SELinux ( 4866): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4866): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4866): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4866): Added TimaKesytore provider
,D/FactoryTestApp( 3840): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.MEDIA_SCANNER_FINISHED
,I/FactoryTestApp( 3840): [XMLDataStorage$parsingXML] FtClient => data parsing was completed.
D/FactoryTestApp( 3840): [FactoryTestBroadcastReceiver$onReceive] ACTION_MEDIA_SCANNER_FINISHED => XML data parsing was failed.
D/FactoryTestApp( 3840): [Support$Values.getString] id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 3840): [Support$Properties.get] property=ro.factory.factory_binary
,I/FactoryTestApp( 3840): [ModuleCommon$setMediascanningCounter]  
,I/FactoryTestApp( 3840): [ModuleCommon$getMediaScanningCount] get : 2
,D/FactoryTest( 3840): User mode
I/FactoryTestApp( 3840): [ModuleCommon$getMediaScanningCount] get : 3
I/IndexBroadcastProcessorService( 4866): lucene onHandleIntent-ACTION_MEDIA_SCANNER_FINISHED
,I/FactoryTestApp( 3840): [ModuleCommon$getMediaScanningCount] get : 3
I/FactoryTestApp( 3840): [ModuleCommon$getMediaScanningCount] get : 3
I/FactoryTestApp( 3840): [ModuleCommon$isRunningFtClient] RUNNING_FTCLIENT : false
D/FactoryTestApp( 3840): [FactoryTestBroadcastReceiver$killProcessSelf] kill process
,I/Process ( 3840): Sending signal. PID: 3840 SIG: 9
,I/IndexBroadcastProcessorService( 4866): lucene systemReadyToIndex
,I/IndexService( 4866): lucene onCreate ...service
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  759): Process com.sec.factory (pid 3840) (adj 0) has died.
W/ContextImpl( 4866): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 4866): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  759): Killing 3968:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,D/GalleryCacheReady( 2779): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 2779): handleMeidaScanFinish()
,D/FaceInterface( 2779): requestFaceScan() is called.
,W/LocalSuggestAlbumData( 2779): query fail: 
,W/LocalSuggestAlbumData( 2779): query fail: 
,I/FaceInterface( 2779): startFaceScan() : waiting 5 sec
,I/dalvikvm( 4866): Could not find method java.lang.management.ManagementFactory.getPlatformMBeanServer, referenced from method org.apache.lucene.util.RamUsageEstimator.<clinit>
W/dalvikvm( 4866): VFY: unable to resolve static method 5877: Ljava/lang/management/ManagementFactory;.getPlatformMBeanServer ()Ljavax/management/MBeanServer;
,D/dalvikvm( 4866): VFY: replacing opcode 0x71 at 0x01ed
,I/IndexService( 4866): lucene beginIndexing
,D/dalvikvm( 1758): GC_CONCURRENT freed 1745K, 39% free 11703K/18948K, paused 5ms+5ms, total 39ms
,W/SQLiteConnectionPool( 1758): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/File    ( 4866): fail readDirectory() errno=13
,I/IndexService( 4866): lucene onDestroy start
I/IndexService( 4866): lucene onDestroy end
,I/IndexService( 4866): lucene cleanupEverything start
I/IndexService( 4866): ERROR: null
,E/ParserThreadsListManager( 4866): Lucene Interrupt in run
I/IndexService( 4866): lucene cleanupEverything end
,I/Process ( 4866): Sending signal. PID: 4866 SIG: 9
,I/MediaStoreImporter( 3994): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  759): Process com.samsung.indexservice (pid 4866) (adj 9) has died.
,I/Icing   ( 1758): Internal init done: storage state 0
,I/Icing   ( 1758): Post-init done
,I/Icing   ( 1758): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  759): Waited long enough for: ServiceRecord{430be2d8 u0 com.google.android.gms/.gcm.GcmService}
,I/IcingCorporaProvider( 2175): UpdateCorporaTask done [took 1526 ms] updated apps [took 1526 ms] 
,V/AlarmManager(  759): waitForAlarm result :4
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 4688): GC_EXPLICIT freed 3866K, 47% free 10126K/18948K, paused 3ms+6ms, total 37ms
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 1318): GC_EXPLICIT freed 491K, 46% free 10283K/18948K, paused 2ms+4ms, total 31ms
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/Icing   ( 1758): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/Icing   ( 1758): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1758): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,E/SMD     (  240): DCD ON
,D/dalvikvm( 4688): GC_EXPLICIT freed 999K, 48% free 10017K/18948K, paused 2ms+6ms, total 33ms
,I/FaceInterface( 2779): startFaceScan() : going on
,D/FaceInterface( 2779): startFaceScan() is called.
,D/dalvikvm(  759): GC_EXPLICIT freed 958K, 13% free 23492K/26936K, paused 8ms+12ms, total 146ms
,D/ContentApp( 1202): startScan() is called.
,D/FaceValue( 1202): mSleepTime: 800
,D/FaceValue( 1202): mMaxThreadNum: 2
,W/FaceValue( 1202): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1202): startScan() is end.
,D/ContentApp( 1202): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1202): isNeedToRestore : start
,D/dalvikvm( 1318): GC_EXPLICIT freed 356K, 46% free 10281K/18948K, paused 3ms+6ms, total 32ms
,I/FaceInterface( 2779): startFaceScan() : going on
,D/FaceInterface( 2779): startFaceScan() is called.
,D/ContentApp( 1202): startScan() is called.
,D/ContentApp( 1202): startScan() is end.
D/ContentApp( 1202): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1202): isNeedToRestore : start
,D/PreloadUpdateManagerStateMachine( 4264): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 4264): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4264): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4264): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 4264): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4264): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 4264): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4264): entry::IDLE
,I/PowerManagerService(  759): [PWL] Off : 30s ago
,D/AmoledAdjustTimer(  759): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/dalvikvm( 4688): GC_EXPLICIT freed 894K, 48% free 10017K/18948K, paused 2ms+6ms, total 30ms
,D/dalvikvm( 1318): GC_EXPLICIT freed 361K, 46% free 10284K/18948K, paused 4ms+6ms, total 32ms
,D/SSRMv2:SIOP(  759): SIOP:: AP = 330, Delta = 10
,I/GAV4    ( 4731): Thread[GAThread,5,main]: No campaign data found.
,D/dalvikvm( 4688): GC_EXPLICIT freed 906K, 48% free 10023K/18948K, paused 4ms+10ms, total 49ms
,D/dalvikvm( 1318): GC_EXPLICIT freed 352K, 46% free 10292K/18948K, paused 5ms+9ms, total 50ms
,E/SMD     (  240): DCD ON
,I/FaceInterface( 2779): startFaceScan() : going on
,D/FaceInterface( 2779): startFaceScan() is called.
,D/ContentApp( 1202): startScan() is called.
,D/ContentApp( 1202): startScan() is end.
,D/ContentApp( 1202): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1202): isNeedToRestore : start
,D/dalvikvm(  759): GC_EXPLICIT freed 364K, 13% free 23445K/26936K, paused 8ms+19ms, total 215ms
,I/CheckinService( 1758): Done disabling old GoogleServicesFramework version
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  759): Waited long enough for: ServiceRecord{42fe5668 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/dalvikvm( 4688): GC_EXPLICIT freed 903K, 48% free 10019K/18948K, paused 4ms+10ms, total 54ms
,D/dalvikvm( 1318): GC_EXPLICIT freed 363K, 46% free 10295K/18948K, paused 4ms+9ms, total 53ms
,E/SMD     (  240): DCD ON
,D/dalvikvm( 4688): GC_EXPLICIT freed 880K, 48% free 10015K/18948K, paused 3ms+11ms, total 48ms
,D/dalvikvm( 1318): GC_EXPLICIT freed 352K, 46% free 10299K/18948K, paused 4ms+8ms, total 49ms
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): waitForAlarm result :4
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  759): waitForAlarm result :4
,V/AlarmManager(  759): waitForAlarm result :4
,I/dalvikvm(  759): Jit: resizing JitTable from 8192 to 16384
V/AlarmManager(  759): waitForAlarm result :4
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/iu.UploadsManager( 1758): End new media; added: 0, uploading: 0, time: 173 ms
,D/dalvikvm(  759): GC_EXPLICIT freed 379K, 13% free 23455K/26936K, paused 7ms+15ms, total 175ms
,D/dalvikvm( 4688): GC_EXPLICIT freed 874K, 48% free 10016K/18948K, paused 3ms+9ms, total 38ms
,E/Watchdog(  759): !@Sync 2
,D/dalvikvm( 1318): GC_EXPLICIT freed 347K, 46% free 10308K/18948K, paused 5ms+8ms, total 52ms
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:20, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  759): mCoverManager.getCoverState() : true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  759): Waited long enough for: ServiceRecord{4325c5a8 u0 com.sec.android.gallery3d/.app.BackgroundCache}
,D/dalvikvm( 4688): GC_EXPLICIT freed 872K, 48% free 10013K/18948K, paused 4ms+10ms, total 48ms
,D/dalvikvm( 1318): GC_EXPLICIT freed 344K, 46% free 10312K/18948K, paused 4ms+9ms, total 49ms
,D/AmoledAdjustTimer(  759): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 310, Delta = -20
,E/SMD     (  240): DCD ON
,I/ActivityManager(  759): Waited long enough for: ServiceRecord{430d89d0 u0 com.samsung.android.MtpApplication/.MtpService}
,D/dalvikvm( 4688): GC_EXPLICIT freed 870K, 48% free 10015K/18948K, paused 3ms+10ms, total 49ms
,D/dalvikvm( 1318): GC_EXPLICIT freed 353K, 46% free 10321K/18948K, paused 5ms+8ms, total 50ms
,D/dalvikvm( 4688): GC_EXPLICIT freed 875K, 48% free 10013K/18948K, paused 3ms+11ms, total 47ms
,D/dalvikvm(  759): GC_EXPLICIT freed 387K, 13% free 23443K/26936K, paused 8ms+18ms, total 218ms
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 1318): GC_EXPLICIT freed 367K, 46% free 10329K/18948K, paused 5ms+9ms, total 50ms
,W/IcingInternalCorpora( 1758): getNumBytesRead when not calculated.
,E/SMD     (  240): DCD ON
,D/dalvikvm( 4688): GC_CONCURRENT freed 1546K, 45% free 10515K/18948K, paused 50ms+23ms, total 180ms
,D/dalvikvm( 4688): WAIT_FOR_CONCURRENT_GC blocked 73ms
,I/SettingSearch/SearchIntentReceiver( 1318): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1318): LOCALE_CHANGED call search setting db finish!!
,I/SettingSearch/SearchIntentReceiver( 1318): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 1318): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1318): LOCALE_CHANGED call search setting db finish!!
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  759): waitForAlarm result :4
,D/Finsky  ( 3698): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 3698): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 3698): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/dalvikvm( 3698): VFY: replacing opcode 0x62 at 0x0038
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/Headlines( 4166): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4166): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4166): Breath 30216 latestRequest time : 1454414781904 current time : 1454414812120
,V/GLSActivity( 1286): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1286): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1286): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
,W/dalvikvm( 1286): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1286): VFY: replacing opcode 0x6e at 0x0046
,I/System.out( 3698): Thread-348(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3698): Thread-348(ApacheHTTPLog):isShipBuild true
,I/System.out( 3698): Thread-348(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 3698): Thread-348 calls detatch()
,V/GLSActivity( 1286): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1286): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 50s ago
,I/qtaguid ( 3698): Failed write_ctrl(u 73) res=-1 errno=22
,I/qtaguid ( 3698): Untagging socket 73 failed errno=-22
W/NetworkManagementSocketTagger( 3698): untagSocket(73) failed with errno -22
,I/System.out( 3698): Thread-349 calls detatch()
,D/Finsky  ( 3698): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/AmoledAdjustTimer(  759): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,V/GLSActivity( 1286): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1286): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 3698): Total arena pages for JIT: 11
,I/dalvikvm( 3698): Total arena pages for JIT: 12
I/dalvikvm( 3698): Total arena pages for JIT: 13
,I/dalvikvm( 3698): Total arena pages for JIT: 14
,I/qtaguid ( 3698): Failed write_ctrl(u 73) res=-1 errno=22
,I/qtaguid ( 3698): Untagging socket 73 failed errno=-22
W/NetworkManagementSocketTagger( 3698): untagSocket(73) failed with errno -22
,I/System.out( 3698): Thread-348 calls detatch()
,D/SSRMv2:SIOP(  759): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 3698): GC_CONCURRENT freed 5561K, 37% free 12125K/18948K, paused 4ms+5ms, total 54ms
,D/dalvikvm( 3698): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 3698): GC_CONCURRENT freed 1557K, 34% free 12534K/18948K, paused 3ms+3ms, total 36ms
,D/dalvikvm( 3698): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 3698): GC_FOR_ALLOC freed 1131K, 32% free 12963K/18948K, paused 30ms, total 30ms
,D/dalvikvm( 3698): GC_CONCURRENT freed 1861K, 24% free 14463K/18948K, paused 5ms+5ms, total 59ms
,V/GLSActivity( 1286): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1286): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 3698): Failed write_ctrl(u 73) res=-1 errno=22
,I/qtaguid ( 3698): Untagging socket 73 failed errno=-22
W/NetworkManagementSocketTagger( 3698): untagSocket(73) failed with errno -22
,I/System.out( 3698): Thread-349 calls detatch()
,D/Finsky  ( 3698): [1] LibraryUtils.isAvailable: com.sec.android.fwupgrade available because owned, overriding [restriction=7].
,D/Finsky  ( 3698): [1] LibraryUtils.isAvailable: com.noknok.android.framework.service available because owned, overriding [restriction=7].
,D/Finsky  ( 3698): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  759): waitForAlarm result :4
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/WearableService( 1214): callingUid 10011, callindPid: 1214
,D/Finsky  ( 3698): [372] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1214): client connected with version: 8296000
,D/Finsky  ( 3698): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3698): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1286): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1286): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3698): Thread-359(HTTPLog):isShipBuild true
,I/System.out( 3698): Thread-359(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  759): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  759): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  759): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = -10
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :4
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  759): !@Sync 3
,D/Finsky  ( 3698): [361] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3698): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 298, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 75s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :4
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 4166): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/Headlines( 4166): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/Headlines( 4166): Breath 67329 latestRequest time : 1454414781904 current time : 1454414849233
,D/FactoryTest( 4777): Not factory mode
,D/FactoryTest( 4777): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4777): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4777): still no open session command from host, so toast
W/ContextImpl( 4777): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4777): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  759): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  759): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 759  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  759): mDVFSHelper.acquire()
,D/LockPatternUtils( 1065): isPcwEnable = null
,D/LockPatternUtils( 1065): isPcwEnable = null
,E/MTPRx   ( 4777): started activity for popup
,I/SQLiteSecureOpenHelper( 2105): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2105): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 4777): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtils( 1065): isPcwEnable = null
,D/SettingsReceiverActivity( 4777): dev.kiessupport is : TRUE
,I/WindowManager(  759): Screenshot max retries 4 of Token{42d5a658 ActivityRecord{42e39360 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{42e34948 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
,D/LockPatternUtils( 1065): isPcwEnable = null
W/WindowManager(  759): Screenshot failure taking screenshot for (720x1280) to layer 21005
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/VacuumService( 1214): Vacuum at: now=1454414849994 tag=VacuumService
,D/dalvikvm( 1758): GC_CONCURRENT freed 1889K, 39% free 11739K/18948K, paused 5ms+5ms, total 45ms
,E/SMD     (  240): DCD ON
,D/CustomFrequencyManagerService(  759): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 759  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  759): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  759): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 759  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/AmoledAdjustTimer(  759): prevTemp = 296, currTemp = 293, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService(  759): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 759  tag : ACTIVITY_RESUME_BOOSTER@9
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  759): !@Sync 4
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 105s ago
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,D/Headlines( 4166): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4166): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4166): Breath 90042 latestRequest time : 1454414781904 current time : 1454414871946
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/ProcessCpuTracker(  759): Skipping unknown process pid 5059
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  759): !@Sync 5
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  759): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  759): waitForAlarm result :8
,D/Headlines( 4166): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 4166): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 4166): Breath 120039 latestRequest time : 1454414781904 current time : 1454414901946
,D/Headlines( 4166): stop 
,D/Headlines( 4166): Breath.onDestroy : 
,I/ActivityManager(  759): Killing 3982:com.sec.pcw.device/1000 (adj 15): empty #43
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 140s ago
,D/AmoledAdjustTimer(  759): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  759): !@Sync 6
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 180s ago
,D/AmoledAdjustTimer(  759): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 7
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 8
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,E/SMD     (  240): DCD ON
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  759): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 225s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/dalvikvm(  759): GC_CONCURRENT freed 3157K, 17% free 23674K/28204K, paused 35ms+34ms, total 436ms
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 9
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  759): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  759): initializing...
,I/TLC_TIMA_PKM_initialize(  759): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  759): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  759): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  759): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  759): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  759): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  759): max_message_size = 524416 = 0x80080,
,D/QSEECOMAPI: (  759): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  759): App is not loaded in QSEE
,D/QSEECOMAPI: (  759): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  759): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  759): Trustlet response is completed
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  759): [PWL] Off : 275s ago
,I/PowerManagerService(  759): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  759): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  759): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=759, ws=null) (elapsedTime=3404)
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  759): !@Sync 10
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  759): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :4
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5099): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5099):  
,I/SELinux ( 5099): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5099):  
I/SELinux ( 5099):  
,I/SELinux ( 5099): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5099): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5099): >>>>> Normal User
,E/dalvikvm( 5099): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5099): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5099): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5099): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5099): Added TimaKesytore provider
,W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5099, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  759): Killing 4013:com.sec.android.cloudagent/u0a2 (adj 15): empty #43
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 11
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 330s ago
,D/AmoledAdjustTimer(  759): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 12
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 13
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 390s ago
,D/AmoledAdjustTimer(  759): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 14
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 15
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  759): [PWL] Off : 455s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  759): !@Sync 16
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  759): !@Sync 17
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,E/SMD     (  240): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  759): !@Sync 18
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 525s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/dalvikvm(  759): GC_FOR_ALLOC freed 2389K, 18% free 23622K/28576K, paused 341ms, total 344ms
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 19
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  759): !@Sync 20
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 600s ago
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 21
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 22
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  759): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  759): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  759): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 23
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  759): [PWL] Off : 680s ago
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 24
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 25
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  759): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 26
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 765s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 27
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 28
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 29
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/dalvikvm(  759): GC_FOR_ALLOC freed 2233K, 18% free 23629K/28576K, paused 342ms, total 345ms
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  759): [PWL] Off : 855s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 30
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ProcessCpuTracker(  759): Skipping unknown process pid 5235
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 31
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager(  759): waitForAlarm result :4
,D/LightsService(  759): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA(  759): getReportingMode :: sensor.mType = 5
D/Sensors (  759): LightSensor setDelay = 200000000
D/Sensors (  759): LightSensor setSensorDelay = 200000000
D/Sensors (  759): Light sensor flush: not enabled 0
D/Sensors (  759): LightSensor enable = 1
D/Sensors (  759): LightSensor enableSensor = 1
D/SensorManager(  759): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  759): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/Sensors (  759): LightSensor enable = 0
,D/Sensors (  759): LightSensor enableSensor = 0
,D/SensorManager(  759): unregisterListener ::   
D/LightsService(  759): [SvcLED]  onSensorChanged::light value = 77
D/LightsService(  759): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ConnectivityService(  759): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1065): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s
,I/PhenotypeConfigurator( 1214): Scheduling Phenotype for one-off execution 10964 seconds from now (1454415677625)
,D/GetConfigurationSnapshotOperation( 1214): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1214): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1214): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1214): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1214): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1214): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1214): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1214): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1214): Using platform SSLCertificateSocketFactory
,E/SMD     (  240): DCD ON
,D/LocationManagerService(  759): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 1286): GC_CONCURRENT freed 1868K, 43% free 10804K/18948K, paused 5ms+6ms, total 57ms
,I/dalvikvm( 1214): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1214): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1214): VFY: replacing opcode 0x6e at 0x003d
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,I/System.out( 1214): Thread-104(HTTPLog):isShipBuild true
,I/System.out( 1214): Thread-104(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1214): GC_CONCURRENT freed 1461K, 37% free 11962K/18948K, paused 6ms+12ms, total 65ms
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 32
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 950s ago
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 33
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 34
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 35
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 1050s ago
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 36
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  759): !@Sync 37
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  759): !@Sync 38
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  759): !@Sync 39
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1945): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,D/dalvikvm(  759): GC_FOR_ALLOC freed 2586K, 18% free 23671K/28576K, paused 653ms, total 657ms
D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  759): !@Sync 40
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,V/AlarmManager(  759): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  759): !@Sync 41
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/UiModeManager(  759): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,E/SMD     (  240): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 1945): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 1945): Disconnected process message: 10
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  759): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5325): 
D/AndroidRuntime( 5325): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5325): CheckJNI is OFF
D/AndroidRuntime( 5325): setted country_code = Poland
D/AndroidRuntime( 5325): setted countryiso_code = PL
D/AndroidRuntime( 5325): setted sales_code = XEO
D/AndroidRuntime( 5325): readGMSProperty: start
D/AndroidRuntime( 5325): readGMSProperty: already setted!!
D/AndroidRuntime( 5325): readGMSProperty: end
D/AndroidRuntime( 5325): addProductProperty: start
D/dalvikvm( 5325): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5325): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5325): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5325): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5325): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5325): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5325): failed to load memtrack module: -2
D/dalvikvm( 5325): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5325): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  759): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  759): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  759): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  759): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  759): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  759): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  759): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  759): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  759): getApplicationUninstallationEnabled
D/ApplicationPolicy(  759): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  759): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  759): START PACKAGE DELETE: observer{1124592632}
D/PackageManager(  759): pkg{<packageName>}
D/PackageManager(  759): user{0}
D/PackageManager(  759): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  759): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  759): !@killApplicatoin: 10179, uninstall pkg
I/dalvikvm(  759): Total arena pages for JIT: 11
I/dalvikvm(  759): Total arena pages for JIT: 12
I/dalvikvm(  759): Total arena pages for JIT: 13
I/dalvikvm(  759): Total arena pages for JIT: 14
I/dalvikvm(  759): Total arena pages for JIT: 15
W/PackageSettings(  759): Skipping PackageSetting{42d0f5b8 com.test.thalitest/10179} due to missing metadata
D/PackageManager(  759): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
E/SMD     (  240): DCD ON
D/AdaptiveEventManager( 1065): action=android.intent.action.PACKAGE_REMOVED
I/FPMS_FingerprintManagerService( 1084): onReceive: android.intent.action.PACKAGE_REMOVED
I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
D/QuickConnect[1.1][2] ( 3358): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/RCPManagerService(  759): PackageReceiver onReceive()
I/HarmonyEASService(  759): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/elm:14132( 4482): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
W/GeofencerStateMachine( 1214): Ignoring removeGeofence because network location is disabled.
D/PackageManager(  759): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "sms"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 4482): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 4482): ElmAgentService : onCreate()
D/elm:14132( 4482): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 4482): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 4482): MDMBridge.getInstance()
D/elm:14132( 4482): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "smsto"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 4482): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mms"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mmsto"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 5352): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5352):  
D/elm:14132( 4482): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 4482): ElmAgentService : onDestroy().
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "sms"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "smsto"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/SELinux ( 5352): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5352):  
I/SELinux ( 5352):  
I/SELinux ( 5352): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5352): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5352): >>>>> Normal User
E/dalvikvm( 5352): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux ( 5352): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/BackupManagerService(  759): removePackageParticipantsLocked: uid=10179 #1
W/InputMethodInfo(  759): Duplicated subtype definition found: , voice
D/TimaKeyStoreProvider( 5352): in addTimaSignatureService
D/TimaKeyStoreProvider( 5352): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5352): Added TimaKesytore provider
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mms"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mmsto"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(  759): GC_EXPLICIT freed 1899K, 17% free 23980K/28576K, paused 9ms+12ms, total 175ms
W/PackageManager(  759): Package source /data/app/com.test.thalitest-14.apk does not exist.
D/PackageManager(  759): Couldn't delete sourFile : 
W/PackageManager(  759): Couldn't delete native library directory /data/app-lib/com.test.thalitest-14
D/AndroidRuntime( 5325): Shutting down VM
D/dalvikvm( 5325): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 2ms
D/PackageManager(  759): return delete result to caller: 1124592632
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5352, uid=10021 requires android.permission.INTERACT_ACROSS_USERS
D/PackageManager(  759): returnCode: 1
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "sms"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService(  759): Package has changed for user 0
D/EnterpriseDeviceManagerService(  759): Admin package name: com.google.android.gms
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "smsto"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 5368): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5368):  
I/ActivityManager(  759): Killing 3880:com.vlingo.midas/u0a33 (adj 15): empty #43
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mms"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mmsto"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 5368): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5368):  
I/SELinux ( 5368):  
I/SELinux ( 5368): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5368): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5368): >>>>> Normal User
E/dalvikvm( 5368): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux ( 5368): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 5368): in addTimaSignatureService
D/TimaKeyStoreProvider( 5368): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5368): Added TimaKesytore provider
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  759): Permission Denial: getCurrentUser() from pid=5368, uid=10024 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 5382): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5382):  
I/ActivityManager(  759): Killing 4091:com.policydm/1000 (adj 15): empty #43
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux ( 5382): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5382):  
I/SELinux ( 5382):  
I/SELinux ( 5382): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5382): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5382): >>>>> Normal User
E/dalvikvm( 5382): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux ( 5382): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/dalvikvm( 5382): Enabling JNI app bug workarounds for target SDK version 8...
D/TimaKeyStoreProvider( 5382): in addTimaSignatureService
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/TimaKeyStoreProvider( 5382): Cannot add TimaSignature Service, License check Failed
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread( 5382): Added TimaKesytore provider
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  759): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  759): clearDefaults: com.test.thalitest
W/FileUtils( 5382): Failed to chmod(/data/data/com.sec.pcw.device/databases/value.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
I/PCWCLIENTTRACE_PushUtil( 5382): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5382): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5382): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_LOG( 5382): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5382): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_SYSTEMReceiver( 5382): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SELinux ( 5396): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5396):  
I/ActivityManager(  759): Killing 3936:com.sec.spp.push/u0a38 (adj 15): empty #43
I/SELinux ( 5396): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5396):  
I/SELinux ( 5396):  
I/SELinux ( 5396): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5396): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5396): >>>>> Normal User
E/dalvikvm( 5396): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10034 ]
E/SELinux ( 5396): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/InputReader(  759): Processing first event
D/TimaKeyStoreProvider( 5396): in addTimaSignatureService
D/TimaKeyStoreProvider( 5396): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5396): Added TimaKesytore provider
D/SSRMv2:SIOP(  759): SIOP:: AP = 300, Delta = 0

```
